# HOOST · 五语言科研项目网站 / Multilingual research project page

## 公开访问 / Public access

- **科研主页 / Research website:** [https://liudan518.github.io/HOOST/](https://liudan518.github.io/HOOST/)
- **论文 PDF 全文 / Full-text PDF（约 10.6 MB）:** [https://liudan518.github.io/HOOST/HOOST.pdf](https://liudan518.github.io/HOOST/HOOST.pdf)
- **BibTeX 引文 / Citation download:** [https://liudan518.github.io/HOOST/S0950705124007767.bib](https://liudan518.github.io/HOOST/S0950705124007767.bib)
- **DOI 原文 / Publisher DOI:** [https://doi.org/10.1016/j.knosys.2024.112142](https://doi.org/10.1016/j.knosys.2024.112142)
- **部署记录 / Deployment history:** [GitHub Actions](https://github.com/liudan518/HOOST/actions)

网页、论文 PDF 与 BibTeX 均可公开访问，无需登录。
The website, paper PDF and BibTeX are publicly accessible without signing in.

本项目通过 GitHub Pages 发布；更新 `main` 分支后会自动构建并部署。
The site is hosted on GitHub Pages and redeploys automatically when `main` is updated.

## Quick start / 使用方法

1. 解压 ZIP 并保留整个 `HOOST_Modern_Multilingual_Website` 目录。
2. 双击 `index.html` 浏览；页面、图片和语言资源均为本地静态文件，无需安装前端框架或联网。
3. 网站可直接部署至 GitHub Pages、Netlify 或任意静态网站服务器。将整个目录内容上传至站点根目录即可。
4. 在网站右上角选择中文、English、Русский、Français 或 العربية。阿拉伯语自动采用从右向左（RTL）排版。

Extract the ZIP, keep the entire website directory, and open `index.html` in a modern browser. The website is fully static and also suitable for GitHub Pages or other static hosting. Language switching covers navigation, research descriptions, captions, table headings, chart explanations, and interactive controls.

## Contents / 文件结构

- `index.html` — 网页主体、响应式 CSS、图像弹窗及交互逻辑。
- `i18n.js` — 五种语言的完整界面与研究解读文案，便于后续调整翻译。
- `S0950705124007767.bib` — 来自用户附件的完整出版社 BibTeX（已与页面展示及一键复制保持一致）。
- `images/` — 从原网页沿用的 10 幅科研图和 6 张表格图片。网页引用了其中 16 张独立原图；图 6 在两处内容中重复展示。
- `HOOST.pdf` — 随原 ZIP 提供的原始论文稿件。
- `previews/` — 五语言桌面预览和移动端预览。

## Design changes / 改版要点

- 采用更强的标题层级、宽屏留白、深蓝色科研主视觉、局部高亮和模块化方法卡片。
- 正文使用两端对齐；图文分栏及科研插图保留原始比例，并设置合适的最大显示高度。
- 核心对比结果加入可访问的 HTML 表格，同时保留原论文表格图片供交叉核对。
- 移动端优化导航和长表格水平滚动；阿拉伯语使用 RTL，公式、引文和数字表格保留 LTR 阅读方向。
- 插图点击放大，支持 Escape 关闭；BibTeX 一键复制。
- 本站未从第三方加载字体或脚本，不含遥测或分析代码。

## Research integrity / 科研信息说明

- 论文中的测量数值及原始图表沿用所提供的 HOOST 网站与 PDF；结果对比中的 17.60 pp 表示**百分点差**。
- 顶部特征空间点图为**概念性示意**，不属于实验结果。
- **BibTeX 已修正**：参考用户提供的 `S0950705124007767.bib`，使用正式发表条目 `@article{LIU2024112142,...}`：Dan Liu 等，*Knowledge-Based Systems*，2024，300，112142，DOI `10.1016/j.knosys.2024.112142`。正文显示、复制和独立下载的 BibTeX 一致。
- 网页不宣称研究数据或代码已经开放。
- 俄语、法语和阿拉伯语已进行机器辅助学术翻译与术语一致性处理；正式对外发表前建议由对应语言的领域研究人员复核。
- 公开部署论文 PDF 和原始论文图件前，请确认相应授权和著作权政策。

## Source visual inspiration / 设计参考

Visual hierarchy and modular single-page academic landing-page practices were informed by `https://quzhan51496.github.io/paper2anything/`. This HOOST page uses independently authored HTML/CSS and does not copy site source code or assets from that reference.
