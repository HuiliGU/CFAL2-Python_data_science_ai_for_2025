### CFAL2 PSM - Python, datascience and ai for 2025

This repository contains python programming fundamentals, machine learning/deep learning applications with real-world financial dataset and natural language processing in market sentiment analysis.

After going through the following four jupyter notebooks, you will be skilled with **pandas, sklearn, pytorch** and be familiar with **linear regression, random forest, XGBoost, ANN, RNN and LSTM**.

- Unit 1: Python Programming Fundamentals Review
- Unit 2: Data Collection, Wrangling and Feature Engineering In Machine Learning
- Unit 3: Financial Forecasting Using Machine and Deep Learning
- Unit 4: Natural Language Processing (NLP) In Python

#### Git commands for reference
**1. Clone a Remote Repository**
```bash
git clone <remote-repo-url>
cd <repo-folder>
```
**2. Check Local and Remote Branches**
```bash
# Local branches
git branch 
# Remote branches
git branch -r
# Local + Remote branches
git branch -a
```
**3. Create a Local Branch Tracking a Remote Branch**
```bash
git checkout -b feature origin/feature
# Pull the latest changes from the remote branch to your local branch. 
git pull
```
**4. Development: Add / Modify Files**
```bash
# Check changes
git status
# Stage files for commit
git add <file1> <file2>
# Or stage all changes
git add .
# Commit changes
git commit -m "Describe your changes"
```
**5. Push Changes to Remote Branch**
```bash
git push origin feature
# For the first push, set upstream:
git push -u origin feature
# After setting upstream, you can simply use git push in the future.
```
**6. Create Additional Branches (e.g., release)**
```bash
git checkout -b release
# Creates a new local branch release and pushes it to remote.
git push -u origin release
```
**7. Delete Branches**
```bash
# Delete local branch
git branch -d feature
# Force delete if not merged
git branch -D feature   
# Delete remote branch
git push origin --delete feature
```





