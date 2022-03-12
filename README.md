# Undersampling vs. Oversampling
Explore the affects of Undersampling vs Oversampling before & after Train-Test split w.r.t to performance metrics.


Undersampling : By randomly removing samples from majority class

  Case1 : Undersampling only the Train dataset  
      
  Case2 : Undersampling the entire dataset and then splitting Train & Test
  
  Undersampling Summary: Deceiving f1-scores, as we remove samples from majority class,  the mathematical formula calculating precision & recall values takes into consideration 
  the fewer class'0' samples from Case-2 as opposed to larger class'0' samples from Case-1. 
  Hence inflating the numbers and the appearance of better model with the increased f1-score.
  
  
Oversampling: By randoming duplicating samples from minority class

  Case1 : Oversampling only the Train dataset  
  
  Case2 : Oversampling the entire dataset and then splitting Train & Test 
  
  Oversampling Summary: As we randomly duplicate data sample of minority class, there is data leakage of duplicated samples into training the model and testing on the same duplicated samples, 
  thereby overfitting the model as opposed to no duplicate data leakage in Case-2 model.
  
  
  
  
  

    

  
