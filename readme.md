# 🎓 Educational Email Domain Validator

A comprehensive JSON database of **25k+** educational institution domains for validating academic email addresses worldwide.

## 📊 Overview

This repository contains a curated list of educational email domains from universities, colleges, and schools across the globe. Use this to verify if an email address belongs to an educational institution for academic discounts, student verification, educational software licensing, and more.

## 🗂️ What's Inside

- **`educational_email_validator.json`** - Complete validator with metadata and institution details

## 📈 Statistics

| Metric | Count |
|--------|-------|
| 🏫 **Total Domains** | **25,131** |
| 🚫 **Flagged/Abused** | **108** |
| 👥 **Group Domains** | **174** |
| 🇷🇴 **Romania (.ro)** | **206** |

### 🌍 Top Educational TLDs

| TLD | Domains |
|-----|---------|
| `.edu` | **2,617** |
| `.org` | **1,558** |
| `.de` | **1,357** |
| `.com` | **1,008** |
| `.uk` | **924** |
| `.br` | **918** |
| `.ru` | **691** |
| `.in` | **687** |
| `.fr` | **671** |
| `.id` | **641** |
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