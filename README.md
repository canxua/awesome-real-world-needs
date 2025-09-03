# Awesome Real World Needs 🗂️

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

<!-- Language Selector -->
<div style="text-align: center; margin: 20px 0;">
  <input type="radio" id="lang-en" name="language" checked onclick="switchLanguage('en')">
  <label for="lang-en" style="margin: 0 10px; padding: 8px 16px; border: 1px solid #ddd; border-radius: 4px; cursor: pointer; background: #007acc; color: white;">English</label>

  <input type="radio" id="lang-zh" name="language" onclick="switchLanguage('zh')">
  <label for="lang-zh" style="margin: 0 10px; padding: 8px 16px; border: 1px solid #ddd; border-radius: 4px; cursor: pointer; background: white; color: #333;">中文</label>
</div>

<script>
function switchLanguage(lang) {
  const enContent = document.getElementById('content-en');
  const zhContent = document.getElementById('content-zh');
  const enBtn = document.getElementById('lang-en').nextElementSibling;
  const zhBtn = document.getElementById('lang-zh').nextElementSibling;

  if (lang === 'en') {
    enContent.style.display = 'block';
    zhContent.style.display = 'none';
    enBtn.style.background = '#007acc';
    enBtn.style.color = 'white';
    zhBtn.style.background = 'white';
    zhBtn.style.color = '#333';
  } else {
    enContent.style.display = 'none';
    zhContent.style.display = 'block';
    zhBtn.style.background = '#007acc';
    zhBtn.style.color = 'white';
    enBtn.style.background = 'white';
    enBtn.style.color = '#333';
  }
}
</script>

<div id="content-en">

> A curated list of real-world software needs & ideas mined from various forums (Reddit, V2EX, Zhihu, etc.). A treasure trove of inspiration for developers & open-source contributors.

**Contributions are welcome!** Whether you submit new needs, write crawlers, or improve docs, all forms of participation are greatly appreciated.

---

## 📖 Table of Contents

