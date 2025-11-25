# 观山月 —— 网页设计与制作期末作业

**课程**：网页设计与制作  
**作者**：nayuta  
**完成时间**：2025年11月  
**主题**：观山月  
**访问方式**：双击 `index2.html` 即可本地预览（推荐Chrome/Edge/Firefox）

---

## 网站预览

![首页](./screenshot/index.png)
![松风谱-黑胶唱片页](./screenshot/leyin.png)
![砚山集-文章详情](./screenshot/wenji.png)
![镜月志-猫咪专栏](./screenshot/tusu.png)
![足迹-ai大模型](./screenshot/zuji.png)

> （若图片未能正常显示，请打开子文件夹screenshots进行查看）

---

## 站点结构

- 根目录页面
    - `index2.html` — 首页
    - `yinzi.html`  — 引子（自我介绍 + 留言表单）
    - `wenji_.html` — 砚山集（文章目录 / 文章列表页）
    - `tusu_.html`  — 镜月志（摄影时间轴 / 相册索引）
    - `leyin_.html` — 松风谱（音乐墙 / 专辑展示）
    - `mood.html`   — 足迹（基于个人数据的ai大模型对话）
    - `frame_lowkey.html` — 框架演示页（作业要求演示）

- 页面截图
    - `screenshots/` — 预览截图文件夹（包含各页面截图）

- 内页（inner页面）
    - 单曲页（唱片详情）、单篇文章详情、单张摄影单页等  

- my-ai-chat（大模型配置文件）
    - .env（api key）  
    - `mood.html`（大模型交互页面）
    - server.js（中转接口）
---

## 作业要求对照表

| 作业要求            | 实现方式                                          | 具体位置                     |
|---------------------|---------------------------------------------------|------------------------------|
| 清晰结构+多页面     | 首页 + 四大栏目 + 详情页                         | 全站                         |
| 统一风格            | 纯黑极简 + Noto Serif SC + 粘性顶部导航          | 全站                         |
| 文本/图片/超链接    | 个人原创文章、摄影作品、跳转链接                 | 全站                         |
| 表格                | 心情日历使用 `<table>`                           | mood.html                    |
| AP Div（绝对定位）  | 黑胶唱片、唱针、封面叠加                         | leyin_inner1.html            |
| 框架                | 全屏 `<iframe>`（视觉无感知）                    | frame_lowkey.html            |
| 表单                | 完整留言表单（文本、单选、多选、文件上传）       | yinzi.html                   |
| CSS                 | Flex、Grid、动画、响应式                 | 各页面内联 style             |
| 行为（JavaScript）  | ① 黑胶唱片播放+旋转<br>② 专辑墙实时搜索<br>③ 下拉菜单<br>④ 年份切换 | leyin_inner1.html<br>leyin_.html<br>mood.html |
| 创意与美观          | 黑胶唱片播放器、猫咪第一人称叙述、杂志布局等、大模型    | 全站                         |

---

## 技术栈

- 纯原生 HTML + CSS + JavaScript
- Google Fonts
- 全手写代码，无模板修改
- 完全响应式，匹配各种设备
- 大模型：deepseek v3（硅基流动托管）
- 后端：node.js + express(极简api中转，静态文件托管)

---

## 写在最后

感谢这学期《网页设计与制作》课程，  
让我把生活里的山风与月光，装进了这个小小的网站。

> “关山难越观山月，观尽山月越关山。”

—— nayuta · 2025