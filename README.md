# Data Analysis With Python

A practical, beginner-friendly, and hands-on course project for learning **Data Analysis with Python** using **Pandas**, **NumPy**, **SQL Server connectivity**, and modern Python project setup with **uv**.

This repository contains Jupyter notebooks covering the most important Python and Pandas concepts required for real-world data analysis.

---

## 📺 YouTube Playlist

All video explanations are available in this playlist:

[Watch Full Course on YouTube](https://youtube.com/playlist?list=PL8R6SZU5x4kULYKT3rQsv3fK4BOIa1LSD&si=kU0GQzuJMp4gEnzV)

---

## 📚 Topics Covered

This project includes practical Jupyter notebooks on the following topics.

### 1. Pandas Basics

- Introduction to Series in Pandas
- Create DataFrame using Python built-in data structures
- Inspect a dataset using Pandas
- Data types in Pandas
- Convert data types in Pandas
- Index in Pandas DataFrame

### 2. Reading Data

- Reading CSV files in Pandas
- Reading Excel files in Pandas
- Connect and read SQL Server data using Pandas

### 3. Selecting, Filtering, and Sorting Data

- How to efficiently subset a Pandas DataFrame
- Filter a Pandas DataFrame using a single condition
- Filter a Pandas DataFrame using multiple conditions
- Filter a Pandas DataFrame using the `loc` method
- Efficient DataFrame filtering
- Sort a Pandas DataFrame
- Axis in Pandas DataFrame

### 4. Creating and Transforming Variables

- Create new variables in Pandas DataFrame
- Use the `assign()` method effectively in Pandas
- Conditional variable creation using `np.where()` and `np.select()`
- Map function in Pandas
- Apply function in Pandas
- ApplyMap function in Pandas

### 5. Working With Text, Dates, and Numeric Operations

- String methods in Pandas
- Arithmetic functions in Pandas
- Date functions in Pandas
- Aggregate functions in Pandas

### 6. Grouping and Summarizing Data

- Groupby function in Pandas
- Pivot table in Pandas
- Crosstab in Pandas

### 7. Reshaping and Combining Data

- Transform data from wide to long format using Pandas `melt()`
- Combine multiple DataFrames using Pandas `concat()`
- Joining DataFrames using Pandas `merge()`

### 8. Data Cleaning and Feature Engineering

- Binning in Pandas
- Fix duplicate rows in Pandas

---

## 🧰 Tools and Technologies Used

This project uses the following tools and technologies:

- Python
- Pandas
- NumPy
- Jupyter Notebook
- SQL Server
- pyodbc
- SQLAlchemy
- uv Python package manager
- VS Code / DataSpell / JupyterLab

---

## 🚀 Project Setup Using uv

This project uses **uv** as the Python package manager.

`uv` is a modern and fast Python package and environment manager. It helps you create virtual environments, install dependencies, and run Python commands in a clean and reproducible way.

Using `uv` makes the project easier to clone, set up, and run on another machine.

---

## ✅ What To Do After Cloning This Project

Follow these steps after cloning the repository.

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

Move into the project folder:

```bash
cd <your-project-folder>
```

---

### 2. Install uv

If `uv` is not already installed, install it first.

For Windows PowerShell:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Check whether `uv` is installed:

```bash
uv --version
```

---

### 3. Restore the Project Environment

If the project contains a `pyproject.toml` file and `uv.lock` file, run:

```bash
uv sync
```

This command will:

- Create a `.venv` virtual environment if it does not already exist
- Install all required project dependencies
- Use the locked dependency versions from `uv.lock`
- Make the project environment consistent across machines

---

### 4. Activate the Virtual Environment

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

On macOS/Linux:

```bash
source .venv/bin/activate
```

After activation, you should see something like this in the terminal:

```bash
(.venv)
```

---

### 5. Add Jupyter Support

If Jupyter and ipykernel are not already installed, run:

```bash
uv add --dev jupyter ipykernel
```

Then register the virtual environment as a Jupyter kernel:

```bash
uv run python -m ipykernel install --user --name=data-analysis-python --display-name "Python (.venv)"
```

When you open a notebook, select this kernel:

```text
Python (.venv)
```

---

## 📦 Common uv Commands

### Install all dependencies

```bash
uv sync
```

### Add a package

```bash
uv add pandas
```

### Add a development package

```bash
uv add --dev jupyter
```

### Run Python

```bash
uv run python
```

### Run a Python script

```bash
uv run python script.py
```

### Check installed packages

```bash
uv pip list
```

### Add Excel file support

```bash
uv add openpyxl xlrd
```

### Add SQL Server support

```bash
uv add pyodbc sqlalchemy
```

---

## 🧠 Who This Course Is For

This course is useful for:

- Beginners learning Python for data analysis
- Data analysts moving from Excel or SQL to Python
- Business analysts who want to learn Pandas
- Students learning practical data analysis
- Professionals preparing for analytics interviews
- Anyone building a strong foundation in Python-based analytics

---

## 🎯 Learning Outcomes

After completing this course, you will be able to:

- Create and manipulate Pandas Series and DataFrames
- Read data from CSV, Excel, and SQL Server
- Inspect and understand datasets
- Understand and convert data types
- Work with DataFrame indexes
- Filter, subset, and sort data
- Create new variables using multiple techniques
- Use `np.where()` and `np.select()` for conditional logic
- Use `map()`, `apply()`, and `applymap()`
- Work with string methods in Pandas
- Work with date functions in Pandas
- Perform arithmetic and aggregate operations
- Summarize data using groupby, pivot tables, and crosstab
- Reshape data from wide to long format
- Combine datasets using concat
- Join datasets using merge
- Create bins and categories
- Identify and fix duplicate rows
- Use uv to manage Python environments and dependencies

---

## ▶️ Recommended Learning Path

Follow the notebooks in sequence.

1. Start with Pandas Series and DataFrame basics
2. Learn how to read data from CSV, Excel, and SQL Server
3. Practice inspecting datasets
4. Understand and convert data types
5. Learn indexing, filtering, sorting, and subsetting
6. Create new variables and apply transformations
7. Work with string, date, arithmetic, and aggregate functions
8. Summarize data using groupby, pivot table, and crosstab
9. Reshape data using melt
10. Combine and join multiple datasets
11. Learn data cleaning topics like binning and duplicate handling

---

## 📝 Working With Notebooks

To open Jupyter Notebook:

```bash
uv run jupyter notebook
```

To open JupyterLab:

```bash
uv run jupyter lab
```

You can also open the project in VS Code or DataSpell and select the `Python (.venv)` kernel.

---

## 🙌 About This Project

This project is part of the **Analytics School** learning series.

The goal of this project is to make Python, Pandas, SQL, and data analysis concepts easy to understand through practical examples and hands-on notebooks.

---

## ⭐ Support

If you find this project helpful:

- Watch the YouTube playlist
- Practice each notebook
- Star the repository
- Share it with other learners

---

## 📄 License

This project is for educational purposes. You may use and modify the notebooks for learning and practice.