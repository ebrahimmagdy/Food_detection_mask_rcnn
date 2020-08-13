# Food_detection_mask_rcnn
<h3>This is an implementation of how to make instance segmentation on 31 category of food

<h3>Useful ressources</h3>
 https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46
 https://github.com/matterport/Mask_RCNN

<h3>Prepare the dataset</h3>
 we selected 31 category fome Food-101 dataset
        ["apple_pie", "baklava", "beef_tartare", "beet_salad", "bibimbap", "bread_pudding"
        , "breakfast_burrito", "cannoli", "cheesecake", "chicken_wings", "chocolate_cake"
        , "cup_cakes", "deviled_eggs", "donuts", "dumplings", "falafel", "french_fries"
        , "fried_rice", "garlic_bread", "hamburger", "hot_dog", "ice_cream", "peking_duck"
        , "pho", "pizza", "ramen", "samosa", "steak", "sushi", "tiramisu", "waffles"]
 make the annotation file to each image in each class we choose 100 image per class
 we used the labelimg to make the annotations in xml formate

<h3>Impelementation</h3>
 clone the reposetory  https://github.com/matterport/Mask_RCNN
 load the pretrained model you can use the pretrained model that trained on coco dataset or the model trained on imagenet dataset,
in mycase i have my model that trained on the 31 class we worked on from Food-101 dataset
 overite the confg class to make your configuration
 overite utils.dataset to prepare your dataset and split data to train and test
 train your model
 test your model
  

