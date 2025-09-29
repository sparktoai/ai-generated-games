# 舒尔特方格训练游戏 & 2048游戏 (Schulte Table Training Game & 2048 Game)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-green.svg)
![Language](https://img.shields.io/badge/language-JavaScript-yellow.svg)

## 项目简介

舒尔特方格训练游戏是一个基于Web的注意力训练工具，旨在帮助用户提高专注力、视觉搜索能力和认知处理速度。该工具采用经典的舒尔特方格训练方法，通过按顺序查找和点击随机排列的数字来锻炼大脑。

我们还添加了经典的2048数字合并游戏，玩家需要在网格上滑动数字方块，将相同数字的方块合并，最终创造出2048方块。

## 功能特性

### 舒尔特方格训练游戏
- 🎮 **多种难度级别**：支持3×3、5×5、7×7、8×8四种难度
- 🌍 **多语言支持**：提供中英文两个版本
- ⏱️ **实时计时**：精确记录完成时间
- 📊 **成绩评估**：根据完成时间和难度给出智能评价
- 📈 **历史记录**：自动保存最近10次训练记录
- 🎨 **响应式设计**：适配各种设备屏幕
- 💾 **本地存储**：使用浏览器localStorage保存数据
- ✅ **即时反馈**：正确和错误操作的视觉反馈

### 2048游戏
- 🎮 **经典4x4网格**：传统2048游戏体验
- 🌍 **多语言支持**：提供中英文两个版本
- 📊 **分数追踪**：实时分数计算和最高分存储
- 🎨 **响应式设计**：适配桌面、平板和移动设备
- ⌨️ **键盘控制**：支持方向键操作
- 👆 **触摸支持**：支持移动设备滑动操作
- 💾 **本地存储**：最高分保存在浏览器localStorage中
- ✨ **流畅动画**：方块移动和合并动画效果

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- localStorage API

## 演示地址

### 舒尔特方格训练游戏
- [英文版](https://sparktoai.com/ai-generated-games/schulte-table-game.html)
- [中文版](https://sparktoai.com/zh/ai-generated-games/schulte-table-game.html)

### 2048游戏
- [英文版](https://sparktoai.com/ai-generated-games/2048-game.html)
- [中文版](https://sparktoai.com/zh/ai-generated-games/2048-game.html)

## 开发过程

### 舒尔特方格训练游戏
- [英文版](https://sparktoai.com/articles/schulte-table-game.html)
- [中文版](https://sparktoai.com/zh/articles/schulte-table-game.html)

### 2048游戏
- [英文版](https://sparktoai.com/articles/2048-game.html)
- [中文版](https://sparktoai.com/zh/articles/2048-game.html)

## 快速开始

### 在线体验

直接在浏览器中打开以下文件之一：

#### 舒尔特方格训练游戏
- 英文版: `schulte-table-game.html`
- 中文版: `zh/schulte-table-game.html`

#### 2048游戏
- 英文版: `2048-game.html`
- 中文版: `zh/2048-game.html`

### 本地运行

1. 克隆或下载此仓库
2. 在浏览器中打开任意HTML文件：
   - `schulte-table-game.html` 或 `zh/schulte-table-game.html`
   - `2048-game.html` 或 `zh/2048-game.html`

### 使用方法

#### 舒尔特方格训练游戏
1. 选择合适的难度级别
2. 点击任意数字开始游戏
3. 按顺序点击数字（从1到最大数字）
4. 查看完成时间和系统评价
5. 继续训练以提高成绩

#### 2048游戏
1. 使用方向键或滑动手势移动方块
2. 相同数字的方块接触时会合并成一个
3. 每次移动后会随机出现一个新方块（2或4）
4. 合成2048方块即为胜利
5. 当棋盘填满且无法合并时游戏结束

## 训练原理 (舒尔特方格)

舒尔特方格是心理学中用来研究和发展注意力的常用方法。训练时，神经元必须快速扫描并识别目标数字，同时抑制其他数字的干扰。长期坚持训练可以：

- 提高视觉注意力
- 增强专注力集中程度
- 加快信息处理速度
- 改善视觉搜索能力

## 文件结构

```
.
├── zh/
│   ├── schulte-table-game.html  # 舒尔特方格中文版本
│   └── 2048-game.html           # 2048游戏中文版本
├── README.md                   # 项目说明文档（英文）
├── README_zh.md                # 项目说明文档（中文）
├── schulte-table-game.html     # 舒尔特方格英文版本
└── 2048-game.html              # 2048游戏英文版本
```

## 浏览器兼容性

- Chrome 50+
- Firefox 45+
- Safari 10+
- Edge 15+

## 开发说明

该项目完全使用原生Web技术构建，无需额外依赖。代码结构清晰，易于维护和扩展。

### 代码特点

- 面向对象设计 (SchulteGridGame 类, Game2048 类)
- 语义化HTML结构
- 响应式CSS设计
- 模块化的JavaScript实现

## 贡献指南

欢迎提交Issue和Pull Request来改进这个项目。

## 许可证

本项目采用MIT许可证，详情请见 [LICENSE](LICENSE) 文件。

## 致谢

感谢所有为这个项目做出贡献的开发者和用户。