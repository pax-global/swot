# 🎓 Educational Email Domain Validator

A comprehensive JSON database of **25k+** educational institution domains for validating academic email addresses worldwide.

## 📊 Overview

This repository contains a curated list of educational email domains from universities, colleges, and schools across the globe. Use this to verify if an email address belongs to an educational institution for academic discounts, student verification, educational software licensing, and more.

## 🗂️ What's Inside

- **`educational_email_validator.json`** - Complete validator with metadata and institution details

## 📈 Statistics

| Metric | Count |
|--------|-------|
| 🏫 **Total Domains** | **25,739** |
| 🚫 **Flagged/Abused** | **100** |
| 👥 **Group Domains** | **172** |
| 🇷🇴 **Romania (.ro)** | **216** |

### 🌍 Top Educational TLDs

| TLD | Domains |
|-----|---------|
| `.edu` | **2,671** |
| `.org` | **1,586** |
| `.de` | **1,388** |
| `.com` | **1,041** |
| `.uk` | **941** |
| `.br` | **924** |
| `.in` | **840** |
| `.ru` | **692** |
| `.fr` | **681** |
| `.id` | **652** |

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

This repository is automatically updated on the 1st day of each month at 7:00 AM Romanian time (EET/EEST).










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
