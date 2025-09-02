# Naive-Bayes-Classification-on-Iris-Data
Using Gaussian Naive Bayes Classification to predict class types of iris flower

## Approach:
-   Given the Iris dataset’s small size and the roughly Gaussian behavior of its features within each class, Gaussian Naïve Bayes is a natural fit for predicting species from sepal/petal measurements.
-   Naïve Bayes offers a fast, interpretable baseline when feature likelihoods can be modeled parametrically (e.g., Gaussian), requiring only per-class means/variances and a prior—well-suited to this dataset.

## Findings:
-   The custom Naïve Bayes implementation matched scikit-learn’s GaussianNB on the same split (posterior probabilities and predicted labels).
-   On the test set, the classifier achieved ~93% accuracy with only two off-diagonal entries in the confusion matrix. While the dataset is small (150 samples), these results indicate Gaussian Naïve Bayes performs very well for this task.
