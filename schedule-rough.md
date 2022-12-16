## Week1 : Intro,  refresher 

Activities:
download the palmer penguins data set and then compare the performance of:
 - k-Nearest Neighbours
 - Decision Tree Classifier
 - Random Forest
 - a multi-layer perceptron
 
You will need to think about: data normalisation, handling missing data, how you estimate classifier accuracy, how you select the hyper-parameters for different algorithms

Download the dataset penguins_size from https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data?resource=download&select=penguins_size.csv

This data has 344 records and seven features:
- Species (use this as the label to be predicted)
- Island
- culmen_length_mm
- culmen_depth_mm
- flipper_length_mm
- body_mass_g
- sex

Use the kaggle page, or the page created by the original authors (resource
here https://allisonhorst.github.io/palmerpenguins/articles/intro.html - in R)
to understand what the data is capturing.


## Week 2: Convolutional neural networks

### Keras/ tensorflow

### Motivation
- Old fashioned image processing via kernels
- Convolutional filters offer ways of (i) automating kernel choice,  
  (ii) building more complex  features(layers), 
  (iii) generalising over presene of artefacts anywhere in the image


### Practical activities - in groups of 3 exploring resources for basic Convnets of CIFAR10
1. Group spends five minutes finding a different notebook/explalantion then
- one person looks at tensorflow or keras documentation and examples
- second looks at Machine Learning mastery
- third looks at the other resource they identified
2. All of them run through their workbooks and note down:
- how easy to follow and self-contained was the explanation?
- what sort of accuracy were they getting?
- how was that accuracy merasured i.e. what metrics, train-test vs cross validation?
- did the resource provide useful pointers for more things to explore?

3. Group compares notes 
4. Class discussion

### Self-directed study: 
How do you decide when to stop training a CNN and how does keras support this?


## Week 2: Convnets and effects of uncertainty.

### Data augmentation,
what does keras support?
how do you decide what is valid?
what could you do yourself?

### practical activity

### class discussion
does data augmentation provide a away of addressing:
- ethical concerns about under-representation of certain groups
- safety concerns for example wrt autonomous vehicles

### self directed study
read paper on things like permutation testing to assess impact of protected characteristics
prepare 5 minute talk on an architecture for pre-trained images e.g. resnet, vgg, inception ...
focussing on what is the new idea e.g. modularisation?

## Week 3 Graph neural networks
(using Jun's CSRC talk slides)

## Week 4 Recurrent Neural Networks
 LSTM
 
 ### practical activities
 - build LSTM for time series data set
 - how do we deal with missing data?
 
 ## Week 5: Autoencoders
 
 ## Week 6 large pretrained language models
 
 ## Week 7 Deep reinforcement learning???
 --or have this is the coursework task??
 
 ## Week 8 Advances in optimisation metaheuristics 
 - noise
 - multi-objective optimisation
 
 ## Week9 Hybrids
 - Guest lecture from Larry on Surrogate assisted optimisation