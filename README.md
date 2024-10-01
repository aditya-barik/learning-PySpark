# Learning PySpark

## Overview
This repository contains my work and exercises from the Udemy course titled **"Spark and Python for Big Data with PySpark"**. The course covers the fundamentals of using Spark with Python, including Spark Streaming, Machine Learning, Spark DataFrames, and more!

Throughout the course, I followed along with the lectures and projects to complete various PySpark-related tasks.

## Course Details
- **Course Title:** [Spark and Python for Big Data with PySpark](https://www.udemy.com/course/spark-and-python-for-big-data-with-pyspark/)
- **Platform:** Udemy
- **Topics Covered:**
  - Setting up a PySpark environment
  - DataFrame operations with PySpark
  - Using Spark in a Linux environment
  - Learning about the Databricks platform
  - Setting up AWS EC2 for big data analysis
  - Using AWS Elastic MapReduce (EMR) service
  - Applying machine learning models with PySpark MLlib
  - Working on projects that mimic real-world situations
  - Creating a spam filter using PySpark and Natural Language Processing (NLP)
  - Analyzing tweets in real-time using Spark Streaming

## Repository Structure
The repository is organized based on the modules covered in the course. Below is an overview of the structure:

```
root\
  ├── course-resources\
  │     - Jupyter notebooks provided with the course
  ├── pyspark-dataframe\
  │     - Jupyter notebooks practicing basics of Spark DataFrames
  ├── pyspark-machine-learning\
  │     - Jupyter notebooks practicing basics and implementing various machine learning algorithms using PySpark MLlib
  ├── sample-data\
  │     - Sample datasets used throughout the course
  ├── README.md
  ├── requirements.txt
  └── setup.sh
```

## How to Use This Repository
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/aditya-barik/learning-PySpark
    ```

2. Open the terminal and navigate to the cloned repository:
    ```bash
    cd <YOUR_PATH>/learning-PySpark
    ```

3. Create a virtual environment in the working directory:
    ```bash
    python -m venv env
    ```

4. Activate the virtual environment:
    - For Windows (Git Bash):
        ```bash
        source env/Scripts/activate
        ```
    - For Linux/MacOS:
        ```bash
        source env/bin/activate
        ```

5. Set up the virtual environment by running the setup script:
    ```bash
    . setup.sh
    ```

6. You are now ready to run any Jupyter notebook using this virtual environment.
