# Hotel Booking Cancellation Prediction

This project develops a deep neural network model to predict hotel booking cancellations for ABC Hotels with 83.6% accuracy. Using booking data with features like lead time, room type, and guest history, we engineered additional variables including booking value and arrival components. After extensive prototyping, we implemented two multilayer perceptron models with batch normalization and dropout layers to prevent overfitting. The selected model outperformed on all metrics (accuracy, precision, recall, and F1 score) while demonstrating better ROC curve performance. The model tends to be slightly under-confident in predicting cancellations, suggesting it would lead to fewer double bookings but potentially more under-booked properties. Recommendations include implementing robust performance monitoring systems and exploring more advanced architectures in future iterations.

# Setup Instructions

This project uses `R`'s `keras3` package with tensorflow backend. [To install this backend, run](https://keras.posit.co/articles/getting_started.html) - run the following line once

> keras3::install_keras(backend = "tensorflow")

This was sufficient to run in a cloud virtual Linux machine but there may be installation issues on other operating systems (e.g. Windows).
