# Week 2 - Halfday 1

## Missions & Activities:

### Activity 1
- **Problem**: Gaining a deep understanding of the available dataset: use case [Titanic dataset](https://www.kaggle.com/c/titanic/data)
- **Hint**: Check pandas methods such as `.head()`, `.info()`, `.describe()`
- **Tools**: NumPy, pandas, scikit-learn
- **New/Consolidation of ML Glossary**: Balanced/unbalanced dataset, imputation

## Expected Outcomes:
A Jupyter notebook for proper data exploration of the Titanic dataset. Your notebook should perform the tasks listed below. In your notebook, systematically use markdown cells to:
- Explain the goal of your code (i.e., what you are doing and *why*)
- Comment on the results
- Provide direct answers to **all** the questions listed below (Section [Questions](#questions))

## Tasks – Data Exploration
0. [*Optional*] Installation of an IDE to work with Jupyter notebooks. Suggestions: Visual Studio Code, PyCharm, etc. Below, you will find the instructions for Visual Studio Code:
    - Install [Git](https://git-scm.com/downloads)
    - Install [Python](https://www.python.org/downloads/) (>3.11)
    - Install [VS Code](https://code.visualstudio.com/download)
    - In VS Code, install the "Python" package
    - In VS Code, install the "Jupyter" package 
    - Create a new project
    - Create a virtual environment (venv)
    - Be sure to select the new venv as the kernel 
    - Open the terminal (ensure the terminal is within the virtual environment) and run the following commands:

        ```bash
        pip install ipykernel
        pip install -U scikit-learn
        pip install numpy
        pip install pandas
        pip install matplotlib
        ```

1. Explore the types of features present in the dataset (numerical vs. categorical)
2. Explore correlations:
    - Between features (X)
    - Between features (X) and the target (y)
3. Analyze whether the dataset is balanced or unbalanced
4. Explore missing values and approaches to deal with them (imputation). You will implement this in the next activity.

## Questions:
At the end of the activity, you should be able to answer these questions and *justify* your answers:
- Why is it important to know the type (numerical vs. categorical) of a feature?
- Why is it important to understand correlations? Is it good to have features highly correlated with each other? Is it good to have features highly correlated with the target?
- List possible problems related to an unbalanced dataset.
- List possible solutions for dealing with an unbalanced dataset.
- Multiple approaches to deal with missing values exist. The scikit-learn library proposes *mean*, *median*, *most frequent*, and *k-NN* imputation methods.
  - When is one approach more suitable than another?
  - Should you impute missing values in the target (y)?
  - Is imputation always a good idea?
