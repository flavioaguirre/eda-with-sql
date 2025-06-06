# 📊 Analysis of Socioeconomic, Crime, and School Data from Chicago with SQL and Python

---

This project analyzes real-world data from the city of Chicago using SQL queries using SQLite3 and Jupyter Notebooks, with the goal of detecting critical social patterns related to poverty, crime, and school safety. The approach relies exclusively on SQL to perform complex and meaningful queries, supported by pandas for initial exploration.

## 📂 Project Structure

- **assets/**: Static files, such as logo images, used in this project.
- **data/**: Contains the data files used to train the models.
- **notebooks/**: Contains all the Jupyter notebooks that document the workflow, from data exploration to modeling.
- **requirements.txt**: Contains all the dependencies required to run the project.

---

## 🧭 Workflow

1. Initial Data Loading and Exploration

- Imported .csv files into SQLite3 databases.
- Use of pandas to review table structures and obtain initial insights.
- Organized folder structure with /data and /notebooks.

2. **Database Design and Creation**

- A SQLite database called `chicago_data.db` was created, containing:
- `chicago_crime_data`
- ``chicago_socioeconomic_data``
- `chicago_public_schools`

3. **SQL Queries for Analysis**

- Analysis of the number of crimes by community.
- Data crossing between crime and poverty (`JOIN` with `chicago_socioeconomic_data`).
- Identification of the most vulnerable areas based on the `hardship_index`.
- Evaluation of average school safety by community.
- Comparison of patterns between education and crime levels.

4. **Interpretation of Results**

- Communities with more than **50% poverty**, high crime rates, and low levels of school safety were identified.
- The `hardship_index` was key to identifying areas with multiple vulnerabilities.
- Simple visualizations with Pandas were used to support the analysis.

5. **Conclusions**

> This analysis cross-referenced crime data, socioeconomic indicators, and school safety, revealing critical realities that deserve attention. Although we could still delve deeper into academic and social variables, we demonstrated that SQL is a powerful tool for understanding and acting on real-world problems, with the hope of a more just and inclusive future.

---

## 🛠️ Technologies Used

- 🐍 Python 3
- 📁 SQLite3
- 📒 Jupyter Notebooks
- 📊 Pandas
- 💾 CSV as a data source

---

## Installation

### Step 1: Create a Virtual Environment

It is recommended that you create a virtual environment for this project. You can do this by following these steps:

```bash
python -m venv .venv
```

### Step 2: Activate the virtual environment

On Linux/MacOS:

````bash
source .venv/bin/activate
````

On Windows:

````bash
.venv/Scripts/activate
````

### Step 3: Install dependencies. Once the environment is activated, install all the necessary dependencies:

````bash
pip install -r requirements.txt
````

### Step 4: Run the notebooks

Now you can start working with the notebooks. Go to the notebooks folder and explore the analyses.

---

## 📬 Contact

**Flavio Aguirre** – [LinkedIn](https://www.linkedin.com/in/flavio-aguirre-12784a252/) – [flavioaguirre0@gmail.com](mailto:flavioaguirre0@gmail.com)
