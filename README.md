# ml_play
features are from https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification
train SVM using the 30s features; 1000 songs, 10 genres, 90% train, 10% test
should probably keep some for cv but I'm not really trying several algorithms or optimising one just setting up something quick

extract features using https://librosa.org/doc/latest/generated/librosa.feature.mfcc.html#librosa.feature.mfcc
20 Mel freq central coeffs; mean over time
