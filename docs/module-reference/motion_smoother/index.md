# motion_smoother

[Repository](https://github.com/hakoroboken/motion_smoother)

## 目的
`motion_smoother`は入力された速度命令を一定の加速度に抑えて一定間隔で出力する。デフォルトでは20ms間隔で出力される。

## Input / Output
### Input
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/cmd_vel/in`  |  `geometry_msgs/Twist`  | 入力ベクトル |


### Output
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/cmd_vel/out`  |  `geometry_msgs/Twist`  | 出力ベクトル |

## Parameters
|  Name  |  Type  | Description | Default value |
| ---- | ---- | ---- | ---- |
|  `gain`  |  `double`  | 最大加速度 | 1.0 |
|  `linearxPr`  |  `bool`  | linear.xをスムーズするか | true |
|  `linearyPr`  |  `bool`  | linear.yをスムーズするか | true |
|  `linearzPr`  |  `bool`  | linear.zをスムーズするか | true |
|  `angularxPr`  |  `bool`  | angular.xをスムーズするか | true |
|  `angularyPr`  |  `bool`  | angular.yをスムーズするか | true |
|  `angularzPr`  |  `bool`  | angular.zをスムーズするか | true |








