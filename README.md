# HM Morse Translator

A premium, production-ready, single-file web application to encode standard text into custom **HM Morse Code** and decode it back in real time. 

The application is completely self-contained in a single HTML file (`index.html`) with no external libraries, frameworks, CDNs, or internet dependencies required. It works 100% offline.

---

## 🌌 The HM Morse System Rules

The system is built on standard International Morse Code but maps symbols and structural boundaries to unique representations.

### Symbol Mapping
* **Dot (`.`)** &rarr; `hm`
* **Dash (`-`)** &rarr; `hmm`

*Examples:*
* **A** (`.-`) &rarr; `hm hmm`
* **B** (`-...`) &rarr; `hmm hm hm hm`
* **C** (`-.-.`) &rarr; `hmm hm hmm hm`

### Formatting & Boundaries
1. **Symbol Separator:** Symbols within a single character are separated by a **single space** (e.g. `hm hmm` for `A`).
2. **Character Separator:** Each translated character is placed on **its own line**.
3. **Word Separator:** A space between words in normal text is represented by **1 blank line**.
4. **Paragraph Separator:** A newline (Enter key) in normal text is represented by **2 blank lines**.

---

## ✨ Features

* **Real-time Translation:** Code translates dynamically as you type.
* **Auto-detect Input Mode:** Detects whether you are typing plain text or HM Morse automatically—no toggle switch required.
* **Responsive Glassmorphism Design:** Beautiful dark UI featuring modern typography, soft glowing highlights, and transitions. It works perfectly on both Desktop (split-screen columns) and Mobile (stacked layout).
* **Smart Copying:** One-click copy buttons for both input and output sections.
* **Quick Swap:** Instantly switch input and output sources.
* **Download Output:** Export your translated content directly to a `.txt` file.
* **Live Word & Character Counters:** Displays counts tailored to each translation mode (including line-separated Morse word boundaries).
* **Custom Guide & Searchable Reference Table:** Quick reference cards showing formatting rules and an interactive, real-time searchable table containing letters, numbers, and common punctuation.
* **Toast Notification System:** In-app floating feedback alerts for actions like copy, swap, clear, and download.

---

## 🚀 Getting Started

Since the entire application is written in vanilla HTML, CSS, and JavaScript with zero external calls:

1. Locate the `index.html` file.
2. Double-click or open it with any web browser (Google Chrome, Firefox, Safari, Microsoft Edge, etc.).
3. Start typing!

---

## 🛠️ Supported Characters

* **Alphanumeric:** `A-Z`, `a-z`, `0-9`
* **Punctuation:** `. , ? ! ' " : ; ( ) & + - / = @ $`
* **Fallback Handling:** Any unsupported characters translate into the standard Morse code for `?` (`hm hm hmm hmm hm hm`) to avoid breaking the tool.
