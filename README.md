# Behavior, Difficulty & Grading: What Drives Retention on Lernnavi?

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repository contains the code, data processing scripts

## Overview

Learner dropout remains a central challenge in online education platforms. This project analyzes user engagement on **Lernnavi**, a curriculum-aligned learning platform used in Swiss secondary schools, to understand what factors most influence student retention.

We investigate:

1. **Behavioral Profiles** — How do user activity patterns affect next-week engagement?  
2. **Perceived Difficulty** — Can task complexity predict dropout?  
3. **Grading Bias** — Are open-ended responses evaluated fairly?

## Methodology

- **Behavior Profiling**: Aggregated event logs into weekly features, grouped into six dimensions of self-regulated learning.  
- **Engagement Prediction**: Time-aware classification using tree-based models and LSTM.  
- **Difficulty Modeling**: Constructed difficulty features from user response time and task correctness.  
- **Bias Detection**: Compared grading outcomes with semantic similarity-based oracle labels using multilingual SBERT.

## Key Findings

- **Effort and regularity** dominate engagement prediction.  
- **Difficulty features alone** are weak predictors of dropout.  
- **Misalignments** in grading open-input questions suggest areas for improvement in evaluation consistency.

## Project Structure

```
├── m2/                   # Milestone 2: Individual exploratory analysis
├── m4/                   # Milestone 4: RQ1 results and code
├── m7/                   # Milestone 6: Final models, evaluation, and report
├── .gitignore            # Git configuration to exclude unnecessary files
└── README.md             # Project documentation
```


## Authors

 Valentine Casalta, 
 Omar Boudarka, 
 Nino Gerber

## License
 
MIT License

Copyright (c) 2025 Valentine Casalta, Omar Boudarka, Nino Gerber

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
