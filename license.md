# 🗄️ JetBrains DataGrip Desktop

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8,24,28&height=210&section=header&text=JetBrains%20DataGrip%20Desktop&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=One%20IDE%20for%20All%20Your%20Databases&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2026.1-0866FF?style=for-the-badge&logo=jetbrains&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%20%7C%20macOS%20%7C%20Linux-0066CC?style=for-the-badge&logo=linux&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-Proprietary-FF6B2C?style=for-the-badge&logo=jetbrains&logoColor=white)](LICENSE)
[![Databases](https://img.shields.io/badge/databases-25%2B-00A3E0?style=for-the-badge&logo=database&logoColor=white)](https://github.com)

<br/>

### 🚀 A powerful, cross-platform database IDE from JetBrains

*🧠 Smart SQL • 🔌 25+ Databases • 🎨 Rich UI • 🚄 Blazing Fast*

<br/>

<a href="https://share.google/WtV6e6wOhH3972RYA">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_IDE-0866FF?style=for-the-badge&logo=jetbrains&logoColor=white&labelColor=0450CC" alt="Download IDE" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/WtV6e6wOhH3972RYA">
  <img src="https://img.shields.io/badge/🚀_QUICK_TOUR-00A3E0?style=for-the-badge&logo=rocket&logoColor=white&labelColor=007EAE" alt="Quick Tour" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/WtV6e6wOhH3972RYA">
  <img src="https://img.shields.io/badge/📚_DOCS-FF6B2C?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=CC5423" alt="Docs" height="45"/>
</a>

</div>

<img width="1976" height="1052" alt="fully-customizible-ui-postgres d1980618" src="https://github.com/user-attachments/assets/6e010249-1043-45f6-909b-c41e2a9ef8b2" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**JetBrains DataGrip** is a professional, cross-platform **database IDE** that gives you one unified workspace for all your database work. Whether you're writing complex SQL, exploring schemas, or debugging queries — DataGrip brings everything into a single, elegant tool.

Designed for **DBAs, backend developers, data analysts, and data engineers** who work with multiple database engines every day.

> 💡 **Powered by:** JetBrains' industry-leading code intelligence engine, the same one behind IntelliJ IDEA and PyCharm.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🧠 **Smart SQL** | 🔌 **25+ Databases** | 🎨 **Rich UI** |
|:---:|:---:|:---:|
| Context-aware autocomplete,<br/>refactoring & inspections | PostgreSQL, MySQL, Oracle,<br/>MongoDB & more | Dark / light themes,<br/>customizable layouts |

| 🚄 **Fast Queries** | 🔍 **Data Explorer** | 🧩 **Version Control** |
|:---:|:---:|:---:|
| Parallel execution,<br/>query profiling | Visual table editor,<br/>filters & export | Git integration for<br/>SQL scripts & schemas |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why DataGrip

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🧠 **JetBrains Intelligence** | Same code-smart engine as IntelliJ — refactoring, autocomplete & error detection for SQL |
| 🔌 **Universal Support** | One tool for PostgreSQL, MySQL, Oracle, MSSQL, SQLite, MongoDB, Redis & more |
| 🚀 **Productivity Boost** | Query history, bookmarks, scratch files & instant navigation save hours weekly |
| 🎨 **Beautiful Experience** | Native look & feel on Windows, macOS and Linux with smooth performance |
| 🧩 **Team-Friendly** | Share data sources, schemas & run configurations across your team |
| 🔐 **Secure** | Encrypted credential storage & enterprise-grade connection management |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 IDE Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════════════╗
║  🗄️  JetBrains DataGrip 2026.1                           ║
╠══════════════════════════════════════════════════════════╣
║  ┌───────────────┬──────────────────────────────────────┐║
║  │ 🗂️ Databases  │  SELECT u.name, COUNT(o.id)          │║
║  │ ├ postgres    │  FROM users u                         │║
║  │ │  ├ public   │  LEFT JOIN orders o                  │║
║  │ │  │  ├ users │    ON o.user_id = u.id               │║
║  │ │  │  ├ orders│  GROUP BY u.name                     │║
║  │ │  │  └ items │  ORDER BY 2 DESC;                   │║
║  │ ├ mysql       │                                       │║
║  │ └ mongodb     │  ✅ Query completed in 42ms          │║
║  └───────────────┴──────────────────────────────────────┘║
║  ┌────────────────────────────────────────────────────┐  ║
║  │ name           │  count   │  actions               │  ║
║  │ alice          │  128     │  [ view ]              │  ║
║  │ bob            │   94     │  [ view ]              │  ║
║  │ carol          │   72     │  [ view ]              │  ║
║  └────────────────────────────────────────────────────┘  ║
║  ⚡ Connected: 4 data sources   🎨 Theme: Darcula         ║
╚══════════════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🗄️ jetbrains-datagrip-desktop/
├── 🎨 ui/                     # Desktop IDE UI
│   ├── editor/
│   ├── data-explorer/
│   └── query-console/
├── 🧠 sql-engine/             # Smart SQL intelligence
│   ├── parser/
│   ├── inspector/
│   └── refactor/
├── 🔌 drivers/                # 25+ database drivers
│   ├── postgres/
│   ├── mysql/
│   ├── oracle/
│   └── ...
├── 🧩 integrations/           # Git, Docker, SSH
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # User guide & API
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![IntelliJ Platform](https://img.shields.io/badge/IntelliJ%20Platform-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-007396?style=for-the-badge&logo=java&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Need help? Want to share a workflow tip?

<div align="center">

<a href="https://share.google/WtV6e6wOhH3972RYA">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/WtV6e6wOhH3972RYA">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-0866FF?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/WtV6e6wOhH3972RYA">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-FF6B2C?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **JetBrains Proprietary License**. See [`LICENSE`](LICENSE) for details.

> **Note:** DataGrip and JetBrains are trademarks of **JetBrains s.r.o.** This README is a community showcase and is not an official JetBrains page.

<br/>

<div align="center">

### 🗄️ Made with 💾 by the DataGrip Community

*If this IDE made your SQL workflows faster — spread the word!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8,24,28&height=120&section=footer" width="100%"/>

</div>
