<div align="center">

<img src="assets/banner.svg" alt="Dibbo Adhikary, Computer Science and Engineering student at KUET" width="100%"/>

<br/>

<a href="mailto:dibboadhikary008@gmail.com"><img src="https://img.shields.io/badge/Email-dibboadhikary008%40gmail.com-0f2233?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/dibbo-adhikary-589442323"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://github.com/Dibbo008?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-0f2233?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/></a>

</div>

---

## About

I am a Computer Science and Engineering student at Khulna University of Engineering & Technology (KUET). My work spans the computing stack: digital logic on FPGAs, graph algorithms and numerical methods in C++, and desktop and web applications that use the Google Gemini API.

Each repository is a working project built to understand a concept properly, with the source open to read.

| Area | What I work on |
| :-- | :-- |
| Hardware and Digital Design | FPGA development, custom CPU architecture, Verilog and VHDL |
| Algorithms and Numerical Methods | Graph algorithms, root finding, linear systems, interpolation, regression, integration |
| Artificial Intelligence | AI assistants and chatbots built on the Google Gemini API |
| Software Development | JavaFX desktop applications, React web applications, game programming in C |

## Technical Stack

| Category | Technologies |
| :-- | :-- |
| Languages | ![C](https://img.shields.io/badge/C-0f2233?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-0f2233?style=flat-square&logo=cplusplus&logoColor=white) ![Java](https://img.shields.io/badge/Java-0f2233?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-0f2233?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-0f2233?style=flat-square&logo=javascript&logoColor=white) ![Verilog](https://img.shields.io/badge/Verilog-0f2233?style=flat-square) ![VHDL](https://img.shields.io/badge/VHDL-0f2233?style=flat-square) |
| Desktop | ![JavaFX](https://img.shields.io/badge/JavaFX_21-0f2233?style=flat-square) ![Maven](https://img.shields.io/badge/Maven-0f2233?style=flat-square&logo=apachemaven&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-0f2233?style=flat-square&logo=sqlite&logoColor=white) ![Jackson](https://img.shields.io/badge/Jackson-0f2233?style=flat-square) ![PDFBox](https://img.shields.io/badge/Apache_PDFBox-0f2233?style=flat-square) |
| Web | ![React](https://img.shields.io/badge/React-0f2233?style=flat-square&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-0f2233?style=flat-square&logo=vite&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-0f2233?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-0f2233?style=flat-square&logo=express&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-0f2233?style=flat-square&logo=netlify&logoColor=white) |
| Hardware Tools | ![Vivado](https://img.shields.io/badge/Vivado-0f2233?style=flat-square) ![Quartus](https://img.shields.io/badge/Quartus-0f2233?style=flat-square) ![ModelSim](https://img.shields.io/badge/ModelSim-0f2233?style=flat-square) ![Logisim](https://img.shields.io/badge/Logisim-0f2233?style=flat-square) |
| AI | ![Gemini](https://img.shields.io/badge/Google_Gemini_API-0f2233?style=flat-square&logo=googlegemini&logoColor=white) |

## Featured Projects

### CareerForge: AI Resume and Career Builder

[Repository](https://github.com/Dibbo008/CareerForge-Desktop) | Java 21, JavaFX 21, SQLite, Jackson, Apache PDFBox, Google Gemini API

A JavaFX desktop application for building professional resumes and cover letters, backed by a local SQLite database and enhanced with Google Gemini. When no API key is available, or a request fails, it falls back to a local generator, so the whole app works offline.

- Secure accounts with salted password hashing
- Dynamic resume builder with live preview, Classic and Modern templates, and light and dark themes
- AI-generated summaries and cover letters with automatic offline fallback
- PDF and JSON export and import, and a searchable table of saved resumes
- To The Point: a two-question wizard that maps a target role to hand-curated learning resources, with no generated links
- Interview preparation chart and a job application tracker

<details>
<summary>Engineering details</summary>

<br/>

| Concept | Implementation |
| :-- | :-- |
| Abstraction and inheritance | `Person` (abstract), `Applicant`, `Student` |
| Generics | `GenericDAO<T>` for data access |
| Multithreading | Three-thread pool through `TaskManager` keeps the UI responsive |
| Asynchronous networking | `HttpClient.sendAsync()` with `CompletableFuture`, responses parsed with Jackson |
| Database design | Nine SQLite tables, cascade deletes, `PreparedStatement` for every query, transactional resume writes |

</details>

### Hardware Design

| Project | Description |
| :-- | :-- |
| [FPGA-Digital-Voting-Machine](https://github.com/Dibbo008/FPGA-Digital-Voting-Machine) | An electronic voting system in Verilog for the Xilinx Artix-7 (Basys 3). It authenticates voter IDs, blocks double voting with a per-voter registry, shows live counts, and announces the winner and runner-up. Includes button debouncing and a time-multiplexed 4-digit 7-segment display. |
| [28-BIT-CPU-Design](https://github.com/Dibbo008/28-BIT-CPU-Design) | A custom 28-bit CPU with its own ALU, built as Logisim circuits. The repository includes an architecture write-up and program files for ADD, SUB, AND, OR, MUL and DIV. |

### AI and Web Applications

| Project | Stack | Description |
| :-- | :-- | :-- |
| [Zippy-AI-Assistant](https://github.com/Dibbo008/Zippy-AI-Assistant) | React, Vite, Gemini API | A dog-themed virtual assistant with voice input through the browser SpeechRecognition API. Deployed on Netlify. |
| [PiXEE-AI-Bot](https://github.com/Dibbo008/PiXEE-AI-Bot) | React, Vite, Gemini 2.5 Flash | A creative chat companion prototype that accepts image uploads as conversation context. Deployed on Netlify. |
| [AiZen-AI-RnC](https://github.com/Dibbo008/AiZen-AI-RnC) | JavaScript | An AI-driven web application. |
| [Votebox-EVM](https://github.com/Dibbo008/Votebox-EVM) | JavaScript | An electronic voting machine project for the web. |

### Algorithms and Numerical Methods

| Project | Language | Contents |
| :-- | :-- | :-- |
| [Advance-Algorithms](https://github.com/Dibbo008/Advance-Algorithms) | C++ | Shortest paths: Dijkstra, Bellman-Ford, Floyd-Warshall, Johnson. Spanning trees: Kruskal, Prim. |
| [Numerical-Theories](https://github.com/Dibbo008/Numerical-Theories) | C++ | Root finding (Bisection, False-Position, Newton-Raphson, Secant), linear systems (Gauss Elimination, Gauss-Jordan), LU decomposition, matrix inversion, Newton's interpolation, linear, power and polynomial regression, Simpson's rules, Runge-Kutta 4th order. |
| [Epitrack-DSA](https://github.com/Dibbo008/Epitrack-DSA) | C++ | Data structures and algorithms practice. |

### Other

| Project | Language | Description |
| :-- | :-- | :-- |
| [SDN-Network-Sim](https://github.com/Dibbo008/SDN-Network-Sim) | JavaScript | Software-defined networking simulation. |
| [COBRA.C-Game](https://github.com/Dibbo008/COBRA.C-Game) | C | A game written in C. |

## Education

**Bachelor of Science in Computer Science and Engineering**
Khulna University of Engineering & Technology (KUET), Khulna, Bangladesh

## Research Interests

- Applied machine learning and AI-assisted software
- FPGA-based systems and custom processor architecture
- Software-defined networking and network simulation
- Graph algorithms and numerical computation

## GitHub at a Glance

<div align="center">

<a href="https://github.com/Dibbo008?tab=followers"><img src="https://img.shields.io/github/followers/Dibbo008?style=flat-square&label=Followers&labelColor=0f2233&color=38bdf8&logo=github&logoColor=white" alt="Followers"/></a>
<a href="https://github.com/Dibbo008/CareerForge-Desktop/commits/main"><img src="https://img.shields.io/github/last-commit/Dibbo008/CareerForge-Desktop?style=flat-square&label=CareerForge%20last%20commit&labelColor=0f2233&color=34d399" alt="CareerForge last commit"/></a>
<a href="https://github.com/Dibbo008/Zippy-AI-Assistant/commits/main"><img src="https://img.shields.io/github/last-commit/Dibbo008/Zippy-AI-Assistant?style=flat-square&label=Zippy%20last%20commit&labelColor=0f2233&color=34d399" alt="Zippy last commit"/></a>

<br/>

<img src="https://img.shields.io/github/languages/top/Dibbo008/CareerForge-Desktop?style=flat-square&label=CareerForge&labelColor=0f2233&color=f59e0b" alt="CareerForge top language"/>
<img src="https://img.shields.io/github/languages/top/Dibbo008/FPGA-Digital-Voting-Machine?style=flat-square&label=FPGA%20Voting&labelColor=0f2233&color=f59e0b" alt="FPGA voting top language"/>
<img src="https://img.shields.io/github/languages/top/Dibbo008/Zippy-AI-Assistant?style=flat-square&label=Zippy&labelColor=0f2233&color=f59e0b" alt="Zippy top language"/>

</div>

---

<div align="center">

Open to collaboration on projects in algorithms, hardware design, and AI.

<a href="mailto:dibboadhikary008@gmail.com"><img src="https://img.shields.io/badge/Get_in_touch-dibboadhikary008%40gmail.com-0f2233?style=flat-square&logo=gmail&logoColor=white" alt="Get in touch"/></a>

</div>
