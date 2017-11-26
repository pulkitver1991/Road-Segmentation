# Road-Segmentation
Code for SMAI Project on Road Segmentation with different Classifiers.

Uploading still in progress


## Dependencies :

* Python2
* Sklearn
* Skimage
* Numpy 
* Glob


## Directory Structure for the code 
```
Road-Segmentation/
|
|--- datasets/
|    |
|    |--- data_road
|    |--- vgg
|
|--- NN_VGG/
|    |
|    |--- Output/
|    |--- nn_vgg.py
|    
|--- SUPERPIX/
|    |
|    |--- main.py
|    |--- test_data.pkl
|    |--- train_data.pkl
|    |--- test_label.pkl
|    |--- train_label.pkl
|    |--- nb_model.pkl
|    
|--- PIX/
|    |
|    |--- main.py
|    |--- test_data.pkl
|    |--- train_data.pkl
|    |--- test_label.pkl
|    |--- train_label.pkl
|    |--- nb_model.pkl
|    
|--- README.md

```

In the datasets, there are two data files present

* data_road : containing the kitti dataset.
* vgg16 : vgg pretrained model

## Setup

1. Clone this repository: `git clone https://github.com/pulkitver1991/Road-Segmentation.git`
2. [Optional] Download Kitti Road Data:
    1. Retrieve kitti data url here: [http://www.cvlibs.net/download.php?file=data_road.zip](http://www.cvlibs.net/download.php?file=data_road.zip)
    2. Download VGG16 Model
    3. Call `python main.py`

## Running the SUPERPIX Code

* The training and testing vector is already created, and is provided in the directory
* If you want to create vector again, set the variable *create_vectors_again* high
* Naive bayes model is already learnt is already provided and be used directly
* To fit a model again, set the variable *start_training_model* high
* Select the Classifier using *select_classifier*
* The available classifiers are : 

	```
	--- Naive Bayes (nb)
	--- SVM (svm)
	--- Random Forest (rf)
	--- KNN (knn)
	```
* The result of the segmented images is saved in *SegmentedImages* Folder

* Segmented Results:

<img src="/SUPERPIX/Screenshots/img2.png" width="300"> <img src="/SUPERPIX/Screenshots/img4.png" width="300"> 

<img src="/SUPERPIX/Screenshots/img1.png" width="300"> <img src="/SUPERPIX/Screenshots/img3.png" width="300"> 



## Running the PIX Code


