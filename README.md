# cardiovascular_dieases_classification
In this project I will use a dataset from Kaggle to predict the survival of patients with heart failure from serum creatine and ejection fraction, and other factors such as age, anemia, diabetes, etc

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Heart failure is a common event caused by CVDs, and this dataset contains 12 features that can be used to predict mortality by heart failure.

Most cardiovascular diseases can be prevented by addressing behavioral risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity, and harmful alcohol use using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidemia, or already established disease) need early detection and management wherein a machine learning model can be of great help.

The model used was a keras sequential with one hidden layer with 12 nuerons and a rectified linear activation function. The output layer at two neurons in line with the number of classifications and using ghe softmax activation fucntion. 

The model was compiled using an adam optimizer.

The results from the model was a F1 score of 0.74.
