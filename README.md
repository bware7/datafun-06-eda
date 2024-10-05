# datafun-06-eda
Project 6 is an opportunity to create your own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## Installation and Setup

### Create a GitHub Repository

Create a new repository on GitHub, including a README file.
Clone the repository to your local machine

```bash
git clone https://github.com/bware7/datafun-06-eda.git
```

### Add a .gitignore File

Ensure the following entries are added to your .gitignore file to exclude unnecessary files from being committed:

```bash
# Python virtual environment
.venv/

# Visual Studio Code settings and workspace
.vscode/

# Compiled Python files
__pycache__/

# Jupyter notebook checkpoints
.ipynb_checkpoints/
```

### Create and Activate a Virtual Environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

```bash
.\.venv\Scripts\activate
```

### Install Dependencies

Add requirements.txt file, it will be used to install with the necessary libraries.

Add the following libraries to your requirements.txt file:

```bash
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn
```

Install into your active project virtual environment with this command:

```bash
py -m pip install -r requirements.txt
```

### Stage and Push Files to GitHub

Use the following Git commands to stage and commit changes:

```bash
git add .
git commit -m "commit: message"
git push origin main
```
## Dataset Description

This dataset contains information on all-time NBA scoring leaders, sourced from Statista. It includes data such as player names, total career points, and ranking among top NBA scorers. The dataset will be used to explore trends in scoring, visualize player performance, and identify key insights about scoring leaders throughout NBA history.

[NBA all-time scoring leaders](https://www.statista.com/statistics/271305/all-time-nba-scoring-leaders/)

## Exploratory Data Analysis Summary

In this EDA project, I explored the dataset of NBA's all-time scoring leaders. Using Python, Jupyter, and various data analytics libraries, I analyzed scoring trends and visualized player performance. The analysis highlighted the career achievements of LeBron James, Kareem Abdul-Jabbar, and Karl Malone. By combining original data with additional scraped statistics, I provided a detailed comparison of scoring, assists, rebounds, and field goal efficiency.

**Key Findings:**

- Scoring Leadership: LeBron James currently leads in total career points, followed closely by Kareem Abdul-Jabbar and Karl Malone.
- All-Around Contributions: LeBron stands out for his versatility, leading in assists among the top scorers, while Karl Malone dominates in rebounding.
- Efficiency: Kareem's impressive field goal percentage demonstrates his effective scoring methods.

This analysis not only showcases the individual greatness of these players but also emphasizes different paths to becoming an NBA legend — whether through efficient scoring, versatile playmaking, or consistent rebounding.