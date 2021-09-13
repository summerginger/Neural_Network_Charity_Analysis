# Neural_Network_Charity_Analysis
# Overview
With the knowledge of machine learning and neural networks, this project use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 
The purpose of doing this anaylsis is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.
# Results
### Data Preprocessing
•	The column "IS_SUCESSFUL"  is considered the variable which contains binary data is the target for our deep learning neural network as it referes to if the charity donation was used effectively.

•	Columns "APPLICAITON_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" are collectively the features of our model.

•	Columns EIN and NAME have been removed from the input data. 

Furthermore, the categorical variables were encoded, split them inot training and testing datasets and applied standardization to the features.

### Compiling, Training, and Evaluating the Model
The input data has 43 features and 25,724 samples.

•	This deep-learning neural network model is selected because it provides the highest accuracy of 73%, it is slight under what we expected. It comprised of two hidden layers with 80 and 50 neurons, as well as with a ReLU activaton function and an output binary classification,Sigmoid.

•	Apply the optimizer adam and the loss function binary_crossetntropy to compile.

•	With the parameters above the accuracy remained well under 75%. However, it actually reached to exactly 75% when it hits at Epoch 88. 

![image](https://user-images.githubusercontent.com/82733723/132998095-e77e1a20-5237-4af1-b353-3d08ce2cce31.png)  

•	Attempted to increase the accuracy the number of neurons, layers and tried a different activation function (tanh), however none of these seemed to significantly improve the models performance.

# Summary
Overall, the deep learning neural network model did not perform the 75% target but close. As a potential improvement we could adapt a supervised manchinie learning model,  such as the Random Forest Classifier be used to combine a multitude of decision tress to generate a classified output. In that case, we could be able to evaluate its performance against the deep learning model. 




