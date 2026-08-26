<!-- README.md — Francesco Castaldi GitHub Profile -->
<div align="center">

<img src="https://readme-typing-svg.demolab.com/?lines=Hi+there,+I'm+Francesco+Castaldi+👋;Computer+Science+Engineer;Machine+Learning+%26+Nowcasting+Systems;Data+Engineering+%26+Apache+Superset;Hardware+Hacking+%26+Reverse+Engineering;Automotive+%26+Kinematics+Engineering;Cycling+%26+Sports+Tech+Enthusiast!&font=Fira+Code&size=22&pause=1000&center=true&duration=3000&width=620&color=38BDF8" alt="Typing animation"/>

# 🚀 Francesco Castaldi
**Computer Science Engineer · ML & Applied Data Science · Automotive & Mechanical Systems · Open Source Contributor**

<p align="center">
  <a href="https://francescocastaldi.it"><img src="https://img.shields.io/badge/Website-francescocastaldi.it-0284C7?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
  <a href="mailto:info@francescocastaldi.it"><img src="https://img.shields.io/badge/Email-info@francescocastaldi.it-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/FrancescoCastaldi"><img src="https://img.shields.io/badge/GitHub-FrancescoCastaldi-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://komarev.com/ghpvc/?username=FrancescoCastaldi&style=for-the-badge&color=0284C7"><img src="https://komarev.com/ghpvc/?username=FrancescoCastaldi&style=for-the-badge&color=0284C7" alt="Profile views"/></a>
</p>

</div>

---

## 🌟 Apache Superset Open Source Contributions

