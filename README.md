# 🚀 Content Split Pro

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Languages](https://img.shields.io/badge/languages-HTML%2C%20CSS%2C%20JS-orange.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

An intelligent web app to split long scripts into perfectly sized, audio-ready blocks for TTS platforms, social media, and more.

[**➡️ View Live Demo ⬅️**](https://wpdevexpert.github.io/content-split-pro/)

---

## 🤔 The Story Behind This Project

This tool was born out of a practical need for my YouTube story channel. I rely on **SPEECHMA**, a fantastic and free unlimited Text-to-Speech (TTS) platform, to generate the voice-overs for my scripts.

However, SPEECHMA has a limitation: it can only process a maximum of **2000 characters** at a time.

Simply cutting a long script at exactly 2000 characters would often result in awkwardly broken sentences, creating unnatural pauses and a poor listening experience for my audience. I needed a way to break down my scripts logically.

**Content Split Pro is the solution.** I built it to intelligently scan a long script and split it into blocks that are under a specified character limit, but it always makes the cut at the **nearest complete sentence**. This ensures that every block of text sent to SPEECHMA is a coherent paragraph, resulting in a smooth, natural-sounding voice-over every time.

---

## ✨ Key Features

* **Intelligent, Sentence-Aware Splitting:** The core feature! It breaks down text based on a character limit without splitting words, prioritizing natural sentence endings.
* **Use-Case Presets:** Quickly set the character limit for platforms like Twitter/X or use it for segmenting video scripts and presentations.
* **Real-Time Content Analysis:** Get instant feedback on your source text as you type, including:
    * Word & Character Counts
    * Sentence & Paragraph Counts
    * Flesch-Kincaid Reading Grade Level
    * Estimated Reading & Speaking Time
* **Interactive Block Management:** Mark generated blocks as "Done" to hide them from the main view and track your progress. Restore them with a single click.
* **Automatic Numbering:** All generated blocks are automatically numbered `(x/n)` to easily track their order.
* **Copy to Clipboard:** Each block has a "Copy" button that includes the content and its `(x/n)` numbering.
* **Zero Dependencies:** The entire application is a **single HTML file**. No installation, no build steps, and no internet connection required after the initial load.
* **Responsive Design:** Clean, modern, and fully usable on both desktop and mobile devices.

---

## 🏁 Getting Started

Since this is a single-file web application, you can use the live demo or run it locally.

**Option 1: Use the Live Demo (Recommended)**

Simply visit the live link: [https://wpdevexpert.github.io/content-split-pro/](https://wpdevexpert.github.io/content-split-pro/)

**Option 2: Run Locally**

1.  **Download the File:**
    * Download the `content-split-pro.html` file from this repository.
2.  **Open in Browser:**
    * Open the downloaded `.html` file in any modern web browser.

---

## 🔧 How to Use for a TTS Workflow

1.  **Input Your Script:** Paste your entire YouTube script into the "Source Text" area.
2.  **Set Your Limit:** In the **Max Chars** input box, enter `2000` to match SPEECHMA's limit.
3.  **Split:** Click the **Split Text** button. Your script will be broken down into perfectly sized, sentence-complete blocks.
4.  **Generate Audio:**
    * Use the **Copy** button on "Block 1" and paste it into SPEECHMA to generate the first audio part.
    * Click **Done** on "Block 1" to move it to the "Completed Blocks" list.
    * Repeat the process for the remaining blocks until your full script is voiced.

---

## 🛠️ Built With

* **HTML5:** For the core structure and content.
* **Tailwind CSS:** For modern, responsive, utility-first styling.
* **Vanilla JavaScript (ES6+):** For all the application logic and interactivity.

---

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.
