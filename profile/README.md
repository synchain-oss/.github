# Synchain

音乐制作协作平台 Synchain 的开源部分：平台本身闭源，跑在你自己电脑上的插件和工具都在这里开源。
The open-source side of Synchain, a collaboration platform for music production. The platform is closed source; the plugins and tools that run on your own machine are open here.

## 插件和工具 / Plugins and tools

| 项目 / Project | 简介 / About | 许可证 / License |
|---|---|---|
| [Synchain Bridge](https://github.com/synchain-oss/synchain-bridge) | DAW 插件，把 DAW 里的音频实时接进浏览器<br>DAW plugin that streams your DAW audio to the browser | GPL-3.0-or-later |
| [SCVB](https://github.com/synchain-oss/scvb) | 多人多声部人声的自动声像与音量平衡（预发布）<br>Automatic pan and level balancing for multi-singer vocals (pre-release) | GPL-3.0-or-later |
| [Synchain Rinne（回环）](https://github.com/synchain-oss/rinne) | 一对反馈插件，把通道信号回送给自己，环路延迟由你设定（开发中，尚未发布）<br>A plugin pair that feeds a channel back into itself, with a loop delay you set (in development, no release yet) | GPL-3.0-or-later |
| [Synchain CLI](https://github.com/synchain-oss/synchain-cli) | 在终端里管理 Synchain 项目<br>Manage Synchain projects from the terminal | MIT |

## OpenTune

让 AI agent 操作开源 AI 人声修音软件 OpenTune。OpenTune 是 DAYA STUDIO 的项目，官方仓库和唯一官方发布渠道是 [YuFeng926/OpenTune](https://github.com/YuFeng926/OpenTune)；这里发布的都不是 OpenTune 官方版本。
Lets AI agents operate OpenTune, the open-source AI vocal pitch-correction app. OpenTune is a project of DAYA STUDIO; its official repository and only official distribution channel is [YuFeng926/OpenTune](https://github.com/YuFeng926/OpenTune). Nothing published here is an official OpenTune release.

| 项目 / Project | 简介 / About | 许可证 / License |
|---|---|---|
| [OpenTune MCP Server](https://github.com/synchain-oss/opentune-mcp-server) | MCP 服务，让 AI agent 读取音高、自动修音、改音符、编排、导出和保存（早期版本）<br>MCP server that lets AI agents read pitch, auto-tune, edit notes, arrange, export and save (early release) | MIT |
| [OpenTune（非官方 fork）](https://github.com/synchain-oss/OpenTune) | 加上本机控制接口的 fork，提供非官方测试版：Windows x64，以及还没在真机上测过的 macOS Apple 芯片版<br>Fork that adds a local control API, with unofficial test builds: Windows x64, plus macOS on Apple silicon (not yet tested on a real Mac) | AGPL-3.0 |
| [OpenTune Beats](https://github.com/synchain-oss/opentune-beats) | 命令行工具，分析伴奏的节拍、小节首拍和速度变化，供 MCP 服务的 `beat-grid` skill 使用<br>Command-line tool that analyzes the beats, downbeats and tempo map of a backing track, used by the MCP server's `beat-grid` skill | MIT |

官网 / Website：[www.synchain.ca](https://www.synchain.ca)
