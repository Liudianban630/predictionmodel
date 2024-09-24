# **Identification and validation of an explainable prediction model of prognosis after Acute cerebral infarction: a prospective study**

## abstract
### background 
### Methods 
### results
24小时内入院，出院后3个月随访计算评分
---
1. 确定纳入的变量，包括table1的制作以及临床意义
2. 

## introdution
Acute cerebral infarction is
Inflammatory corpuscle 
The machine learning (ML) 
In this study, we aimed to develop 

## Introduction

### 1. Introduction to Acute Cerebral Infarction and the Importance of Prognosis Prediction

Acute Cerebral Infarction (ACI), commonly known as ischemic stroke, remains a major cause of death and long-term disability worldwide. It occurs due to the sudden obstruction of blood flow to the brain, often resulting from an embolism or thrombosis, which leads to neuronal damage and functional impairments (Feigin et al., 2014). Early and accurate prediction of prognosis in ACI patients is crucial for optimizing treatment strategies, resource allocation, and patient counseling (Lees et al., 2010). The ability to predict outcomes such as survival, functional recovery, and recurrence risk is essential for improving patient care and reducing the burden on healthcare systems (Mochari-Greenberger et al., 2015).

### 2. Inflammatory Indicators and Their Association with the Prognosis of Acute Cerebral Infarction

Inflammation is a key component of the pathophysiological response to cerebral ischemia. Following an ischemic event, a complex inflammatory cascade is triggered, involving both the central nervous system and peripheral immune responses (Chamorro et al., 2012). Elevated levels of inflammatory biomarkers such as C-reactive protein (CRP), interleukin-6 (IL-6), and tumor necrosis factor-alpha (TNF-α) have been associated with increased stroke severity and worse outcomes (Whiteley et al., 2011; Emsley et al., 2003). These markers reflect the extent of tissue damage and the body's response to injury, making them valuable predictors of prognosis (Kamel et al., 2015). Understanding the role of inflammation in ACI can inform the development of targeted therapies and enhance prognostic models (Simmons & Grant, 2016).

### 3. Introduction to Machine Learning and SHAP Method

Machine learning (ML) offers advanced analytical capabilities for handling complex and high-dimensional datasets, making it a powerful tool for medical prognosis (Obermeyer & Emanuel, 2016). In stroke research, ML algorithms can integrate various clinical and biological variables to create predictive models with superior accuracy compared to traditional statistical methods (Kansagra et al., 2020). The SHapley Additive exPlanations (SHAP) method provides a framework for interpreting these models by quantifying the contribution of each feature to the prediction (Lundberg & Lee, 2017). SHAP values enhance the transparency and interpretability of ML models, which is critical for their application in clinical settings where understanding the decision-making process is as important as the predictions themselves (Molnar, 2019).

### 4. Aim of Our Study

The aim of our study is to develop and validate a predictive model for the prognosis of Acute Cerebral Infarction using inflammatory indicators, leveraging machine learning techniques. We intend to evaluate the model's performance in terms of discrimination and calibration, ensuring it accurately predicts patient outcomes. Furthermore, we aim to employ the SHAP method to interpret the importance of individual inflammatory markers, providing insights into their roles in prognosis. Our ultimate goal is to enhance the understanding of the prognostic value of inflammatory responses in ACI and to develop a robust predictive tool that can improve clinical decision-making and patient management.

In summary, this research seeks to integrate inflammatory biomarkers and machine learning methodologies to advance prognostic modeling in Acute Cerebral Infarction, potentially leading to better patient outcomes and more efficient healthcare delivery.

---

### References

