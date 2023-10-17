# Explainability_Breast_Cancer
Explainability using Shap and performance improved using GPT


One of the strongest usecase of LLMs for Data scientists, bridging the gap of domain, functional understanding while developing or experimenting with different models. 
What can be a better dataset than a healthcare data to understand how it can simplify the explanation for a data scientist and in-turn improve explainability of the models for higher adoption. 
I used an open-source data to understand if GenAI /LLMs can bridge the gap between data collection, data management, model selection, model explainability processes to improve business adoption. 
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

I was really astonished to see how impactful it was!
I went from an output which looked like this, 
Patient ID: ABC ->  Model prediction: Malignant (80% probability) -> top 5 variables: [radius_worst,  area_worst, compactness_se, concavity_worst, concavity_se]
To this,
Patience ID ABC -> 


For Patient ABC, the higher chances(80%) of malignancy of cancer is primarily caused by factors like larger variations and complexities in the length and boundary of the tumor, more severe concave portions, highest standard deviations of gray-scale values, larger sizes, and greater distances from the center to points on the perimeter of the tumor. These factors suggest a higher likelihood of aggressive and harmful characteristics in the cancer.

(Note, this is not validated by any professional expert, yet it certainly shows that a strong prompt engineering can make a solution more explainable, usable, adoptable, and hence responsible)
Chatgpt was used to understand the column definitions using a abstract of the paper https://www.spiedigitallibrary.org/conference-proceedings-of-spie/1905/1/Nuclear-feature-extraction-for-breast-tumor-diagnosis/10.1117/12.148698.short?SSO=1. The same broader definitions are used to build summary statements in chatgpt(please note the Chatgpt is not part of this code)
