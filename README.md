# Hybrid-ECS-With-2D-Art-Example
ECS およびHybrid ECSと、2Dアートスタイルで利用されるコンポーネントとの連携可能性をテストするUnity Project です。

# Componentの対応状況
URPにおけるLight2D系コンポーネントと各機能のECSへの変換サポート状況
| Component | Support |Description|
| ---- | ---- |----|
| Sprite-Lit(Material)|true|Materialの描画が可能。|
| Light2D|false*|Entity Light2Dはサポートされていない。(*GameObject Light2D ->Entity Sprite-Lit による陰は可能)|
| ShadowCaster2D | false |サポートされていない|
