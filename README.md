# Twitter Sentiment Analysis

## Overview
This project focuses on the analysis of sentiments expressed in tweets. Utilizing advanced machine learning techniques, it categorizes tweets as either positive or negative. This analysis provides valuable insights into public opinion and sentiment on various topics.

## Objective
The primary goal of this project is to accurately determine the sentiment of a tweet. This can be applied in numerous domains such as marketing, political campaigns, public relations, and customer service to understand and respond to public sentiment effectively.

## Dataset
The analysis is based on the Sentiment140 dataset, which contains 1,600,000 tweets extracted using the Twitter API. Each tweet in the dataset is labeled as either positive or negative.

## Methodology
1. **Data Preprocessing:** The dataset underwent a series of preprocessing steps including text normalization, removing URLs, emojis, and non-alphabetic characters, and tokenization.
2. **Feature Extraction:** We used TF-IDF Vectorization to convert the preprocessed tweets into a format suitable for model training.
3. **Model Training and Evaluation:** Several machine learning models were trained and compared, including Bernoulli Naive Bayes, Linear Support Vector Classification, and Logistic Regression. The models were evaluated based on their accuracy, with a particular focus on understanding the trade-offs between model complexity and performance.

## Key Findings
- Logistic Regression provided the best balance between accuracy and computational efficiency.
- The project highlights the importance of comprehensive data preprocessing in NLP tasks.
- The analysis revealed common patterns and themes in sentiment expression on Twitter.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Matplotlib, Seaborn

## How to Run the Project
1. Clone the repository to your local machine.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Run the "twitter-sentiment-analysis.ipynb " Jupyter notebook. 

## Contributing
Feel free to fork this project, submit pull requests, or send us your feedback and suggestions!

## License
[MIT License](LICENSE)

## Contact Information
For any additional questions or comments, please contact me at [scobos.append@gmail.com].
