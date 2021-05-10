# Grocery Store Dataset

This repository contains the dataset of natural images of grocery items. All natural images was taken with a smartphone camera in different grocery stores. We ended up with 5125 natural images from 81 different classes of fruits, vegetables, and carton items (e.g. juice, milk, yoghurt). The 81 classes are divided into 42 coarse-grained classes, where e.g. the fine-grained classes 'Royal Gala' and 'Granny Smith' belong to the same coarse-grained class 'Apple'. For each fine-grained class, we have downloaded an iconic image and a product description of the item, where some samples of these can be seen on this page below. The dataset was presented in the paper ["A Hierarchical Grocery Store Image Dataset with Visual and Semantic Labels"](https://arxiv.org/pdf/1901.00711.pdf), which appeared at WACV 2019.

## How to use the dataset

The files **train.txt**, **val.txt** and **test.txt** in the folder **dataset** includes the paths to the images in the training, validation and test set respectively. Each row in these two files consists of the path to an image and its fine-grained label followed by its coarse-grained label, where both labels are represented as integers. 

The 81 fine-grained classes and their coarse-grained classes can be found in **classes.csv** in the folder **dataset**. The classes corresponding label (an integer) is also included in addition to the paths to their iconic image and the product description. 

Feel free to download the dataset and apply it to your model. When time allows, I will upload code that is related to the paper above, such that the results in the paper can be reproduced.  

## Samples of natural images

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

## Samples of iconic images


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

## Samples of product descriptions

**Granny Smith:** Granny Smith is a green apple with white, firm pulp and a clear acidity in the flavor.

**Red Bell Pepper:** The red peppers are much sweeter than the green ones. It also contains more vitamins and antioxidants than the green. Peppers are good to eat raw in salads and as garnish, but are also good to fry, stew or gratinate, for example. with filling. Paprika also fits well in pots, gratins and pies.

**Bravo Apple Juice:** Ready to drink apple juice from concentrate. Fresh and sour taste. Fits the breakfast table, as quencher and meal drink.

## Updates
* 2019-11-07: Added validation set with 292 natural images from 59 classes.

## Citation
If you use this dataset for your research, please cite our [paper](https://arxiv.org/abs/1901.00711):

```
@inproceedings{klasson2019hierarchical,
  title={A Hierarchical Grocery Store Image Dataset with Visual and Semantic Labels},
  author={Klasson, Marcus and Zhang, Cheng and Kjellstr{\"o}m, Hedvig},
  booktitle={IEEE Winter Conference on Applications of Computer Vision (WACV)},
  year={2019}
}
```

## Acknowledgement
This research was funded by [Stiftelsen Promobilia](https://www.promobilia.se/) in Stockholm, Sweden.
