<div align="center">

# 🐍 Python Data Structures & Conditional Statements

### Lists • Dictionaries • Sets • IF-Elif-Else

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Anaconda](https://img.shields.io/badge/Topic-DataStructures-44A833?style=for-the-badge&logo=anaconda&logoColor=white)


</div>

## 📑 Table of Contents

- [📖 Overview](#-overview)
- [🎯 Learning Objectives](#-learning-objectives)
- [📂 Repository Structure](#-repository-structure)
- [🧩 Assignment Breakdown](#-assignment-breakdown)
- [🚀 Getting Started](#-getting-started)
- [💻 Sample Output](#-sample-output)
- [🧠 Key Takeaways](#-key-takeaways)
- [🛠️ Tech Stack](#️-tech-stack)
- [👤 Author](#-author)

---

## 📖 Overview

**This repository contains my solution to **Python Data Structures & Conditional statements**, which covers the core built-in data structures in Python and basic decision-making with conditional statements. All the work is written and executed in a Jupyter Notebook, with each task documented using inline comments and short explanations**.

## 🎯 Learning Objectives

- ✅ Create, modify, and access **Lists**
- ✅ Store and manipulate key-value data with **Dictionaries**
- ✅ Understand uniqueness and immutability rules of **Sets**
- ✅ Perform set operations such as **union** and **intersection**
- ✅ Build decision logic using **`if`, `elif`, and `else`**
- ✅ Accept and validate **user input**

---

## 📂 Repository Structure

```
📦 python-data-structures-assignment

 ┣ 📓 List, Dictionary, Set & Conditional Statements.ipynb         # Solution notebook

 ┣ 📄 Python Data Structures - List, Dictionary, Set & Conditional Statements.pdf      # Assignment question paper
 
 ┗ 📝 README.md

```

---

## 🧩 Assignment Breakdown

### 📋 1. Lists: Creation, Modification & Access

| Task | Operation | Method Used |
|------|-----------|-------------|
| Create lists | `age_list` (integers), `name_list` (strings) | `[ ]` |
| Add an item | Append `"Yazhini"` to `name_list` | `append()` |
| Insert an item | Insert `30` at index 2 in `age_list` | `insert()` |
| Remove an item | Remove `"Yazhini"` from `name_list` | `remove()` |
| Remove last item | Pop the last age | `pop()` |
| Add many items | Extend with `[29, 30, 26]` | `extend()` |
| Sort | Descending order | `sort(reverse=True)` |
| Statistics | Max, Min, Sum of ages | `max()`, `min()`, `sum()` |
| Access | First, last, slice, reverse | Indexing, slicing, `reverse()` |

### 📖 2. Dictionaries: Creation, Modification & Access

- 🔹 Created `student_marks` mapping five students to marks (0–100)
- 🔹 Accessed a specific student's mark using its key
- 🔹 Added a new student **Janani** with a mark of **80**
- 🔹 Updated an existing student's mark to **82**
- 🔹 Displayed data using `keys()`, `values()`, and `items()`

### 🔣 3. Sets: Operations

- 🔹 Built `my_set` from repeated vowels and observed that duplicates are removed automatically
- 🔹 Tried `my_set[4] = 's'` and documented why it fails (sets do not support indexing or item assignment)
- 🔹 Created `set1` and `set2`, then computed:
  - **Union** → `set1 | set2`
  - **Intersection** → `set1 & set2`

### 🎓 4. Operators & Conditional Statements: Performance Category Program

The program prompts for a score from **0 to 10** and prints a performance category with a custom message.

| Score Range | Category | Message |
|-------------|----------|---------|
| Greater than 7 | 🟢 **Above Average** | Excellent work! Keep up the great performance. |
| 4 to 7 (inclusive) | 🟡 **Average** | Good effort! Keep practicing, there's room for improvement. |
| Less than 4 | 🔴 **Below Average** | Need to improve your performance, consistent practice will lead to better results. |
| Below 0 or above 10 | ⚠️ **Invalid** | Please enter a score between 0 and 10. |

---

## 🚀 Getting Started

### Prerequisites

- 🐍 Python 3.8 or higher
- 📓 Jupyter Notebook or JupyterLab (included with Anaconda)
  
---

## 💻 Sample Output

**List operations**

```python
>>> name_list.append('Yazhini')
['Sukumar', 'Bucchi', 'Srikanth', 'Kayadu', 'Nani', 'Yazhini']

>>> age_list.sort(reverse=True)
[30, 30, 29, 27, 26, 26, 25, 24]

Max age: 30
Min age: 24
Sum of ages: 217
```

**Set operations**

```python
>>> my_set = {'a','e','i','o','u','a','a','i'}
{'a', 'e', 'i', 'o', 'u'}

Union: {1, 2, 3, 5, 7, 8, 9, 10}
Intersection: {3, 5}
```

**Performance category program**

```text
Enter your score 0 to 10: 6
Average: Good effort! Keep practicing, there's room for improvement.
```

---

## 🧠 Key Takeaways

| Concept | Insight |
|---------|---------|
| 📋 **List** | Ordered, mutable, allows duplicates, and supports indexing and slicing |
| 📖 **Dictionary** | Stores key-value pairs with fast lookup by key |
| 🔣 **Set** | Unordered, stores unique values only, and does **not** support indexing |
| 🔀 **Conditionals** | `if-elif-else` chains evaluate top to bottom and stop at the first match |

> 💡 **Why does `my_set[4] = 's'` fail?**

> Sets are unordered collections, so their elements have no index position.

>  Python raises `TypeError: 'set' object does not support item assignment`.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | Programming language |
| ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) | Interactive notebook environment |
| ![Anaconda](https://img.shields.io/badge/-Topic-44A833?logo=anaconda&logoColor=white) | Data Structures & Conditional statement |
| ![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white) | Code hosting |

---

## 👤 Author

**Y. Srihari**

**Aspiring Data Analyst**

**Python | SQL | Excel | Power BI**
