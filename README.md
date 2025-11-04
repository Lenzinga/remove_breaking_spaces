# Non-breaking Space Cleaner

When copying code or text from chatbots, PDFs, or certain websites, invisible **non-breaking spaces (NBSP)** often sneak in.  
These characters (`U+00A0`, `U+202F`, or `&nbsp;`) can break formatting, indentation, or cause unexpected behavior in code.

This small, single-file **HTML app** automatically replaces all those NBSPs with regular spaces — in real time.

## 🧩 Features
- Paste your text or code on the left side  
- Automatically cleaned output on the right  
- Displays the number of replacements  
- One-click **Copy** button for the cleaned text  
- Works entirely offline (just open the `.html` file in a browser)

## 🧠 How It Works
The app scans your input for:
- `&nbsp;` literal strings  
- Unicode non-breaking spaces (`\u00A0`)  
- Narrow non-breaking spaces (`\u202F`)

It replaces all of them with standard spaces (`" "`), so you can safely paste clean code elsewhere.

## 🚀 Usage
1. Open `index.html` in your browser  
2. Paste any text into the **Input** field  
3. The cleaned version appears automatically on the **Output** side  
4. Click **Copy** to copy the cleaned text to your clipboard

## 💡 Example
**Input:** `const x = 42; // contains NBSP`  
**Output:** `const x = 42; // clean`

---

**License:** MIT  
**Author:** Lenzinga  
