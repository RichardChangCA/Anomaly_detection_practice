# Anomaly_detection_practice

<h3>Useful study resouces</h3>

1. Medium, Credit Card Fraud Detection using Autoencoders in Keras: https://medium.com/@curiousily/credit-card-fraud-detection-using-autoencoders-in-keras-tensorflow-for-hackers-part-vii-20e0c85301bd

autoencoder is an unsupervised learning method, threshold to determine whether a data point is anomaly or not is an important hyper-parameter to tune, and you can use labeled data in testing step to find the best threshold in your dataset. for numerical dataset, you only need fully connected layers in the autoencoder structures(like multi-layer perceptron(MLP)), without convolutional neural network(CNN) or recurrent neural network(RNN) knowledge.

2. Medium, Anomaly Detection with Autoencoders Made Easy: https://towardsdatascience.com/anomaly-detection-with-autoencoder-b4cdce4866a6

Autoencoder can do dimensionality reduction, which is better than PCA. Antoencoder can find the main pattern of the majority class, which can reveal outliers. Interestingly, during the process of dimensionality reduction, outliers are identified. We can say outlier detection is a by-product of dimension reduction. PCA is a linear-transoformation dimentionality reduction and autoencoder is a non-linear-transfomation dimentionality reduction. In addition, there are several hyper-links inside of this article(why anomaly detection, feature enginnering in anomaly detection, etc.). PyOD is a Pyhton package for anomly detection. the outlier is a data point that generated new input is distant from other data points. You can also use ensemble learning to combine many outlier detection models together to predict outliers, to avoid overfitting.

3. Medium, Fraud Detection Under Extreme Class Imbalance: https://towardsdatascience.com/fraud-detection-under-extreme-class-imbalance-c241854e60c

4. Medium, Fraud detection: the problem, solutions and tools: https://towardsdatascience.com/fraud-detection-the-problem-solutions-and-tools-dd8977b435c9

- Statistical techniques: average, quantiles, probability distribution, association rules

- Supervised ML algorithms: logistic regression, neural net, time-series analysis

- Unsupervised ML algorithms: Cluster analysis, Bayesian network, Peer group analysis, break point analysis, Benford’s law (law of anomalous numbers)
