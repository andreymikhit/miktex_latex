# TeX / LaTeX / TeXstudio

### 1. Install in Windows TeX or MiKTex:
- **Download** and install TeX Live from [https://www.tug.org/texlive/](https://www.tug.org/texlive/)
- Concise instructions, per platform:
  - [ ] install on Unix/GNU/Linux
  - [ ] install on Windows -> install-tl-windows.exe
  - [ ] install on MacOS: MacTeX distribution
- Choose **Ways to acquire TeX Live**:
  - [ ] download,
  - [x] **an ISO image or via torrent,**
  - [ ] on DVD,
  - [ ] other methods.
- **Acquiring TeX Live as an ISO image**
  - [x] **download from a nearby CTAN mirror; or**
  - [ ] manually choose from the mirror list; or
  - [ ] retrieve it via the torrent network (info below)
- Index of /tex-archive/systems/texlive/Images/
  - [x] Download `texlive2025.iso	2025-03-08 15:57	6.0G`
- Install process:
  - [x] mount ISO and run `install-tl-windows.bat`
  - [x] than click on Install and
  - [x] wait for `--no-strict --all ...done` (4813/4813) and Close
- Than start _TexWorks editor_ or install _TeXStudio_ editor (see step 2.)
- Install also:
- [ ] TeX Live Manager (tlmgr)
- [ ] Readme [https://www.dante.de/installation-von-tex-live-unter-windows/](https://www.dante.de/installation-von-tex-live-unter-windows/])
- alternatively to TeX Live download and install MikTeX from [https://miktex.org/download](https://miktex.org/download)
  - [ ] basic-miktex-25.12-x64.exe

> _Readme: WiKi TeX - MiKtex - Latex - TeXstudio [https://ru.wikibooks.org/wiki/LaTeX/Установка_LaTeX](https://ru.wikibooks.org/wiki/LaTeX/Установка_LaTeX)_

### 2. Install in Windows TeXstudio Editor
- start _TexWorks editor_ (TeX Live) or:
- Download and install TeXstudio Editor from [https://texstudio.sourceforge.net/](https://texstudio.sourceforge.net/)
  - [x] texstudio-4.9.1-win-qt6-signed.exe
- OR install LyX from [https://www.lyx.org/Download#toc3](https://www.lyx.org/Download#toc3)
  - [ ] LyX-244-Installer-1-x64.exe

### 3. First document:
- start _TexWorks_, _TeXStudio_ or other editors
- proof  that conv. mode is `PdfLaTeX`
- save file to `first.tex` and write as example

```tex
% --- first.tex ---

\documentclass[11pt,a4paper,sans]{moderncv}
\moderncvstyle{classic}
\moderncvcolor{blue}

\usepackage[scale=0.75]{geometry}

\name{Joe}{Mustermann}
\title{Curriculum Vitae}
\address{123 Main Street}{City, State 12345}{Country}
\phone[mobile]{+1~(234)~567~890}
\email{joenmustermann@email.com}

\begin{document}

\makecvtitle

% Content sections go here

\end{document}
```
