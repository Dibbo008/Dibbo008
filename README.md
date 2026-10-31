<div align="center">

<img src="assets/banner.svg" alt="Dibbo Adhikary, Computer Science and Engineering student at KUET" width="100%"/>

<br/>

<a href="mailto:dibboadhikary008@gmail.com"><img src="https://img.shields.io/badge/Email-dibboadhikary008%40gmail.com-0f2233?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/dibbo-adhikary-589442323"><img src="https://img.shields.io/badge/LinkedIn-Dibbo%20Adhikary-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://github.com/Dibbo008?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-0f2233?style=flat-square&logo=github&logoColor=white" alt="Repositories"/></a>

</div>

---

## About

I am a Computer Science and Engineering student at Khulna University of Engineering & Technology (KUET). I build systems at several levels of the stack: digital logic on FPGAs, graph algorithms and numerical methods in C++, and desktop and web applications that use the Google Gemini API.

Each repository is a working project built to understand a concept thoroughly, with the source open to read.

| Area | Focus |
| :-- | :-- |
| Hardware and Digital Design | FPGA development, custom CPU architecture, Verilog and VHDL |
| Algorithms and Numerical Methods | Graph algorithms, root finding, linear systems, interpolation, regression, integration |
| Artificial Intelligence | AI assistants and chatbots built on the Google Gemini API |
| Software Development | JavaFX desktop applications, React web applications, game programming in C |

## Technical Stack

| Category | Technologies |
| :-- | :-- |
| Languages | C, C++, Java, Python, JavaScript, Verilog, VHDL |
| Desktop | Java 21, JavaFX 21, Maven, SQLite (JDBC), Jackson, Apache PDFBox |
| Web | React, Vite, Node.js, Express, Netlify |
| Hardware Tools | Vivado, Quartus, ModelSim, Logisim |
| AI | Google Gemini API |

## Featured Projects

### CareerForge: AI Resume and Career Builder

[Repository](https://github.com/Dibbo008/CareerForge-Desktop) | Java 21, JavaFX 21, SQLite, Jackson, Apache PDFBox, Google Gemini API

A JavaFX desktop application for building professional resumes and cover letters, backed by a local SQLite database and enhanced with Google Gemini. When no API key is available, or a request fails, it falls back to a local generator, so the whole application works offline.

- Secure accounts with salted password hashing
- Dynamic resume builder with live preview, Classic and Modern templates, and light and dark themes
- AI-generated summaries and cover letters with automatic offline fallback
- PDF and JSON export and import, and a searchable table of saved resumes
- Role-to-learning-resource wizard that maps a target role to hand-curated resources, with no generated links
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
| [FPGA-Digital-Voting-Machine](https://github.com/Dibbo008/FPGA-Digital-Voting-Machine) | Electronic voting system in Verilog for the Xilinx Artix-7 (Basys 3). Authenticates voter IDs, blocks double voting with a per-voter registry, shows live counts, and announces the winner and runner-up. Includes button debouncing and a time-multiplexed 4-digit 7-segment display. |
| [28-BIT-CPU-Design](https://github.com/Dibbo008/28-BIT-CPU-Design) | Custom 28-bit CPU with its own ALU, built as Logisim circuits. Includes an architecture write-up and program files for ADD, SUB, AND, OR, MUL and DIV. |

### AI and Web Applications

| Project | Stack | Description |
| :-- | :-- | :-- |
| [Zippy-AI-Assistant](https://github.com/Dibbo008/Zippy-AI-Assistant) | React, Vite, Gemini API | Dog-themed virtual assistant with voice input through the browser SpeechRecognition API. Deployed on Netlify. |
| [PiXEE-AI-Bot](https://github.com/Dibbo008/PiXEE-AI-Bot) | React, Vite, Gemini 2.5 Flash | Creative chat companion prototype that accepts image uploads as conversation context. Deployed on Netlify. |
| [AiZen-AI-RnC](https://github.com/Dibbo008/AiZen-AI-RnC) | JavaScript | AI-driven web application. |
| [Votebox-EVM](https://github.com/Dibbo008/Votebox-EVM) | JavaScript | Electronic voting machine project for the web. |

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
| [COBRA.C-Game](https://github.com/Dibbo008/COBRA.C-Game) | C | Game written in C. |

## GitHub Activity

<table>
  <tr>
    <td width="50%" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/github_dark/0-profile-details.svg"/>
        <img src="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/default/0-profile-details.svg" alt="GitHub profile details" width="100%"/>
      </picture>
    </td>
    <td width="50%" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/github_dark/3-stats.svg"/>
        <img src="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/default/3-stats.svg" alt="GitHub stats" width="100%"/>
      </picture>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/github_dark/1-repos-per-language.svg"/>
        <img src="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/default/1-repos-per-language.svg" alt="Repositories per language" width="100%"/>
      </picture>
    </td>
    <td width="50%" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/github_dark/2-most-commit-language.svg"/>
        <img src="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/default/2-most-commit-language.svg" alt="Most committed languages" width="100%"/>
      </picture>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/github_dark/4-productive-time.svg"/>
        <img src="https://raw.githubusercontent.com/Dibbo008/Dibbo008/main/profile-summary-card-output/default/4-productive-time.svg" alt="Commits by time of day" width="50%"/>
      </picture>
    </td>
  </tr>
</table>

## Education

**Bachelor of Science in Computer Science and Engineering**
Khulna University of Engineering & Technology (KUET), Khulna, Bangladesh

## Research Interests

- Applied machine learning and AI-assisted software
- FPGA-based systems and custom processor architecture
- Software-defined networking and network simulation
- Graph algorithms and numerical computation

## Contact

Open to collaboration on projects in algorithms, hardware design, and AI.

- Email: [dibboadhikary008@gmail.com](mailto:dibboadhikary008@gmail.com)
- LinkedIn: [Dibbo Adhikary](https://www.linkedin.com/in/dibbo-adhikary-589442323)
