
In this project, a Deep Neural Network is evaluated for the task of Object
Detection using low luminance dataset. Existing techniques uses a deep
learning architecture to detect multiples objects during night time. In
this work, a existing protocol for object detection is followed and a DNN
is evaluated using Exclusively Dark Image dataset. Since the images were
not annotated in the Ex-Dark dataset, a custom dataset is created using
this dataset. The training images in the customized dataset are annotated
using LabelImg tool. The model is trained and tested using training and
testing dataset respectively. The result for this project demonstrates that
the losses occuring due to low brightness are minimalized. For the evalu-
ation of this model IOU metric is used and different IOU thresholds are
compared to calculate the Average Precision.
