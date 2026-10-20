<p align="center">
  <img src="assets/banner.png" width="100%" alt="Ding Chen">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=2800&pause=800&color=FF79C6&center=true&vCenter=true&width=620&lines=Hi%2C+I%27m+Ding+Chen;Turning+one+sentence+into+real+results;Two+projects%2C+two+totally+different+problems" alt="Ding Chen">
</p>

<p align="center">
  <a href="mailto:dc59763551@163.com"><img src="https://img.shields.io/badge/Email-dc59763551%40163.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/549763551"><img src="https://img.shields.io/badge/GitHub-549763551-8B5CF6?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://549763551.github.io/spider-solitaire/"><img src="https://img.shields.io/badge/Live%20Demo-Spider%20Solitaire-22C55E?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Demo"></a>
  <img src="https://komarev.com/ghpvc/?username=549763551&style=for-the-badge&color=DB2777&label=VISITORS" alt="Visitors">
</p>

<p align="center">
  <img src="assets/divider.png" width="100%" alt="">
</p>

### 🌈 About · 关于我

- 🛰 **正在构建** — **GeoAgent**：把遥感分析从「写脚本」变成「说一句话」
- 🃏 **也在做** — 一个零依赖的纯前端纸牌游戏，顺手把前端基本功练一遍
- 🧠 **关注** — 智能体的任务规划与工具调度、栅格数据处理、可交互的 Web 界面
- 💡 **做事方式** — 先把东西做出来，再把它做好

<p align="center">
  <sub>一个偏后端重计算（Python · 栅格数据 · LLM 编排），一个偏前端轻交互（原生 JS · 零依赖）——两边都在练。</sub>
</p>

### 🚀 Selected Work · 精选项目

#### 🛰 GeoAgent · 遥感栅格分析智能体

<p align="center">
  <a href="https://github.com/549763551/geoagent"><img src="assets/preview-geoagent.jpg" width="100%" alt="GeoAgent 工作台"></a>
</p>

用一句自然语言下达遥感分析任务，智能体自主完成 **任务理解 → 记忆召回 → 自主规划 → ReAct 工具调用 → 结果交付**，并实时流式呈现每一步。

- **11 个**遥感分析工具，统一注册表 + OpenAI Function Calling 协议暴露
- **18 个**数据集定义，换研究区只需按目录约定放数据
- 未配置 LLM Key 时**自动降级**为离线规则模式，功能完整可用
- 附演示数据生成脚本：无真实数据也能一条命令跑通全链路

`Python` `FastAPI` `rasterio` `NumPy` `SciPy` `SSE`

<p align="left">
  <a href="https://github.com/549763551/geoagent"><img src="https://img.shields.io/badge/源码-geoagent-181717?style=flat-square&logo=github&logoColor=white" alt="repo"></a>
  <img src="https://img.shields.io/badge/实测-离线模式%200.9s%20出图-22C55E?style=flat-square" alt="bench">
</p>

#### 🕷 Spider Solitaire · 纯前端蜘蛛纸牌

<p align="center">
  <a href="https://549763551.github.io/spider-solitaire/"><img src="assets/preview-spider.jpg" width="100%" alt="Spider Solitaire"></a>
</p>

**零依赖**的原生 JS 蜘蛛纸牌：单花色 / 双花色 / 四花色三档难度，带计分、计时、撤销、提示、自动收牌与音效。

- 手写牌局引擎（发牌、合法移动判定、自动完成判定），配套**单元测试**
- 不引任何框架与第三方库，断网也能玩
- GitHub Actions 自动部署到 GitHub Pages

`JavaScript` `HTML5` `CSS3` `GitHub Actions` `MIT`

<p align="left">
  <a href="https://549763551.github.io/spider-solitaire/"><img src="https://img.shields.io/badge/在线试玩-立即开一局-22C55E?style=flat-square&logo=googlechrome&logoColor=white" alt="demo"></a>
  <a href="https://github.com/549763551/spider-solitaire"><img src="https://img.shields.io/badge/源码-spider--solitaire-181717?style=flat-square&logo=github&logoColor=white" alt="repo"></a>
</p>

### 🧰 Toolbox · 常用工具

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/rasterio-GDAL-4B8BBE?style=flat-square" alt="rasterio">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="Actions">
</p>

### ✨ Now · 最近

- **2026.10** — 开源 **GeoAgent**：遥感栅格分析智能体，含 11 个工具与离线降级
- **2026.10** — **Spider Solitaire** 上线 GitHub Pages，可直接在线开局
- **2026.10** — 建立 GitHub 主页，开始记录做过的东西

---

<!--
  ═══════════════════════════════════════════════════════════════
  B 方案的动态统计卡片
  说明：目前 3 个仓库、提交数还少，统计卡片会显示接近全 0，反而扣分。
       等仓库和提交积累起来后，删掉这一整段的首尾注释标记即可启用。

  ⚠️ 网络实测（2026.10）：github-readme-stats.vercel.app 与
     github-profile-trophy.vercel.app 在本机网络下连接超时，
     启用前请改为自建实例或换成可达的镜像域名，否则会显示破图。
     已生效的 readme-typing-svg.demolab.com、img.shields.io、
     komarev.com 均实测可达；横幅、页脚与项目预览图都在本仓库内，永不破图。
  ═══════════════════════════════════════════════════════════════

<div align="center">

  <img height="165" src="https://github-readme-stats.vercel.app/api?username=549763551&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=549763551&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="langs">

</div>

-->

<p align="center">
  <img src="assets/footer.png" width="100%" alt="">
</p>

<p align="center"><sub>Thanks for stopping by · 欢迎通过邮件与我联系</sub></p>
