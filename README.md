
</p>
<h1 align="center"> Bike Sharing Demand Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>


![Screenshot (28)](https://user-images.githubusercontent.com/102009481/177788412-1f515f71-0654-4a26-9c05-f3598f4f034d.png)




<p>Developed a regression model using algorithms such as Random Forest and XGBoost to predict the hourly demand of bikes.Performed hyperparameter tuning techniques and achieved R2 score of 92% using XGBoost model and reduced the public waiting time significantly.</p>

<h2> :floppy_disk: Project Files Description</h2>


<p>This Project includes 2 executable files, 1 text files ,1 h5 file as well as 1 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>
  
  <li><b>Bike_Sharing_Demand_Prediction_Apoorva_KR.ipynb</b> - Includes all functions required for classification operations  and generates the model.h5 file after execution.</li>
  <li><b>final_individual_notebook_Bike_Sharing_Demand_Prediction_Apoorva_KR.ipynb</b> -  after execution, evaluation is done on the unseen data as in confusion_matrix.txt.</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>model.h5</b> - Model contains information about the predictions of the train set, continous value.</li>
  <li><b>result.txt</b> - Contains information about the MSE and adjusted R2 of the test set.</li>
  
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>Dataset</b> - Includes all dataset  for the training phase  and testing phase of the model in the csv format.</li>
  
</ul>


  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Random Forest Regression </h2>

<p> Regression is the other task performed by a random forest algorithm. A random forest regression follows the concept of simple regression. Values of dependent (features) and independent variables are passed in the random forest model.

In a random forest regression, each tree produces a specific prediction. The mean prediction of the individual trees is the output of the regression. This is contrary to random forest classification, whose output is determined by the mode of the decision trees’ class.

Although random forest regression and linear regression follow the same concept, they differ in terms of functions. The function of linear regression is y=bx + c, where y is the dependent variable, x is the independent variable, b is the estimation parameter, and c is a constant. The function of a complex random forest regression is like a blackbox.
   
  ![Screenshot (30)](https://user-images.githubusercontent.com/102009481/177840433-ff993854-46d5-4a0f-bc39-941a6e05d1cc.png)


<h2> :book: XGboost </h2>

<p> XGBoost is a powerful approach for building supervised regression models. The validity of this statement can be inferred by knowing about its (XGBoost) objective function and base learners. The objective function contains loss function and a regularization term. It tells about the difference between actual values and predicted values, i.e how far the model results are from the real values. The most common loss functions in XGBoost for regression problems is reg:linear, and that for binary classification is reg:logistics. Ensemble learning involves training and combining individual models (known as base learners) to get a single prediction, and XGBoost is one of the ensemble learning methods. XGBoost expects to have the base learners which are uniformly bad at the remainder so that when all the predictions are combined, bad predictions cancels out and better one sums up to form final good predictions.


![Screenshot (31)](https://user-images.githubusercontent.com/102009481/177841156-6e6d4692-ef27-40b3-afd6-f84c60442ba2.png)




![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>


<p><b>1) final_individual_notebook_Bike_Sharing_Demand_Prediction_Apoorva_KR.ipynb</b></p>
<p> This file must be executed, to define all the functions and variables required for regression operations which leads to the production of the model.h5 file. and to evaluate the model performance on unseen data






 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

< Apoorva KR > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/apoorva-r-gowda/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/apoorvaKR12695)



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>'Mobile Price Prediction Using Machine Learning Blog' . [Online].</p>
      <p>Available: https://medium.com/@Nivitus./mobile-price-prediction-using-machine-learning-fa9cab6fb242
  </li>
  
  <li><p>'Mobile Price Prediction Through Four Classification Algorithms '. [Online].</p>
      <p>Available: https://www.analyticsvidhya.com/blog/2022/02/learn-mobile-price-prediction-through-four-classification-algorithms/ /</p>
  </li>
  <li><p>Youtube.com,'Mobile Price Classification and Prediction using 3 Machine Learning Algorithms'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=rROyz_hZjKQ</p>
  </li>
  <li><p>Youtube.com, 'Mobile Price Prediction Kaggle Dataset Analysis | Data Science | ML | Kaggle'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=880YXMnTeu4</p>
  </li>
  <li><p>Manisha-sirsat.blogspot.com, 'What is Confusion Matrix and Advanced Classification Metrics?'. [Online].</p>
      <p>Available: https://manisha-sirsat.blogspot.com/2019/04/confusion-matrix.html</p>
  </li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)




