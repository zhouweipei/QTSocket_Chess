# QTSocket_Chess
清华大学计算机系程设训练暑假小学期大作业2——网络通信的象棋对战平台

### 介绍
中国象棋是起源于中国的一种棋戏，属于二人对抗性游戏的一种，在中国有着悠久的历史。本次大作业要求同学们基于Qt实现支持网络对战的象棋软件，并要求支持残局的保存与恢复。

### 基本要求
（1）软件拥有主界面和菜单栏，点击菜单栏弹出弹窗进行连接。

（2）server端要求等待连接时可以取消，client端要求能输入对战的IP及端口，并显示成功建立连接。

（3）正确绘制象棋棋盘及棋子。

（4）软件能依据规则正确走子。

（5）软件能判断胜负，被将军时能发出特殊音效；提供认输按钮，一方认输游戏结束；每步走子有时间限制，超时判负。

（6）游戏结束，在server端和client端分别弹窗说明游戏结束，并注明获胜方。

（7）菜单栏拥有残局输入的入口，选择文件载入加载残局，建立连接进行对战。

（8）残局对战的保存文件要求采用固定格式（后附说明）。

（9）对战进行中可以点击相应按钮，保存残局到本地文件，此时server/client端都会将残局保存到本地文件。
