# STARTUP-SUCCESS-ANALYSIS
Find from the data that start up is aquired or not
PURPOSE:

  A]TO FIND WHICH STARTUP IS SUCCSES AFTER SEVERAL YEARS OR AQUIRED OR NOT BY ANY ANGEL INVESTOR
 
WORKDONE:

A]PREPROCESSING SUCH AS REMOVING NULL VALUES AND FILL FEATURE WITH BY CENTRAL TENDECY
B]REMOVE UNRELATED FEATURE WHICH IS NOT MUCH COLINEAR
C]FEATURE ENGINEERING
D]USING LABLE ENCODER CONVERT OBJECT INTO NUM DATATYPE(INT,FLOAT)
E]SPLIT DATA INTO X & Y
F]BUILDING MUILIPLE COLUMN
G]FIND ACCURACY OF DIFFERENT COLUMN
H]APPLYNG HYPERTUNER 
I]TOOK INPUT FROM USER AND PREDICT THE RESULT



Conclusion : 
      A] purpose of this dataset is to find from the data that start up is aquired or not by learning from Privious data
      B] In this i build muiltiple Models such as knn,svc,Dt,Logistics,Random forest
         But  i get max accuracy in random forest as well as DeCition Tree which is nearly 75%
      C] after that i apply  hypertuner such as mean_sample_leaf(pruning tech) on random forest to increse the accuracy of our model
         and it incresses at 77%.
      D] IN LAST:all can see that i took the value from user and find that startup is awuired or not.
    
