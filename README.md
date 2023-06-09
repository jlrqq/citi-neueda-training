# citi-neueda-training
This repository contains the codebase for Team 50's project as part of the Neueda Training in Citi (APAC).

## A. Motivation
Loan default poses a significant business risk, especially for banks who provide various loans to various clients across multiple financial backgrounds. When borrowers fail to repay their loans, it adversely impacts the bank's profitability and hence stability, since these defaults lead to financial losses, reduced liquidity, and hampered capital adequacy.

Even the world's leading banks such as Citi are not excluded from such risks. In 2020, the coronavirus pandemic had a large impact on the economy, virtually halting economic activity and causing a flood of expected defaults on loans, plunging profits for the bank which had to prepare countermeasures to steer itself through rough tides. 

Hence, it is crucial for banks must employ rigorous risk management strategies to mitigate default risks, and ensure the sustainability of their operations.

This project aims to supplement such risk management using technology in the form of data analytics and machine learning; we aim to identify the important factors in determining whether a loan will be defaulted on. By getting a better idea of how to determine a loan's probability of being defaulted on, the bank can take preemptive measures or precautions and be well prepared for defaults.

## B. Hypothesis
The probability of a loan being defaulted depends on various factors such as the applicant's income, credit score, loan amount, rate of interest and more.

## C. Dataset
To work on the hypothesis, the team is using the [Loan Default Dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset) from Kaggle. This dataset was chosen for its multitude of features for each loan being tracked, its high usability score (10/10), as well as it being relatively recent at the time this project was developed (2019).

## D. Setting Up
For best practices, we will use a virtual environment to contain any dependencies for the project.

This section assumes that you have:

- A working version of Python (^3.7, versions after 3.4 will come with the pip package manager installed)

### 1. Create the virtual environment (we will name it "env") 
From the project's root directory:
```shell
python -m venv env
```

### 2. Start the virtual environment
Windows:
```shell
env\Scripts\Activate
```

Linux/MacOS:
```bash
source env/bin/activate
```

### 3. Download the dependencies using the requirements text file
```shell
pip install -r requirements.txt
```

> Once done, the jupyter notebook can be configured to point to this virtual environment so all the dependencies are isolated nicely. Otherwise, you can always use your default python environment if you prefer that 👍