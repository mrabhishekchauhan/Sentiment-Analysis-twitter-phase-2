# Sentiment-Analysis-twitter-phase-2
Making use of n-gram features to achieve Sentiment Analysis on twitter using  Maximum Entropy classifier, Decision tree and Naïve Bayes. The aim is to model and track the public sentiment on twitter based on the domain of Annual Budget-2018


Usage
Preprocessing

    Run preprocess.py <raw-csv-path> on both train and test data. This will generate a preprocessed version of the dataset.
    Run stats.py <preprocessed-csv-path> where <preprocessed-csv-path> is the path of csv generated from preprocess.py. This gives general statistical information about the dataset and will two pickle files which are the frequency distribution of unigrams and bigrams in the training dataset.

After the above steps, you should have four files in total: <preprocessed-train-csv>, <preprocessed-test-csv>, <freqdist>, and <freqdist-bi> which are preprocessed train dataset, preprocessed test dataset, frequency distribution of unigrams and frequency distribution of bigrams respectively.

For all the methods that follow, change the values of TRAIN_PROCESSED_FILE, TEST_PROCESSED_FILE, FREQ_DIST_FILE, and BI_FREQ_DIST_FILE to your own paths in the respective files. Wherever applicable, values of USE_BIGRAMS and FEAT_TYPE can be changed to obtain results using different types of features as described in report.
