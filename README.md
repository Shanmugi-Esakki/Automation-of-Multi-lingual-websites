# 🌐 Automated Multilingual Website Translation and Enhancement using Azure Translator

## 📌 Project Description

This project automates the process of translating static HTML web pages into multiple languages using the **Microsoft Azure Translator API**.

It parses HTML content using **BeautifulSoup** and translates the textual content (e.g., headings, paragraphs, spans, titles, and anchor texts) into target languages like **English (en)**, **French (fr)**, and **Spanish (es)**.
##### Note: Replace the code with your Azure credencials.

### 🔧 Key Features

- ✅ Automated translation of HTML content using Azure Translator API  
- ✅ Targets multiple languages configurable via a list of language codes  
- ✅ Maintains original HTML structure while replacing textual content  
- ✅ Saves translated files in organized, language-specific output folders  
- ✅ Appends a `<script src="/scripts/language.js">` tag for dynamic functionality across translated pages  
- ✅ Handles missing tags and translation failures gracefully

---

## 📂 Directory Structure

```plaintext
multilingual-website/
├── original_html/           # Input directory with original English HTML files
├── translated_html/         # Output directory with translated HTML files per language
│   ├── en/
│   ├── fr/
│   └── es/
├── translate.py             # Python script for translating HTML content
├── inject_script.py         # Python script to add language.js script to translated files
└── scripts/
    └── language.js          # JavaScript for dynamic behavior (optional)


