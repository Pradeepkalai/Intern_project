# 🚀 Intern Project

## 📅 Day 1: Text Normalization, Tokenization & Stopword Removal using NLTK

---

## 📖 Overview

This project demonstrates fundamental **Natural Language Processing (NLP)** preprocessing techniques using **Python** and **NLTK**.

### ✅ Features

- **Text Normalization** – Converts text to lowercase.
- **Tokenization** – Splits text into individual words.
- **Stopword Removal** – Removes common English stopwords to retain meaningful words.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python 3.x | Programming Language |
| NLTK | Natural Language Processing Library |

---

## 📦 Installation

Install NLTK using the following command:

```bash
pip install nltk
```

---

## 📥 Required NLTK Resources

The following resources are downloaded automatically when the program runs:

```python
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
```

---

## ⚙️ Working Process

### 🔹 Step 1: Input Text

The user enters a paragraph or sentence.

**Example:**

```text
Hello World! This is an NLP Project.
```

---

### 🔹 Step 2: Text Normalization

All characters are converted to lowercase.

**Before:**

```text
Hello World! This is an NLP Project.
```

**After:**

```text
hello world! this is an nlp project.
```

---

### 🔹 Step 3: Tokenization

The normalized text is split into individual words.

**Input:**

```text
hello world
```

**Output:**

```python
['hello', 'world']
```

---

### 🔹 Step 4: Stopword Removal

Common English words such as:

```text
is, am, are, the, and, of, in, on, for, to
```

are removed from the tokenized list.

**Example:**

```python
['this', 'is', 'an', 'nlp', 'project']
```

⬇️

```python
['nlp', 'project']
```

---

## 🎯 Output

The program displays:

- ✅ Original Text
- ✅ Normalized Text
- ✅ Tokenized Words
- ✅ Filtered Words After Stopword Removal

---

## 📚 Learning Outcomes

After completing this project, you will understand:

- Text preprocessing in NLP
- Text normalization techniques
- Word tokenization using NLTK
- Stopword removal methods
- Basic NLP workflow using Python

---

## 🌟 Project Summary

This project serves as a beginner-friendly introduction to **Natural Language Processing (NLP)** using **Python** and **NLTK**. It demonstrates how raw text can be cleaned and prepared for further NLP tasks through normalization, tokenization, and stopword removal.

---

### 👨‍💻 Developed as Part of Internship Training

**Day 1 – NLP Text Preprocessing using NLTK**
