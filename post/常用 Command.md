Screen 全屏窗口管理器，即使窗口不可见，Screen 也会在断开连接后继续运行命令。常用于远程运行长任务担心 SSH 会话掉线
```shell
screen # Start a screen session  
screen -ls # List running services  
screen -r # Attach to session
```
Ncdu 命令提供一个快读、方便的查看磁盘使用情况的视图，可以快速的查看哪个目录占用最多的磁盘空间
```shell
ncdu
```
列出所有的 systemd 服务
```shell
systemctl -l -t service | less
```
