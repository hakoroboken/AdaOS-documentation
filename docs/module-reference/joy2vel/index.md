# joy2vel

[Repository](https://github.com/hakoroboken/joy2vel)

## 目的
`joy2vel`は`sensor_msgs/Joy Message`を`geometry_msgs/Twist Message`に変換するモジュールである。デバッグや手動を操作を行う際に使用する。

## Input / Output
### Input
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/joy`  |  `sensor_msgs/Joy`  | input joystic message |

### Output
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/cmd_vel`  |  `geometry_msgs/Twist`  | output twist message |

## Parameters
This package has no parameters.