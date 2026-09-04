<div align="center">

# Awesome Terminal Apps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 精选的终端/CLI 应用，支持 Windows — 游戏、音乐工具和创意应用。

应用按 **Windows 兼容性** 分级，让你清楚知道什么能原生运行：

- **Native** - 有预编译 Windows .exe 或 .zip，零依赖
- **MSYS2** - 需要 MSYS2/MinGW 编译（基于 ncurses）
- **Cross-platform** - Rust/Go/C++ 跨平台构建
- **Python** - Python 应用
- **Web** - 浏览器或 SSH 可玩

</div>

---

## 目录

- [街机](#街机)
- [益智](#益智)
- [Roguelike](#roguelike)
- [策略](#策略)
- [棋盘](#棋盘)
- [卡牌](#卡牌)
- [音乐](#音乐)
- [创意工具](#创意工具)
- [其他](#其他)
- [安装器](#安装器)
- [贡献指南](#贡献指南)
- [致谢](#致谢)

---

## 街机

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [0verkill](https://github.com/hackndev/0verkill) | MSYS2 | C | 血腥 2D 动作死斗游戏 |
| [aop](https://raffi.at/view/code/aop) | MSYS2 | C | Ambassador of Pain - 高难度街机 |
| [ascii-invaders](https://github.com/macdice/ascii-invaders) | MSYS2 | C | 太空侵略者克隆 |
| [ascii-patrol](http://ascii-patrol.com/) | Web | C | 月球巡逻克隆 |
| [ascii-snake](https://github.com/cyphar/ascii-snake) | MSYS2 | C | 贪吃蛇 |
| [bastet](http://fph.altervista.org/prog/bastet.html) | **Native** | C++ | 邪恶俄罗斯方块，专门给你最差的方块 |
| [bootmine](https://github.com/io12/BootMine) | MSYS2 | ASM | 512 字节启动扇区扫雷 |
| [bootrogue](https://github.com/nanochess/bootRogue) | MSYS2 | ASM | 510 字节启动扇区 Roguelike |
| [bricks](https://github.com/nanochess/bricks) | MSYS2 | ASM | 510 字节启动扇区打砖块 |
| [ctris](https://github.com/dominikhackl/ctris) | MSYS2 | C | 俄罗斯方块克隆 |
| [fbird](https://github.com/nanochess/fbird) | MSYS2 | ASM | 启动扇区 Flappy Bird |
| [gorched](https://github.com/zladovan/gorched) | **Cross-platform** | Go | 沙丘之战克隆 |
| [invaders](https://github.com/nanochess/invaders) | MSYS2 | ASM | 512 字节太空侵略者 |
| [just-asteroids](https://github.com/gabrielvictorcf/just-asteroids) | **Cross-platform** | Rust | 小行星克隆 |
| [moon-buggy](https://www.seehuhn.de/pages/moon-buggy) | MSYS2 | C | 月球飙车 |
| [myman](https://myman.sourceforge.io/) | MSYS2 | C | 吃豆人文字版 |
| [ninvaders](http://ninvaders.sourceforge.net/) | MSYS2 | C | 太空侵略者 |
| [nsnake](https://sourceforge.net/projects/nsnake/) | MSYS2 | C | 经典贪吃蛇 |
| [pacman](http://slaout.linux62.org/pacman/index.html) | MSYS2 | Python | 吃豆人克隆 |
| [pillman](https://github.com/nanochess/pillman) | MSYS2 | ASM | 512 字节吃豆人 |
| [piu-piu-SH](https://github.com/vaniacer/piu-piu-SH) | **Cross-platform** | Shell | 横版射击游戏 |
| [sshtron](http://sshtron.zachlatta.com/) | Web | Go | SSH 多人光 cycle |
| [terminal-phase](https://gitlab.com/dustyweb/terminal-phase) | **Cross-platform** | Rust | 太空射击 |
| [tet-ris](https://github.com/manorajesh/tet-ris) | **Cross-platform** | Rust | 1984 风格俄罗斯方块 |
| [tinytetris](https://github.com/taylorconor/tinytetris) | **Cross-platform** | C++ | 80x23 终端俄罗斯方块 |

## 益智

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [2048](https://github.com/mevdschee/2048.c) | **Native** | C | 经典 2048，无依赖 |
| [2048-cli](https://github.com/Tiehuis/2048-cli) | MSYS2 | C | ncurses 版 2048 |
| [cmines](https://www.muppetlabs.com/~breadbox/software/cgames.html) | MSYS2 | C | 扫雷克隆 |
| [csol](https://github.com/nielssp/csol) | **Cross-platform** | C | 纸牌游戏合集 |
| [floodit](https://github.com/smmspiers/FloodIt) | **Cross-platform** | C | 洪水填充颜色游戏 |
| [greed](http://www.catb.org/~esr/greed/) | MSYS2 | C | 数字吞噬谜题 |
| [minecurses](https://github.com/christosmarg/minecurses) | **Cross-platform** | Python | 扫雷变体 |
| [minesviiper](https://gir.st/mines.html) | MSYS2 | C | vi 键位扫雷 |
| [minesweep-rs](https://github.com/cpcloud/minesweep-rs) | **Cross-platform** | Rust | Rust 版扫雷 |
| [nudoku](https://github.com/jubalh/nudoku) | MSYS2 | C | ncurses 数独 |
| [nuzzle](https://github.com/dead-end/nuzzle) | **Cross-platform** | Rust | 谜题合集 |
| [puzzl](https://github.com/pravj/puzzl) | **Cross-platform** | Rust | 滑动谜题 |
| [sudoku-rs](https://github.com/MitchelPaulin/sudoku-rs) | **Cross-platform** | Rust | Rust 版数独 |

## Roguelike

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [adom](https://www.adom.de/) | **Native** | C | 古代神秘领域 |
| [angband](https://rephial.org/) | MSYS2 | C | 地牢探索经典 |
| [brogue](https://sites.google.com/site/broguegame/) | **Cross-platform** | C | 美丽的地牢爬行者 |
| [brogue-ce](https://github.com/tmewett/BrogueCE) | **Cross-platform** | C | Brogue 社区版 |
| [cataclysm](https://web.archive.org/web/20190209031801/http://en.cataclysmdda.com/) | **Native** | C++ | 末日生存 |
| [crawl](https://crawl.develz.org/wordpress/) | **Cross-platform** | C++ | 地牢爬行石汤 |
| [diablorl](https://diablo.chaosforge.org/) | **Native** | C++ | 暗黑破坏神 Roguelike |
| [doomrl](https://drl.chaosforge.org/) | **Native** | C++ | 毁灭战士风格 Roguelike |
| [frozen-depths](https://frozendepths.net/) | **Native** | C++ | 氛围感 Roguelike |
| [gearhead](http://www.gearheadrpg.com/) | **Native** | C++ | 机甲 Roguelike |
| [nethack](https://www.nethack.org/) | **Native** | C | 1987 年至今的经典 |
| [rogue](https://man.netbsd.org/rogue.6) | MSYS2 | C | 原版 BSD rogue |

## 策略

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [chess-tui](https://github.com/thomas-mauran/chess-tui) | **Cross-platform** | Rust | 终端国际象棋 |
| [chs](https://github.com/nickzuber/chs) | **Cross-platform** | Rust | 对战 Stockfish 的国际象棋 |
| [connect4](https://github.com/badescunicu/connect4) | MSYS2 | Python | 四子棋 |
| [curse-of-war](https://a-nikolaev.github.io/curseofwar/) | MSYS2 | C | 快节奏即时战略 |
| [gnugo](https://www.gnu.org/software/gnugo/) | **Native** | C | GNU 围棋 |
| [gnuchess](https://www.gnu.org/software/chess/) | **Native** | C | GNU 国际象棋 |
| [shogi](https://www.gnu.org/software/gnushogi/) | **Native** | C | 日本将棋 |

## 棋盘

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [dab](https://man.netbsd.org/dab.6) | MSYS2 | C | 点格棋 - BSD |
| [hinversi](https://sourceforge.net/projects/hinversi/) | MSYS2 | C | 黑白棋 |
| [mancala](https://shh.thathost.com/pub-unix/#Mancala) | MSYS2 | C | 曼卡拉棋 |

## 卡牌

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [bluemoon](http://www.catb.org/~esr/bluemoon/) | MSYS2 | C | 蓝月亮纸牌 |
| [canfield](https://man.openbsd.org/canfield.6) | MSYS2 | C | Canfield 纸牌 - BSD |
| [cpat](http://cpat.sourceforge.net/) | **Native** | C | 纸牌游戏合集 |
| [freecell](https://www.linusakesson.net/software/freecell.php) | MSYS2 | C | 空当接龙 |
| [freecell-ng](https://github.com/ostrosablin/freecell) | MSYS2 | C | 带求解器的空当接龙 |

## 音乐

终端钢琴、音乐播放器、可视化工具、DJ 工具和合成器。

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [cava](https://github.com/karlstav/cava) | **Native** | C | 终端标准条形频谱可视化器 |
| [musikcube](https://github.com/clangen/musikcube) | **Native** | C++ | 终端音乐播放器 + 音频引擎 + 流媒体服务器 |
| [kew](https://github.com/ravachol/kew) | **Native** | C | 沉浸式终端播放器，Sixel 专辑封面 |
| [piango](https://github.com/SirSobhan0/piango) | **Native** | Go | 低延迟复音合成器，8 种乐器，3 个八度 |
| [phosphor-studio](https://github.com/joshjetson/phosphor) | Cross-platform | Rust | 终端 DAW：6 种合成器，10 套鼓组，300+ 音色 |
| [textstep](https://github.com/illobo/textStep) | Cross-platform | Rust | 终端步进音序器 + 鼓机 + 双合成器 |
| [imbolc](https://github.com/mohsenil85/imbolc) | Cross-platform | Rust | 完整终端 DAW：58 种乐器，39 种效果，LAN 协作 |
| [termus](https://github.com/mrbrutti/termus) | **Native** | Go | 生成式音乐乐器，9+ 算法，WAV/MIDI 导出 |
| [mixr](https://github.com/chris-mclennan/mixr) | **Native** | Rust | 完整终端 DJ 应用，双碟引擎，Claude AI DJ |
| [beat-gen](https://github.com/glebis/beat-gen) | Cross-platform | JavaScript | CLI 全曲生成器，9 种流派，MIDI/WAV 导出 |
| [upiano](https://github.com/eliasdorneles/upiano) | Python | Python | Textual TUI + FluidSynth 终端钢琴 |
| [tpiano](https://github.com/gfargo/tPiano) | Cross-platform | TypeScript | React/Ink 构建的终端钢琴 |
| [acordes](https://github.com/pushpop/Acordes) | Python | Python | TUI MIDI 合成器 + 钢琴 + 16 步鼓机 |
| [sq](https://github.com/chriserin/sq) | **Native** | Go | 终端 MIDI 音序器，欧几里得节奏，vim 风格 |
| [tty-clock](https://github.com/xorg62/tty-clock) | Cross-platform | C | 经典终端数字时钟，屏保模式 |
| [clock-rs](https://github.com/Oughie/clock-rs) | **Native** | Rust | 现代终端时钟、计时器、秒表 |
| [sigye](https://github.com/am2rican5/sigye) | **Native** | Rust | 功能丰富的时钟，6 种模式，FIGlet 字体，番茄钟 |
| [programmer-calculator](https://github.com/alt-romes/programmer-calculator) | Cross-platform | C | 程序员终端计算器，二进制/十六进制/十进制 |

## 创意工具

ASCII 艺术编辑器和绘图工具。

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [durdraw](https://github.com/cmang/durdraw) | Python | Python | ASCII/Unicode/ANSI 艺术编辑器，支持动画 |
| [ascii-draw](https://github.com/Nokse22/ascii-draw) | Python | Python | 完整 ASCII 绘图应用，FIGlet 文字，表格，树 |
| [figo](https://github.com/auricvex/figo) | Cross-platform | Rust | ASCII 艺术生成器，方框，流程图，图表 |
| [termdraw](https://github.com/benvinegar/termdraw) | Cross-platform | TypeScript | 终端绘图编辑器 |

## 其他

| 应用 | 级别 | 语言 | 说明 |
|------|------|------|------|
| [corewar](http://www.corewar.info/) | **Native** | C | 编程对战游戏 |
| [doom-ascii](https://github.com/wojciech-graj/doom-ascii) | **Native** | C | ASCII 版毁灭战士 |
| [dwarf-fortress](https://www.bay12games.com/dwarves/) | **Native** | C++ | 矮人要塞 |
| [frotz](https://davidgriffith.gitlab.io/frotz/) | **Cross-platform** | C | Z-machine 解释器 |
| [nbsdgames](https://github.com/abakh/nbsdgames) | MSYS2 | C | 18 款文字游戏合集 |
| [open-adventure](https://gitlab.com/esr/open-adventure) | **Cross-platform** | C | 巨穴冒险 |
| [pokete](https://github.com/lxgr-linux/pokete) | Python | Python | 终端宝可梦 |
| [robotfindskitten](http://robotfindskitten.org/) | **Cross-platform** | C | 禅意模拟 |
| [wordle-cli](https://github.com/ajeetdsouza/clidle) | **Cross-platform** | Rust | 终端 Wordle |

---

## 安装器

使用 PowerShell 安装器一键安装应用：

```powershell
# 列出所有应用
.\scripts\tap.ps1 list

# 按级别筛选
.\scripts\tap.ps1 list --tier native

# 按分类筛选
.\scripts\tap.ps1 list --category roguelike

# 安装应用
.\scripts\tap.ps1 install nethack

# 安装所有 native 应用
.\scripts\tap.ps1 install --all --tier native

# 卸载应用
.\scripts\tap.ps1 remove nethack

# 更新已安装应用
.\scripts\tap.ps1 update

# 设置自定义安装路径（默认自动检测非 C 盘）
.\scripts\tap.ps1 config -AppsDir D:\my\apps

# 查看当前配置
.\scripts\tap.ps1 config
```

应用默认安装到第一个非 C 盘（如 `D:\apps\terminal`）。只有 C 盘时回退到 `%USERPROFILE%\apps\terminal`。

---

## 贡献指南

参见 [CONTRIBUTING.md](CONTRIBUTING.md)。

---

## 致谢

本列表建立在优秀的 [ligurio/awesome-ttygames](https://github.com/ligurio/awesome-ttygames) 基础之上，该仓库收录了 200+ 款 Unix ASCII 游戏。我们的目标是扩展它，增加：

- **Windows 兼容性分级** - 让用户清楚知道什么能原生运行
- **一键安装** - 通过 PowerShell 脚本，支持 .exe 和 .zip
- **应用分类** - 按类型组织（游戏、音乐、创意工具）

---

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在适用法律允许的范围内，贡献者已放弃对此作品的所有版权和相关权利。
