# Undersampling & Oversampling w.r.t before/after Train-Test split

Explore the affects of Undersampling vs Oversampling before & after Train-Test split w.r.t to performance metrics.


Undersampling : By randomly removing samples from majority class

  Case1 : Undersampling only the Train dataset after Train-Test split  
      
  Case2 : Undersampling the entire dataset before Train & Test split
  
  Undersampling Summary: Deceiving f1-scores, as we remove samples from majority class,  the mathematical formula calculating precision & recall values takes into consideration 
  the fewer class'0' samples from Case-2 as opposed to larger class'0' samples from Case-1. 
  Hence inflating the numbers and the appearance of better model with the increased f1-score.
  
  
Oversampling: By randoming duplicating samples from minority class

  Case3 : Oversampling only the Train dataset after the Train-Test split
  
  Case4 : Oversampling the entire dataset before the Train & Test 
  
  Oversampling Summary: As we randomly duplicate minority class for Case4, there is data leakage of duplicated samples into training the model and testing on the same duplicated samples, 
  thereby overfitting the model as opposed to no duplicate data leakage in Case-3 model.
  
  
  
  
  

    

  
