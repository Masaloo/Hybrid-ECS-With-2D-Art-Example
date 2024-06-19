# Hybrid-ECS-With-2D-Art-Example
ECS およびHybrid ECSと、2Dアートスタイルで利用されるコンポーネントとの連携可能性をテストするUnity Project です。

URPにおけるLight2D系コンポーネント

| Component | ConvertEntity |Description|
| ---- | ---- |----|
| Sprite-Lit(Material)|true|Materialの描画が可能。|
| Light2D|false*|Entity Light2Dはサポートされていない。(*GameObject Light2D ->Entity Sprite-Lit による陰は可能)|
| ShadowCaster2D | false |サポートされていない|
