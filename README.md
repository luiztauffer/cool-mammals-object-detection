# The Cool Mammals Project - Object Detection
This is the repository for the object detection part of the Cool Mammals project. It contains a couple of useful files for data preparation, model training and inference.
A series of blog posts detailing it can be found at [Guacamole Data Science](https://luiztauffer.github.io/guacamole-data-science/posts/2019-03-17-cool-mammals-project/).

Datasets and trained models are usually large, so I decided to not upload them. If you're finding it difficult to understand the folder structure and the files that should be present at each, please check the folders above and the examples I give. 

After a model is trained and the frozen graph is produced, the folder structure should look like this:

```
.
├── data
├── images
    ├── test
    ├── train
├── pre_trained_model
├── trained-inference-graphs
    ├── exported_graph_1
    ├── exported_graph_2
├── training
(other files)
```

Here's some nice examples of our cool mammals detection into action:

![ex1](example_result_1.jpg)

![ex2](example_result_2.jpg)

![ex3](example_result_3.jpg)