- Chamorro, Á., Meisel, A., Planas, A. M., Urra, X., van de Beek, D., Veltkamp, R., ... & Bornstein, N. (2012). The immunology of acute stroke. *Nature Reviews Neurology*, 8(7), 401-410.
- Emsley, H. C., Smith, C. J., Georgiou, R. F., Vail, A., Hopkins, S. J., Rothwell, N. J., & Tyrrell, P. J. (2003). A randomised phase II study of interleukin-1 receptor antagonist in acute stroke patients. *Journal of Neurology, Neurosurgery & Psychiatry*, 74(8), 1305-1310.
- Feigin, V. L., Norrving, B., & Mensah, G. A. (2014). Global burden of stroke. *Circulation Research*, 120(3), 439-448.
- Kamel, H., Iadecola, C., & Grudzien, A. (2015). Brain-immune interactions and ischemic stroke: clinical implications. *Archives of Neurology*, 69(5), 576-580.
- Kansagra, A. P., Goyal, M. S., Hamilton, S., & Albers, G. W. (2020). Automated assessment of the Alberta stroke program early CT score (ASPECTS): a systematic review of current methodologies and clinical use. *Journal of NeuroInterventional Surgery*, 12(7), 748-753.
- Lees, K. R., Bluhmki, E., von Kummer, R., Brott, T. G., Toni, D., Grotta, J. C., ... & Hacke, W. (2010). Time to treatment with intravenous alteplase and outcome in stroke: an updated pooled analysis of ECASS, ATLANTIS, NINDS, and EPITHET trials. *The Lancet*, 375(9727), 1695-1703.
- Lundberg, S. M., & Lee, S. I. (2017). A unified approach to interpreting model predictions. *Advances in Neural Information Processing Systems*, 30.
- Mochari-Greenberger, H., Mosca, L., Aggarwal, B., & Liao, M. (2015). Racial and ethnic differences in hospital length of stay among patients with acute ischemic stroke. *Journal of Stroke and Cerebrovascular Diseases*, 24(1), 33-39.
- Molnar, C. (2019). *Interpretable Machine Learning*. Lulu.com.
- Obermeyer, Z., & Emanuel, E. J. (2016). Predicting the future—big data, machine learning, and clinical medicine. *The New England Journal of Medicine*, 375(13), 1216-1219.
- Simmons, S. C., & Grant, G. A. (2016). Biomarkers in stroke: a potential approach to the chaos. *Neurosurgical Focus*, 40(3), E11.
- Whiteley, W., Tseng, M. C., & Sandercock, P. (2011). Blood biomarkers in the diagnosis and prognosis of acute stroke: a systematic review. *Stroke*, 42(10), 3433-3439.

## Introduction

### 1. Introduction to Acute Cerebral Infarction and the Importance of Prognosis Prediction

Acute Cerebral Infarction (ACI), commonly known as ischemic stroke, remains a major cause of death and long-term disability worldwide. It occurs due to the sudden obstruction of blood flow to the brain, often resulting from an embolism or thrombosis, which leads to neuronal damage and functional impairments (Feigin et al., 2014). Early and accurate prediction of prognosis in ACI patients is crucial for optimizing treatment strategies, resource allocation, and patient counseling (Lees et al., 2010). The ability to predict outcomes such as survival, functional recovery, and recurrence risk is essential for improving patient care and reducing the burden on healthcare systems (Mochari-Greenberger et al., 2015).

### 2. Inflammatory Indicators and Their Association with the Prognosis of Acute Cerebral Infarction

Inflammation is a key component of the pathophysiological response to cerebral ischemia. Following an ischemic event, a complex inflammatory cascade is triggered, involving both the central nervous system and peripheral immune responses (Chamorro et al., 2012). Elevated levels of inflammatory biomarkers such as C-reactive protein (CRP), interleukin-6 (IL-6), and tumor necrosis factor-alpha (TNF-α) have been associated with increased stroke severity and worse outcomes (Whiteley et al., 2011; Emsley et al., 2003). These markers reflect the extent of tissue damage and the body's response to injury, making them valuable predictors of prognosis (Kamel et al., 2015). Understanding the role of inflammation in ACI can inform the development of targeted therapies and enhance prognostic models (Simmons & Grant, 2016).

### 3. Introduction to Machine Learning and SHAP Method

Machine learning (ML) offers advanced analytical capabilities for handling complex and high-dimensional datasets, making it a powerful tool for medical prognosis (Obermeyer & Emanuel, 2016). In stroke research, ML algorithms can integrate various clinical and biological variables to create predictive models with superior accuracy compared to traditional statistical methods (Kansagra et al., 2020). The SHapley Additive exPlanations (SHAP) method provides a framework for interpreting these models by quantifying the contribution of each feature to the prediction (Lundberg & Lee, 2017). SHAP values enhance the transparency and interpretability of ML models, which is critical for their application in clinical settings where understanding the decision-making process is as important as the predictions themselves (Molnar, 2019).

### 4. Aim of Our Study

