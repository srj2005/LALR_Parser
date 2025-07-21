# 📊 LALR Parsing Table Generator


## 🚀 Overview

This tool provides:
- A modern **frontend interface using Streamlit**
- Upload capability for **Transition** and **CLR State** files
- Interactive visualization of **LALR Parsing Tables**
- **Expandable views** for in-depth exploration of states & lookaheads
- Option to **download parsing tables** as CSV files

---

## ✨ Features

✅ Upload `transitions.txt` and `clr_states.txt`  
✅ Parse and extract transition and CLR data  
✅ Auto-generate **LALR Parsing Table**  
✅ Expand CLR states with **lookahead info**  
✅ **Download as CSV**  
✅ Clean and interactive **Streamlit UI**

---

## 🛠️ Tech Stack

| Layer      | Technology     |
|------------|----------------|
| Frontend   | Streamlit      |
| Backend    | Python         |
| Data       | Pandas         |

---

## 📁 File Descriptions

### `app.py`
- Streamlit interface
- Handles file uploads
- Parses and displays parsing tables
- Supports CSV export

### `transitions.txt`
Maps states to transitions using Python-like dict notation.

**Example:**
```plaintext
0|{'S': 1, 'C': 2, 'c': 3, 'd': 4}
2|{'C': 5, 'c': 6, 'd': 7}
