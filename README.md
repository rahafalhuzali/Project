# Disaster Tweets Classification

This project focuses on classifying tweets as real disaster tweets or not using Natural Language Processing (NLP) techniques. It uses a dataset from Kaggle's **"Real or Not? NLP with Disaster Tweets"** competition.

![Project Status](https://img.shields.io/badge/Status-In%20Progress-yellow.svg)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Code Walkthrough](#code-walkthrough)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

---

## Overview

The goal of this project is to classify tweets into two categories:
- **Disaster Tweets (target = 1)**: Tweets related to real disasters.
- **Non-Disaster Tweets (target = 0)**: Tweets unrelated to disasters.

Key highlights of this project:
- Utilizes `ydata-profiling` for Exploratory Data Analysis (EDA).
- Prepares datasets for future NLP model training.
- Provides a framework for understanding the dataset and feature engineering.

---

## Dataset

The dataset is sourced from Kaggle's competition: **[Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)**.

### Files:
- **Train Dataset**: `/kaggle/input/nlp-getting-started/train.csv`
- **Test Dataset**: `/kaggle/input/nlp-getting-started/test.csv`

### Features:
1. `id`: Unique identifier for each tweet.
2. `keyword`: A keyword from the tweet (if available).
3. `location`: The location the tweet was sent from (if available).
4. `text`: The actual tweet content.
5. `target`: Target variable (1 if the tweet is about a real disaster, 0 otherwise — only in the training set).

---

## Installation

### Prerequisites

- Python 3.10+
- Jupyter Notebook
- Kaggle API for downloading datasets (if required).

### Steps:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