The aim of our study is to develop and validate a predictive model for the prognosis of Acute Cerebral Infarction using inflammatory indicators, leveraging machine learning techniques. We intend to evaluate the model's performance in terms of discrimination and calibration, ensuring it accurately predicts patient outcomes. Furthermore, we aim to employ the SHAP method to interpret the importance of individual inflammatory markers, providing insights into their roles in prognosis. Our ultimate goal is to enhance the understanding of the prognostic value of inflammatory responses in ACI and to develop a robust predictive tool that can improve clinical decision-making and patient management.

In summary, this research seeks to integrate inflammatory biomarkers and machine learning methodologies to advance prognostic modeling in Acute Cerebral Infarction, potentially leading to better patient outcomes and more efficient healthcare delivery.

---

### References

- Chamorro, Á., Meisel, A., Planas, A. M., Urra, X., van de Beek, D., Veltkamp, R., ... & Bornstein, N. (2012). The immunology of acute stroke. *Nature Reviews Neurology*, 8(7), 401-410.
- Emsley, H. C., Smith, C. J., Georgiou, R. F., Vail, A., Hopkins, S. J., Rothwell, N. J., & Tyrrell, P. J. (2003). A randomised phase II study of interleukin-1 receptor antagonist in acute stroke patients. *Journal of Neurology, Neurosurgery & Psychiatry*, 74(8), 1305-1310.
- Feigin, V. L., Norrving, B., & Mensah, G. A. (2014). Global burden of stroke. *Circulation Research*, 120(3), 439-448.
- Kamel, H., Iadecola, C., & Grudzien, A. (2015). Brain-immune interactions and ischemic stroke: clinical implications. *Archives of Neurology*, 69(5), 576-580.
- Kansagra, A. P., Goyal, M. S., Hamilton, S., & Albers, G. W. (2020). Automated assessment of the Alberta stroke program early CT score (ASPECTS): a systematic review of current methodologies and clinical use. *Journal of NeuroInterventional Surgery*, 12(7), 748-753.
- Lees, K. R., Bluhmki, E., von Kummer, R., Brott, T. G., Toni, D., Grotta, J. C., ... & Hacke, W. (2010). Time to treatment with intravenous alteplase and outcome in stroke: an updated pooled analysis of ECASS, ATLANTIS, NINDS, and EPITHET trials. *The Lancet*, 375(9727), 1695-1703.
- Lundberg, S. M., & Lee, S. I. (2017). A unified approach to interpreting model predictions. *Advances in Neural Information Processing Systems*, 30.
- Mochari-Greenberger, H., Mosca, L., Aggarwal, B., & Liao, M. (2015). Racial and ethnic differences in hospital length of stay among patients with acute ischemic stroke. *Journal of Stroke and Cerebrovascular Diseases*, 24(1), 33-39.
- Molnar, C. (2019). *Interpretable Machine Learning*. Lulu.com.
- Obermeyer, Z., & Emanuel, E. J. (2016). Predicting the future—big data, machine learning, and clinical medicine. *The New England Journal of Medicine*, 375(13), 1216-1219.
- Simmons, S. C., & Grant, G. A. (2016). Biomarkers in stroke: a potential approach to the chaos. *Neurosurgical Focus*, 40(3), E11.
- Whiteley, W., Tseng, M. C., & Sandercock, P. (2011). Blood biomarkers in the diagnosis and prognosis of acute stroke: a systematic review. *Stroke*, 42(10), 3433-3439.

## Methods
### study population
The prospective study in China was conducted in 
### data collection and processing
### Model development and comparison
The data from the prospective study were divided, with 70% utilized for training and 30% for validation(internal validation), for the purpose of avoiding overfitting. 
The total of 30 features mentioned above were used to develop the prediction models. Missing data were handled by multiple imputation method, and the proportions of missing data per variable are shown in Supplementary Table S1. Twelve Machine Learning models, namely, logistic regression (LR), decision tree (DT), random forest (RF), K-nearest neighbor (KNN), artificial neutral network(ANN),  extra tree (ET), adaptive boosting (AdaBoost), gradient boosting machine (GBM), light gradient boosting machine (LightGBM),  support vector machine (SVM), Naive Bayes and extreme gradient boosting(XGboost) were used to predict the prognosis of patients after acute cerebral infarction. In order to optimize the prediction model, ranom search was applied to obtain the final hyperparameters.
Several commonly used evaluation indexs, such as the area under the receiver-operating-characteristic(ROC) curve(AUC), sensitivity, specificity, postive predictive value (PPV), negative predictive value (NPV), accuracy, and F1 score, were used to evaluated the reliability of these models. We also conducted five-fold and ten-fold cross validations in the prospective study for the validation of the prediction model.
### Feature selection and model explanation
SHAP (SHapley Additive exPlanations) is a game theotetic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions.


