# Intel-image-classification-Hyperparametrs-Analysis-
The goal of this project is studying different neural networks using Tensorflow and Keras for image classification. The models are MLP,CNN, and ResNet-50. The table below shows different parameters that we tried in the MLP model. The report file contains classification metrics of all implemented models. 

![Screen Shot 2022-06-04 at 11 24 29 AM](https://user-images.githubusercontent.com/70451567/172011809-e823dd88-9495-416d-a4d0-25ff190ea56d.png)


**Dataset**

Intel image dataset contains six different files which are the labels(classes) for the images. These labels are Buildings, Forest, Glacier, Mountain, Street, and Sea. For preprocessing, we used OpenCV and fed it to our models. 

<img width="386" alt="Picture2" src="https://user-images.githubusercontent.com/70451567/172011473-4964adc9-0142-4926-8228-23f32ec35009.png">


**Results**

Finally, after comparing different implemented models in previous sections we
have observed:

• Increasing number of hidden layers can increase the efficiency of the
model, but we must also prevent overfitting.

• Decreasing and increasing learning rate may decrease the accuracy of
the model, so it is suggested to find the best one.

• Adam optimizer works better than SGD in this study.

• If the validation accuracy does not follow training accuracy, you can
increase validation split proportion.

• Dropout is more suitable than L1 and L2 regularization in this neural
network.

• If during training a model, the growth of training and test accuracy is
stopped, using a more complex model can help.


• If the training accuracy is high, using a more complex method does not
improve the result, but causes high overfitting.

