## GradCAM as Black-box Explainability method for Deepfake Detection CNN models (XceptionNet)
### Overview
#### Assignment 1 for COMP-6936 (Advanced Machine Learning)
This repository demonstrates applying Explainable AI method like `Grad-CAM` to CNN model, `XceptionNet`, for Deepfake Detection task. By employing `Grad-CAM`, it helps to give more insights and justify on how decisions are made by CNN models.

### Pretrained model used:
- `XceptionNet`: the model has been trained on dataset from [Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics](https://github.com/yuezunli/celeb-deepfakeforensics), then it is used to predict on new dataset, [Kaggle Deepfake Detection Challenge](https://www.kaggle.com/competitions/deepfake-detection-challenge/data), which it has never seen before. Thus, the results can help to draw conclusion on how well the model can generalize on unseen data.
