# SC3-GW

[Repository](https://github.com/hakoroboken/SC3-GW)

## 目的
`SC3-GW`はiOS Appである`SmartController3`と接続するためのパッケージである。自動で接続を確立し、定期的に接続確認を行う。将来的にSmartController3 Gen2(仮)への対応が行われ現在のバージョンと互換性がないバージョンが配布されます。なお、現在のバージョンはブランチをかえて残されます。

## Input / Output
### Input
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/sc3_gw/info`  |  `std_msgs/String`  | アプリに表示するメッセージ |
|  `/sc3_gw/error`  |  `std_msgs/String`  | アプリに表示するエラーメッセージ |


### Output
|  Name  |  Type  | Description |
| ---- | ---- | ---- |
|  `/sc3_gw/joy`  |  `sensor_msgs/Joy`  | コンソールコントローラの操作情報 |
|  `/sc3_gw/SmartUI`  |  `sensor_msgs/Joy`  | アプリに実装されたUI情報 |

## Parameters
|  Name  |  Type  | Description | Default value |
| ---- | ---- | ---- | ---- |
|  `port`  |  `int`  | SC3と通信するためのポート | 64201 |
|  `nic`  |  `string`  | SC3と通信するためのnic | "lo" |
|  `debug`  |  `bool`  | デバッグ有効/無効 | false |
|  `c1`  |  `string`  | SmartUIボタンラベル | "c1" |
|  `c2`  |  `string`  | SmartUIボタンラベル | "c2" |
|  `s1`  |  `string`  | SmartUIスライダーラベル | "s1" |
|  `s2`  |  `string`  | SmartUIスライダーラベル | "s2" |



