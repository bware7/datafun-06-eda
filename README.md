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
git commit -m "initial commit"
git push origin main
```
