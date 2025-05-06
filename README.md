🧠 Deepfake Detection Using CNN and Hybrid Models
This repository presents a comprehensive approach to detecting real vs. fake facial images using both deep learning and hybrid machine learning models. Leveraging StyleGAN-generated images, we explore how feature extraction via pretrained CNNs (Xception & DenseNet121) can be effectively combined with traditional classifiers (SVM and Naïve Bayes) for robust deepfake detection.

📊 Project Highlights
Dataset: 140,000 images (70k real from Flickr + 70k fake from StyleGAN)

CNN Models: Xception & DenseNet121 with transfer learning

Hybrid Models: CNN-based feature extraction + SVM / Bernoulli Naïve Bayes

Optimization: Grid Search, EarlyStopping, ModelCheckpoint, ReduceLROnPlateau

Performance:

DenseNet121: 99.33% accuracy, 0.997 AUC

DenseNet-SVM: 99.03% accuracy, high efficiency

Xception-SVM & NB models also performed competitively
