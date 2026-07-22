<div align="center">

# Ray Jones

**AI academic workflows · Astrometry & Data analysis · Local automation**

[![Website](https://img.shields.io/badge/sues.fun-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://sues.fun)
[![GitHub](https://img.shields.io/badge/GitHub-yangzhe0-24292f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yangzhe0)

<br />

![Tech stack](https://skillicons.dev/icons?i=python,ts,js,react,nextjs,astro,svelte,nodejs,tailwind,git,docker,vscode)

</div>

---

<table align="center" style="border: none; border-collapse: collapse; width: 100%; margin-bottom: 20px;">
  <tr style="border: none;">
    <td valign="top" style="border: none; width: 68%; line-height: 1.6;">
      <h2 style="border-bottom: none; margin-top: 0; padding-bottom: 0;">Hi, I'm Ray Jones 👋</h2>
      <p style="margin-top: 10px;">我目前的研究和开发工作主要围绕三个核心领域展开：</p>
      <ol style="padding-left: 20px; margin-top: 5px;">
        <li style="margin-bottom: 6px;"><strong>AI 与学术知识流</strong>：基于本地 LLM 与 RAG 技术，构建高效、可追踪的前沿论文捕获与研究助理工具。</li>
        <li style="margin-bottom: 6px;"><strong>天体测量与数据分析</strong>：高精度处理天文/工业观测数据、改正星表系统差，并提供智能诊断与计算服务。</li>
        <li style="margin-bottom: 6px;"><strong>本地自动化与个人生态</strong>：优化日常重复的工作流程，将工具开发与个人网站、简历系统紧密结合。</li>
      </ol>
      <p style="margin-top: 15px; margin-bottom: 0;">这里展示了我对高效工作流的探索，以及将学术研究和日常开发打磨成易于理解、运行和复用的开源工具的尝试。</p>
    </td>
    <td valign="middle" align="center" style="border: none; width: 32%; padding-left: 20px;">
      <img src="avatar.jpg1" width="220" style="border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);" alt="Ray Jones" />
    </td>
  </tr>
</table>

<div align="center">
<br />

<kbd>local RAG agent</kbd>
<kbd>arxiv intelligence</kbd>
<kbd>astrometry & orbit</kbd>
<kbd>local automation</kbd>
<kbd>reproducible research</kbd>

</div>

---

## Build Areas

| Area | Focus | Key Projects |
|---|---|---|
| [AI Academic Workflows](#ai-driven-academic-workflows) | 本地学术 RAG、前沿论文监测流水线、AI 开发对话归档 | **ScholarPulse**, **PaperAgent**, **Trae Exporter** |
| [Scientific Research & Data Analysis](#scientific-research--data-analysis) | 木卫星历计算、历史观测标准化、星表系统差改正、列车轴承故障诊断 | **ANCOJ**, **Star Catalog Bias**, **study_shumo** |
| [Local Automation & Ecosystem](#local-automation--personal-ecosystem) | 个人写作平台、本地局域网媒体管理、自动化简历部署 | **sues.fun**, **Local Video Manager**, **Resume Site** |

---

## AI-Driven Academic Workflows

探索如何利用大模型和检索增强生成（RAG）技术，优化个人的学术追踪与代码资产管理。

*   [**ScholarPulse**](https://github.com/yangzhe0/project_scholarpulse)：
    本地优先、无第三方依赖的前沿研究情报监测流水线。通过 arXiv Atom API 自动捕获最新论文，归一化去重并调用本地 Ollama (Qwen) 生成结构化中文日报与概览索引。每日通过 systemd 定时调度，成果原子化落盘于 Obsidian，并基于通知契约（JSON）触发 OpenClaw 向 Telegram 投递消息。
*   [**PaperAgent**](https://github.com/yangzhe0/project_paperagent) | [**Demo**](https://paper.sues.fun)：
    面向学术论文的本地知识库问答 Agent。基于 Streamlit 框架，集成 MinerU 深度解析、BGE-M3 向量化与 FAISS 检索。设计了**混合查询路由**，优先通过确定性索引处理作者、对比等精确查询，开放式问题再流式进入本地大模型（Ollama）的 RAG 链条，并提供文件级的来源追踪与运行耗时诊断。
*   [**Trae Chat Exporter**](https://github.com/yangzhe0/project_trae_exporter)：
    专门针对 Trae 研发智能体的对话导出工具。利用远程调试协议，自动进行长对话多轮滚动扫描，一键导出生成便于阅读的 HTML、便于整理的 Markdown 以及保留消息元数据的 JSON，完美保存 AI 辅助编程的交互记录。

---

## Scientific Research & Data Analysis

专注于将物理模型与数据算法工程化，解决天文观测与工业诊断中的实际数据问题。

*   **ANCOJ (A New Catalogue of Observations of Jupiter)**：
    *(私有仓库)* 整理、清洗并标准化了 IMCCE 记录的 **57,258** 条木星卫星历史观测数据。使用 SOFA 库将各种混乱的时间尺度统一转换为 **地球时 (TT)**，并在三维空间向量层面实现了 TOD (True of Date) 到 **ICRS** 坐标系的精密转换，为动力学模型拟合提供了最干净的底噪数据。
*   [**Star Catalog Systematic Bias Correction**](https://github.com/yangzhe0/project_scb)：
    一个全天区星表系统差改正系统。通过在 HEALPix 网格上与 Gaia DR3 进行交叉匹配，推导并平滑了 **17 个历史星表**（包含 USNO-A2.0, AGK3, UCAC4 等）的位置与自行系统偏差。采用 cuML KDTree 进行 GPU 加速匹配（匹配耗时缩短 14 倍），并基于 RBF 薄板样条插值生成连续的全天区改正图。
*   [**Ephemeris & Finder Chart Tool**](https://github.com/yangzhe0/project_ephemeris)：
    基于 Flask 开发的轻量级观测辅助 Web 工具。实时对接 SAI MSU 星历服务器，自动将北京时间转换为 UTC 并进行高精度计算，同时自动从 STScI 下载对应的 DSS 数字化巡天图像，绘制并预览带视场范围（FOV）的卫星寻星图。
*   [**study_shumo (轴承故障诊断)**](https://github.com/yangzhe0/study_shumo)：
    基于 Jupyter Notebook 的高速列车轴承故障诊断研究。使用时频分析与机器学习算法对轴承振动信号进行特征提取与分类。

---

## Local Automation & Personal Ecosystem

打磨本地工具与发布系统，将知识沉淀和个人名片转为高效的自动化资产。

*   [**sues.fun (tool_blog)**](https://github.com/yangzhe0/project_blog)：
    基于 Astro、Svelte、Tailwind CSS 和 Pagefind 搜索引擎构建的个人静态博客与写作系统，也是我整理工具开发记录、科研验证与学习笔记的长期台架。
*   [**Local Video Manager (tool_video)**](https://github.com/yangzhe0/project_video)：
    本地视频整理与多端浏览工具。包含一个桌面端批处理程序（FFmpeg 批量去片头片尾、自动视频抽帧并生成同名缩略图）和一个基于 Flask 的局域网视频管理网站（支持移动端响应式播放、按标签筛选、文件名搜索、重命名以及软删除）。
*   **Resume & Materials Sites** | [**Resume**](https://me.sues.fun) · [**Materials**](https://cj.sues.fun)：
    *(私有仓库)* 部署在 Vercel 上的个人简历与证明材料静态展示站点，配置了 Puppeteer 自动化构建脚本，支持每次修改网页简历提交后，云端全自动渲染并输出为用于打印的 PDF 版本。

---

## Public Entry Points

| Direction | Entry | Why it exists |
|---|---|---|
| AI Academic Pipeline | [ScholarPulse](https://github.com/yangzhe0/project_scholarpulse) | Automate arXiv paper discovery, local Ollama summaries, Obsidian archiving, and Telegram notifications. |
| Academic RAG Agent | [PaperAgent](https://github.com/yangzhe0/project_paperagent) | A local paper-QA workflow with deterministic route and file-level source tracking. |
| AI Chat Backup | [Trae_Chat_Exporter](https://github.com/yangzhe0/project_trae_exporter) | Export active Trae conversations to structured HTML/MD/JSON over debug port. |
| Catalog Systematic Correction | [star_catalog_bias](https://github.com/yangzhe0/project_scb) | Publish positions and proper motions correction tables for 17 historical catalogs against Gaia DR3. |
| Observation Ephemeris | [study_ephemeris](https://github.com/yangzhe0/project_ephemeris) | Real-time Jovian satellite ephemeris calculator and DSS finder chart builder. |
| Bearing Fault Diagnosis | [study_shumo](https://github.com/yangzhe0/study_shumo) | Diagnostic research on high-speed train bearings using Jupyter notebooks. |
| Local Media Management | [tool_video](https://github.com/yangzhe0/project_video) | Batch process local videos and host a mobile-friendly local streaming web server. |
| Personal Publishing | [tool_blog](https://github.com/yangzhe0/project_blog) | Maintain sues.fun as a long-term personal knowledge database and writing system. |
| Resume Hosting | [Resume Site](https://me.sues.fun) | Static me.sues.fun & cj.sues.fun websites with automated Puppeteer PDF generation. |

---

<div align="center">
<br />

<strong>More notes and project writing live at <a href="https://sues.fun">sues.fun</a>.</strong>

</div>
