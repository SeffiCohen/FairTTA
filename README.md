# FairTTA: A Test-Time-Augmentation Method for ML Bias Mitigation
This repository represents open-source research developed by [Nurit Cohen-Inger]  (https://www.linkedin.com/in/nurit-cohen-inger-265269b2/) and [Seffi Cohen](https://www.linkedin.com/in/seffi-cohen-11182046/)

<br>
<div>

In recent years, fairness in machine learning systems has become a critical concern due to the potential negative impact of these systems in real-world applications, such as hiring processes, financial risk assessments, and criminal justice recidivism. While current research on AI fairness and bias mitigation primarily targets pre-processing methods (data used for model training) and in-processing methods (model improvement), post-processing methods addressing the outputs of existing, deployed machine learning systems receive comparatively less attention. In this paper, we introduce "FairTTA," an innovative approach for reducing bias in black-box model predictions by utilizing the Test-Time Augmentation technique in a post-processing manner, generating synthetic data through a Conditional Generative Adversarial Network (CTGAN). Our experimental analysis across various datasets demonstrates that the proposed method substantially improves bias metrics related to the protected attribute, with minor degradation to the model's accuracy. FairTTA achieves better fairness in comparison to both the baseline without bias mitigation and the baseline with another post-processing approach. 

 ## Install
clone our repo
```
git clone [https://github.com/SeffiCohen/FairTTA/]
```
install requirements
```
pip install fairlearn
pip install category_encoders
pip install sdv

```

## How To Run
demo
```
colab_demo.ipynb
```
train
```

```

