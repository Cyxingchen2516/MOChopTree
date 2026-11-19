# MOChopTree

《心灵终结 3.3.6》（Mental Omega 3.3.6）的客户端插件。

## 功能

- `Ctrl + W` 让选中的步兵/载具开始砍树
- 砍倒一棵后自动扫描半径内最近的树继续砍，直到范围内没有树

## 配置

```ini
[ChopTree]
Enable=1
Hotkey=Ctrl+W
RadiusCells=18   ; 扫描半径（格）
Interval=15      ; 扫描间隔
```
## 安装

1. 需要先安装 [Syringe](https://github.com/Ares-Developers/Syringe)（心灵终结自带）。
2. 把本目录下的文件放进游戏根目录（`gamemd.exe` 所在目录）。
3. 启动游戏即可。删除文件即卸载。

## 说明

- 纯客户端插件：不修改游戏模拟数据、不发送指令，联机时对方无需安装。
