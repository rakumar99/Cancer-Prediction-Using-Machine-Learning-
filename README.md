# Cancer-Prediction-Using-Machine-Learning


## Project Overview:

This project aims to classify breast cancer as either malignant or benign using machine learning algorithms. The classification models are built using PyCaret, an open-source, low-code machine learning library in Python. By leveraging various algorithms, the project identifies the best-performing model for accurate breast cancer detection based on cell nucleus features from a digitized image of a fine needle aspirate (FNA).


## Dataset Information:

The dataset consists of features computed from digitized images of fine needle aspirate samples from breast masses. These features describe the characteristics of the cell nuclei present in the image, allowing for accurate classification of the mass as either malignant or benign.


## Attribute Information:


<h5>
  
ID Number: Unique identifier for each case.
  
Diagnosis: Indicates if the tumor is malignant (M) or benign (B).
  
Ten Real-Valued Features Computed for Each Cell Nucleus:

Radius: Mean of distances from the center to points on the perimeter.

Texture: Standard deviation of gray-scale values.

Perimeter

Area

Smoothness: Local variation in radius lengths.

Compactness: (Perimeter^2 / Area) - 1.0.

Concavity: Severity of concave portions of the contour.

Concave Points: Number of concave portions of the contour.

Symmetry

Fractal Dimension: "Coastline approximation" - 1.

For each feature, the mean, standard error, and worst or largest values were computed, resulting in 30 total features per image.</h5>


## Class Distribution:


<h5>

  Benign (B): 357 cases
  
  Malignant (M): 212 cases
  
  Download Link: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data </h5>



## Libraries Used:


<h5>
  
The following Python libraries were utilized in the project for data analysis, visualization, and model building:


pandas: For data manipulation and analysis.

matplotlib: For plotting graphs and visualizing data trends.

seaborn: For statistical data visualization. </h5>


## Machine Learning Algorithms:


<h5>
  
Several machine learning classification algorithms were applied and compared using PyCaret to identify the most effective model for breast cancer detection:

Logistic Regression

Decision Tree

Random Forest

Extra Trees

XGBoost

LightGBM

CatBoost

Best Model Performance

Best Model AUC: 99.47%

This high AUC score demonstrates the model’s excellent ability to distinguish between malignant and benign tumors, ensuring a reliable classification</h5>


## Future Work:

Hyperparameter Tuning: Fine-tune model parameters to further improve accuracy.

Additional Feature Engineering: Create new features to enhance the predictive power of the models.

Deep Learning: Explore the use of deep learning models for even higher accuracy.



## Conclusion:


<h5>This project successfully classifies breast cancer as malignant or benign using a variety of machine learning algorithms in PyCaret. With an AUC score of 99.47%, the model offers an effective solution for early detection and diagnosis of breast cancer, providing valuable insights into improving healthcare outcomes.</h5>
