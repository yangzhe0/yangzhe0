<div align="center">

# Ray Jones

**Local tools · Writing system · Astronomy research**

[![Website](https://img.shields.io/badge/sues.fun-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://sues.fun)
[![GitHub](https://img.shields.io/badge/GitHub-yangzhe0-24292f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yangzhe0)

</div>

## Hi, I'm Ray Jones

我在做的东西大概可以分成三类：把日常重复工作变成小工具，把学习和研究沉淀到个人网站里，把天文数据处理过程整理成可以复现的代码和结果。

这个 Profile 不是想做一个仓库目录，而是想给人一个快速印象：我关心真实工作流，也喜欢把杂乱的实验过程打磨成能被别人理解、运行和继续使用的东西。

<div align="center">

<kbd>local tools</kbd>
<kbd>writing system</kbd>
<kbd>astronomy data</kbd>
<kbd>research code</kbd>
<kbd>reproducible artifacts</kbd>

</div>

## Build Areas

| Area | Focus |
|---|---|
| [Local Workflow Tools](#local-workflow-tools) | 小型本地工具、自动化流程、媒体管理、AI 对话归档 |
| [Writing System](#writing-system) | 个人网站、长期笔记、项目文档、可检索知识库 |
| [Astronomy Research](#astronomy-research) | 星历工具、自然卫星观测、星表系统差改正、可复现科研代码 |

## Local Workflow Tools

我会把自己反复遇到的麻烦做成小工具。它们通常不是为了展示某个技术栈，而是为了把一个真实流程变短、变稳、变容易回头检查。

**Trae Chat Exporter** 把 Trae 当前打开的对话导出成 `HTML`、`Markdown` 和 `JSON`。它适合保存长对话、整理 AI 辅助开发记录，也方便把聊天内容变成后续可处理的数据。

**tool_video** 是一个本地视频管理系统，重点放在手机访问时的性能和体验：分页加载、缩略图缓存、单实例播放器、分类过滤、重命名和软删除，都是围绕本地媒体库的真实使用做的。

## Writing System

[sues.fun](https://sues.fun) 是我的个人网站，也是把工具、研究、学习笔记慢慢沉淀下来的地方。它背后的 **tool_blog** 基于 Astro、Svelte、Tailwind CSS 和 Pagefind，包含文章、归档、搜索、RSS、暗色模式、多语言文本和 Markdown 插件。

我希望它不只是“博客”，而是一个持续整理知识和项目的工作台：工具怎么做出来、科研代码怎么验证、踩过的坑怎么复用，都可以在这里变成长期内容。

## Astronomy Research

这部分是我更偏科研的工作。**study_ephemeris** 把自然卫星星历、观测参数和 DSS 寻星图接到一个 Flask Web 工具里，适合把观测前的计算与查图流程做得更直接。

**star_catalog_bias** 是目前更适合作为成果入口的仓库：它提供 17 个历史星表相对于 Gaia DR3 的空间分辨位置与自行系统差改正表，按 HEALPix 网格组织，并附带全天系统差图、统计分布图和最小查询脚本。

<div align="center">

<a href="https://github.com/yangzhe0/star_catalog_bias">
  <img width="720" src="https://raw.githubusercontent.com/yangzhe0/star_catalog_bias/main/ucac4_systematics_map.png" alt="UCAC4 systematic bias map" />
</a>

</div>

## Public Entry Points

| Direction | Entry | Why it exists |
|---|---|---|
| AI workflow archive | [Trae_Chat_Exporter](https://github.com/yangzhe0/Trae_Chat_Exporter) | Preserve and reuse long AI coding conversations |
| Local media workflow | [tool_video](https://github.com/yangzhe0/tool_video) | Manage a local video library from mobile devices |
| Personal publishing | [tool_blog](https://github.com/yangzhe0/tool_blog) | Maintain sues.fun as a long-term writing system |
| Observation helper | [study_ephemeris](https://github.com/yangzhe0/study_ephemeris) | Generate ephemeris results and finder charts |
| Research result | [star_catalog_bias](https://github.com/yangzhe0/star_catalog_bias) | Publish catalog systematic-bias correction tables |

## Stack

<div align="center">

![Tech stack](https://skillicons.dev/icons?i=python,ts,js,react,nextjs,astro,svelte,nodejs,tailwind,git,docker,vscode)

</div>

<div align="center">
<br />

<strong>More notes and project writing live at <a href="https://sues.fun">sues.fun</a>.</strong>

</div>
