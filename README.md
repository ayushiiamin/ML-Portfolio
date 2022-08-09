# ML-Portfolio

This portfolio comprises of work on the FER-2013 dataset demonstrating it's results on various ML algorithms

<br />
The link to the Kaggle dataset: https://www.kaggle.com/ananthu017/emotion-detection-fer

### Pre-processing the images:

* Converted the raw BGR images to Grayscale.
* Performed Normalization and Thresholding.
* To reduce the run-time and usage of memory, flattened the images.

## 1 - Naïve Bayes Classifier:

* Chose the **BernoulliNB** model offered by Scikit-Learn.
* Computed the Precision, Recall, TP Rate, and FP Rate for each of the emotions (*Angry, Disgusted, Fearful, Happy, Neutral, Sad, and Surprised*) separately.
* Generated the top 10 correlations for each of the emotions separately and computed the Precision, Recall, TP Rate, and FP Rate for each emotion.

**Built With:** Python, OpenCV, Anaconda, NumPy, Scikit-Learn, Matplotlib, Pandas, TensorFlow, Keras
