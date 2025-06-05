# 🧠 Behavior, Difficulty & Grading: What Drives Retention on Lernnavi?

This repository contains the code, data processing scripts

## 📘 Overview

Learner dropout remains a central challenge in online education platforms. This project analyzes user engagement on **Lernnavi**, a curriculum-aligned learning platform used in Swiss secondary schools, to understand what factors most influence student retention.

We investigate:

1. **Behavioral Profiles** — How do user activity patterns affect next-week engagement?  
2. **Perceived Difficulty** — Can task complexity predict dropout?  
3. **Grading Bias** — Are open-ended responses evaluated fairly?

## 🧰 Methodology

- **Behavior Profiling**: Aggregated event logs into weekly features, grouped into six dimensions of self-regulated learning.  
- **Engagement Prediction**: Time-aware classification using tree-based models and LSTM.  
- **Difficulty Modeling**: Constructed difficulty features from user response time and task correctness.  
- **Bias Detection**: Compared grading outcomes with semantic similarity-based oracle labels using multilingual SBERT.

## 🧪 Key Findings

- **Effort and regularity** dominate engagement prediction.  
- **Difficulty features alone** are weak predictors of dropout.  
- **Misalignments** in grading open-input questions suggest areas for improvement in evaluation consistency.

## 📂 Project Structure

<pre lang="markdown"><code> ``` ├── data/ # Raw and processed Lernnavi data ├── figures/ # Plots used in the final report ├── models/ # Trained models and clustering artifacts ├── src/ # Scripts for feature engineering, training, and evaluation ├── paper/ # LaTeX source code for the report │ └── lernnavi_report.tex ├── requirements.txt # Python dependencies └── README.md # Project documentation ``` </code></pre>

## 👩‍🔬 Authors
 Valentine Casalta
 Omar Boudarka
 Nino Gerber
