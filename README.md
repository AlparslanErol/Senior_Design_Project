# Senior_Design_Project
Boğaziçi University Electrical Electronics Engineering EE 492 Senior Design Project

# Summary

  Machine learning is considered an important method for the detection of anomaly network traffic by an intrusion detection system (IDS). The three big and common schemes borrowed from the machine-learning community in recent academic research are neural networks, support vector machines (SVM) and decision-making trees or forests with boosting and ensemble methods.\
  In this paper, some machine learning and deep dearning algorithms such supervised learning as  gaussian naive bayes (GNB), decision-making trees (DT), ada boost classifier (ABC), random forest (RF), light gradient boosting (LGB) and such unsupervised deep learning method as Auto-Encoder (AE) are implemented with a uniform environment and the purpose of exploring the practice and issues of using these approaches in detecting anomaly behaviors. After data preprocessing and feature selection part some manipulation are implemented to the dataset. GNB, DT, ABC, RF and LGB are implemented and found that LGB has the best performance. Then deep dive into LGB model and used binary and multiclass classisficaiton methods with parameter tuning. Because of balance importance cross entropy and for data unbalancy between normal and attack type variables, focal loss is used to down-weight for normal type data and get the best solutions. Also an unsupervised learning (AE) added to the list and all this algorithms are compared.\
  The experiments were conducted on the intrusion detection dataset called KDD’99 cup dataset. After exploratory data analysis, it is found that, 1 feature has no impact on target, 3 feature have highly correlated with each other, ~78% of initial data are duplicated and some features are not important for target when they are compared with the important features.\
  The comparison of the different machine learning model results with and without dimensionality reduction is also done.
  
  # Conclusion
  
  The main purpose of this project is to developed machine learning models that can detect different anomaly attack types. Some machine learning and deep dearning algorithms such supervised learning as  gaussian naive bayes (GNB), decision-making trees (DT), ada boost classifier (ABC), random forest (RF), light gradient boosting (LGB) and such unsupervised deep learning method as Auto-Encoder (AE) are implemented with a uniform environment and the purpose of exploring the practice and issues of using these approaches in detecting anomaly behaviors. After data preprocessing and feature selection part some manipulation are implemented to the dataset. GNB, DT, ABC, RF and LGB are implemented and found that LGB has the best performance. Then deep dive into LGB model and used binary and multiclass classisficaiton methods with parameter tuning. Because of balance importance cross entropy and for data unbalancy between normal and attack type variables, focal loss is used to down-weight for normal type data and get the best solutions. Also an unsupervised learning (AE) added to the list and all this algorithms are compared and all results are given above.\
  For future project, after precise feature extraction to BOUN (Boğaziçi University) network attack dataset, light gradient boosting model with focal loss and parameter optimization can use for supervised learning or auto-encoder can be used for unsupervised learning.

