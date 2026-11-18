<div align="center">

<h1><img src="./assets/quantatier-header-q-corner-v1.1r2.png" width="42" alt="">Quantatier</h1>

Tools for quantitative research and strategy workflows

<a href="#darwin"><img src="./assets/quantatier-badge-darwin-compact.png" width="66" height="26" alt="Darwin"></a>&#8201;&#8201;<a href="#cloud"><img src="./assets/quantatier-badge-cloud-compact.png" width="62" height="26" alt="Cloud"></a>&#8201;&#8201;<a href="https://github.com/quantatier-apps/community/discussions"><img src="./assets/quantatier-badge-community-compact.png" width="96" height="26" alt="Community"></a>

<sub><a href="GETTING_STARTED.md">Getting Started</a>&#8201;·&#8201;<a href="https://github.com/quantatier-apps/community/discussions/categories/announcements">Updates</a>&#8201;·&#8201;<a href="https://github.com/quantatier-apps/community/issues/new/choose">Report&#160;an&#160;Issue</a></sub>

</div>

---

## About Quantatier

Quantatier develops tools for quantitative strategy research and workflows. **Darwin** hosts desktop apps for strategy execution, historical backtesting, spread trading, and market-data management. **Cloud** provides strategy version management, backtest task coordination, and report analysis.

This community is a place to learn about the products, ask questions, share ideas, and follow updates.

## Community Guides

| Guide | What you will find |
| --- | --- |
| [Getting Started](GETTING_STARTED.md) | Product guides and where to begin with Darwin or Cloud. |
| [Support](SUPPORT.md) | Where to ask a question, report a problem, and include useful details. |
| [Contributing](CONTRIBUTING.md) | How to participate in discussions and improve the public documentation. |

## Products

### Darwin

<a href="#start-with-darwin"><img src="./assets/quantadarwin-logo-white-plate.png" alt="Quantadarwin — Darwin product introduction" width="220"></a>

**Desktop apps for quantitative research and trading workflows.**

Choose an app for the work you want to do. Each guide explains that app's requirements, operations, and results.

#### Supported apps

##### [CTA Strategy](docs/darwin/cta-strategy.md)

Create and manage single-instrument CTA strategy instances. Initialize, start, stop, and monitor strategies that use configured trading gateways.

##### [CTA Backtester](docs/darwin/local-backtesting.md)

Configure historical CTA backtests in a desktop interface. Review statistics, charts, orders, and trades, and run parameter optimization where supported.

##### [CTA Backtester Plus](docs/darwin/cta-backtester-plus.md)

Execute CTA backtest batches on a Darwin device using local historical data. Tasks are submitted from Cloud; the app saves their results and returns execution status and reports to Cloud.

##### [Spread Trading](docs/darwin/spread-trading.md)

Define spreads made from multiple contract legs and follow calculated spread prices. Run spread algorithms or automated spread strategies through configured trading interfaces.

##### [Data Manager](docs/darwin/data-manager.md)

Inspect and maintain historical market data. Import or export supported CSV files, and download history through configured data services.

##### [Data Recorder](docs/darwin/data-recorder.md)

Select instruments and record supported live tick and bar data to a local database. Monitor recording messages and logs while the market-data connection is active.

[Getting started with Darwin →](#start-with-darwin) · [Ask the community](https://github.com/quantatier-apps/community/discussions)

### Cloud

<a href="#cloud"><img src="./assets/quantacloud-logo-white-plate.png" alt="Quantacloud — Cloud product introduction" width="220"></a>

Cloud supports preparing strategy versions, coordinating backtest tasks with Darwin, and reviewing returned results.

- [Strategy Workspace](docs/cloud/strategy-workspace.md)
- [Tasks & Results](docs/cloud/tasks-and-results.md)

Available features and workflows depend on the product version and configuration.

## Getting Started

### Start with Darwin

Use [Getting Started](GETTING_STARTED.md) to choose an app guide. Follow the installation and setup instructions supplied with your distribution, then use the guide for that app's workflow and requirements.

## Updates and Releases

Find product notes and updates in [Announcements](https://github.com/quantatier-apps/community/discussions/categories/announcements).

## Community

### Help and Feedback

| What you need | Where to go |
| --- | --- |
| Help using or configuring an app | [Q&A](https://github.com/quantatier-apps/community/discussions/categories/q-a) |
| Report a reproducible defect or a specific improvement | [Issues](https://github.com/quantatier-apps/community/issues/new/choose) |
| Read official product changes and community notices | [Announcements](https://github.com/quantatier-apps/community/discussions/categories/announcements) |
| Read the maintainers' series on quantitative systems design | [Engineering](https://github.com/quantatier-apps/community/discussions/categories/engineering) |

See the [Support guide](SUPPORT.md) for a question and issue checklist, or the [Contributing guide](CONTRIBUTING.md) for ways to participate. Our [welcome post](https://github.com/quantatier-apps/community/discussions/1) is another place to start.

When reporting a problem, describe what you were trying to do, what happened, and any steps that help explain it. **Do not share passwords, API keys, account information, private strategies, or other sensitive data in public.**

Corrections and improvements to the public documentation are welcome through pull requests or Issues. Product source code remains private; usage questions and suggestions can be discussed in the community.

## Business Inquiries

For custom development, integration, or other business inquiries, please contact [qtstrategy_web@foxmail.com](mailto:qtstrategy_web@foxmail.com).

For product questions and feedback, visit [Discussions](https://github.com/quantatier-apps/community/discussions) or [Issues](https://github.com/quantatier-apps/community/issues).

Please do not post confidential business information in public discussions or issues.

## Third-Party Projects

Quantatier products may incorporate or integrate third-party projects. Those projects remain the property of their respective owners and are subject to their own licenses. Applicable notices and license information are provided with the relevant distribution.

### Libraries and Frameworks

Quantatier’s development uses libraries and frameworks including [PySide6](https://doc.qt.io/qtforpython/), [pyqtgraph](https://www.pyqtgraph.org/), [NumPy](https://numpy.org/), [pandas](https://pandas.pydata.org/), [Vue](https://vuejs.org/), and [Element Plus](https://element-plus.org/). We thank their authors and contributors.

### Quantitative Projects

Some Darwin components are derived from or incorporate [vn.py](https://github.com/vnpy/vnpy). We thank its authors and contributors.

### References and Future Exploration

Quantatier also draws inspiration from the wider quantitative community, including [vectorbt](https://github.com/polakowo/vectorbt), [Zipline](https://github.com/quantopian/zipline), and Microsoft’s [Qlib](https://github.com/microsoft/qlib). These projects are not currently integrated. Their inclusion does not imply endorsement or partnership.

We thank the authors and contributors of these projects for their work.

---

<div align="center">

**Quantatier** · Built for practical quantitative workflows.

[Updates](https://github.com/quantatier-apps/community/discussions/categories/announcements) · [Discussions](https://github.com/quantatier-apps/community/discussions) · [Issues](https://github.com/quantatier-apps/community/issues) · [Business Inquiries](#business-inquiries)

</div>
