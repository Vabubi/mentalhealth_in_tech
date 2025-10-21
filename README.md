# Mental Health in the Tech Industry

## Project Description

`mental_health_analysis` is an exploratory data analysis project using SQL and Python libraries such as Pandas, NumPy, Matplotlib, Seaborn and SciPy.
The dataset originates from Kaggle and examines responses from professionals working in the technology sector.
The goal is to explore how mental health conditions affect tech employees, identify demographic trends and measure workplace attitudes toward mental health using statistical analysis and confidence intervals.

### Table of contents in the notebook

1. Project Setup and Data Acquisition

2. Database Exploration

    2.1 Checking Available Tables

    2.2 Exploring Table Structures

3. Querying and Loading the Final Dataset

4. Overview of Respondents

    4.1 Sample Size

    4.2 Sociodemographic Features

    4.3 Sampling Bias

5. Exploratory Data Analysis (EDA)

    5.1 Statistical Summaries

    5.2 Visual Analysis

    5.3 Mental Health Condition Prevalence

    5.4 Mental Health Condition Comparison

    5.5 Confidence Intervals for Mental Health Prevalence

6. Insights and Answers to the Aim

7. Future Improvements

### How to Use

1. Clone the repository

   ```bash
   git clone github.com/TuringCollegeSubmissions/jplesk-DS.v3.2.1.5.git
   ```

2. Enter the project folder

   ```bash
   mental_health_project
   ```

3. Activate your environment

   ```bash
   jupyter notebook
   ```

   Then open `Notebooks/Mental_project.ipynb` to start the analysis.
---

### Data

* **Source file**: `data/mental_health.sqlite`
* **Tables**: `Survey`, `Question`, `Answer`
* **Final dataset**: Combined via SQL joins into a single DataFrame containing:
  * **UserID** respondent identifier
  * **SurveyDescription** survey metadata
  * **questiontext** survey questions
  * **AnswerText** responses
* **Records**: 236,898 total responses
* **Unique Respondents**: 4,218
---

### File Structure

* mental_health_project/ - Root directory housing all project components

  ```
  data/
  notebooks/
  .gitignore
  README.md
  requirements.txt
  ```

* **data/** - Contains the SQLite database file `mental_health.sqlite`

  ```
  mental_health.sqlite
  ```

* **notebooks/** - Holds the Jupyter notebook and its PDF export

  ```
  Mental_project.ipynb
  .ipynb_checkpoints/
  ```

* **.gitignore** - Excludes caches, environment files, checkpoints, and IDE junk

* **requirements.txt** - Lists Python dependencies

* **README.md** - Provides the project overview and usage instructions

---

### Summary of Insights

* **Demographics:** Majority are young professionals (25-35), male and based in the United States (especially California and Washington).
* **Roles:** Most respondents work as Back-End or Front-End Developers, showing overrepresentation of technical roles.
* **Mental Health Prevalence:**
  * 42% currently have a mental health disorder.
  * 63% report that mental health interferes with their work when untreated.
* **Employer Attitudes:** Only 26% believe their employer takes mental health as seriously as physical health.
* **Confidence Intervals:** 95% CIs confirm statistical reliability-indicating widespread, not random, mental health challenges across tech.
* **Bias:** Strong sampling bias toward male, U.S. based developers.
---

### Prerequisites

* SQL (SQLite database queries)
* Python 3.8 or higher
* pip (Python package installer)
* Git (to clone the repository)
* Jupyter Notebook or JupyterLab
* Project dependencies (install via):

  ```bash
  pip install -r requirements.txt
  ```

---

### Contributing

Contributions are welcome!

---

## Author
Created by Jokūbas
