# Loadmap
## 大まかな計画
- 2023 Q1
    - HakoroboGems.ManualのStable版をリリース
    - HakoroboGems.AutoのAlpha版をリリース
- 2023 Q2
    - HakoroboGems.AutoのFirst Stable版をリリース

<br>

## 各モジュールごとの計画

### joy2vel
機能追加などの大幅な変更は行わない。動作の安定化を目指す。

### MotionSmoother
機能追加などの大幅な変更は行わない。動作の検証を行い安定性向上に努める。

### Vecmonitor
使用しやすいようにパラメータの追加等を行う。ただし優先度は低め。

### HakoroboGemsCLI
- デバッグツール群を提供する。

### Mission Planner
- HakoroboGemsCLIやRoboUIからの指令を受け取る。
- システムの状態監視を行う。

### Twist2MCMessage
- マイコンに送る文字列を決定する。

### ROS2Serial
- マイコンとシリアル通信を行う。

### RoboUI
- 調整中

### シナリオシミュレータ
- ロボット経路計画などを検証するシナリオシミュレータだけは早めに完成させたい。

### デジタルツインシミュレータ
- Isaac Simで制作する予定。優先度低め。

### センサーシミュレータ
基本的にセンサーのROSbagを回すだけ。挙動として正しいかどうかを検証するエンジンを作る・