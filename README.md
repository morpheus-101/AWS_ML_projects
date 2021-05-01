# AWS_ML_projects
This repository consists of 3 Machine Learning serverless applications deployed on AWS.
AWS services used:
AWS lambda for serverless compute
S3 for storing the trained ML model and the function code
API gateway for accepting HTTP requests and formatting HTTP responses
Cloudwatch for monitoring data about function executions
Cloudformation to monitor various serverless stacks
</br>
</br>
</br>

## Parts of speech tagging
This app takes a string of text and generates parts of speech tags for the words in the input string. Used NLTK library for generating POS tags.
</br>
<p align="center">
  <img height="420" width="860" src="https://github.com/RishikeshDhayarkar/AWS_ML_projects/blob/main/aws_ml_proj_pics/nlp_1.png">
</p>  
</br>
</br>
</br>


## Dependency parsing
This app is responsible for generating dependency relationships between all the words in a given input sentence. 
The above two application use Spacy and NLTK libraries for generating outputs. 
</br>
<p align="center">
  <img height="370" width="860" src="https://github.com/RishikeshDhayarkar/AWS_ML_projects/blob/main/aws_ml_proj_pics/nlp_2.png">
</p>  
</br>
</br>
</br>

## Regression model for housing price prediction
This is a simple application that uses a linear regression model to predict housing prices in california. The inputs to this algorithm are features of a 
house such as number of rooms, block population, geo-location, average house occupancy, median house age, median income of block etc. Used Scikit-learn library to generate predictions from the linear model.
</br>
<p align="center">
  <img height="250" width="900" src="https://github.com/RishikeshDhayarkar/AWS_ML_projects/blob/main/aws_ml_proj_pics/reg_1.png">
</p>  
</br>
</br>
</br>

## Image classification model
This application is basically a multiclass classification Deep learning model that can be used classify images into one of thousand classes. The input to this app is an image and the output is a probability distribution over all possible classes. The class corresponding to the highest probability is the predicted label of the class.  
The app displays the probabilities for the seven most likely classes. Resnet50 and Inception V3 are used in this excercise to generate the output probabilities. The final prediction is based on the averaged outputs from both the models. 
</br>
<p align="center">
  <img height="520" width="960" src="https://github.com/RishikeshDhayarkar/AWS_ML_projects/blob/main/aws_ml_proj_pics/class_1.png">
</p>  
</br>
</br>
</br>
