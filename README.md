# Neural_Network_Charity_Analysis

## Overview of the analysis: 

Beks- a Data Scientist/Programmer for AlphabetSoup- an organization that has donated over a billion dollars to organizations and foundations that help the environment and the wellbeings of others and unify/beautify the world. The CEO asked Beks if she could analyze and vet every organization and foundation that they donated to and predict where to make investments. 

Beks has received a dataset with over 34,000 organizations that have received funding from Alphabet. The CEO asked Beks if she could:

1. Determine which organization / Foundation to donate to?
2. Determine which organization/ Foundation is a high risk?  

## Results: 

Data Preprocessing

**What is variable(s) considered the target(s) for your model?**

Once we dropped the columns, when then looked at the number of foundations or organizations that received over 100 applications. When then targeted those organizations that were successful based on consideration and completion. 

<img width="1004" alt="Screen Shot 2022-10-13 at 11 38 12 PM" src="https://user-images.githubusercontent.com/106892740/195779279-8902532f-7024-499c-9578-7bf5bcb510b4.png">


**What variable(s) are considered to be the features for your model?**

As for the feature, it was based on the application's success. Both the target and the features dealt with the application and their success to help determine the accuracy of the Neural Network and machine learning models.

<img width="1027" alt="Screen Shot 2022-10-13 at 10 52 50 PM" src="https://user-images.githubusercontent.com/106892740/195777869-3e62da71-9ff8-47af-aa69-d38635b343f4.png">

**What variable(s) are neither targets nor features and should be removed from the input data?**


After receiving the dataset, we dropped EIN and Names columns. 

<img width="1012" alt="Screen Shot 2022-10-12 at 8 12 56 PM" src="https://user-images.githubusercontent.com/106892740/195490823-4421c76e-d33d-4f4d-8fee-015cf88a086a.png">

Compiling, Training, and Evaluating the Model


**How many neurons, layers, and activation functions did you select for your neural network model, and why?**

I started with ten neurons on the first hidden layer and eight neurons on the second hidden layer and used the relu(Rectified Linear Unit) activation on both as the input features. As for the output or the last hidden layer, I used the sigmoid(S-Curve) as the activation. 

I was trying to have the model input positive numbers and output negative numbers to get to an accurate number to determine the success and failure of the dataset. Once the input is formulated based on the number of times it was asked to push, the output displays the accuracy percentage. Below you see the data testing compiling, training, and evaluation. 

<img width="1023" alt="Screen Shot 2022-10-14 at 6 31 30 PM" src="https://user-images.githubusercontent.com/106892740/195963113-445354b1-df25-4348-8be4-be58f69dc9a3.png">

<img width="832" alt="Screen Shot 2022-10-14 at 6 33 02 PM" src="https://user-images.githubusercontent.com/106892740/195963141-99b501c9-4510-485c-8ade-2afea000920d.png">

**Were you able to achieve the target model performance?**

It appears that the accuracy is 52% which is very low. I then conducted an optimized approach using the "adam" optimizer (gradient-based optimization of stochastic objective functions). 

<img width="1053" alt="Screen Shot 2022-10-13 at 11 44 26 PM" src="https://user-images.githubusercontent.com/106892740/195780187-c1d6e2b9-5626-4dcc-b9fc-da0535946973.png">

**What steps did you take to try and increase model performance?**

I used the adam and the binary_crossentropy to determine my loss, increasing the neuron by five epochs. I tested the model over three times to come up with an accuracy of 72% and a loss of 55%. Such numbers would be okay based on the questions. However, 72% is still low. 

<img width="847" alt="Screen Shot 2022-10-13 at 11 45 49 PM" src="https://user-images.githubusercontent.com/106892740/195780407-7ef16cc4-ecc7-4031-95f9-3881824b324b.png">

## Summary: 

Overall, the deep learning model showed several ways it could read a large dataset and how to answer the question or information that you're researching. As for this model and the request, I noticed the first model relu appeared to show low numbers, but when I optimized the model with "adam," the accuracy was approved, and the neurons increased. I recommend using more than one deep learning model to gather the information you're looking for. 

