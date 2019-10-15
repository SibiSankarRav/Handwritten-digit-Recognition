# Handwritten-digit-Recognition

Automated Handwritten digit recognition is widelzy used today - from recognizing zip codes on mail envelopes to recognizing amounts written on bank checks.  This Logistic Regression and Neural Network model will be used for the classfication of the handwritten digits.  The model is trained with 5000 training Examples.  The training sample is 20 * 20 pixel grayscale image of the digit.  Each pixel is represented by a floating point number indicating the grayscale intensity at that location.  The 20*20 grid of pixels is unrolled into a 400 dimensional vector, thus 5000*40 matrix.

The classifier is based on the one vs all classification.  Since there are 10 different digits.  There are 10 different classifiers for each digit.

In Neural Network model, the feed forward propagation algorithm is used to use our weights for prediction.  NN is a simple 3 layer model.
