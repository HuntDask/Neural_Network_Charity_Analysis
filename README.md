# Neural_Network_Charity_Analysis
 
## Overview of the project
In our project, we are creating neural networks and deep learning models to collect data about charities. We are asked to analyze and the impact of each charity donation and predict which charities are best to donate towards. Vex, our company, is in charge of data collection and analysis for the entire organization. Many donations are not as impactful as people think, and many orgnaizations take some percentage of the money that is donated. The company ALphapbet soup has asked us at Vex to create a mathmatical data driven solution to determine and predict the most loyal and faithful charities that the money could go towards. We are desigining and training modules using he python library and use machine learning as well to help create a robust neural network to help determine our charity data set.

## Results

### Data Preprocessing
- For our targeted variables for the model, we are looking to see if the charity(target) is being labled as a succesfull target to invest in for the ALphabetSoup company. 
- IS_SUCCESSFUL is the feature variable for our model created.
- To improve our coding, we are probably able to remove the NAME and EIN columns due to the fact that they do not help in our accuracy results from our model created.

### Compiling, Traing, and Evaluating the Model
- for our neurons, layers and acivations functions, we decided to use different numbers per layer in our model. In our first layer, we had 110 neurons and moved to 80 neurons for layer 2. it was a diving by 2 each time for layers 3 and 4, going from 80 in layer 2 to 40 in layer 3 and 20 in layer 4 respectivelly. each of these neuron numbers were calcuated baed on the activation that it gave us for our model. 
<img width="906" alt="neuron layers functions" src="https://user-images.githubusercontent.com/107444840/204600247-1b52317a-45d0-42ae-8ace-8047fa81f156.png">

- We were not able to reach the 75% mark for the target in our model. The closest we were able to acheive from our analysis was at the 0.72373, or around 72% total accuracy.

- To increase our model performance, I tried to delte some of the random columns that wer not genrating any higher of an accuracy for us in our model such as STATUS column. These did not help in acheiving a higher accurancy, and we were able to see that from our results. To get our highest possible reuslts from our model, we had to examine the early layers and sigmoid actrivation at the following layers after in order to examine and analyze the best results possible. 

## Summary
The highest point of accuracy that we wre able to acheive in our AlphabetSoupCharity jupyter notebook model from the test data was at 0.72373, or about 72% accuracy with the correct layering and neurons respecitvelly. I beleive that we should try and use a different model to solve the classifation problem such as the random forest clssifier becuae it does not intend to use the outlying data as much as our model used in our analysis.
