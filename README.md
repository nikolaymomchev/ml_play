# ml_play
Features are from https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification. First train SVM using the 30 seconds features csv; 1000 songs, 10 genres, 90% are used for training, 10% test

I should probably keep some for cv but I'm not really trying several algorithms or optimising one. This is just setting up something quick.


Extract features using https://librosa.org/doc/latest/generated/librosa.feature.mfcc.html#librosa.feature.mfcc. 
20 Mel freq central coeffs taken as the mean over time. This is essentially a subset of the original features. The 20 mfcc are stored into csv.
