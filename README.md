
# Amazon Sentiment Analysis

## Project Summary

This project uses **Natural Language Processing (NLP)** to analyze customer sentiment from Amazon product reviews. By applying **VADER** and **RoBERTa** models, the analysis identifies key trends in customer satisfaction and uncovers actionable insights. The results help businesses understand customer perspectives, allowing for strategic decision-making to improve product offerings, customer service, and overall user experience.

![Amazon Poster Image](https://github.com/robingodinho/Amazon_Machine_Learning/blob/3fb754fa7e1075875be3c62ab719af22cc5413d0/amazon_img.png)
## Table of Contents

1. [Project Summary](#project-summary)
2. [Business Problem](#business-problem)
3. [Solution Approach](#solution-approach)
4. [Project Features](#project-features)
5. [Technical Overview](#technical-overview)
6. [Results & Insights](#results--insights)
7. [Applications & Potential Impact](#applications--potential-impact)
8. [How to Run the Analysis](#how-to-run-the-analysis)
9. [Future Enhancements](#future-enhancements)
10. [Get Involved](#get-involved)
11. [License](#license)

## Business Problem

As e-commerce continues to grow, **understanding customer sentiment is critical** for businesses looking to maintain a competitive edge. Analyzing reviews provides insight into customer satisfaction, product issues, and emerging trends. However, manual review analysis is costly and time-consuming. This project addresses the need for **automated sentiment analysis** to help businesses efficiently interpret vast amounts of customer feedback, enabling them to make data-driven decisions.

## Solution Approach

Using **two advanced NLP techniques**—**VADER** and **RoBERTa**—this project provides a robust solution for sentiment classification. Each technique offers unique advantages:

- **VADER** provides a quick and interpretable approach for analyzing sentiment with high accuracy for general and social media contexts.
- **RoBERTa**, a transformer-based model, is fine-tuned on the Amazon review data, offering a more nuanced understanding of sentiment with high accuracy.

## Project Features

- **Data Preprocessing**: Cleans and prepares raw review data for analysis.
- **Sentiment Analysis**: Applies both VADER and RoBERTa models for sentiment classification.
- **Performance Comparison**: Evaluates both models, highlighting accuracy, precision, and recall to help identify the best solution for various business needs.
- **Visualization & Reporting**: Provides visual summaries and actionable insights for business stakeholders.

## Technical Overview

- **Programming Language**: Python
- **Core Libraries**: pandas, numpy, nltk, transformers, matplotlib, scikit-learn
- **Data Source**: Amazon Product Reviews dataset
- **Models Used**: VADER (rule-based), RoBERTa (deep learning)

The project is organized as follows:

```
amazon-sentiment-analysis/
│
├── data/                        # Raw and processed data files
├── notebooks/                   # Jupyter notebooks for analysis
├── scripts/                     # Python scripts for preprocessing & model analysis
├── models/                      # Saved models
├── results/                     # Output metrics & visualizations
├── README.md                    # Project documentation
└── requirements.txt             # Project dependencies
```

## Results & Insights

The analysis provides the following business insights:
- **Customer Sentiment Overview**: The breakdown of positive, neutral, and negative sentiments helps gauge overall customer satisfaction.
- **Key Drivers of Negative Sentiment**: By identifying common words and themes in negative reviews, businesses can pinpoint specific areas for improvement.
- **Comparison of Model Performance**: The results illustrate the strengths of each approach, with VADER providing fast insights and RoBERTa offering greater detail and accuracy.
![Vader and Roberta Models](https://github.com/robingodinho/Amazon_Machine_Learning/blob/3fb754fa7e1075875be3c62ab719af22cc5413d0/Vader_Roberta_analysis.png)

![Sentiment graphs](https://github.com/robingodinho/Amazon_Machine_Learning/blob/3fb754fa7e1075875be3c62ab719af22cc5413d0/graphs.png)

## Applications & Potential Impact

The insights derived from this project can benefit various business departments:

- **Product Development**: Understand customer pain points and prioritize product improvements.
- **Customer Service**: Detect and respond to recurring issues in customer feedback, improving customer satisfaction.
- **Marketing & Sales**: Analyze sentiment trends over time to measure the impact of marketing campaigns or product launches.

## How to Run the Analysis

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/amazon-sentiment-analysis.git
   cd amazon-sentiment-analysis
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Data Preprocessing**
   ```bash
   python scripts/data_preprocessing.py
   ```

4. **Run Sentiment Analysis**
   - For VADER:
     ```bash
     python scripts/vader_sentiment.py
     ```
   - For RoBERTa:
     ```bash
     python scripts/roberta_sentiment.py
     ```

## Future Enhancements

To further enhance the project, the following developments are planned:

- **Integration of Additional Models**: Experiment with models such as DistilBERT for optimized performance.
- **Real-Time Analysis**: Implement a real-time sentiment dashboard for immediate insights.
- **Topic Modeling**: Enhance sentiment analysis by identifying specific topics discussed within positive and negative reviews.

## Get Involved

Your contributions are welcome! If you have suggestions for improvement or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
