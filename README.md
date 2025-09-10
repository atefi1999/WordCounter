# Word Counter

A simple Python application to **analyze text files** and count words, characters, sentences, and unique words.  
It also displays the **top 10 most common words** and can save the results to a file.

---

## ✨ Features

- Count total characters in a text file  
- Count total sentences (`.`, `!`, `?`)  
- Count total words  
- Count unique words  
- Display the **top 10 most common words**  
- Save results to a text file (`output.txt` by default)  

---

## 🛠 Requirements

- Python 3.x  
> No external libraries required — only Python standard library.

---

## ▶️ Usage

### 1. Run the program
```bash
python word_counter.py
```

### 2. Input
```backtick
Enter the filename: sample.txt
```

### 3. Example Output
```backtick
📊 Word Counter Results
------------------------------
Characters: 1024
Sentences : 45
Words     : 200
Unique    : 150
```

🔝 Top 10 Most Common Words:
```backtick
the: 15
and: 12
to: 10
Python: 8
is: 7
...
```

### 4. Output Files
```backtick
results.txt → Contains the analysis results
```

---
## 📂 Project Structure

```markdown
.
├── word_counter.py   # Main program
├── sample.txt        # Example input text file
└── README.md         # Project documentation
```
