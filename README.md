# Data Creation and Analysis using Pandas

This project demonstrates how to create, manipulate, and analyze data in Python using **Pandas** and **NumPy**.  
The notebook is designed as a simple example for anyone learning data analysis or exploring basic data operations in Python.

---

#What This Notebook Covers

The notebook walks through:
- **Creating a dataset** using Python dictionaries and converting it into a DataFrame.
- **Adding calculated columns**, such as profit margin.
- **Inspecting data** with functions like `head()`, `info()`, `describe()`, and `shape`.
- **Selecting and filtering rows** using `.loc` and conditional statements.
- **Summarizing and understanding data** through statistical methods and descriptive analysis.

#Dataset Overview
The dataset represents a small mock sales dataset with the following columns:

| Column | Description |
|--------|--------------|
| **Employee** | Name of the salesperson |
| **Region** | Region of operation (North, South, East, West) |
| **Product** | Product sold |
| **Month** | Month of sale |
| **Sales** | Sales amount in INR |
| **Profit** | Profit earned in INR |
| **Profit Margin** | Derived column = Profit / Sales |

#Libraries Used
- **Pandas** — For data handling and analysis  
- **NumPy** — For numerical operations  

Install them using:
```bash
pip install pandas numpy
