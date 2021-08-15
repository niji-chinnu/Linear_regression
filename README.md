car price prediction  -Linear Regression Model

The model was build to predict the car price based on the given features:

   Brand,Body,Model,Mileage,engine Volume,Engine Type & Registration
         
The data is cleaned by removing outliers and and null values

The multi colinear features are removed usin VIF factor 

ols model is created using statsmodel.api it is evaluated usong   rscore,adjrescore and p values 
 
 rscore ,adj rscore > .70 cosidered as good model, the features having p values >.05 is considered as significant features 

Forward and Backward selection is done to  tune the model improve its performance and to find out the significant features that is contributing more to target feature 

Linear Regresssion Model is build using Scikit learn and residual is been evaluated 

L1 & L2 regularization is done to improve thee performance of the model

Conclusion: From ols model, scikit learn model and after L1 & L2 regularization we got accuracy of the model as .67 which is average accuracy







