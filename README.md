# 🎓 Educational Email Domain Validator

A comprehensive JSON database of **26k+** educational institution domains for validating academic email addresses worldwide.

## 📊 Overview

This repository contains a curated list of educational email domains from universities, colleges, and schools across the globe. Use this to verify if an email address belongs to an educational institution for academic discounts, student verification, educational software licensing, and more. We use this data across all apps within [pax.global](https://pax.global) ecosystem.

## 🗂️ What's Inside

- **`educational_email_validator.json`** - Complete validator with metadata and institution details

## 📈 Statistics

| Metric | Count |
|--------|-------|
| 🏫 **Total Domains** | **26,497** |
| 🚫 **Flagged/Abused** | **100** |
| 👥 **Group Domains** | **172** |
| 🇷🇴 **Romania (.ro)** | **220** |

### 🌍 Top Educational TLDs

| TLD | Domains |
|-----|---------|
| `.edu` | **2,736** |
| `.org` | **1,608** |
| `.de` | **1,410** |
| `.com` | **1,061** |
| `.in` | **1,039** |
| `.uk` | **964** |
| `.br` | **937** |
| `.ru` | **692** |
| `.fr` | **687** |
| `.id` | **678** |

## 📋 Domain Structure

Each domain entry contains detailed information:

```json
{
  "mit.edu": {
    "name": "Massachusetts Institute of Technology",
    "additional_names": ["MIT"],
    "is_group": false,
    "verified": true,
    "is_abused": false
  },
  "unibuc.ro": {
    "name": "University of Bucharest",
    "additional_names": [],
    "is_group": false,
    "verified": true,
    "is_abused": false
  }
}
```

### 🏷️ Field Descriptions

- **`name`** - Primary institution name
- **`additional_names`** - Alternative names, campuses, or abbreviations
- **`is_group`** - `true` if domain is shared by multiple institutions
- **`verified`** - Always `true` (all domains are verified educational institutions)
- **`is_abused`** - `true` if domain has been flagged for abuse/misuse

## 🔄 Updates

This repository is automatically updated on the 1st day of each month around 7:00 AM or 8:00 AM Romanian time (Dorel sometimes wakes up late; aka winter/summer time).
Latest data is also reflected in the README.










## 📅 **Source**: [JetBrains/swot](https://github.com/JetBrains/swot) repository

## 📄 License

This project follows the same license as the source data from [JetBrains/swot](https://github.com/JetBrains/swot).

## 🙏 Credits

- **Data Source**: [JetBrains/swot](https://github.com/JetBrains/swot) - Community-maintained list of educational institutions
- **Community**: Thousands of contributors to the original swot database

---

## 🤝 Contributing

This repository is automatically maintained. To add or update educational domains, please contribute to the upstream [JetBrains/swot](https://github.com/JetBrains/swot) repository.

---

🌟 **Star this repository** if you find it useful for your educational verification needs!