> Lundberg SM, Erion G, Chen H, DeGrave A, Prutkin JM, Nair B, Katz R, Himmelfarb J, Bansal N, Lee SI. From Local Explanations to Global Understanding with Explainable AI for Trees. Nat Mach Intell. 2020 Jan;2(1):56-67. doi: 10.1038/s42256-019-0138-9. Epub 2020 Jan 17. PMID: 32607472; PMCID: PMC7326367.

> Mitchell R, Frank E, Holmes G. GPUTreeShap: massively parallel exact calculation of SHAP scores for tree ensembles. PeerJ Comput Sci. 2022 Apr 5;8:e880. doi: 10.7717/peerj-cs.880. PMID: 35494875; PMCID: PMC9044362.

> Lundberg SM, Erion G, Chen H, DeGrave A, Prutkin JM, Nair B, Katz R, Himmelfarb J, Bansal N, Lee SI. From Local Explanations to Global Understanding with Explainable AI for Trees. Nat Mach Intell. 2020 Jan;2(1):56-67. doi: 10.1038/s42256-019-0138-9. Epub 2020 Jan 17. PMID: 32607472; PMCID: PMC7326367.

The SHAP method was used to rank the importance of input features and explain the results of the prediction model, which is an good approch to overcome the "black-box" issue of machine learning methods.
SHAP value-assisted feature selection was used to restrict the prediction model from 30 to 5 features in accordance with feature importance rank. The final model with the best predictive ability in the process of reducing features was chosen for further analysis.
The SHAP method also offered glolbal and local explanations for the models. Global explanation for the association between input features and outcomes, and local explanation for demonstate a specific prediction for an individual child by the specific data.

### Web page deployment tool based on streamlit framework
For the utility of the model in clinical settings, the final prediction model was implemented into a web application established based on the Streamlit Python-based framework. When the values of corresponding features from the final model are provided, the application can return the probability of bad prognosis, also the force plot for the individual patient.

### Statistal analysis
Data analysis were coducted using python version 3.8.1 and R version. Continuous variables with skewed distributions were presented as median with interquartile range and compared using the Mann-Whitney U test or Kruskal-Wallis H test. Categorical variables were presented as numbers with percentages and compared using the Chi-square test or Fisher’s exact test. A two-tailed P value < 0.05 was considered statistically significant.

## results
### patient characteristics
This prospective study involved 1017 acute cerebral infarction patients hospitalized within 24 hours for the identificaiton of the prediction model. Details of the study design are displayed in Fig.1.
Among the 1017 patients in the 
### Model development and performance comparison
The data collected were used to generate 12 ML models to predict the prognosis of acute cerebral infarction patients. Among the 12 models, RF model (AUC=0.897) had the best predictive effect for prognosis, followed by GBM model (AUC=0.890) and ET model (AUC=0.879). The discriminative performances of these 12 models are listed in Table 2, and the ROC curves and the SHAP summary plots of the top 20 features for the top five best-performing ML models are presented in Fig.2. During 
### Identification of the final model 
The final model was identified during the feature reduction of the RF model. As 

### Internal validation of the final model

### Model explanation
SHAP method is utilized to interpret the output

### Concenient application of clinical utility
The final prediction model was implemented into the web application for clinical application, as shown in Fig.5. The application will automatically predict the risk of prognisis when the actual values of the 6 features required for the model are entered. Additionally, a force plot for the individual patient will also be displayed to indicate the features that contribute to the decision of prognosis: the blue features on the right are the features pushing the prediction towards good prognosis. The web application is accessible online at http:

### Prognostic implications
The investigation of 


## **Discussion**
This is a first prospective study, to our knowledge, to investigate and compare 12 ML models for comprehensive prognosis prediction analyses. We identified a set of predictive risk factors and constructed a prediction model for 
To date, numerous studies have concentrated on
Due to the lack of guidelines or consensus for 
The final model we developed had a superior ability 
The other major finding in this study
We should acknowledge several limitations of this study.
In conclusion,

#### **Contributors**

