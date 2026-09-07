# 雨岸赛车 / Rain Coast

一款原创海岸公路竞速游戏。驾驶银色跑车，在两张可选地图上挑战蓝色 AI 对手。全新的「云脊天路」单圈约 6.10 公里，包含百米风脊、云顶隧道、赤岩峡谷、矿坑回旋和泄洪飞坡；经典「雨岸远征」也完整保留。

## 打开即玩

**[进入雨岸赛车网页版](https://kevinkaslana093.github.io/rain-coast/)**

支持电脑键盘与手机触屏操作，无需下载或安装。驾驶设置中可在 60%–120% 之间调整转向灵敏度，并自动保存。每次比赛会从两首背景音乐中随机选择，播放结束后自动换曲。

![雨岸赛车起跑画面](docs/start-line.png)

## 下载试玩

前往 [Releases](../../releases/latest) 下载 `RainCoast-Windows-v0.6.1.zip`。

1. 完整解压 ZIP。
2. 双击 `RainCoast.exe`。
3. 点击游戏窗口，按 `W` 或 `↑` 开始比赛。

无需安装 Unreal Engine。目前提供 Windows 64 位版本。

Release 同时提供 macOS 构建就绪工程；它需要在 Mac 上用 UE 5.8 和 Xcode 编译，不是已经编译好的 `.app`。

## 操作

| 按键 | 功能 |
| --- | --- |
| W / ↑ | 开始比赛、加速 |
| S / ↓ | 刹车、倒车 |
| A / D 或 ← / → | 转向 |
| Space | 漂移 |
| R | 回到赛道，增加 3 秒 |
| N | 重新开始 |
| Esc | 暂停 / 继续 |
| Tab | 切换镜头 |
| F1 | 自动驾驶演示 / 切回手动 |
| Alt + F4 | 退出 |

## 当前版本

网页版当前加入两张地图和随机音乐播放。`v0.6.1` Windows 下载包仍是离线单人试玩版：两圈竞速，挑战蓝色 AI 对手。真人联机暂未加入。

若启动时提示缺少 Visual C++ 运行组件，请运行游戏包内的：

`Engine/Extras/Redist/en-us/vc_redist.x64.exe`

欢迎在 [Issues](../../issues) 反馈操控手感、赛道问题、电脑配置和运行情况。

---

## English

Rain Coast is an original coastal road racing game with two selectable courses. The new Skyline Road course is about 6.10 km per lap and crosses a high ridge, summit tunnel, red-rock canyon, mine switchbacks, and a spillway jump. The classic Rain Coast course remains available.

Download `RainCoast-Windows-v0.6.1.zip` from [Releases](../../releases/latest), extract the entire ZIP, and launch `RainCoast.exe`. Unreal Engine is not required. Windows x64 only.

Press `W` or `Up` to start and accelerate. Use `S`/`Down` to brake, `A`/`D` or arrow keys to steer, `Space` to drift, `R` to recover, `N` to restart, `Esc` to pause, `Tab` to change camera, and `F1` to toggle autodrive.

This is currently an offline single-player preview. Online multiplayer is not included yet.

The release also includes a macOS build-ready UE5 project. It requires UE 5.8 and Xcode on a Mac and is not a precompiled `.app`.

**[Play Rain Coast in your browser](https://kevinkaslana093.github.io/rain-coast/)** — no download required. Each race randomly selects one of two background tracks and automatically continues with the other when a track ends.

© 2026 Rain Coast. All rights reserved.
