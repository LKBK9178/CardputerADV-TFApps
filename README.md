# Cardputer ADV TF 卡软件分发仓库

M5 助手「软件库 · 下载」的软件源（catalog.json 为清单）。

## 软件
| ID | 类型 | 说明 |
|---|---|---|
| TETRIS | 游戏 | 经典俄罗斯方块 |
| G2048 | 游戏 | 数字合并 2048 |
| BREAKOUT | 游戏 | 打砖块 Breakout |
| SHOOTER | 游戏 | 射击小游戏 |
| SNAKE | 游戏 | 贪吃蛇 |
| AUDIO | 媒体 | 音视频解码播放器（可开文件，数据放 TF 卡 FILES\AUDIO） |
| DOOM | 游戏 | 毁灭战士 DOOM（含 DOOM.WAD，ESP-NOW 联机预留） |

## 目录结构
- APPS/<软件名>/{app.bin, meta.txt, icon.raw}  软件包（写入 TF 卡 APPS 隐藏目录）
- catalog.json  软件清单（M5 助手软件库读取）