- [Data Sources](#-data-sources)
- [Needs List](#-needs-list)
- [Project Vision](#-project-vision)
- [How to Contribute](#-how-to-contribute)
- [Contributors](#-contributors)
- [License](#-license)

## 🌐 Data Sources

We currently collect needs from the following platforms (More are welcome!):

| Platform | Section/Keywords | Status |
| :--- | :--- | :--- |
| [V2EX](https://www.v2ex.com/) | `Questions`, `Share Creations`, `Ideas` | ✅ Active |
| [Reddit](https://www.reddit.com/) | `r/SomebodyMakeThis`, `r/lightbulb`, `r/AppIdeas` | ✅ Active |
| [Zhihu](https://www.zhihu.com/) | Questions like `有哪些软件/APP` | 🚧 Planned |
| [Product Hunt](https://www.producthunt.com/) | Upcoming products & discussions | 🚧 Planned |
| [Hacker News](https://news.ycombinator.com/) | `Ask HN` | 🔜 Todo |
| **Weibo, Douban, etc.** | **To be explored** | 💡 Help wanted |

*✅ Active 🚧 Planned 🔜 Todo 💡 Help wanted*

## 📋 Needs List

All needs are categorized by tags and stored in the [`/data`](/data) directory. Each entry contains metadata like source, description, and popularity.

| ID | Title | Source | Tags | Popularity | Status |
| :-- | :--- | :--- | :--- | :--- | :--- |
| 001 | [A tool to auto-organize desktop screenshots by content](https://www.v2ex.com/t/123456) | V2EX | `#tool` `#automation` `#image` | 42 👍 | `open` |
| 002 | [An app to track "who did I lend this to"](https://www.reddit.com/r/SomebodyMakeThis/...) | Reddit | `#app` `#productivity` | 128 👍 | `open` |

**View the full list:**
*   **[Browse all needs (by platform)](/data/by-platform/)**
*   **[Browse all needs (by tag)](/data/by-tag/)**

## 🎯 Project Vision

1.  **Bridge problems and solutions**: Let every "I wish there was an app for..." idea in the world have a chance to be seen and built by talented developers.
2.  **Lower the barrier to inspiration**: Provide developers with a centralized, high-quality source of ideas, saving time spent on aimless searching.
3.  **Build a community**: Bring together creators who love solving real-world problems with technology.

## 🤝 How to Contribute

We greatly appreciate any form of contribution! Please read our [Contribution Guide](CONTRIBUTING.md) for detailed instructions.

**Main ways to contribute:**

1.  **Submit a Need**: If you see an interesting "need" post online, please [submit an Issue](https://github.com/your-username/awesome-real-world-needs/issues/new?template=SUBMIT_NEED.md) and send us the link!
2.  **Contribute Code**: Help us write or improve **crawler scripts** for a platform. Code is in the [`/crawlers`](/crawlers) directory.
3.  **Improve Documentation**: Improve docs, translations, fix typos, etc.
4.  **Discuss & Share**: Discuss the feasibility of needs, or share this project with more people!

## ✨ Contributors

Thanks to all contributors who make this project better! ([emoji key](https://allcontributors.org/docs/en/emoji-key))

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/your-username"><img src="https://avatars.githubusercontent.com/u/your-avatar?v=4" width="100px;" alt="Your Name"/><br /><sub><b>Your Name (You)</b></sub></a><br /><a href="#projectManagement" title="Project Management">📆</a> <a href="#ideas" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</div>

<!-- Chinese Content -->
<div id="content-zh" style="display: none;">

> 一个从各大网络社区（如 V2EX、Reddit、知乎等）收集并精选的真实世界软件需求与创意的仓库。旨在为开源贡献者、产品经理和开发者提供一个源源不断的“灵感宝库”。

**欢迎贡献！** 无论你是提交新的需求链接、编写爬虫，还是完善文档，任何形式的参与都让我们离目标更近一步。

---

## 📖 目录

- [数据来源](#-数据来源)
- [需求列表](#-需求列表)
- [项目愿景](#-项目愿景)
- [如何贡献](#-如何贡献)
- [贡献者](#-贡献者)
- [许可证](#-许可证)

## 🌐 数据来源

我们目前从以下平台采集需求（欢迎推荐更多！）：

| 平台 | 板块/关键词 | 状态 |
| :--- | :--- | :--- |
| [V2EX](https://www.v2ex.com/) | `问与答`、`分享创造`、`奇思妙想` | ✅ 活跃采集 |
| [Reddit](https://www.reddit.com/) | `r/SomebodyMakeThis`, `r/lightbulb`, `r/AppIdeas` | ✅ 活跃采集 |
| [知乎](https://www.zhihu.com/) | `有哪些软件/APP` 类问题 | 🚧 计划中 |
| [Product Hunt](https://www.producthunt.com/) | 即将推出的产品 & 讨论 | 🚧 计划中 |
| [Hacker News](https://news.ycombinator.com/) | `Ask HN` | 🔜 待开始 |
| **微博、豆瓣等** | **待探索** | 💡 寻求贡献 |

*✅ 活跃采集 🚧 计划中 🔜 待开始 💡 寻求贡献*

## 📋 需求列表

所有需求都按标签分类，并存储在 [`/data`](/data) 目录下。每个需求条目包含来源、描述、热度等元数据。

| ID | 标题 | 来源 | 标签 | 热度 | 状态 |
| :-- | :--- | :--- | :--- | :--- | :--- |
| 001 | [需要一个能自动整理电脑桌面截图并按内容分类的软件](https://www.v2ex.com/t/123456) | V2EX | `#工具` `#自动化` `#图片` | 42 👍 | `待解决` |
| 002 | [一个可以记录“我把这个东西借给谁了”的App](https://www.reddit.com/r/SomebodyMakeThis/...) | Reddit | `#应用` `#效率` | 128 👍 | `待解决` |

**查看完整列表：**
*   **[按平台浏览所有需求](/data/by-platform/)**
*   **[按标签浏览所有需求](/data/by-tag/)**

## 🎯 项目愿景

1.  **连接问题与解决方案**：让世界上每一个“要是有个软件能...”的想法，都有被天才开发者看到并实现的机会。
2.  **降低灵感获取门槛**：为开发者提供一个集中式的、高质量的创意来源，省去漫无目的地搜索时间。
3.  **构建社区**：汇聚一群热爱用技术解决现实问题的创造者。

## 🤝 如何贡献

我们无比欢迎任何形式的贡献！请阅读我们的 [贡献指南](CONTRIBUTING.md) 以了解详细流程。

**主要有以下几种方式：**

1.  **提交需求**：如果你在网上看到有趣的“需求”帖子，欢迎[提交一个 Issue](https://github.com/your-username/awesome-real-world-needs/issues/new?template=SUBMIT_NEED.md) 并把链接发给我们！
2.  **贡献代码**：帮助我们编写或完善某个平台的**采集脚本** (Crawler)，代码在 [`/crawlers`](/crawlers) 目录。
3.  **完善文档**：改进文档、翻译、修复错别字等。
4.  **讨论与分享**：讨论需求实现的可行性，或者将这个项目分享给更多的人！

## ✨ 贡献者

感谢所有让这个项目变得更好的贡献者们！([emoji key](https://allcontributors.org/docs/en/emoji-key))

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/your-username"><img src="https://avatars.githubusercontent.com/u/your-avatar?v=4" width="100px;" alt="Your Name"/><br /><sub><b>Your Name (You)</b></sub></a><br /><a href="#projectManagement" title="Project Management">📆</a> <a href="#ideas" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

本项目遵循 [all-contributors](https://github.com/all-contributors/all-contributors) 规范，欢迎任何领域的贡献。

## 📄 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

</div>
