# SAEON - Identifying marine invertebrates

### Objective

The objective of the challenge is to correctly classify images of deep sea invertebrates.. 

Challenge: https://zindi.africa/hackathons/umojahack-1-saeon-identifying-marine-invertebrates/data

Ended up in position 15 on leaderboard.

### Metric for success
- Log loss

### Understanding the context

The images are of various species of marine invertebrates found off of the coast of South Africa. Further details of the species can be found in the linked field guide.

There are 3111 images in the train set, 1423 images in the test set and 137 different species. The test set has the same class distribution as the training set

### Approach

CRISP- DM methodology will be applied. Below steps will be undertaken to create the classifer.

- Business understanding - understanding the background about deep sea marine invertebrates
- Data understanding - Explore the images
- Exploratory data analysis - check the distribution
- Feature engineering - data augmentation
- Data modelling - Baseline model, Transfer learning and data augmentation
- Model interpretation - Interpret based on model output
- Upload to Zindi

### Enhancements

- Sampling using random.random() not efficient. Consider using good old train_test_split

- Perform KFold cross validation. 

- Ensembling different models
 
- Optimize on image augmentation.

- Optimize model using other transfer learning techniques. VGG was better than Resnet50 but further checks required.

- Oversampling/downsampling required?
