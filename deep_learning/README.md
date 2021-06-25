# Deep Learning in PAMGuard

## Introduction
The continued increase in the storage capacity and battery life of acoustic recorders is allowing industry and academia to collect passive acoustic monitoring (PAM) data over ever larger spatial and temporal scales. With this glut of new data comes a problem - what do we do with all the hugely complex data that is collected by acoustic recorders? How do we accurately extract the already variable vocalisations of our target species within the dynamic and highly variable soundscapes? In the past, manual or semi-manual validation of data might have been an option (humans are still the best at pattern recognition) but with such large quantities of data this is no longer feasible. We need accurate automated algorithms but over the past decades developing such algorithms which are applicable to a wide range of environments, species and soundscape contexts has proven to be extremely difficult...

Deep learning is a subset of machine learning which uses artificial neural networks to train highly accurate classifiers. Deep learning is a popular buzzword today and it has real benefits for acoustics compared to previous machine learning methods. Deep learning classifiers are scalable (i.e. they increases in accuracy with the more training data you feed them) and it automatically extracts features from input data (sort of). This makes deep learning classifiers more accurate than previous machine learning methods and provides us with powerful, deployable and generic methods of building highly accurate acoustic classifiers, enabling large-scale PAM studies. However, whilst a huge code ecosystem exists around deep learning technologies there are still significant technical barriers in deploying deep learning models on acoustic data. This is where PAMGuard comes in. 

PAMGuard's deep learning module can import many different types of deep learning model and this tutorial provides two examples; one for right whales using a deep learning classifier developed by [Shiu et al (2020)](https://www.nature.com/articles/s41598-020-57549-y) and another in which a model trained using the [AnimalSpot](https://github.com/ChristianBergler/ANIMAL-SPOT) framework is used to classify Danish bat species. 

## Tutorial
The full tutorial is located in the [Deep learning in PAMGuard.pdf](Deep learning in PAMGuard.pdf) file. 

## Installatioon
The deep learning module will be available as a core module from PAMGuard 2.01.06 onwards. This can be downloaded from the [PAMGuard website](www.pamguard.org).

## Other resources
The tutorial takes users through the various features of the deep learning module, however, the general help files for the module are [here](https://github.com/macster110/PAMGuard_DeepLearningSegmenter/blob/master/deep_learning_help.md) for reference. These can also be accessed within PAMGuard. 
