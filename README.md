<!-- README.md — Francesco Castaldi -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="Francesco Castaldi — Computer Science Engineer" width="880">
  </picture>
</div>

<div align="center">
  <a href="https://francescocastaldi.it"><img src="https://img.shields.io/badge/Website-francescocastaldi.it-C9BFA8?style=flat-square&labelColor=2B2823" alt="Website"></a>
  <a href="mailto:info@francescocastaldi.it"><img src="https://img.shields.io/badge/Email-info@francescocastaldi.it-C9BFA8?style=flat-square&labelColor=2B2823" alt="Email"></a>
</div>

<br>

<div align="center">
  <p>
    Computer Science Engineer &middot; Business Consultant at <b>Maps Healthcare S.p.A.</b><br>
    MSc Informatics for Management &mdash; University of Bologna
  </p>
  <p>
    <i>I build analytics platforms, measurement systems and engineering tooling &mdash;<br>
    and contribute the same work upstream, where it is reviewed by people who know better.</i>
  </p>
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/rule-dark.svg">
    <img src="assets/rule-light.svg" width="320" alt="">
  </picture>
</div>

### I &mdash; Open Source

<sub>Where my work goes through public review. Counts link to the live pull request list for each project. Status as of 7 October 2026.</sub>

<br>

| Project | Domain | My pull requests |
| :--- | :--- | :--- |
| **[apache / superset](https://github.com/apache/superset)** | Enterprise data exploration & visualization | [9 merged &middot; 10 in review](https://github.com/apache/superset/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[nodejs / node](https://github.com/nodejs/node)** | JavaScript runtime built on Chrome's V8 engine | [1 in review](https://github.com/nodejs/node/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[mattermost / mattermost-plugin-mscalendar](https://github.com/mattermost/mattermost-plugin-mscalendar)** | Microsoft 365 calendar integration | [1 in review](https://github.com/mattermost/mattermost-plugin-mscalendar/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[Canner / WrenAI](https://github.com/Canner/WrenAI)** | Conversational GenAI agent for Text-to-SQL | [1 merged &middot; 1 in review](https://github.com/Canner/WrenAI/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[evidence-dev / evidence](https://github.com/evidence-dev/evidence)** | Business intelligence as code | [4 in review](https://github.com/evidence-dev/evidence/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[trinodb / trino](https://github.com/trinodb/trino)** | Distributed SQL query engine | [1 merged](https://github.com/trinodb/trino/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[slothflowlabs / duckle](https://github.com/slothflowlabs/duckle)** | Workspace orchestration & template engine | [2 merged](https://github.com/slothflowlabs/duckle/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[docker / cli](https://github.com/docker/cli)** | Docker command-line interface | [1 merged](https://github.com/docker/cli/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[questdb / mcp-server-questdb](https://github.com/questdb/mcp-server-questdb)** | Model Context Protocol server for QuestDB | [1 merged](https://github.com/questdb/mcp-server-questdb/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[kanisterio / kanister](https://github.com/kanisterio/kanister)** | Data management for Kubernetes | [1 in review](https://github.com/kanisterio/kanister/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[anthropics / claude-code](https://github.com/anthropics/claude-code)** | Agentic command-line coding assistant | [1 in review](https://github.com/anthropics/claude-code/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |

<br>

**Apache Superset** is where most of that upstream work lives &mdash; query correctness, engine metadata, visual plugin sorting, and the Italian localization.

Open right now:

- [#45039](https://github.com/apache/superset/pull/45039) &nbsp;&middot;&nbsp; connected dashboard auto-refresh dropdown to configured intervals
- [#45038](https://github.com/apache/superset/pull/45038) &nbsp;&middot;&nbsp; remapped native filter scopes when duplicating charts on dashboard copy
- [#45036](https://github.com/apache/superset/pull/45036) &nbsp;&middot;&nbsp; supported custom user models during dashboard and MCP chart operations
- [#44945](https://github.com/apache/superset/pull/44945) &nbsp;&middot;&nbsp; prevented duplicate onChange calls in RadioButtonControl to fix form submission side-effects
- [#44894](https://github.com/apache/superset/pull/44894) &nbsp;&middot;&nbsp; hardened select component with robust option deduplication and new option handling
- [#43695](https://github.com/apache/superset/pull/43695) &nbsp;&middot;&nbsp; completed the metadata definitions for the remaining database engine specs and added the matching unit test suites *(approved, CI green, rebase pending)*
- [#44358](https://github.com/apache/superset/pull/44358) &nbsp;&middot;&nbsp; updates the dashboard last-modified timestamp when a chart is added *(approved, CI green)*
- [#44355](https://github.com/apache/superset/pull/44355) &nbsp;&middot;&nbsp; enabled equality operators for boolean filters on the Databricks engine *(approved, rebase pending)*
- [#44464](https://github.com/apache/superset/pull/44464) &nbsp;&middot;&nbsp; added sorting by metrics and groupby in the MCP XY chart plugin *(CI green)*
- [#43697](https://github.com/apache/superset/pull/43697) &nbsp;&middot;&nbsp; hardened the guest anti-tamper check against scalar control string iteration

Merged since late August:

- [#43566](https://github.com/apache/superset/pull/43566) &nbsp;&middot;&nbsp; added metadata blocks to every remaining incomplete engine spec
- [#43584](https://github.com/apache/superset/pull/43584) &nbsp;&middot;&nbsp; moved optional icons outside the label element in Explore
- [#43586](https://github.com/apache/superset/pull/43586) &nbsp;&middot;&nbsp; set the default catalog on datasets created from file uploads
- [#43585](https://github.com/apache/superset/pull/43585) &nbsp;&middot;&nbsp; restricted Prophet time grain schema validation to supported grains
- [#43565](https://github.com/apache/superset/pull/43565) &nbsp;&middot;&nbsp; preserved optimizer hints when formatting semicolon-terminated SQL
- [#43564](https://github.com/apache/superset/pull/43564) &nbsp;&middot;&nbsp; removed `@has_access_api` from the filter state REST API
- [#43274](https://github.com/apache/superset/pull/43274) &nbsp;&middot;&nbsp; brought the Italian translation to full coverage with placeholder validation

<sub>Alongside it:
&middot; **Node.js** [#66478](https://github.com/nodejs/node/pull/66478) *(in review)*: introduced <code>unicodeLineSeparators</code> option to the core readline interface for Unicode-compliant newline delimiter processing.<br>
&middot; **Mattermost** [#550](https://github.com/mattermost/mattermost-plugin-mscalendar/pull/550) *(in review, CI green)*: fixed event time formatting (space between time and AM/PM, Issue #318) in the Microsoft Calendar plugin with unit tests &mdash; CodeRabbit AI review approved, CLA verified, qualifies for Contributor Mug.<br>
&middot; **WrenAI** [#2753](https://github.com/Canner/WrenAI/pull/2753) *(merged)* &amp; [#2754](https://github.com/Canner/WrenAI/pull/2754) *(in review)*: exposed Cube <code>orderBy</code> in the WASM TypeScript SDK (Issue #2700) and safeguarded multiline subquery wrap against trailing comment swallowing in SQL dialect generation (Issue #2733).<br>
&middot; **Evidence** ([4 in review](https://github.com/evidence-dev/evidence/pulls?q=is%3Apr+author%3AFrancescoCastaldi)): architected an i18n localization system with LanguageSelector, and built <code>&lt;MetricCard&gt;</code>, <code>&lt;FilterPresets&gt;</code>, and <code>downIsGood</code> metric configuration; the interactive cross-filtering pull request has since been closed by the maintainers.<br>
&middot; **QuestDB** [#7](https://github.com/questdb/mcp-server-questdb/pull/7) *(merged)*: documented Gemini CLI among the supported coding agents for the QuestDB MCP server.<br>
&middot; **Trino** [#31130](https://github.com/trinodb/trino/pull/31130) *(merged)*: corrected terminology and documentation inconsistencies.<br>
&middot; **Docker CLI** [#7250](https://github.com/docker/cli/pull/7250) *(merged)*: resolved Zsh completion arithmetic evaluation errors &mdash; two follow-up proposals on error hooks and service mount ordering were closed without merge.<br>
&middot; **Kanister** [#4192](https://github.com/kanisterio/kanister/pull/4192) *(in review, CI green)*: introduced <code>imagePullSecrets</code> support into the operator Helm chart.<br>
&middot; **Claude Code** [#65344](https://github.com/anthropics/claude-code/pull/65344) *(in review)*: corrected a premature return in the stale-issue marking script and added a <code>--debug</code> flag to the duplicate auto-close tooling.<br>
&middot; **Duckle** [#275](https://github.com/slothflowlabs/duckle/pull/275) &amp; [#276](https://github.com/slothflowlabs/duckle/pull/276) *(merged)*: engineered dynamic time offsets and resilient active job crash recovery.
</sub>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/rule-dark.svg">
    <img src="assets/rule-light.svg" width="320" alt="">
  </picture>
</div>

### II &mdash; Selected Work

<sub>Public repositories and engineering systems, most recent first.</sub>

<br>

| Project | What it is | Built with |
| :--- | :--- | :--- |
| **portfolio-tracker** | Real-time portfolio intelligence (v1.3.2): Gemini 3.5 Flash Lite commentary, HMAC-authenticated dispatch triggers, Vercel serverless | TypeScript, Gemini AI, Vercel |
| **CheckLensRB** | Multivariate tracking service (v1.2.0) with serverless edge API, dynamic status routing, and automated parcel monitoring | TypeScript, Serverless |
| **[mini-jersey-studio](https://github.com/FrancescoCastaldi/mini-jersey-studio)** | 3D cycling jersey customizer: SVG-to-WebGL planar projection, GLB import, tech-pack export | Three.js, WebGL |
| **[ci-cervical-lbc](https://github.com/FrancescoCastaldi/ci-cervical-lbc)** | Computational imaging on cervical LBC slides: total-variation vs. U-Net vs. diffusion | Jupyter, PyTorch |
| **[toyota-m15a-connecting-rod](https://github.com/FrancescoCastaldi/toyota-m15a-connecting-rod)** | Connecting-rod design for the Yaris Mk4 1.5L: inertia, Goodman-Smith fatigue, FEM convergence | Python, CAD, FEM |
| **[VeloMetric](https://github.com/FrancescoCastaldi/VeloMetric)** | Predictive wear analytics for road bikes &mdash; drivetrain decay from ride telemetry | Swift |
| **[TruMetraPla](https://github.com/FrancescoCastaldi/TruMetraPla)** | Productivity intelligence for metalworking shop floors, from spreadsheet to KPI dashboard | Python, Streamlit |
| **[Esame-UUXD](https://github.com/FrancescoCastaldi/Esame-UUXD)** | TPER transport portal redesign &mdash; Double Diamond, +35 SUS points (72.5), 80% task completion | UX Research |
| **[sir-markov-chain](https://github.com/FrancescoCastaldi/sir-markov-chain)** | SIR epidemic model as a discrete-time Markov chain, with Monte Carlo trajectories | Jupyter, NumPy |
| **[gpx-editor](https://github.com/FrancescoCastaldi/gpx-editor)** | Browser-based GPX editor for power and speed traces &mdash; fully offline | JavaScript |

<br>

<sub>Specialized tooling &amp; data infrastructure:
&middot; **Stratum Suite** includes <code>stratum-bar</code> (v0.3.8 with outlier pinning &amp; 3D isometric engine), <code>calendar-filter</code> (native dashboard cross-filter with date range broadcasting), <code>stratum-heatmap</code>, <code>hierarchical-table</code>, and <code>kpi-comparison</code>.<br>
&middot; **Developer Swag Toolchain**: Automated outreach dispatcher with Aruba SMTPS, rate-limiting, and IMAP Sent mailbox synchronization.<br>
&middot; **Healthcare DWH &amp; ETL Automation**: High-throughput ETL engines (Sirio / SISMART), star schema dimensional modeling, indexed view materialization, and sub-second analytical dashboard responsiveness for hospital clinical operations.
</sub>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/rule-dark.svg">
    <img src="assets/rule-light.svg" width="320" alt="">
  </picture>
</div>

### III &mdash; Toolkit

| Area | Tools |
| :--- | :--- |
| **Languages** | Python &nbsp;&middot;&nbsp; TypeScript &nbsp;&middot;&nbsp; JavaScript &nbsp;&middot;&nbsp; Go &nbsp;&middot;&nbsp; Rust / WASM &nbsp;&middot;&nbsp; SQL &nbsp;&middot;&nbsp; Java &nbsp;&middot;&nbsp; C# &nbsp;&middot;&nbsp; Swift &nbsp;&middot;&nbsp; Bash |
| **Data & BI** | Apache Superset &nbsp;&middot;&nbsp; Trino &nbsp;&middot;&nbsp; WrenAI &nbsp;&middot;&nbsp; Evidence &nbsp;&middot;&nbsp; SQLGlot &nbsp;&middot;&nbsp; PostgreSQL &nbsp;&middot;&nbsp; DuckDB &nbsp;&middot;&nbsp; SQL Server &nbsp;&middot;&nbsp; Pandas |
| **Frontend & Viz** | React &nbsp;&middot;&nbsp; Svelte &nbsp;&middot;&nbsp; Three.js / WebGL &nbsp;&middot;&nbsp; ECharts &nbsp;&middot;&nbsp; Streamlit &nbsp;&middot;&nbsp; Tailwind CSS |
| **AI & Machine Learning** | Google Gemini API &nbsp;&middot;&nbsp; PyTorch &nbsp;&middot;&nbsp; scikit-learn &nbsp;&middot;&nbsp; OpenCV &nbsp;&middot;&nbsp; Jupyter |
| **Systems, Cloud & CI** | Docker &nbsp;&middot;&nbsp; Kubernetes &nbsp;&middot;&nbsp; Helm &nbsp;&middot;&nbsp; Vercel Serverless &nbsp;&middot;&nbsp; GitHub Actions &nbsp;&middot;&nbsp; Linux &nbsp;&middot;&nbsp; Git |
| **Engineering & Kinematics** | SolidWorks &nbsp;&middot;&nbsp; ANSYS FEM &nbsp;&middot;&nbsp; Dynamic Simulation &nbsp;&middot;&nbsp; LaTeX |

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/rule-dark.svg">
    <img src="assets/rule-light.svg" width="320" alt="">
  </picture>
</div>

### IV &mdash; Activity

<div align="center">

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api?username=FrancescoCastaldi&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&hide_title=true&hide_rank=false&bg_color=00000000&text_color=A9A396&icon_color=9CA68D&ring_color=B99B6B">
    <img src="https://github-readme-stats-fast.vercel.app/api?username=FrancescoCastaldi&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&hide_title=true&hide_rank=false&bg_color=00000000&text_color=4A463E&icon_color=6B705C&ring_color=A68A64" height="170" alt="GitHub statistics">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=FrancescoCastaldi&layout=compact&langs_count=8&hide_border=true&hide_title=true&bg_color=00000000&text_color=A9A396">
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=FrancescoCastaldi&layout=compact&langs_count=8&hide_border=true&hide_title=true&bg_color=00000000&text_color=4A463E" height="170" alt="Most used languages">
  </picture>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=FrancescoCastaldi&hide_border=true&hide_title=true&bg_color=00000000&color=C0A57B&line=B99B6B&point=9CA68D&area=true&area_color=6B705C">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=FrancescoCastaldi&hide_border=true&hide_title=true&bg_color=00000000&color=8A6F47&line=A68A64&point=6B705C&area=true&area_color=C9BFA8" width="880" alt="Contribution activity over the last year">
  </picture>

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/rule-dark.svg">
    <img src="assets/rule-light.svg" width="320" alt="">
  </picture>
</div>

<div align="center">
  <sub>Francesco Castaldi &nbsp;&middot;&nbsp; Modena, Italia &nbsp;&middot;&nbsp; <a href="https://francescocastaldi.it">francescocastaldi.it</a></sub>
</div>
