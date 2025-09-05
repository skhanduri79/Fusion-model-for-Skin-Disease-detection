This project aims to mimic clinical analysis for skin disease detection using pre trained models of CNN and autoencoders. 
we have image dataset and csv file with patient meta data. 

Goal:
1. Combine image data and clinical features using multi-modal learning.
2. Investigate autoencoders as an alternative to CNNs for image feature extraction.
3. Evaluate performance improvements with data fusion

Conclusion:

Three modeling strategies compared:
1. Pretrained CNNs + Metadata: Strong performance, especially MobileNet (F1: 0.76)
2. Fine-tuned CNNs + Metadata: Underperformed due to overfitting on limited data
3. Autoencoder + Metadata Fusion: Achieved best F1-score (0.77), balanced results across classes
