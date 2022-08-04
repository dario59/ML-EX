# ML-EX

The objective of this analysis is to correctly predict wine quality from its characteristics. Variables in use were about chemical attributes of the finite product (chlorides, alcohol etc.). Quality it's expressed in a scale from 1 to 10. All the other features were in different scale. Decided to go with a 10 fold approach. For academic purpose, it wasn't necessary to do more than 1 repeats. I've runned and compared various alghoritm to do the job:
-	Linear Regression (not transformed, prev. in mean);
-	Log Log Regression (because all the features are strictly positive I've decided to give it a shot);
-	KNN;
-	Decision Threes;
-	Random forest Threes;

It turns out random forest threes it's the best of the bunch, because there isn't a linear correlation between data so a more ductile model than linear regression is needed to make prevision. RFT gives less performance errors than the other two models.

All the code is written in R Studio, R Version 4.1.3.
