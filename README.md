# FairTTA: A Test-Time-Augmentation Method for ML Bias Mitigation
This repository represents open-source research developed by [Nurit Cohen-Inger] (https://www.linkedin.com/in/nurit-cohen-inger-265269b2/) and [Seffi Cohen] (https://www.linkedin.com/in/seffi-cohen-11182046/)

<br>
<div>

In recent years, the imperative for fairness in machine learning systems has escalated, driven by the potential for negative
outcomes in critical real-world applications, including hiring pro-
cesses, financial risk assessments, and criminal justice recidivism.
While the bulk of research in AI fairness and bias mitigation has been directed towards pre-processing methods (enhancing the data used for model training) and in-processing methods (improving the models themselves), post-processing strategies, which address the outputs of already deployed machine learning systems, have not been as thoroughly explored. In this paper, we propose "FairTTA," a groundbreaking approach to improve bias in black-box model predictions. This method leverages Test-Time Augmentation (TTA), employing a Conditional Generative Adversarial Network (CTGAN) to generate synthetic augmentations to replicate the corresponding sample, but with the opposite value of the protected attribute, along with adjustments. This ensures fairness by providing equal opportunities to both privileged and unprivileged values. Our rigorous experimental analysis across a spectrum of datasets reveals that our approach markedly
enhances bias metrics concerning the protected attribute, FairTTA
achieves 53.4% better fairness, with a 4% decrease in the model’s
accuracy compared to non-mitigated benchmark, demonstrates superior fairness outcomes across alternative post-processing methods.

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
```
tta-fairml.ipynb

Choose the dataset to run (RECRUIT_SEX, CREDIT_SEX, ADULT_SEX, COMPAS_SEX)
```

