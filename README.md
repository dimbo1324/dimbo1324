<img src="https://capsule-render.vercel.app/api?type=venom&color=0:ff6b35,30:ff3d71,60:c020d0,100:00d9ff&height=220&section=header&text=Engineer%20who%20makes%20machines%20think.&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=55&stroke=ffffff&strokeWidth=1" width="100%"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=18&duration=2000&pause=600&color=FF6B35&center=true&vCenter=true&width=680&lines=%E2%9A%A1+IIoT+Engineer+%C2%B7+Digital+Twin+Architect+%C2%B7+Industrial+AI;%F0%9F%8F%AD+I+write+code+that+runs+on+300+MW+power+plants.;%F0%9F%A7%A0+My+AI+learns+from+physics%2C+not+from+noise.;%F0%9F%8C%8E+Building+the+automated+future+from+Montevideo.;%F0%9F%94%A5+If+my+bug+crashes%2C+a+turbine+shuts+down.)](https://git.io/typing-svg)

<br/>

[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dimaprihodko180@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dmitry-prihodko-6282b8372/)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/dimbo1324)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/dimaprihodko180/)

![](https://komarev.com/ghpvc/?username=dimbo1324&color=ff6b35&style=flat-square&label=engineers+visited)

</div>

---

<br/>

<div align="center">

## ⚡ Who I Am

</div>

<table border="0">
<tr>
<td valign="top" width="55%">

I'm **Dmitry** — a software engineer obsessed with one idea:

> *What if every industrial machine could think, predict, and protect itself?*

I build the software layer between **raw physics** and **intelligent decisions**. My tools are thermodynamic equations, neural networks, and industrial protocols. My output is systems that don't just monitor — they *understand*.

Right now I'm building **CogniBoiler** — a full-stack digital twin of a gas-fired power plant. A virtual 300 MW boiler that obeys the laws of thermodynamics, controlled by a PID cascade, watched by an AI that was trained on real physics.

Not a demo. Not a tutorial project. **The kind of thing that gets deployed.**

<br/>

```
📍 Based in:   → Montevideo, Uruguay (relocating 2026)
🌎 Markets:    USA · Uruguay · Argentina
🎯 Mission:    Make critical infrastructure safer & autonomous
💬 Languages:  Python · Go · C++ · English · Russian · (ES soon)
```

</td>
<td valign="top" width="45%" align="center">

<br/>

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dimbo1324&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=ff6b35&icon_color=00d9ff&text_color=c9d1d9&rank_icon=percentile&include_all_commits=true&count_private=true&custom_title=My+GitHub+Universe)](https://github.com/dimbo1324)

<br/>

[![Streak](https://streak-stats.demolab.com?user=dimbo1324&theme=tokyonight&hide_border=true&background=0d1117&ring=ff6b35&fire=ff3d71&currStreakLabel=ff6b35&sideLabels=8b9bb4&dates=8b9bb4)](https://git.io/streak-stats)

</td>
</tr>
</table>

---

<br/>

<div align="center">

## 🔥 What I'm Building Right Now

</div>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║    ██████╗ ██████╗  ██████╗ ███╗  ██╗██╗██████╗  ██████╗ ██╗██╗     ███████╗██████╗  ║
║   ██╔════╝██╔═══██╗██╔════╝ ████╗ ██║██║██╔══██╗██╔═══██╗██║██║     ██╔════╝██╔══██╗ ║
║   ██║     ██║   ██║██║  ███╗██╔██╗██║██║██████╔╝██║   ██║██║██║     █████╗  ██████╔╝ ║
║   ╚██████╗╚██████╔╝╚██████╔╝██║ ╚████║██║╚═════╝ ╚██████╔╝██║███████╗███████╗██║     ║
║                                                                              ║
║         AI-Driven Digital Twin · Steam Power Generation · 300 MW            ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

</div>

<table>
<tr>
<td width="33%" align="center" valign="top">

### ⚛️ Physics Layer
*The foundation. Real thermodynamics.*

```
dU/dt = Q_in − Q_steam − Q_loss
dP/dt = f(T, m_water, V_drum)
W_elec = η · ṁ · (h_in − h_out)
```

RK45 ODE solver · 10 Hz simulation
5 controllable valve actuators
Realistic sensor noise

</td>
<td width="33%" align="center" valign="top">

### 🎛️ Control Layer
*Industrial-grade PLC logic.*

```
Power  → [PID₁] → Pressure target
Press  → [PID₂] → Fuel valve %
Level  → [PID₃] → Feedwater valve
Temp   → [PID₄] → Spray injection
```

Cascade PID · Safety interlocks
Emergency stop < 100ms
Ziegler-Nichols auto-tuning

</td>
<td width="33%" align="center" valign="top">

### 🧠 AI Layer
*Three models. One mission.*

```
LSTM Autoencoder  → Anomaly detection
Transformer       → Efficiency advisor
GRU + Weibull     → Predictive maint.
```

Trained on synthetic physics data
F1 > 0.85 · FPR < 5%
MLflow experiment tracking

</td>
</tr>
</table>

<div align="center">

**Protocols:** `OPC UA (IEC 62541)` · `MQTT 5.0` · `gRPC` · `Protocol Buffers`

**Security:** `mTLS everywhere` · `JWT RS256` · `AES-256-GCM` · `Immutable audit log`

**Infra:** `Docker` · `Kubernetes` · `Helm` · `GitHub Actions CI/CD` · `Grafana`

<br/>

[![CogniBoiler](https://github-readme-stats.vercel.app/api/pin/?username=dimbo1324&repo=cogniboiler&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=ff6b35&icon_color=00d9ff&text_color=c9d1d9&description_lines_count=3)](https://github.com/dimbo1324/cogniboiler)

</div>

---

<br/>

<div align="center">

## 🛠️ Full Tech Arsenal

</div>

<div align="center">

| Domain | Stack |
|--------|-------|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) |
| **Industrial IIoT** | ![MQTT](https://img.shields.io/badge/MQTT-FF6B35?style=flat-square&logo=eclipse-mosquitto&logoColor=white) ![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![OPC UA](https://img.shields.io/badge/OPC%20UA-FF6B35?style=flat-square&logoColor=white) |
| **AI & Data** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-4DABCF?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![sklearn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Protobuf](https://img.shields.io/badge/Protobuf-FF6B35?style=flat-square&logoColor=white) |
| **Infra & DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![K8s](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![GH Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Security** | ![JWT](https://img.shields.io/badge/JWT%20RS256-FB015B?style=flat-square&logo=jsonwebtokens&logoColor=white) ![TLS](https://img.shields.io/badge/mTLS-00D9FF?style=flat-square&logo=letsencrypt&logoColor=white) ![AES](https://img.shields.io/badge/AES--256--GCM-00D9FF?style=flat-square&logoColor=white) |
| **Quality** | ![ruff](https://img.shields.io/badge/ruff-F7B500?style=flat-square) ![mypy](https://img.shields.io/badge/mypy%20strict-2A6DB5?style=flat-square) ![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=pre-commit&logoColor=black) ![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square) |

</div>

---

<br/>

<div align="center">

## 📈 Activity

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=dimbo1324&bg_color=0d1117&color=ff6b35&line=ff6b35&point=ffffff&area_color=1a1a2e&area=true&hide_border=true&custom_title=Building%20consistently%2C%20one%20commit%20at%20a%20time)](https://github.com/ashutosh00710/github-readme-activity-graph)

[![Trophies](https://github-profile-trophy.vercel.app/?username=dimbo1324&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8)](https://github.com/ryo-ma/github-profile-trophy)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dimbo1324&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=ff6b35&text_color=c9d1d9&langs_count=8)](https://github.com/dimbo1324)

</div>

---

<br/>

<div align="center">

## 🌍 The Big Picture

</div>

> I'm not just writing code for a portfolio.
> I'm building a system that — with the right hardware — could run a real power plant.
>
> Because the world runs on infrastructure that was built decades ago.
> Most of it isn't smart. Most of it isn't safe enough. Most of it isn't talking to each other.
>
> **I want to change that. Starting with one boiler. Then a city. Then a country.**

<br/>

<div align="center">

```
2025 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━▶ 2027

  [▓▓▓░░░░░░░]  CogniBoiler v1.0          ← in progress
  [░░░░░░░░░░]  ✈️  Montevideo, Uruguay    ← 2026
  [░░░░░░░░░░]  🌎 IIoT brand LATAM       ← 2026–2027
  [░░░░░░░░░░]  🔬 Real hardware pilot    ← 2027
  [░░░░░░░░░░]  📡 Open-source SCADA      ← beyond
```

<br/>

**Ready to collaborate? Let's build something that matters.**

<br/>

[![Let's Talk](https://img.shields.io/badge/Let's%20Talk%20→%20Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/dimbo1324)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20→%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dmitry-prihodko-6282b8372/)

<br/>
<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d9ff,50:ff6b35,100:c020d0&height=120&section=footer&text=Engineer+who+makes+machines+think.&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=twinkling" width="100%"/>

</div>
