# Sentiment Analysis of Amazon Product Reviews

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to analyze sentiment from Amazon product reviews using natural language processing techniques. By examining the sentiments expressed in user reviews, we can gain insights into customer satisfaction and product performance. The goal is to classify reviews into positive, negative, and neutral sentiments based on the text content.

## Dataset

The dataset consists of 5000 Amazon product reviews with the following fields:

- **Id**: Unique identifier for the review.
- **ProductId**: Identifier for the product.
- **UserId**: Identifier for the user.
- **ProfileName**: Name of the user.
- **HelpfulnessNumerator**: Number of users who found the review helpful.
- **HelpfulnessDenominator**: Total number of users who rated the helpfulness of the review.
- **Score**: Rating given by the user (1-5).
- **Time**: Timestamp of the review.
- **Summary**: Summary of the review.
- **Text**: Full text of the review.

## Requirements

To run this project, ensure you have the following libraries installed:

- Python 3.x
- pandas
- matplotlib
- seaborn
- nltk

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn nltk
