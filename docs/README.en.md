# 🇬🇧 Khamenei Speeches Chronological Tree Archive (1979–2026)
### Official Textual Corpus & Primary Source Repository for Computational Linguistics, History, and AI Research

---

## 📌 Executive Summary
This repository contains the authoritative, chronological, and hierarchical text archive of speeches, sermons, and public addresses by Ayatollah Seyyed Ali Khamenei, spanning 47 years from **May 1979 to January 2026** (1357 to 1404 Solar Hijri). It provides scholars, computational linguists, and AI researchers with clean, verified primary source materials formatted according to open-science standards.

---

## 🛡️ Strict Corpus Quality Principles
- **Unabridged Transcripts Only:** All summaries, news snippets, and partial quotations have been programmatically identified and removed.
- **Exclusion of Editorializing:** Secondary analyses, editorial commentaries, and media interpretations are excluded to guarantee unbiased primary source authenticity.
- **Resolution of Historical Variants:** Where multiple entries existed for the same calendar event, the version exhibiting the highest word count and accompanied by official documentation (such as PDF scans) was selected as canonical.

---

## 📁 Repository Directory Structure
The dataset follows an intuitive chronological tree hierarchy:
```text
data/
└── YYYY/
    └── MM/
        └── YYYYMMDD_id<ID>_<SanitizedTitle>/
            ├── content.md        # Full speech transcript in clean Markdown
            ├── metadata.json     # Standardized JSON metadata (Gregorian & Solar dates, URL, word count)
            ├── original.html     # Pristine raw HTML snapshot preserved for auditability
            └── document.pdf      # Official publication PDF (when archived)
```

---

## 📈 Dataset Statistics
- **Total Canonical Speeches:** 1,066
- **Word Count:** 3,156,132 tokens
- **Character Count:** 16,533,837 characters
- **Temporal Span:** May 12, 1979 – January 17, 2026
- **Format:** Plaintext Markdown, UTF-8 encoded, without proprietary lock-in.

---

## 🔗 Associated Ecosystem
- [khamenei-speeches-datasets](https://github.com/mostafao-alavi/khamenei-speeches-datasets): Consolidated datasets in Parquet, JSON Lines, and SQLite with full-text search (FTS5).
- [khamenei-speeches-tools](https://github.com/mostafao-alavi/khamenei-speeches-tools): Automated scrapers, WAF bypass engine, and deduplication auditing tools.
