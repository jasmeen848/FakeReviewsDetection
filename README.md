# FakeReviewsDetection

Fake reviews seem to be everywhere these days, leaving customers unsure over which products or businesses are actually any good. Whether you’re shopping on Amazon, checking out a restaurant on Tripadvisor, or reading about a potential employer on Glassdoor, there’s always a risk that the reviews you’re reading are fake.

Fake review detection models - 
  1. Models that use solely text-based features, such as the content of the review.
  2. Models that use solely non-text features, such as reading ease, review scores, and the number of prior reviews.
  3. Models that use a combination of text-based and non-text based features.
  
 To build a fake review detection model solely based on the review text itself, and will be focusing on detecting the presence of fake reviews generated with GPT-2 in a dataset that contains both GPT-2 computer-generated reviews and human generated reviews.
 
 Packages used-
  NLTK packages for preprocessing our text data, 
  the TfidfVectorizer from scikit-learn to prepare our data using the TF-IDF algorithm, 
  plus a range of different classification algorithms, including XGBoost, LightGBM, CatBoost, and various scikit-learn implementations, such as Multinomial Naive Bayes, Decision Trees, Random Forests, and various others.
