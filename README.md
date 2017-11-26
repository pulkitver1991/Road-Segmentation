# Road-Segmentation
Code for SMAI Project on Road Segmentation with different Classifiers.

Uploading still in progress


## Dependencies :
```
--- [Python2] 
--- [Sklearn]
--- [Skimage]
--- [Numpy] 
--- [Glob]
```

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
		Retrieve kitti data url [here](http://www.cvlibs.net/download.php?file=data_road.zip)


	* vgg16 : vgg pretrained model,
		[link to download]() 

# Running the SuperPix Code


