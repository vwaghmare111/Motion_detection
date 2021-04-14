# Motion_detection
Three different manufacturing activities were performed during the experiement mentioned in Project 1 and 2. Using same data, I have classified three activities with 95% accuracy on test data.

Feature engineering:
1) Integrate original timeseries.
2) Low pass filtered Fourier transformation.
3) Downsampled both the features from step 1 and 2 using simple mean at 1 min epoch

Pipeline including pre-processing:
1) Random Over Sampler.
3) Robust Scaler.
4) Although LinearSVC, SVM Classifier, Logistic Regression all performed at par, however, winner was Linear Discriminant Analysis model.
