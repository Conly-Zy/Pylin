# 专业级Linux服务器巡检工具 (v8.0)

这是一款基于Python和PyQt5开发的图形化（GUI）Linux服务器巡检工具。它旨在提供一个美观、易用且功能强大的界面，以满足三级等保要求下的Linux服务器日常巡检需求。

## ✨ 核心功能

- **现代化UI**: 采用专业、护眼的暗色主题开发者控制台风格。
- **SSH连接管理**: 独立的连接/断开功能，并有清晰的状态指示灯。
- **实时命令控制**:
    - 支持通过拖动行号来**实时调整巡检命令的执行顺序**。
    - 支持动态添加、编辑和删除巡检项。
    - 支持一键恢复默认巡检列表（带安全确认）。
- **多样化报告导出**:
    - 一键生成**带有数据可视化图表**的精美HTML报告。
    - 支持导出一目了然的纯文本（TXT）报告。
- **模块化设计**: 项目代码结构清晰，遵循关注点分离原则，易于维护和扩展。


## 🛠️ 技术栈 (Tech Stack)

- **核心语言**: Python 3
- **GUI框架**: PyQt5
- **远程连接**: Paramiko
- **报告生成**: Jinja2 (用于HTML模板)
- **样式**: QSS (Qt Style Sheets)

