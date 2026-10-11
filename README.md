# 蝴蝶诗人 | ButterflyPoet 工程作品集

这是一个面向电子工程、嵌入式系统、控制与自动化方向的个人作品集网站，使用原生 HTML、CSS 和 JavaScript 编写，通过 GitHub Pages 免费部署，无需服务器或前端构建工具。

> 当前版本：**V1.3**。网站内的示例项目及描述为占位内容，正式公开个人经历前应替换为真实资料。

## 网站功能

- 中英文界面切换（中文名称：**蝴蝶诗人**；英文名称：**ButterflyPoet**）。
- 浅色、深色主题切换，首页科幻背景自动适配主题。
- 蓝青紫渐变、SVG 参数化曲线、缓慢流动光晕与装饰性轨道。
- 项目卡片、分类筛选及工程项目详情弹窗。
- 技术笔记、经历时间轴、技术栈和联系方式。
- 时间轴滚动进入动画、响应式布局及减少动画偏好适配。

## 文件结构

```text
ButterflyPoet.github.io/
├── index.html                       # 网站入口
├── README.md                        # 中文项目说明
├── CHANGELOG.md                     # 版本更新日志
├── assets/
│   ├── css/
│   │   ├── style.css                # 基础布局与组件样式
│   │   └── sci-fi-background.css    # 科幻背景样式与动画
│   ├── images/
│   │   └── parametric-waves.svg     # 参数化曲线图案
│   └── js/
│       ├── data.js                  # 项目、时间轴等数据
│       └── main.js                  # 页面交互逻辑
└── lang/
    ├── zh.json                      # 中文文案
    └── en.json                      # 英文文案
```

## 部署与更新

1. 在 GitHub 创建公开仓库 `ButterflyPoet.github.io`（用户名为 ButterflyPoet 时）。
2. 将本压缩包**解压后的内容**上传至仓库 `main` 分支的根目录，替换同名文件。
3. 在仓库 **Settings → Pages** 中选择 **Deploy from a branch → main → /(root)**。
4. 等待 Actions 部署成功，访问 https://butterflypoet.github.io/ 。

以后更新只需要上传修改过的文件，不必重复创建仓库或重新设置 Pages。建议每次发布前保留 Git 提交记录，以便回滚。

## 日常维护

- 修改个人介绍、双语文案：`lang/zh.json`、`lang/en.json`。
- 修改项目、时间轴、技术栈等数据：`assets/js/data.js`。
- 修改页面结构和链接：`index.html`。
- 修改常规布局、颜色与卡片：`assets/css/style.css`。
- 修改首页渐变、曲线和光效：`assets/css/sci-fi-background.css` 与 `assets/images/parametric-waves.svg`。
- 每次发布新版本时更新 `CHANGELOG.md`；`README.md` 只保留当前项目说明。

## 内容与版权提醒

当前网站中的项目示例不代表本人已经完成的工程成果。公开课程作业、团队项目、工程源码、照片或实验数据前，请先确认课程规定、知识产权及相关人员授权。网站视觉方向参考 Lain-Ego 公开作品集，代码与装饰性图形为独立实现。
