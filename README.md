# Backprop to image for saliency map visualization and GradCAM implementation

We visualize saliency map from a pretrained VGG19 model of two images using the simple gradient method. 

![Dog](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/resize_input.jpg)     ![Saliency map](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/input_salmap.JPG) 

![Dog](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/resize_cat_dog.png)     ![Saliency map](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/catdog_salmap.PNG) 

A curious question, what makes the network think that image label is a dog or a cat?? GradCAM is a visualization technique for deep learning networks to visualize what the network looks for in an image when classifying a particular class label.

![Img](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/cat_dog.png)     ![Dog](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/gradcam_dog.png)   ![Cat](https://github.com/manasmacherla/Visualization-of-gradients/blob/master/gradcam_tigercat.png)   

For more information, please go through the paper: https://arxiv.org/pdf/1610.02391v1.pdf
The paper authors' torch implementation: https://github.com/ramprs/grad-cam


Method for usage will be updated soon. :)