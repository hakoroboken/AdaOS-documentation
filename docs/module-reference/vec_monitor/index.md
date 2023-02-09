# vec_monitor

[Repository](https://github.com/hakoroboken/vec_monitor)

## 目的
`vec_monitor`は`geometry_msgs/Twist`型のメッセージを記録してCSVファイルにエクスポートします。同時に二つのtopicをサブスクライブできるため特定のノードの検証に最適です。デフォルトで10msごとにサブスクライブしているメッセージの最新のメッセージのみをCSVファイルに記録します。

## Input / Output
### Input
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/vel_1`  |  `geometry_msgs/Twist`  | Twsit message |
|  `/vel_2`  |  `geometry_msgs/Twist`  | Twsit message |

### Output
This package has no output.

## Parameters
This package has no parameters.