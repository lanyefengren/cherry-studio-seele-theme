# Black.css - CherryStudio Seele Theme

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![GitHub release](https://img.shields.io/github/release/username/Black.css.svg)]()


## 安装

### 方法一：直接下载

1. 下载 [Black.css](./Black.css) 文件
2. 打开 Cherry Studio 设置
3. 进入「显示设置」→「自定义CSS」
4. 导入或粘贴CSS内容

### 方法二：克隆仓库

```bash
git clone https://github.com/yourusername/Black.css.git
```

## 配置

### 设置背景图片

在CSS文件中找到以下变量并修改：

```css
--chat-background-image: url("你的图片地址");
```

支持：
- 本地文件路径（如 `file:///C:/path/to/image.jpg`）
- 在线图片URL（如 `https://example.com/image.jpg`）

### 自定义颜色

所有颜色都通过CSS变量定义，可以在 `:root` 中修改：

```css
:root {
    --gradient-assistant: linear-gradient(135deg, rgba(45, 45, 45, 0.95), rgba(35, 35, 35, 0.9));
    --gradient-user: linear-gradient(135deg, rgba(40, 40, 40, 0.75), rgba(30, 30, 30, 0.7));
    /* 更多变量... */
}
```

## 功能说明

### 输入框跑马灯效果

当AI智能体运行时，输入框会显示动态渐变边框：

- **激活条件**：
  - 输入框获得焦点时
  - AI正在生成回复时
  - 手动添加 `.ai-active` 类

- **颜色方案**：
  - 爱马仕橙 `#ff6a01`
  - 紫罗兰 `#8a2be2`
  - 青色 `#00d4ff`

### AI状态指示器

- **思考状态**：输入框显示脉冲动画
- **运行状态**：显示状态指示点
- **数据流动**：背景显示流动效果

## 浏览器兼容性

| 浏览器 | 支持版本 |
|--------|---------|
| Chrome | 88+ |
| Firefox | 78+ |
| Safari | 14+ |
| Edge | 88+ |

### 已知问题

- 某些旧版浏览器可能不支持 `mask-composite` 属性
- 建议使用最新版本浏览器以获得最佳体验

## 许可证

本项目采用 [GNU Affero General Public License v3.0](./LICENSE) 或更高版本许可。

### 重要说明

- 你可以自由使用、修改和分发本软件
- 任何修改版本必须以相同许可证发布
- 网络使用（如SaaS）也要求提供源代码
- 必须保留原始版权声明和许可证文本

### 来源

本项目包含来自以下项目的代码或灵感：

| 项目 | 许可证 | 用途 |
|------|--------|------|
| [just-flowing-border.css](https://github.com/Cle2ment/CherryStudio_themes/blob/master/themes/just-flowing-border.css) | MIT-like | 输入框动画效果 |
| [LuminaFlow.css](https://github.com/RMSHE-MSH/LuminaFlow-for-CherryStudio) | AGPL-3.0 | CSS组织结构灵感 |
| CherryStudio-by-bilibili.css | Unknown | 主题概念参考 |
| Hatsune Miku.css | Unknown | 变量组织参考 |

详见 [NOTICE](./NOTICE) 文件。

## 贡献

欢迎贡献代码、报告问题或提出建议！






## 致谢

- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - 优秀的AI客户端
- 所有参考项目的作者
- 社区贡献者

---
- 这是本人在GitHub上发布的第一个项目，尚处于学习与探索阶段。
- 如有任何问题或建议，欢迎通过Issue提出，非常感谢您的关注与指教！

