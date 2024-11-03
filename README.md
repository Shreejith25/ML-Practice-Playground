# ML-Practice-Playground

## Decision Tree Classifier with Pre-Pruning & Post-Pruning

File name : Decision_Tree

This project showcases a Decision Tree Classifier using the Iris dataset , implementing Pre-Pruning and Post-Pruning techniques to improve model performance and prevent overfitting. The classifier is built in Python, leveraging scikit-learn for model building, tuning, and evaluation.

Libraries Used
    - Pandas
    - sklearn
    - matplotlib


### 📂 Project Files
classifier.py - Main code file containing model setup, training, and evaluation.
README.md - This file with documentation.
requirements.txt - List of required Python packages.
### 📚 Overview
The Iris dataset is used to train and evaluate the model, which is split into training and testing sets in a 70-30 split (random state = 42). The objective is to classify flowers into three categories: Setosa, Versicolor, and Virginica based on features like 🌱 sepal length, sepal width, petal length, and petal width.

### Training the Model
#### Post-Pruning
Post-pruning involves growing the tree fully and then trimming it back to control complexity.

####  Pre-Pruning
Pre-pruning restricts the tree's growth during training by limiting parameters like max_depth and criterion.


Post-Pruning: Allows the tree to grow entirely before reducing complexity, often yielding high accuracy.
Pre-Pruning: Controls tree growth from the start, reducing overfitting risks early.

## Data Analysis and Visualization Tools: ydata-profiling, AutoViz, and D-Tale

File name : Automated_EDA_libraries

### Overview

 We explore three powerful libraries for data profiling, visualization, and analysis. By applying these libraries to popular datasets like titanic and tips, we streamline exploratory data analysis (EDA) and gain quick insights into data distributions, correlations, and trends
    
    Libraries used
        - Pandas 
        - Numpy 
        - Seaborn
        - Matplotlib
        - ydata-profiling (formerly pandas-profiling) - For creating comprehensive data profiling reports.
                Installation: `pip install ydata-profiling`
        - AutoViz - For automated data visualization.
                Installation: `pip install autoviz`
        -D-Tale - For interactive data visualization and exploration within Jupyter notebooks.
                `Installation: pip install dtale`

#### **ydata-profiling (formerly pandas-profiling)**
Overview: This library generates a detailed HTML report with insights into data types, missing values, distributions, and correlations, helping you understand your dataset quickly.

#### **AutoViz**
Overview: AutoViz is an automated data visualization tool that can generate insightful visualizations for any dataset with minimal input.

#### **D-Tale**
Overview: D-Tale is an interactive visualization and data exploration tool that integrates with Jupyter notebooks. It allows users to explore datasets in real-time with a GUI interface.

📢 Disclaimer
These tools provide a powerful starting point for data analysis, but they only scratch the surface. Mastering data analysis requires an understanding of statistical concepts, data cleaning techniques, and knowing when and how to apply different visualization methods effectively.
    
    

