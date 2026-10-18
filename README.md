<div align="center">

<img src="assets/home-screen.svg" width="100%" alt="Ahmad Yaseen's home screen. The tiles are his projects: BMO, AnyPS5 Launcher, Hopcord, Brackora, AnyPS5 contributions and the ay_os portfolio.">

<a href="https://www.linkedin.com/in/ahmad-yaseen-8937942a0/"><img src="https://img.shields.io/badge/LinkedIn-Ahmad%20Yaseen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:ai.ahmad.3a4@gmail.com"><img src="https://img.shields.io/badge/Email-ai.ahmad.3a4%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/ahmad3a4?tab=followers"><img src="https://img.shields.io/github/followers/ahmad3a4?style=for-the-badge&logo=github&label=Followers&color=1d3fa8" alt="GitHub followers"></a>

</div>

## Hi there 👋, I'm Ahmad

**Data Science & AI Engineer · Technical Entrepreneur · Full-Stack Developer**

I specialize in building high-performance, low-latency AI pipelines, autonomous systems, and scalable web solutions. As the founder of **Brackora**, I bridge the gap between complex programming and practical digital automation.

Lately I've also been getting PS5 software running on PC. I built a launcher for [AnyPS5](https://github.com/boykopovar/AnyPS5) and contribute fixes to its reimplemented PS5 system libraries.

### 🚀 What I do

- **AI & Computer Vision:** developing real-time inference models and tracking systems.
- **Edge Computing:** running local LLMs and optimizing TTS/STT pipelines on constrained hardware.
- **Web Development:** crafting clean, responsive, and robust digital platforms.
- **Systems & emulation:** C++ fixes to AnyPS5, written to match FreeBSD (the PS5's OS base), and tooling around it.

## 🎮 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [AnyPS5 Launcher](https://github.com/ahmad3a4/AnyPS5-Launcher)
A PS5-style home screen and game library for AnyPS5 on Windows: add a game, press Play. It converts, checks compatibility, and launches, and it stays on the newest AnyPS5 straight from the official repo.

<a href="https://github.com/ahmad3a4/AnyPS5-Launcher"><img src="https://raw.githubusercontent.com/ahmad3a4/AnyPS5-Launcher/main/docs/screenshots/console-view.png" width="100%" alt="AnyPS5 Launcher's PS5-style home screen"></a>

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Tkinter](https://img.shields.io/badge/Tkinter-555?logo=python&logoColor=white) ![MIT](https://img.shields.io/badge/license-MIT-blue) [![Stars](https://img.shields.io/github/stars/ahmad3a4/AnyPS5-Launcher?style=flat&logo=github&label=stars)](https://github.com/ahmad3a4/AnyPS5-Launcher/stargazers)

</td>
<td width="50%" valign="top">

### [BMO](https://github.com/ahmad3a4/bmo)
A real-time, voice-interactive AI companion with true personality, sub-second latency, and a face that shows its feelings. Inspired by BMO from Adventure Time, running on a Raspberry Pi 5.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi%205-A22846?logo=raspberrypi&logoColor=white) [![Stars](https://img.shields.io/github/stars/ahmad3a4/bmo?style=flat&logo=github&label=stars)](https://github.com/ahmad3a4/bmo/stargazers)

### [Hopcord](https://github.com/ahmad3a4/hopcord)
An original 2D platformer that runs live inside a Discord voice channel as a Discord Activity. Race whoever else is in the call to the flag.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Discord](https://img.shields.io/badge/Discord%20Activity-5865F2?logo=discord&logoColor=white)

### [ay_os portfolio](https://github.com/ahmad3a4/portfolio)
My portfolio, rebuilt as a fake operating-system desktop.

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

</td>
</tr>
</table>

## 🧩 Open source: AnyPS5

[AnyPS5](https://github.com/boykopovar/AnyPS5) converts PS5 executables into native PC programs and reimplements the PS5's system libraries. My contributions so far:

| | Contribution | Status |
|---|---|---|
| 🔧 | [**#5502**](https://github.com/boykopovar/AnyPS5/pull/5502) `sysctlnametomib`: a missing kernel function that stopped a Java 25 homebrew app from loading. Written to match FreeBSD; verified by a contributor and merged by a maintainer. | ![](https://img.shields.io/github/pulls/detail/state/boykopovar/AnyPS5/5502?label=%20) |
| 🔧 | [**#5831**](https://github.com/boykopovar/AnyPS5/pull/5831) Atomic `O_APPEND` writes on Windows: concurrent appends were losing about 1 in 8 lines. Cross-checked by contributors on Windows and Linux, then merged. | ![](https://img.shields.io/github/pulls/detail/state/boykopovar/AnyPS5/5831?label=%20) |
| 🔧 | [**#6287**](https://github.com/boykopovar/AnyPS5/pull/6287) The same fix for `fopen`/`freopen` append streams, found through the log of the PS5MC media center, which was losing characters. | ![](https://img.shields.io/github/pulls/detail/state/boykopovar/AnyPS5/6287?label=%20) |
| 🐞 | [**#5931**](https://github.com/boykopovar/AnyPS5/issues/5931) Found that closing Syobon Action crashed AnyPS5's exit path, then validated the two fixes on Windows. | ![](https://img.shields.io/github/issues/detail/state/boykopovar/AnyPS5/5931?label=%20) |
| 🎮 | Game bring-up threads: [Java 25 LAN / DNS (#5501)](https://github.com/boykopovar/AnyPS5/discussions/5501), which now starts on AnyPS5, and [Syobon Action (#5932)](https://github.com/boykopovar/AnyPS5/discussions/5932) | |

## 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Piper TTS](https://img.shields.io/badge/Piper%20TTS-444?style=flat-square)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ahmad3a4/ahmad3a4/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ahmad3a4/ahmad3a4/output/github-snake.svg">
  <img alt="A snake eating Ahmad's GitHub contribution graph" src="https://raw.githubusercontent.com/ahmad3a4/ahmad3a4/output/github-snake.svg">
</picture>

## 📫 Let's connect

- **LinkedIn:** [ahmad-yaseen-8937942a0](https://www.linkedin.com/in/ahmad-yaseen-8937942a0/)
- **Email:** [ai.ahmad.3a4@gmail.com](mailto:ai.ahmad.3a4@gmail.com)