I actively contribute to **[Apache Superset](https://github.com/apache/superset)** (Apache Software Foundation), building core database specifications, SQL parser optimizations, and REST API enhancements:

<div align="center">
<table>
<tr>
<td width="33%" align="center">
<b>🔗 <a href="https://github.com/apache/superset/pull/43564">PR #43564</a></b><br/>
<sub><code>fix(dashboard)</code></sub><br/>
<p align="left">Fixed <code>401 Unauthorized</code> regression on <code>DashboardFilterStateRestApi</code>, aligning cache permission verification with command-level security.</p>
<img src="https://img.shields.io/badge/Status-Ready%20to%20Merge-success?style=flat-square"/>
</td>
<td width="33%" align="center">
<b>🔗 <a href="https://github.com/apache/superset/pull/43565">PR #43565</a></b><br/>
<sub><code>fix(sql)</code></sub><br/>
<p align="left">Resolved SQLGlot AST comment relocation bug preventing trailing comments from corrupting optimizer hint blocks (<code>/*+ SET_VAR */</code>).</p>
<img src="https://img.shields.io/badge/Status-Ready%20to%20Merge-success?style=flat-square"/>
</td>
<td width="33%" align="center">
<b>🔗 <a href="https://github.com/apache/superset/pull/43566">PR #43566</a></b><br/>
<sub><code>feat(db_engine_specs)</code></sub><br/>
<p align="left">Added full metadata specifications for all 7 missing database engines (Aurora, IBM i, ClickHouse, Databricks, Kusto, OpenSearch).</p>
<img src="https://img.shields.io/badge/Status-Ready%20to%20Merge-success?style=flat-square"/>
</td>
</tr>
</table>
</div>

---

## 🎯 Featured Projects

<div align="center">
<table>

<!-- ROW 1: AI / Radar Nowcasting & Superset Matrix Grid -->
<tr>
<td width="50%" valign="top">
<h3 align="center">🌦️ HailCast-ML</h3>
<p align="center"><em>Real-Time Hail Tracking & Convective Nowcasting Platform</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Py--ART-Radar-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-REST-009688?style=flat-square&logo=fastapi&logoColor=white"/>
</p>
<p align="left">Full-stack meteorological intelligence platform processing open-source radar sweeps (ODIM HDF5) from Protezione Civile & EUMETNET. Computes severe storm kinematics (Waldvogel POSH, MESH, VIL, SCIT Tracking) with optical flow nowcasting and interactive GIS dashboards.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/hailcast-ml"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>

<td width="50%" valign="top">
<h3 align="center">📊 Hierarchical Table & Matrix Grid</h3>
<p align="center"><em>Apache Superset 6.1.0 Visualization Plugin</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-5.0-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Apache%20Superset-6.1.0-205493?style=flat-square&logo=apache"/>
  <img src="https://img.shields.io/badge/Emotion-CSS-D26AC2?style=flat-square"/>
</p>
<p align="left">Advanced multi-dimensional Matrix Grid & Pivot Table plugin for Apache Superset with infinite recursive row & column hierarchies, aggregated rollup headers, cell heatmaps, sparklines, conditional formatting, and real-time dashboard cross-filtering.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/superset-plugin-chart-hierarchical-table"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>
</tr>

<!-- ROW 2: Hardware/IoT & Calendar Filter -->
<tr>
<td width="50%" valign="top">
<h3 align="center">🖨️ Epson Air Resuscitator</h3>
<p align="center"><em>Wireless Waste Ink Pad Resetter & Telemetry Suite</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-SNMP-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Reverse%20Engineering-EEPROM-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Wi--Fi-Telemetry-blue?style=flat-square"/>
</p>
<p align="left">Zero-cost wireless solution to bypass manufacturer end-of-life bricking on Epson EcoTank/WorkForce printers. Features SNMP OID extraction, raw byte packet reverse-engineering over Wi-Fi, automatic EEPROM waste ink counter resets, and telemetry.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/epson-air-resuscitator"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>

<td width="50%" valign="top">
<h3 align="center">📅 Calendar Cross-Filter Plugin</h3>
<p align="center"><em>Apache Superset Heatmap Date Picker</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-4.1-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-17-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tests-27%2F27%20Passed-brightgreen?style=flat-square"/>
</p>
<p align="left">Interactive, selectable calendar heatmap chart plugin for Apache Superset. Click single dates or Shift-Click date ranges to cross-filter an entire dashboard simultaneously. Features 6 color palettes, week numbering, and rich tooltips.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/superset-plugin-chart-calendar-filter"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>
</tr>

<!-- ROW 3: Automotive Engineering & 3D WebGL Studio -->
<tr>
<td width="50%" valign="top">
<h3 align="center">🏎️ Toyota M15A Connecting Rod</h3>
<p align="center"><em>Structural, Kinematic, Fatigue & FEM CAD Engineering</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/CAD-SolidWorks-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/FEM-Ansys%20Structural-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/ISO%20GPS-Drawings-success?style=flat-square"/>
</p>
<p align="left">Full mechanical engineering design of the connecting rod for the Toyota Yaris Mk4 1.5L Dynamic Force engine (M15A-FKS/FXE). Dynamic inertia calculations, Goodman-Smith fatigue criteria, FEA mesh convergence, and technical ISO GPS manufacturing tables.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/toyota-m15a-connecting-rod"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>

<td width="50%" valign="top">
<h3 align="center">👕 Mini Jersey Studio</h3>
<p align="center"><em>Interactive 3D WebGL Apparel Customizer</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-WebGL-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Three.js-3D-black?style=flat-square&logo=three.js"/>
  <img src="https://img.shields.io/badge/Canvas%202D-SVG%20Projection-orange?style=flat-square"/>
</p>
<p align="left">Real-time 3D cycling jersey customizer with dynamic planar texture projection, custom GLB/GLTF model import, live pattern manipulation, and automated Tech Pack production export for sublimation printing.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/mini-jersey-studio"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>
</tr>

<!-- ROW 4: Probabilistic Models & UUXD Design -->
<tr>
<td width="50%" valign="top">
<h3 align="center">🦠 SIR Markov Chain Simulation</h3>
<p align="center"><em>Discrete-Time Stochastic Epidemic Modeling</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-SciPy-013243?style=flat-square&logo=numpy"/>
  <img src="https://img.shields.io/badge/Unibo-Modelli%20Probabilistici-yellow?style=flat-square"/>
</p>
<p align="left">Discrete-time Markov Chain simulation of the SIR epidemiological model. Features transition probability matrix computation, Monte Carlo stochastic trajectory analysis, parameter sensitivity testing, and comparison against continuous ODE models.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/sir-markov-chain"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>

<td width="50%" valign="top">
<h3 align="center">🎨 TperTutti (UX Design)</h3>
<p align="center"><em>Double Diamond Public Transport Portal Redesign</em></p>
<p align="center">
  <img src="https://img.shields.io/badge/Double%20Diamond-4%20Phases-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/SUS%20Score-72.5%2F100-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/Prototype-22%20Pages-blue?style=flat-square"/>
</p>
<p align="left">Complete end-to-end User Experience redesign of the TPER public transport platform (Bologna). Validated with quantitative usability metrics: +35 points SUS improvement (72.5), 80% task completion, and an innovative guided Trainer Mode for elderly citizens.</p>
<div align="center">
  <a href="https://github.com/FrancescoCastaldi/Esame-UUXD"><img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github"/></a>
</div>
</td>
</tr>

</table>
</div>

---

## 🧰 Tech Stack & Tools

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | `Python`, `TypeScript`, `JavaScript (ES6+)`, `C / C++`, `Swift`, `SQL`, `Bash`, `LaTeX` |
| **Frontend & Visualization** | `React`, `TypeScript`, `Three.js / WebGL`, `Emotion / CSS-in-JS`, `Streamlit`, `HTML5 Canvas` |
| **Data & BI Ecosystem** | `Apache Superset`, `SQLGlot`, `PostgreSQL`, `MySQL`, `ClickHouse`, `Pandas`, `NumPy`, `SciPy` |
| **Machine Learning & Nowcasting** | `Py-ART`, `Scikit-Learn`, `OpenCV`, `Optical Flow`, `TensorFlow / PyTorch`, `Jupyter` |
| **Engineering & IoT** | `SolidWorks CAD`, `ANSYS FEM`, `SNMP Protocol`, `Reverse Engineering`, `Hardware Telemetry` |
| **DevOps & Tooling** | `Git / GitHub Actions`, `Docker`, `Linux / PowerShell`, `Vite`, `Webpack`, `npm / yarn / pip` |

</div>

---

## 📈 GitHub Activity & Stats

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=FrancescoCastaldi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="175" alt="GitHub Stats" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=FrancescoCastaldi&layout=compact&theme=tokyonight&hide_border=true" height="175" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=FrancescoCastaldi&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">
  <sub>Designed with precision by <b>Francesco Castaldi</b> · © 2026</sub>
</div>
