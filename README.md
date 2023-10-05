# Stack Overflow Question Quality Prediction

![title](indiv-proj-imgs/stack-overflow-logo.png)

Stack Overflow, the renowned question and answer platform for programmers, is an essential resource in the software development world. However, the platform's effectiveness relies on the quality of questions posted by users. In this project, we tackle the challenge of predicting the quality of Stack Overflow questions to enhance the user experience and facilitate efficient knowledge sharing.

## Problem Overview

The problem at hand is to identify which questions are likely to attract community engagement and productivity. With millions of questions on the platform, locating valuable information can be challenging. Users often encounter poorly structured, ambiguous, or duplicate questions that hinder their search for answers. The goal is to leverage advanced natural language processing techniques, specifically the BERT model, to predict question quality accurately.

## Dataset

We utilize a comprehensive dataset from [Kaggle](https://www.kaggle.com/datasets/imoore/60k-stack-overflow-questions-with-quality-rate) containing 60,000 questions from Stack Overflow, spanning the years 2016 to 2020. These questions are categorized into three distinct quality classes, providing a rich dataset for training and evaluation.

## Key Highlights and Recommendations

Our approach, utilizing the BERT model, achieved a test accuracy of 91.18%. This demonstrates the effectiveness of natural language processing techniques in assessing question quality. Future work involves incorporating deep learning explainability methods to gain insights into the model's decision-making process.

By continuously refining the model and addressing data challenges, we aim to contribute to the improvement of the Stack Overflow community. Our goal is to provide a valuable resource for developers seeking high-quality answers to their programming questions.

## Installation Guide

To set up this project in your environment, you can use the provided `requirements.txt` file. Run the following command to install the necessary packages:

```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.