# project2-teamLAN
## Repository Contents 

## SRC
### Installing/Building the Code
Our approach will be a Convolutional neural network algorithm (CNN). To build the code, we're primarily utilizing the Keras API running on TensorFlow. 

The following packages will need to be installed in order to build the code: keras, tensorflow, plotly, htmltools, caret, NbClust, and dplyr.

### Code Usage


## Data
### Data Dictionary
| Column | Data Type | Description |
| --- | --- | --- |
| nonDemented | Image | MRI scan presents no signs of dementia |
| veryMildDemented | Image | MRI scan presents very mild signs of dementia |
| mildDemented | Image | MRI scan presents mild signs of dementia |
| moderateDemented | Image | MRI scan presents moderate signs of dementia (the most extreme) |

### Link to Data
[Data](https://www.kaggle.com/datasets/shahidzikria/alz-dataset) 

### Notes about Data
The data is composed of MRI scan images in JPEG format. The code found in the SRC file develops separate datasets to both train and test the convolutional neural network. The images belonging to the dataset categories are assigned a corresponding number label(nonDemented-0, veryMildDemented-1, mildDemented-2, and moderateDemented-3). 

## Figures 

| Figure | Image | Description|
| --- | --- | --- |


## References
[TensorFlow Image Classification](https://www.tensorflow.org/tutorials/images/classification)
[TensorFlow for R: Basic Image Classification](https://tensorflow.rstudio.com/tutorials/keras/classification)  
[CNN Tutorial](https://www.simplilearn.com/tutorials/deep-learning-tutorial/convolutional-neural-network) 

