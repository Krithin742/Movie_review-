Source: IMDB Movie Reviews dataset (IMDB Dataset.csv)

Columns:

review: Text of the movie review

sentiment: Label indicating positive or negative
Technologies Used

Python 3.x

Libraries:

pandas – data manipulation

numpy – numerical operations

sklearn – vectorization & ML algorithms

nltk – text preprocessing

matplotlib / seaborn – visualization (if applicable)

Model Pipeline

Data Loading: Load and inspect the IMDB dataset.

Data Cleaning: Handle missing values, lowercase text, and remove HTML tags or punctuation.

Text Preprocessing:

Tokenization

Stopword removal

Lemmatization or stemming (optional)

Feature Extraction:

CountVectorizer or TfidfVectorizer

Model Training:

MultinomialNB or LogisticRegression

Evaluation:Accuracy, confusion matrix, and classification report

