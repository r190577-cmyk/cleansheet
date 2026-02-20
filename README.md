# cleansheet

# 🧹 BlankRow Cleaner

> **Fix your Excel & CSV files in one click — no formulas, no macros, no steps needed.**

---

## 💡 The Problem

Every Excel user faces this — you have data with **scattered blank cells across rows and columns**. Excel has no direct way to detect and delete these incomplete rows in one click.

You either have to:
- Manually filter column by column ❌
- Write complex formulas ❌
- Run VBA macros ❌
- Use Go To Special (which doesn't work for scattered blanks) ❌

**BlankRow Cleaner solves this in seconds.** ✅

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎯 **Choose Columns** | Select exactly which columns to check for blanks — others are ignored |
| 👀 **Before & After Preview** | See original data and clean preview side by side before deleting |
| 📄 **CSV & Excel Support** | Works with `.xlsx`, `.xls`, and `.csv` files |
| ↩ **Undo Delete** | Made a mistake? One click restores your original data |
| 🔍 **Auto Detection** | Automatically detects how many real columns your file has |
| 💻 **100% Client-Side** | Your data never leaves your browser — fully private |
| ⚡ **No Installation** | Just open the HTML file — works in any browser |

---

## 🚀 How It Works

```
1. Upload your Excel or CSV file
        ↓
2. Select which columns to check for blanks
        ↓
3. App highlights all incomplete rows in red
        ↓
4. Preview Before & After tabs to verify
        ↓
5. Click Delete & Download → Clean file ready! ✅
```

---

## 📸 Example

**Input Data:**

| Name   | Degree | Branch |
|--------|--------|--------|
| Geetha | B.Tech | CSE    |
| Latha  | B.Tech |        |  ← INCOMPLETE
| Ram    |        | CSE    |  ← INCOMPLETE
| Kiran  | M.Tech | IT     |

**Output Data (after clean):**

| Name   | Degree | Branch |
|--------|--------|--------|
| Geetha | B.Tech | CSE    |
| Kiran  | M.Tech | IT     |

---

## 🛠️ Tech Stack

- **HTML5** — Structure
- **CSS3** — Styling & animations
- **Vanilla JavaScript** — Logic (no frameworks!)
- **SheetJS (xlsx.js)** — Excel & CSV parsing and export
- **Google Fonts** — Syne + JetBrains Mono

---

## 📂 Project Structure

```
blankrow-cleaner/
│
├── BlankRowCleaner.html     ← Main app (entire project in one file!)
├── README.md                ← You are here
└── TestData_100rows.xlsx    ← Sample test file with 100 rows
```

---

## ⚡ Getting Started

No installation needed. Just:

# Open in browser
open BlankRowCleaner.html

Or simply **download the HTML file** and open it in any browser. Done! ✅

---

## 🗺️ Roadmap

- [x] Detect scattered blank rows
- [x] Column selector
- [x] Before & After preview tabs
- [x] CSV support
- [x] Undo delete
- [ ] Duplicate row remover
- [ ] Column trimmer (remove extra spaces)
- [ ] Multi-sheet Excel support
- [ ] Dark/Light theme toggle
- [ ] Drag to reorder columns

---


## 👨‍💻 Author

**Madhvai Muttukuru**

> *"In today's fast world, people need quick answers — not 10 steps to delete a blank row."*

- 🐙 [GitHub](https://github.com/r190577-cmyk/)
