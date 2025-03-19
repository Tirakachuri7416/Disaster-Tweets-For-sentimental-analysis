Disaster Tweets Classification
Overview
This project focuses on classifying tweets into disaster-related and non-disaster-related categories using Natural Language Processing (NLP) techniques and machine learning models. The dataset consists of tweets labeled as either disaster (1) or not disaster (0).
Dataset

The dataset contains the following columns:
id: Unique identifier for each tweet.
text: The tweet content.
target: Label (1 for disaster, 0 for non-disaster).

Project Workflow

Data Preprocessing
Handling missing values.
Text cleaning (removing special characters, stopwords, and URLs).
Tokenization, stemming, and lemmatization.
Converting text to numerical form using TF-IDF vectorization.

Model Training
Multinomial Naïve Bayes
Logistic Regression
K-Nearest Neighbors (KNN)

Model Evaluation
Generating confusion matrices and classification reports.
Performing cross-validation.
Selecting the best-performing model based on accuracy and recall.

Results

Model                                      Accuracy
Multinomial Naïve Bayes                     80.70%
Logistic Regression                         80.00%
K-Nearest Neighbors (KNN)                   66.00%

Best Performing Model: Multinomial Naïve Bayes with 80.70% accuracy.

Future Improvements
Experiment with Word2Vec or BERT embeddings for feature extraction.
Perform hyperparameter tuning for improved accuracy.
Apply ensemble learning techniques to enhance model performance.

Installation & Usage

Prerequisites
Make sure you have Python installed along with the required libraries:
pip install numpy pandas scikit-learn nltk

Running the Project
Clone the repository:
git clone https://github.com/your-username/disaster-tweets-classification.git

Navigate to the project directory:
cd disaster-tweets-classification

Run the main script:
python main.py

Contributing
Feel free to contribute by opening an issue or submitting a pull request!

License
This project is licensed under the MIT License.

Contact
For any questions, reach out via [tvnnavyasree123@gmail.com] or open an issue on GitHub.
