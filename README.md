# CW-85 EDU 智算平台 (Educational Scientific Calculator Simulator)

[](https://opensource.org/licenses/MIT)

**CW-85 EDU 智算平台** is a suite of zero-dependency, single-file browser simulators developed for secondary school mathematics education, teacher whiteboard projection, and student self-study. Built to emulate the workflow and tactile button sequences of the UK's most widely used GCSE examination calculators—specifically the **fx-85GT X (GT-X Series)** and **fx-83GT CW (ClassWiz CW Series)**—without using proprietary trademarks, copyrighted logos, or manufacturer artwork.

Students and teachers using this simulator can transfer their calculation habits and button sequences directly to physical examination hardware without relearning workflows.

---

## 🌟 What's New in This Release

### 1. 📱 Mobile Full-Screen Calculator Mode (全屏計數機模式)
- **One-Tap Clean Interface**: Tap **`全屏計數機`** (or **`Full Screen Calc`**) to instantly hide the browser header, tabs, and desktop workbench. The entire mobile screen becomes a dedicated handheld calculator.
- **Floating Controls**: A lightweight floating control pill remains at the top-right corner to cycle color chassis themes (`🎨`)—defaulting to **Pink Theme**—or expand back to the full pedagogical workspace (`↙ 展開工具列`) at any time.

### 2. 🖥️ Teacher Projector Layout & Synchronized Screen (投影示範模式)
- Inspired by live classroom teaching requirements, tap **`投影佈局`** (or **`Projector Mode`**) to switch into split presentation layout.
- **Giant Synchronized LCD Display**: Displays expressions, 2D fractions/surds, and calculation results enlarged up to 300% on the projector, paired with real-time top status flags (`S`, `A`, `√□`, `D`, `FIX`, `SCI`, `M`).
- **Live Classroom Keystroke Stream**: Logs teacher button presses in real time (`[SHIFT] → [■/□] → ...`) with interactive demonstration tools.

### 3. 🌐 Pure Language Toggle (純繁中 / Pure English)
- **Default Language**: Set to **English** for classroom compatibility.
- **Toggle Mode**: Easily switch between English and 繁體中文 interfaces for bilingual support.

### 4. 📐 Authentic High-Resolution LCD Digits & Table Display
- **Bold Monospace LCD Typography**: Built with proportional tabular digits (`Courier Prime`), enlarged input expressions (`18px`), and bold output results (`23px`) for enhanced legibility.

---

## 📦 Included Editions

| File | Emulated Hardware Workflow | Target Examination Standards | Primary Characteristics |
| :--- | :--- | :--- | :--- |
| `index.html` | **ClassWiz CW Series Workflow** (fx-83GT CW / fx-85GT CW) | New UK GCSE Mathematics & KS3/4 Syllabus | `HOME` 5-app launcher, circular D-pad with center `OK` & `BACK`, `CATALOG`, `TOOLS`, `FORMAT` menu, Math Box. |

---

## 🚀 Deployment & Embedding

Each simulator is completely self-contained in a single HTML file—no Node.js build, server backend, or external asset dependencies needed.

### 1. Local & Classroom Offline Use
Download `index.html` and double-click to open in any modern browser without requiring an internet connection.

### 2. GitHub Pages / Cloudflare Pages Free Hosting
1. Push this repository to GitHub.
2. In GitHub, go to **Settings → Pages**, select the branch (`main`), folder (`/root`), and click **Save**. Your site will be live at `https://<username>.github.io/<repo>/`.

### 3. Embedding in Google Sites / School LMS
1. Open your Google Site editor.
2. Select **Insert (插入) → Embed (嵌入) → Embed code (嵌入程式碼)**.
3. Paste the contents of `index.html` into the dialog, click **Next → Insert**.

---

## ⚖️ Educational Notice & Fair Use
**CW-85 EDU 智算平台** is an independent, non-affiliated educational simulation software. Not officially sponsored, endorsed, or certified by any calculator manufacturer or examination board.

---

## 📄 License
Distributed under the [MIT License](https://opensource.org/licenses/MIT). Free for schools, teachers, students, and educational institutions.