# fast-ai
This is the solution for [Dogs vs Cats competition in Kaggle](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition) instructed by **Jeremy Howard (fastai)** [video](https://www.youtube.com/watch?v=e3aM6XTekJc&t=5474s), [lecture note](http://wiki.fast.ai/index.php/Lesson_2_Notes), [Github](https://github.com/fastai/courses/blob/master/deeplearning1/nbs/dogs_cats_redux.ipynb)

This model takes advantage of [Transfer Learning](http://cs231n.github.io/transfer-learning/) by using pretrained VGG model with vgg16 class and it's run in Keras (Theano as backend).

**Directory structure**
```
fast-ai
│   README.md
|
|---utils
│   │   utils.py
|   |   vgg16.py
│   │   vgg16bn.py
|   |
│---lessons
|   
|---dogs_vs_cats:
|   |   data
|   |   intermediate
```

**Data source**
- [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats)
 + Create data path
 
     ```mkdir ./dogs_vs_cats/data```
 + Put train and test data to data path
 
