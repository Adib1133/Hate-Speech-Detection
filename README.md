Hate Speech Detection, A machine learning project that detects hate speech and offensive language in social media content using various classification algorithms.

Overview:
This project implements an automated system for detecting hate speech and offensive language in social media posts, specifically targeting content from platforms like X (formerly Twitter). The system uses multiple machine learning classifiers to categorize text into three categories:
  1. Hate speech
  2. Offensive language
  3. Neither

Motivation:
The proliferation of harmful content on social media platforms has made automated content moderation tools increasingly important. This project aims to:
  1. Promote online safety and well-being
  2. Protect vulnerable communities
  3. Support content moderation efforts
  4. Contribute to ethical AI development
  5. Advance research in automated content detection

Dataset:
The project uses the dataset from Davidson et al.'s paper on "Automated Hate Speech Detection and the Problem of Offensive Language." The dataset has been collected from the kaggle.com. The dataset contains:
  1. Total samples: 24,802 posts
  2. Hate speech: 3,972 samples
  3. Offensive language: 20,298 samples
  4. Neither: 432 samples
For this implementation, we used 5,000 rows from the original dataset.

Preprocessing:
The following preprocessing techniques were applied to clean and prepare the data:
  1. Removal of punctuation
  2. Text lowercasing
  4. Tokenization
  5. Removal of stop words
  6. Lemmatization

Models Implemented:
We experimented with three different classification algorithms:

  1. Logistic Regression
  2. Naive Bayes Classifier
  3.K-Nearest Neighbors (KNN)

After thorough testing and comparison:
  • Logistic Regression achieved the highest accuracy at approximately 96%
  • Naive Bayes and KNN performed similarly with accuracies around 89-90%
  • Detailed confusion matrices are available in the implementation

Future Work:
  • Implementation of sarcasm and irony detection
  • Real-time monitoring and feedback system
  • Enhanced model interpretability
  • Integration with social media platforms
  • Privacy-focused deployment considerations

Davidson, T., Warmsley, D., Macy, M., & Weber, I. (2017). Automated Hate Speech Detection and the Problem of Offensive Language. https://arxiv.org/abs/1703.04009
Dataset available at: https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset
