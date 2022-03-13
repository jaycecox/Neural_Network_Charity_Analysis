# Neural_Network_Charity_Analysis
## Purpose:

Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results:


1.	What variable(s) are considered the target(s) for your model?

“Is_Successful” is the target of the model.

2.	What variable(s) are considered to be the features for your model?
The features of the model are :

![Features](https://user-images.githubusercontent.com/92542382/158071745-3c280bf2-738e-4741-8929-2a0647fea6e0.PNG)


3.	What variable(s) are neither targets nor features, and should be removed from the input?

Removed from the input:

![removed1](https://user-images.githubusercontent.com/92542382/158071858-583bbcbb-076a-4cf9-9072-46359e272bb9.PNG)

![removed2](https://user-images.githubusercontent.com/92542382/158071863-f6d95585-831c-4724-a697-9f98132f4560.PNG)

4.	How many neurons, layers, and activation functions did you select for your neural network model, and why?


![Neurons, Layers, Activation](https://user-images.githubusercontent.com/92542382/158071949-cee9f2c9-11a9-4957-9a0d-87c6a66f9603.PNG)


It is best practice to have at least 3 times the neurons than the number of inputs. I used 3 layers because we had more inputs to process.

5.  Were you able to achieve the target model performance?

Yes

![accuracy](https://user-images.githubusercontent.com/92542382/158072168-ec3af8d4-eec0-43ce-a897-4da40f53d1ed.PNG)

6.  What steps did you take to try and increase model performance?

Increase the number of inputs by keeping the column "NAME", binning the "NAME" values, and encoding them. 

![names binning](https://user-images.githubusercontent.com/92542382/158072260-4f6d2784-0554-4fb5-9885-a97c64ac17ba.PNG)

![encoding names](https://user-images.githubusercontent.com/92542382/158072293-4d495cbf-1fd2-4444-8e0c-49bd651d9dec.PNG)

Also increased the neurons from 80/50 and 2 layers:

![Neurons, Layers, Activation](https://user-images.githubusercontent.com/92542382/158072423-9d232aa2-3f8a-4deb-b6ef-96ba2e593f2c.PNG)

## Summary:

By increasing the number of inputs, the optimized deep learning model had more to learn from in order to make a more accurate decision. The acccuracy score was .789. A Random Forrest Classifer could have also been used as it can also easily handle outliers and nonlinear data. The number of estimators and tree depth can be increased with a Random Forrest Classifier to mimic the neurons and layers of a Neural Network. 




