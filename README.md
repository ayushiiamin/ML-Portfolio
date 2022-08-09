# ML-Portfolio

This portfolio comprises of work on the FER-2013 dataset demonstrating it's results on various ML algorithms

<br />
The link to the Kaggle dataset: https://www.kaggle.com/ananthu017/emotion-detection-fer

### Emotions present in the FER-2013 image dataset:

* Angry
* Disgusted 
* Fearful 
* Happy 
* Neutral
* Sad
* Surprised

### Metrics Computed for each Emotion and ML Algorithm:

* Precision
* Recall
* F-1 Score
* Accuracy
* True Positive (TP) value
* False Positive (FP) value
* True Negative (TN) value
* False Negative (FN) value
* TP rate and FP rate

### Pre-processing the images:

* Converted the raw BGR images to Grayscale.
* Performed Normalization and Thresholding.
* To reduce the run-time and usage of memory, flattened the images.

## 1 - Naïve Bayes Classifier:

* Chose the **BernoulliNB** model offered by Scikit-Learn. Computed the above mentioned metrics for each emotion separately.
* Generated the top 3, 5, and 10 correlations for each of the emotions separately and computed the necessary metrics.
* Performed **PCA Dimensionality Reduction** on the image dataset.

## 2 - K - Means Clustering:

**Built With:** Python, OpenCV, Anaconda, NumPy, Scikit-Learn, Matplotlib, Pandas, TensorFlow, Keras
