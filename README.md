## Pneumonia Detection from Chest X-Ray Images                                         

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Description
<pre>
1. Detected Pneumonia from Chest X-Ray images using Custom Deep Convololutional Neural Network and by retraining pretrained model “InceptionV3” with 5856 images of X-ray (1.15GB).
2. For retraining removed output layers, freezed first few layers and fine-tuned model for two new label classes (Pneumonia and Normal).
3. With Custom Deep Convololutional Neural Network attained testing accuracy 89.53% and loss 0.41.
</pre>



<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : InceptionV3 && Custom Deep Convolutional Neural Network
Optimizers              : Adam
Loss Function           : categorical_crossentropy

<b>For Custom Deep Convolutional Neural Network : </b>
<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 30
Training Time           : 2 Hours

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Testing</b>
Accuracy (F-1) Score    : 89.53%
Loss                    : 0.41
Precision               : 88.37%
Recall (Pneumonia)      : 95.48% (For positive class)
<!--Specificity             : -->
</pre>


<kbd>
<a href="https://i.imgur.com/km4MF3J.png"></a>
</kbd>



#### Tools / Libraries
<pre>
Languages               : Python
Tools/IDE               : Google Colab
Libraries               : Keras, TensorFlow, Inception, ImageNet
</pre>

