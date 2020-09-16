# Breast-Cancer-Prediction-using-Machine-Learning-Algorithms
Breast cancer (BC) is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths according to global statistics, making it a significant public health problem in today’s society. The early diagnosis of BC can improve the prognosis and chance of survival significantly, as it can promote timely clinical treatment to patients. Further accurate classification of benign tumors can prevent patients undergoing unnecessary treatments. Thus, the correct diagnosis of BC and classification of patients into malignant or benign groups is the subject of much research. Because of its unique advantages in critical features detection from complex BC datasets, machine learning (ML) is widely recognized as the methodology of choice in BC pattern classification and forecast modeling. In our model we used the available dataset (divided into test and training data) and employed two different ML algorithms to predict the class of the test data into M or B.

# Description of Dataset
## Attributes Information:-
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.<br/> 
Attribute Information:<br/> 
1) ID number<br/> 
2) Diagnosis (M = malignant, B = benign) Ten real-valued features are computed for each cell nucleus:<br/> 
  a) radius (mean of distances from center to points on the perimeter)<br/> 
  b) texture (standard deviation of gray-scale values)<br/> 
  c) perimeter<br/> 
  d) area<br/> 
  e) smoothness (local variation in radius lengths) f) compactness (perimeter^2 / area - 1.0)<br/>
  g) concavity (severity of concave portions of the contour)<br/> 
  h) concave points (number of concave portions of the contour)<br/>
  i) symmetry<br/> 
  j) fractal dimension ("coastline approximation" - 1)<br/> 
The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, and field 23 is Worst Radius. All feature values are recoded with four significant digits.
