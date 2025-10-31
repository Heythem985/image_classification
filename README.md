# Weather Image Classifier

This project is a Weather Image Classifier that automatically predicts the weather condition displayed in an image. The dataset is divided into training and evaluation sets, each containing images from four categories: shine, sunrise, rain, and cloudy.

To extract meaningful image features, I used PyTorch with img2vec to convert each image into a vector representation. These feature vectors were then used to train a Random Forest Classifier built with Scikit-learn.

The model achieved an accuracy score of 0.94, demonstrating strong performance on the evaluation dataset.
Finally, the trained model was saved using Pickle, allowing it to be easily loaded and used directly for predictions without retraining.

 ## Technologies Used

PyTorch – for image feature extraction using img2vec

Scikit-learn (sklearn) – for model training, evaluation, and performance metrics

Pickle – for model serialization and reuse
