# imdb-sentiment-analysis-and-genre-
part of a capstone project
. would be providing gdrive link for dataset soon


## Project Approach

Phase 1 Cleaning (Score 30 + 10 Extra credits):

Each student must solve

    Read the labelled data from respective folders (pos & neg) and store in data-frames (eg: train_df & test_df) with suitable structure

            Hint: columns = [review, label]

    Remove stop words from the data
    Removing punctuations, HTML tags (like br) etc.
    Apply Stemming and Lemmatization

 Extra Credits

    Apply feature selection to select most important words/features and drop others (Bonus)

Phase 2 Exploration (Score 30 + 20 Extra credits):

Each student must solve

    For labelled data, find the most common words associated with each category (positive & negative)
    Discover the lowest frequency and highest frequency words

 Extra Credits

    Read unlabeled data from respective folder (unsup) and store in unsup_df
    Create a cluster to separate positive and negative words (bonus) using k-means algorithm

 Phase 3 Visualization (Score 30 + 10 Extra credits):

Each student must solve

    Create a word cloud with positive and negative words after cleansing
    Visualise the positive and negative words distribution (Hint: Histogram)

 Extra Credits

    Repeat visualization step 1 & 2 after feature selection and note the impact (Bonus)

 Phase 4 Hypothesis testing  and Feature Selection (Score 10):

Each student must solve

    Create Hypothesis involving relationships between dependent and independent variables using parametric/non-parametric tests for various machine learning algorithms such as k-means clustering,  classification algorithms.

 Phase 5 Model Building (Score 80 + 180 Extra credits):

 Each student must solve

    Supervised Learning: Build a sentiment analysis model to predict positive and negative classes (Score 40)
    Unsupervised Learning: Build a clustering model consisting of 2 clusters based on positive and negative reviews (Score 40)

 Extra Credits

    Supervised Learning: Compare the performance of different machine learning models, at least 2 (Score 40)
    Unsupervised Learning: Compare the performance of different models, at least 2 (Score 40)
    Divide the data into 4 clusters to enable finding more classes. Analyse each cluster and try to find the correct label for the new cluster. Repeat clustering until 4 new labels can be found, other than the original labels (positive and negative) (Score 50)
    Active Learning: Cluster the training dataset and try and find the genre. Manually annotate the cluster and then try to find the labels in the new testing dataset. (Score 50)
