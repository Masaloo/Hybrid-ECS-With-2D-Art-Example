# Hybrid-ECS-With-2D-Art-Example
ECS およびHybrid ECSと、2Dアートスタイルで利用されるコンポーネントとの連携可能性をテストするUnity Project です。

URPにおけるLight2D系コンポーネント

---
|Component||
|ShadowCaster2D|false|
---
| Component | ConvertEntity |Description|
| ---- | ---- |----|
| Sprite-Lit(Material)|true|Materialの描画が可能。|
| Light2D|false*|*GameObject Light2D ->Entity Sprite-Lit による陰は可能|
| ShadowCaster2D | false|サポートされていない|
