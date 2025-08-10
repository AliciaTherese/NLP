#  NLP Text Cleaner (PyQt6 GUI) 🧹

An elegant desktop application built with **PyQt6** to clean messy text using **regular expressions**.  
It removes HTML tags, URLs, emails, scripts, phone numbers, repeated punctuation, and more — all in a beautiful GUI.

---

## ✨ Features
- 🧽 **Text Cleaning** – Removes:
  - HTML tags
  - URLs & email addresses
  - JavaScript-like variable/script patterns
  - HTML entities (`&amp;`, `&copy;`, etc.)
  - Phone numbers
  - Repeated punctuation
  - Special characters (except allowed ones)
  - Extra spaces
- 🖥 **GUI Interface** – Simple and responsive design
- 📡 **Live Preview** – Optional real-time cleaning as you type
- 📝 **Console Log** – Fake "processing" steps for a realistic NLP pipeline feel
- 📋 **Copy Output** – Quickly copy cleaned text to clipboard
- 🧹 **Clear All** – Reset input, output, and console

---

## 📦 Installation

Make sure you have **Python 3.8+** installed.

1. **Clone this repository**
```bash
git clone https://github.com/your-username/nlp-text-cleaner.git
cd nlp-text-cleaner
