<!-- README.md ,  Francesco Castaldi -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="Francesco Castaldi ,  Computer Science Engineer" width="880">
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

<sub>Where my work goes through public review. Counts link to the live pull request list for each project. Status as of 24 October 2026.</sub>

<br>

| Project | Domain | My pull requests |
| :--- | :--- | :--- |
| **[apache / superset](https://github.com/apache/superset)** | Enterprise data exploration & visualization | [16 merged &middot; 5 in review](https://github.com/apache/superset/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[nodejs / node](https://github.com/nodejs/node)** | JavaScript runtime built on Chrome's V8 engine | [1 in review](https://github.com/nodejs/node/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[mattermost / mattermost-plugin-mscalendar](https://github.com/mattermost/mattermost-plugin-mscalendar)** | Microsoft 365 calendar integration | [2 merged &middot; 2 in review](https://github.com/mattermost/mattermost-plugin-mscalendar/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[Canner / WrenAI](https://github.com/Canner/WrenAI)** | Conversational GenAI agent for Text-to-SQL | [2 merged](https://github.com/Canner/WrenAI/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[evidence-dev / evidence](https://github.com/evidence-dev/evidence)** | Business intelligence as code | [3 in review](https://github.com/evidence-dev/evidence/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[trinodb / trino](https://github.com/trinodb/trino)** | Distributed SQL query engine | [1 merged &middot; 1 in review](https://github.com/trinodb/trino/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[slothflowlabs / duckle](https://github.com/slothflowlabs/duckle)** | Workspace orchestration & template engine | [2 merged](https://github.com/slothflowlabs/duckle/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[docker / cli](https://github.com/docker/cli)** | Docker command-line interface | [1 merged](https://github.com/docker/cli/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[netdata / netdata](https://github.com/netdata/netdata)** | Real-time infrastructure monitoring | [1 merged](https://github.com/netdata/netdata/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[questdb / questdb](https://github.com/questdb/questdb)** | High-performance time-series database | [1 in review](https://github.com/questdb/questdb/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[questdb / mcp-server-questdb](https://github.com/questdb/mcp-server-questdb)** | Model Context Protocol server for QuestDB | [1 merged](https://github.com/questdb/mcp-server-questdb/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[kanisterio / kanister](https://github.com/kanisterio/kanister)** | Data management for Kubernetes | [1 in review](https://github.com/kanisterio/kanister/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[anthropics / claude-code](https://github.com/anthropics/claude-code)** | Agentic command-line coding assistant | [1 in review](https://github.com/anthropics/claude-code/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[iausathub / satchecker](https://github.com/iausathub/satchecker)** | IAU CPS SatHub tool for satellite position prediction | [5 in review](https://github.com/iausathub/satchecker/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[PostHog / posthog.com](https://github.com/PostHog/posthog.com)** | Official docs, website, and handbook for PostHog | [1 in review](https://github.com/PostHog/posthog.com/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |
| **[walkersutton / Cyclemetry](https://github.com/walkersutton/Cyclemetry)** | Telemetry video overlays from GPS data | [5 merged](https://github.com/walkersutton/Cyclemetry/pulls?q=is%3Apr+author%3AFrancescoCastaldi) |

<br>

**Apache Superset** is where most of that upstream work lives &mdash; query correctness, engine metadata, visual plugin sorting, and the Italian localization.

Open right now:

- [#45205](https://github.com/apache/superset/pull/45205) &nbsp;&middot;&nbsp; added unit test coverage for CockroachDB, MotherDuck, DynamoDB, Firebolt, Google Sheets, Synapse, and OceanBase engine specs
- [#45186](https://github.com/apache/superset/pull/45186) &nbsp;&middot;&nbsp; widened cryptography and msgpack ranges and bumped pyarrow floor to resolve Trivy vulnerabilities (#45087)
- [#44945](https://github.com/apache/superset/pull/44945) &nbsp;&middot;&nbsp; prevented duplicate onChange calls in RadioButtonControl to fix form submission side-effects *(approved)*
- [#44894](https://github.com/apache/superset/pull/44894) &nbsp;&middot;&nbsp; hardened select component with robust option deduplication and new option handling
- [#43695](https://github.com/apache/superset/pull/43695) &nbsp;&middot;&nbsp; completed the metadata definitions for the remaining database engine specs and added the matching unit test suites *(approved)*

Merged since late August:

- [#45051](https://github.com/apache/superset/pull/45051) &nbsp;&middot;&nbsp; prevented horizontal filter bar from vanishing on cross-filter
- [#45039](https://github.com/apache/superset/pull/45039) &nbsp;&middot;&nbsp; connected dashboard auto-refresh dropdown to configured intervals
- [#45038](https://github.com/apache/superset/pull/45038) &nbsp;&middot;&nbsp; remapped native filter scopes when duplicating charts on dashboard copy
- [#45036](https://github.com/apache/superset/pull/45036) &nbsp;&middot;&nbsp; supported custom user models during dashboard and MCP chart operations
- [#44464](https://github.com/apache/superset/pull/44464) &nbsp;&middot;&nbsp; added sorting by metrics and groupby in the MCP XY chart plugin
- [#44358](https://github.com/apache/superset/pull/44358) &nbsp;&middot;&nbsp; updates the dashboard last-modified timestamp when a chart is added
- [#44355](https://github.com/apache/superset/pull/44355) &nbsp;&middot;&nbsp; enabled equality operators for boolean filters on the Databricks engine
- [#43586](https://github.com/apache/superset/pull/43586) &nbsp;&middot;&nbsp; set the default catalog on datasets created from file uploads
- [#43585](https://github.com/apache/superset/pull/43585) &nbsp;&middot;&nbsp; restricted Prophet time grain schema validation to supported grains
- [#43584](https://github.com/apache/superset/pull/43584) &nbsp;&middot;&nbsp; moved optional icons outside the label element in Explore
- [#43566](https://github.com/apache/superset/pull/43566) &nbsp;&middot;&nbsp; added metadata blocks to every remaining incomplete engine spec
- [#43565](https://github.com/apache/superset/pull/43565) &nbsp;&middot;&nbsp; preserved optimizer hints when formatting semicolon-terminated SQL
- [#43564](https://github.com/apache/superset/pull/43564) &nbsp;&middot;&nbsp; removed `@has_access_api` from the filter state REST API
- [#43274](https://github.com/apache/superset/pull/43274) &nbsp;&middot;&nbsp; brought the Italian translation to full coverage with placeholder validation

<sub>Alongside it:
&middot; **Node.js** [#66478](https://github.com/nodejs/node/pull/66478) *(in review)*: introduced <code>unicodeLineSeparators</code> option to the core readline interface for Unicode-compliant newline delimiter processing.<br>
&middot; **Mattermost** ([2 merged &middot; 2 in review](https://github.com/mattermost/mattermost-plugin-mscalendar/pulls?q=is%3Apr+author%3AFrancescoCastaldi)): merged connect message button on POST (#552, Issue #316) and event time AM/PM spacing (#550, Issue #318); in review: user time format preferences in views and notifications (#553, Issue #358), and token refresh and store lifecycle tests (#554, Issue #423).<br>
&middot; **WrenAI** [#2753](https://github.com/Canner/WrenAI/pull/2753) &amp; [#2754](https://github.com/Canner/WrenAI/pull/2754) *(both merged)*: exposed Cube <code>orderBy</code> in the WASM TypeScript SDK (Issue #2700) and safeguarded multiline subquery wrap against trailing comment swallowing in SQL dialect generation (Issue #2733).<br>
&middot; **Evidence** ([3 in review](https://github.com/evidence-dev/evidence/pulls?q=is%3Apr+author%3AFrancescoCastaldi)): architected an i18n localization system with LanguageSelector, and built <code>&lt;MetricCard&gt;</code>, <code>&lt;FilterPresets&gt;</code>, and <code>downIsGood</code> metric configuration.<br>
&middot; **QuestDB** [#7850](https://github.com/questdb/questdb/pull/7850) *(in review)*: guarded SQL integer type boundaries against out-of-range float and double casting; and [#7](https://github.com/questdb/mcp-server-questdb/pull/7) *(merged)*: documented Gemini CLI among the supported coding agents for the QuestDB MCP server.<br>
&middot; **Trino** [#31130](https://github.com/trinodb/trino/pull/31130) *(merged)*: corrected terminology and documentation inconsistencies; and [#31546](https://github.com/trinodb/trino/pull/31546) *(in review)*: retained Iceberg NDV statistics across row-level write operations.<br>
&middot; **Docker CLI** [#7250](https://github.com/docker/cli/pull/7250) *(merged)*: resolved Zsh completion arithmetic evaluation errors &mdash; two follow-up proposals on error hooks and service mount ordering were closed without merge.<br>
&middot; **Netdata** [#24352](https://github.com/netdata/netdata/pull/24352) *(merged)*: skipped space charting for optical and read-only drives on Windows.<br>
&middot; **Kanister** [#4192](https://github.com/kanisterio/kanister/pull/4192) *(in review, CI green)*: introduced <code>imagePullSecrets</code> support into the operator Helm chart.<br>
&middot; **Claude Code** [#65344](https://github.com/anthropics/claude-code/pull/65344) *(in review)*: corrected a premature return in the stale-issue marking script and added a <code>--debug</code> flag to the duplicate auto-close tooling.<br>
&middot; **Duckle** [#275](https://github.com/slothflowlabs/duckle/pull/275) &amp; [#276](https://github.com/slothflowlabs/duckle/pull/276) *(merged)*: engineered dynamic time offsets and resilient active job crash recovery.<br>
&middot; **Cyclemetry** ([5 merged](https://github.com/walkersutton/Cyclemetry/pulls?q=is%3Apr+author%3AFrancescoCastaldi)): hardened render-core template deserialization for floats and isolated scene inheritance ([#53](https://github.com/walkersutton/Cyclemetry/pull/53)), added calories telemetry with activity and UI summaries ([#55](https://github.com/walkersutton/Cyclemetry/pull/55)), overlay trim brackets on the playback timeline ([#56](https://github.com/walkersutton/Cyclemetry/pull/56)), and Svelte 5 runes reactivity fixes with video accessibility captions ([#54](https://github.com/walkersutton/Cyclemetry/pull/54)).<br>
&middot; **SatChecker** ([5 in review](https://github.com/iausathub/satchecker/pulls?q=is%3Apr+author%3AFrancescoCastaldi)): fixed ECEF to ITRS coordinate conversion ([#267](https://github.com/iausathub/satchecker/pull/267)), bounded dates more than two weeks in the future ([#270](https://github.com/iausathub/satchecker/pull/270)), documented the newest-before record selection rule for TLEs at epoch ([#271](https://github.com/iausathub/satchecker/pull/271)), removed the duplicate execution_time parameter in FOV metrics ([#268](https://github.com/iausathub/satchecker/pull/268)), and added objects and satellites processed counts to FOV metrics ([#269](https://github.com/iausathub/satchecker/pull/269)).<br>
&middot; **PostHog** [#21289](https://github.com/PostHog/posthog.com/pull/21289) *(in review)*: handled API errors and loading-state cleanup in the teams useTeam hook.
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
| **[fuel-ledger-android](https://github.com/FrancescoCastaldi/fuel-ledger-android)** | Offline Android vehicle logbook for fuel, running costs and maintenance reminders with an amber instrument cluster | Kotlin, Jetpack Compose |
| **[BenzaTracker](https://github.com/FrancescoCastaldi/BenzaTracker)** | Multi-interface fuel consumption and spending KPI tracker with CLI, desktop GUI, Flask web dashboard, and PDF reporting | Python, Flask, SQLite |
| **[mini-jersey-studio](https://github.com/FrancescoCastaldi/mini-jersey-studio)** | 3D cycling jersey customizer: SVG-to-WebGL planar projection, GLB import, tech-pack export | Three.js, WebGL |
| **[ci-cervical-lbc](https://github.com/FrancescoCastaldi/ci-cervical-lbc)** | Computational imaging on cervical LBC slides: total-variation vs. U-Net vs. diffusion | Jupyter, PyTorch |
| **[toyota-m15a-connecting-rod](https://github.com/FrancescoCastaldi/toyota-m15a-connecting-rod)** | Connecting-rod design for the Yaris Mk4 1.5L: inertia, Goodman-Smith fatigue, FEM convergence | Python, CAD, FEM |
| **[VeloMetric](https://github.com/FrancescoCastaldi/VeloMetric)** | Predictive wear analytics for road bikes: drivetrain decay from ride telemetry | Swift |
| **[TruMetraPla](https://github.com/FrancescoCastaldi/TruMetraPla)** | Productivity intelligence for metalworking shop floors, from spreadsheet to KPI dashboard | Python, Streamlit |
| **[Esame-UUXD](https://github.com/FrancescoCastaldi/Esame-UUXD)** | TPER transport portal redesign: Double Diamond, +35 SUS points (72.5), 80% task completion | UX Research |
| **[sir-markov-chain](https://github.com/FrancescoCastaldi/sir-markov-chain)** | SIR epidemic model as a discrete-time Markov chain, with Monte Carlo trajectories | Jupyter, NumPy |
| **[gpx-editor](https://github.com/FrancescoCastaldi/gpx-editor)** | Browser-based GPX editor for power and speed traces: fully offline | JavaScript |

<br>

<sub>Specialized tooling &amp; data infrastructure:
&middot; **Stratum Suite**: Custom visualization plugins for Apache Superset 6.1.0 (<code>stratum-bar</code>, <code>hierarchical-table</code>, <code>calendar-filter</code>, <code>stratum-heatmap</code>, and <code>kpi-comparison</code>).<br>
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
| **Languages** | Python &nbsp;&middot;&nbsp; TypeScript &nbsp;&middot;&nbsp; JavaScript &nbsp;&middot;&nbsp; Go &nbsp;&middot;&nbsp; Rust / WASM &nbsp;&middot;&nbsp; SQL &nbsp;&middot;&nbsp; Kotlin &nbsp;&middot;&nbsp; Java &nbsp;&middot;&nbsp; C# &nbsp;&middot;&nbsp; Swift &nbsp;&middot;&nbsp; Bash |
| **Data & BI** | Apache Superset &nbsp;&middot;&nbsp; Trino &nbsp;&middot;&nbsp; WrenAI &nbsp;&middot;&nbsp; Evidence &nbsp;&middot;&nbsp; SQLGlot &nbsp;&middot;&nbsp; QuestDB &nbsp;&middot;&nbsp; PostgreSQL &nbsp;&middot;&nbsp; DuckDB &nbsp;&middot;&nbsp; SQL Server &nbsp;&middot;&nbsp; Pandas |
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
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api?username=FrancescoCastaldi&show_icons=true&hide_border=false&border_color=3A372F&border_radius=8&bg_color=00000000&text_color=A9A396&icon_color=9CA68D&ring_color=B99B6B&title_color=E8E2D5&card_width=437">
    <img src="https://github-readme-stats-fast.vercel.app/api?username=FrancescoCastaldi&show_icons=true&hide_border=false&border_color=D2C9B6&border_radius=8&bg_color=00000000&text_color=4A463E&icon_color=6B705C&ring_color=A68A64&title_color=1F1D1A&card_width=437" width="437" height="195" alt="GitHub statistics">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=FrancescoCastaldi&hide_border=false&border=3A372F&border_radius=8&background=00000000&stroke=B99B6B&ring=B99B6B&fire=B99B6B&currStreakNum=E8E2D5&sideNums=E8E2D5&currStreakLabel=9CA68D&sideLabels=9CA68D&dates=9CA68D&card_width=437">
    <img src="https://streak-stats.demolab.com/?user=FrancescoCastaldi&hide_border=false&border=D2C9B6&border_radius=8&background=00000000&stroke=A68A64&ring=A68A64&fire=A68A64&currStreakNum=1F1D1A&sideNums=1F1D1A&currStreakLabel=6B705C&sideLabels=6B705C&dates=6B705C&card_width=437" width="437" height="195" alt="GitHub streak stats">
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
