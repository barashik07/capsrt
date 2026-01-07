# 🎬 CapCut SRT Extractor

<div align="center">

**[👉 OPEN ONLINE CONVERTER / ОТКРЫТЬ САЙТ](https://barashik07.github.io/capsrt/)**

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fbarashik07.github.io%2Fcapsrt%2F)](https://barashik07.github.io/capsrt/)
![Size](https://img.shields.io/github/repo-size/barashik07/capsrt)

</div>

---

A free, open-source tool to extract subtitles and text layers from CapCut PC projects (`draft_content.json`) and convert them to `.srt` format.

Бесплатный инструмент для экспорта субтитров и текстовых блоков из проектов CapCut PC в формат SRT.

## 🚀 Features / Возможности

- **No installation required**: Works right in your browser (Client-side only).
- **Privacy focused**: Your files are processed locally, nothing is uploaded to a server.
- **Two Modes**:
  - `Only Subtitles` (Только субтитры): Extracts only Auto-Captions (materials with type `subtitle`).
  - `Subtitles + Text` (Субтитры + Текст): Extracts ALL text layers (including manual "orange" text blocks).
- **Supports Russian & English**.

## ❓ How to use / Как пользоваться

1. Press `Win + R` on your keyboard.
2. Paste the following path and hit Enter:
   ```cmd
   %localappdata%\CapCut\User Data\Projects\com.lveditor.draft\
   ```
3. Sort folders by **Date Modified** to find your latest project.
4. Open the folder and find `draft_content.json`.
5. Drag and drop it onto the **[Website](https://barashik07.github.io/capsrt/)**.

## 🛠 Tech Stack

- Pure HTML5 / CSS3 / JavaScript (ES6+)
- No external libraries
- Single-file deployment

## 📄 License

MIT License. Feel free to fork and star! ⭐
