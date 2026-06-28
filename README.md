<!-- ====================== HEADER ====================== -->

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&text=Alexey%20Gaydel&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Android%20Developer%20%E2%80%A2%20Kotlin%20%E2%80%A2%20Jetpack%20Compose%20%E2%80%A2%20KMP&descAlignY=58&color=0:5B21B6,100:A855F7"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3200&pause=900&color=A855F7&center=true&vCenter=true&width=780&lines=Building+production-grade+Android+applications;Jetpack+Compose+%7C+Kotlin+Multiplatform;Clean+Architecture+%7C+Offline-first+Apps;Backend+experience+with+ASP.NET+Core"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7C3AED?style=for-the-badge&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-8B5CF6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Kotlin%20Multiplatform-A855F7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Android-6D28D9?style=for-the-badge"/>
</p>

---

## 👨‍💻 About

Android developer with **3 years of Kotlin experience**. I build complete products — from UI and architecture to backend APIs, databases, and deployment. Not demos.

Currently open to Android opportunities.

---

## ⚡ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,java,git,github,gradle,ktor,dotnet,cs,postgres,sqlite,linux"/>
</p>

<table align="center">
<tr>

<td align="center" width="33%">

<img src="https://skillicons.dev/icons?i=kotlin,androidstudio" height="40"/>

**Mobile**

Kotlin · Jetpack Compose · Material 3
Kotlin Multiplatform · Navigation
Room · WorkManager

</td>

<td align="center" width="33%">

<img src="https://skillicons.dev/icons?i=dotnet,postgres,sqlite" height="40"/>

**Backend**

ASP.NET Core · Entity Framework Core
Ktor · REST APIs
PostgreSQL · SQLite · Railway

</td>

<td align="center" width="33%">

<img src="https://skillicons.dev/icons?i=git,github" height="40"/>

**Architecture**

Clean Architecture · MVVM
Repository Pattern · Dependency Injection
Koin · Offline-first · Testing

</td>

</tr>
</table>

---

## 📌 Featured Projects

---

# <img src="lifetracker_icon.webp" width="96"> LifeTracker

<p align="center">
  <img src="https://img.shields.io/badge/Android-34A853?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kotlin-7C3AED?style=for-the-badge&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-8B5CF6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
</p>

<p align="center">
  <b>Full-stack gamified productivity application built with modern Android architecture.</b>
</p>

---

| Layer | Stack |
|-------|-------|
| <img src="https://skillicons.dev/icons?i=kotlin" height="18"/> Android | Kotlin · Jetpack Compose · Clean Architecture · Koin · Room · Retrofit · WorkManager |
| <img src="https://skillicons.dev/icons?i=dotnet" height="18"/> Backend | ASP.NET Core · Entity Framework Core · PostgreSQL · Railway |

---

**Highlights:**

- 🎯 Real client-server architecture with offline-first sync and conflict resolution
- 📡 Typed `NetworkResult` · 🛡 Custom `SafeApiCaller`
- ✨ Glassmorphism Bottom Navigation
- 🎒 Inventory mechanics · 🏆 Daily quests · 🔥 Streak system · 📊 Statistics dashboard

---

<details>
<summary><b>🏗 Architecture</b></summary>

```
                 UI
                 │
         Jetpack Compose
                 │
            ViewModel
                 │
           Repository
        ┌────────┴────────┐
        │                 │
      Room           Retrofit
        │                 │
     SQLite        ASP.NET Core API
                          │
                     PostgreSQL
```

</details>

---

# <img src="tradelog_icon.webp" width="82"> TradeLog

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin%20Multiplatform-A855F7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Compose%20Multiplatform-9333EA?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenRouter-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Desktop-6D28D9?style=for-the-badge"/>
</p>

<p align="center">
  <b>Cross-platform trading journal for Android & Desktop with AI-assisted analytics.</b>
</p>

---

| Layer | Stack |
|-------|-------|
| <img src="https://skillicons.dev/icons?i=kotlin" height="18"/> Application | Kotlin Multiplatform · Compose Multiplatform · SQLDelight · Ktor Client |
| <img src="https://img.shields.io/badge/AI-111827?style=flat-square&logoColor=white" height="18"/> AI | OpenRouter |

---

**Highlights:**

- 📱 Shared Android + Desktop codebase · 📐 Adaptive UI via `WindowSizeClass`
- 📊 Analytics by pair, setup, weekday and session
- 💼 Multi-account portfolio · 💰 Commission & swap-adjusted P&L · 📅 Daily P&L heatmap
- 🎯 Prop-firm challenge tracking · 🤖 AI-generated trade reviews · ☁ Cloud-ready architecture

---

<details>
<summary><b>🏗 Architecture</b></summary>

```
          Android        Desktop
               │             │
               └──────┬──────┘
                      │
        Compose Multiplatform UI
                      │
                 Shared Domain
                      │
                 Shared Data
              ┌───────┴────────┐
              │                │
         SQLDelight       Ktor Client
              │                │
         Local Cache      AI Services
```

</details>

---

## 🧠 Philosophy

I enjoy building software that solves real problems — complete products with scalable architecture, production-ready code, polished UI/UX, backend infrastructure, testing, and long-term maintainability.

---

## 🚀 Current Focus

- Multi-module Gradle architecture
- Performance & optimization
- Backtesting engine (TradeLog)
- UI polish & animations
- Kotlin Multiplatform improvements
- Testing (JUnit5 + MockK)

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Witty-Charm&show_icons=true&theme=transparent&hide_border=true&title_color=A855F7&icon_color=C084FC&text_color=D1D5DB"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Witty-Charm&layout=compact&theme=transparent&hide_border=true&title_color=A855F7&text_color=D1D5DB"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Witty-Charm&theme=transparent&hide_border=true&ring=A855F7&fire=C084FC&currStreakLabel=A855F7"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Witty-Charm&theme=react-dark&bg_color=00000000&hide_border=true&color=A855F7&line=C084FC&point=ffffff&area=true"/>
</p>

---

## 📫 Contact

<p align="center">
  <a href="mailto:alexgaydle@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" />
  </a>
  <a href="https://t.me/graydle">
    <img src="https://cdn.simpleicons.org/telegram" width="48" height="48" />
  </a>
  <a href="https://www.linkedin.com/in/alex-gaydel-264622288/">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:5B21B6,100:A855F7&section=footer"/>
</p>
