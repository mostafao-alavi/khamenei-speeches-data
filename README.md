# 🏛️ Ayatollah Khamenei Speeches & Works Chronological Archive (1357–1404 / 1979–2026)
### Official Textual Tree-Structured Corpus / آرشیو جامع و منظم درختی بیانات و آثار حضرت آیت‌الله خامنه‌ای

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Speeches: 1066](https://img.shields.io/badge/Full_Speeches-1%2C066-emerald.svg)](https://github.com/mostafao-alavi/khamenei-speeches-data)
[![Time Span: 47 Years](https://img.shields.io/badge/Timeline-1357--1404-blue.svg)](https://github.com/mostafao-alavi/khamenei-speeches-data)
[![Word Count: 3.15M](https://img.shields.io/badge/Total_Words-3.15M-purple.svg)](https://github.com/mostafao-alavi/khamenei-speeches-data)
[![Encoding: UTF-8](https://img.shields.io/badge/Encoding-UTF--8-green.svg)](https://github.com/mostafao-alavi/khamenei-speeches-data)

---

## 🌐 Project Ecosystem / اکوسیستم مخازن سه‌گانه
| Repository | Role | Content | Link |
| :--- | :--- | :--- | :--- |
| 📂 **`khamenei-speeches-data`** | **Primary Source Archive** | آرشیو درختی متن کامل سخنرانی‌ها به تفکیک سال و ماه (Markdown, JSON, HTML, PDF) | [GitHub](https://github.com/mostafao-alavi/khamenei-speeches-data) |
| 📊 **`khamenei-speeches-datasets`** | **AI & Analytics Datasets** | دیتاست‌های تجمیعی هوش مصنوعی (Parquet, JSONL, SQLite FTS5) برای RAG و LLM | [GitHub](https://github.com/mostafao-alavi/khamenei-speeches-datasets) |
| ⚙️ **`khamenei-speeches-tools`** | **Engineering & Crawler** | موتور دانلودر ضد مسدودی، ممیزی داده‌ها، و خط لوله استخراج و پاکسازی | [GitHub](https://github.com/mostafao-alavi/khamenei-speeches-tools) |

---

## 🌍 Complete Multilingual Documentation / مستندات کامل چندزبانه
برای مطالعه مستندات به زبان‌های دیگر، روی پیوندهای زیر کلیک کنید:
- 🇮🇷 **[فارسی (Persian)](docs/README.fa.md)** - نسخه کامل فارسی
- 🇬🇧 **[English (Default)](docs/README.en.md)** - Full English documentation
- 🇸🇦 **[العربية (Arabic)](docs/README.ar.md)** - التوثيق الكامل باللغة العربية
- 🇨🇳 **[中文 (Chinese)](docs/README.zh.md)** - 完整的中文技术文档
- 🇫🇷 **[Français (French)](docs/README.fr.md)** - Documentation complète en français
- 🇹🇷 **[Türkçe (Turkish)](docs/README.tr.md)** - Türkçe tam dokümantasyon
- 🇷🇺 **[Русский (Russian)](docs/README.ru.md)** - Полная документация на русском языке

---

## 🇬🇧 Project Highlights & Architecture Summary

### Core Objective
This repository serves as the definitive, open, and audit-grade chronological repository of all official speeches delivered by Seyyed Ali Khamenei between **1979 and 2026 (1357 to 1404 Solar Hijri)**. Every entry in this repository preserves **only unabridged, full-text transcripts**, rigorously filtering out news summaries, analytical commentaries, and partial excerpts.

### Directory Organization
```text
data/
├── 1357/
│   └── 02/
│       └── 13570222_id.../
│           ├── content.md        # Complete sanitized Markdown text
│           ├── metadata.json     # Standardized bibliographic metadata
│           ├── original.html     # Raw HTML snapshot for verification
│           └── document.pdf      # Official publication PDF (when available)
...
└── 1404/
    └── 10/
        └── 14041027_id58804_.../
```

### Key Metrics
- **Total Unabridged Speeches:** 1,066
- **Total Word Count:** 3,156,132 words
- **Total Characters:** 16,533,837 characters
- **Coverage:** 47 consecutive years (1357 SH through 1404 SH)
- **Integrity Guarantee:** Deduplicated using word-count and transcript-audit scoring.
