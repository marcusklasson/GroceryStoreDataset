# Grocery Store Dataset

This repository contains the dataset of natural images of grocery items. All natural images was taken with a smartphone camera in different grocery stores. The dataset was presented in the paper "A Hierarchical Grocery Store Image Dataset with Visual and Semantic Labels", which will appear at WACV 2019.

The files **train.txt** and **test.txt** in the folder **dataset** includes the paths to the images in the training and test set respectively. Each row in these two files consists of the path to an image and its fine-grained label followed by its coarse-grained label, where both labels are represented as integers. 

The 81 fine-grained classes and their coarse-grained classes can be found in **classes.csv** in the folder **dataset**. The classes corresponding label (an integer) is also included in addition to the paths to their iconic image and the product description. 

Feel free to download the dataset and apply it to your model. When time allows, I will upload code that is related to the paper above, such that the results in the paper can be reproduced.  

### Samples of natural images

<p align="center">
  <img src="/sample_images/natural/Granny-Smith.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Pink-Lady.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Lemon.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Banana.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Vine-Tomato.jpg" width="150" title="hover text">
</p>
<p align="center">
  <img src="/sample_images/natural/Yellow-Onion.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Green-Bell-Pepper.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Arla-Standard-Milk.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Oatly-Natural-Oatghurt.jpg" width="150" title="hover text">
  <img src="/sample_images/natural/Alpro-Fresh-Soy-Milk.jpg" width="150" title="hover text">
</p>

### Samples of iconic images


<p align="center">
  <img src="/sample_images/iconic/Granny-Smith_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Pink-Lady_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Lemon_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Banana_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Vine-Tomato_Iconic.jpg" width="150" title="hover text">
</p>
<p align="center">
  <img src="/sample_images/iconic/Yellow-Onion_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Green-Bell-Pepper_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Arla-Standard-Milk_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Oatly-Natural-Oatghurt_Iconic.jpg" width="150" title="hover text">
  <img src="/sample_images/iconic/Alpro-Fresh-Soy-Milk_Iconic.jpg" width="150" title="hover text">
</p>

### Samples of product descriptions

**Granny Smith:** Granny Smith is a green apple with white, firm pulp and a clear acidity in the flavor.


### To do:

* Add link to paper.
* Upload code related to the paper.
* Translate all txt files for packages with information about ingredients and nutrition values. Currently, all items until Arla Standard milk have been translated.

