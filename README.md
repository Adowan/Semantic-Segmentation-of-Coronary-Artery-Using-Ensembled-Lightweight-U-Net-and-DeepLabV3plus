# Semantic-Segmentation-of-Coronary-Artery-Using-Ensembled-Lightweight-U-Net-and-DeepLabV3-
During the past decade, coronary heart disease has emerged as a significant health concern, and  various types of coronary artery diseases have been identified. To accurately assess the severity of  these diseases, researchers have turned to deep learning models for reliable segmentation of  important blood vessels. 
# Proposed Model
In this study, a novel ensemble model was introduced, which effectively segmented coronary arteries from X-ray coronary images. The model employed a lightweight Unet and DeepLabV3+ architecture and utilized 426 images. Ground truth images were manually created using ImageJ software. The preprocessed images were simultaneously fed into both architectures, and their predictions were combined using a weighted approach for the final segmentation. The model achieved a high** IOU score of 0.8450**, indicating accurate segmentation of the desired region. Furthermore, the precision and F1_score of the model were 0.887 and 0.851, respectively, while the **sensitivity and specificity** values stood at **0.781 and 0.888**. Notably, this ensemble model showcased the closest values among the various methods tested. Throughout the study, rigorous optimization was performed on regularization techniques, hyperparameters, and other performance features to maximize the model's IOU score. As a result, this ensemble model is considered the most effective approach for coronary artery segmentation, providing a valuable tool for early-stage diagnosis of coronary artery disease in XCA images without requiring the presence of a doctor.
# Workflow

![image](https://github.com/Adowan/Semantic-Segmentation-of-Coronary-Artery-Using-Ensembled-Lightweight-U-Net-and-DeepLabV3-/assets/64413677/09c73bc6-a355-4351-beef-030a9165756a)

# Performance Graph
![image](https://github.com/Adowan/Semantic-Segmentation-of-Coronary-Artery-Using-Ensembled-Lightweight-U-Net-and-DeepLabV3-/assets/64413677/25d3cd68-9c4d-4cbc-b6c2-e8056a5beb26)
# Comparison with existing model

![image](https://github.com/Adowan/Semantic-Segmentation-of-Coronary-Artery-Using-Ensembled-Lightweight-U-Net-and-DeepLabV3-/assets/64413677/8a3323d3-4e96-4544-8ad5-4729cb2354c0)
# Result- Segmented Image
![image](https://github.com/Adowan/Semantic-Segmentation-of-Coronary-Artery-Using-Ensembled-Lightweight-U-Net-and-DeepLabV3-/assets/64413677/8eafed81-d039-46f5-8093-092e9092e325)

