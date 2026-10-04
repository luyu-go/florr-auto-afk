# florr-auto-afk (Auto-Start Edition)

基于 [Shiny-Ladybug/florr-auto-afk](https://github.com/Shiny-Ladybug/florr-auto-afk) 改编。

在原项目基础上增加了 **自动启动** 功能：程序启动后自动开始挂机，无需手动点击运行按钮。

## 与原版的关系

本项目是原项目的衍生作品（derivative work），遵循原项目的
GNU General Public License v3.0 许可证。

- 原项目仓库：https://github.com/Shiny-Ladybug/florr-auto-afk
- 原项目作者：Shiny-Ladybug
- 原项目许可证：GNU General Public License v3.0
- 本改编版新增：自动启动逻辑

## 使用说明

### 运行环境

- Windows 10/11
- 建议 Python 3.11（源码运行）
- 直接运行打包版 `segment.exe` 无需 Python

### 快速开始

1. 将 `segment.exe` 与 `gui/`、`models/`、`capture/`、`extensions/`、
   `config.json`、`conversation.json`、`extension.swap.json` 放在同一目录
2. 右键 `segment.exe` -> 以管理员身份运行
3. 程序启动后会自动开始挂机

### 配置

编辑 `config.json` 可以调整各项参数。详见原项目 [Settings.md](https://github.com/Shiny-Ladybug/florr-auto-afk/blob/main/Settings.md)。

## 许可证

本项目采用 GNU General Public License v3.0 发布。
详见 [LICENSE](./LICENSE) 文件。

## 免责声明

**使用本项目即表示你已知悉并接受以下风险：**

1. 本工具仅用于个人学习和技术研究。
2. 使用自动化脚本可能违反 florr.io 的服务条款，**可能导致账号被封禁**。
3. 作者不对因使用本工具而产生的任何后果负责，包括但不限于账号封禁、数据丢失。
4. 本软件按“原样”提供，不提供任何明示或暗示的担保。

完整免责声明请见 [DISCLAIMER.md](./DISCLAIMER.md)。

## 致谢

感谢 [Shiny-Ladybug](https://github.com/Shiny-Ladybug) 开发的原项目。