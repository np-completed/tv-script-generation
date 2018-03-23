# TV Script Generation
In this project, I generate a [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV script using a recursive neural network (RNN).  The model uses part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data)  scripts from 27 seasons.  The RNN generates a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).

## Get the Data
The data is available at links posted above.  I use a subset of the original dataset.  It consists of only the scenes in Moe's Tavern.  This doesn't include other versions of the tavern, like "Moe's Cavern", "Flaming Moe's", "Uncle Moe's Family Feed-Bag", etc..

## Software Suite

* TensorFlow  
* Keras  
* Python 3.6

For more detailed list of python packages the requirements file is accurate (ha ha maybe, good luck). TensorFlow is a new technology so expect changes regularly, i.e. every week this model will need some updates. To avoid problems and show repeatibility of results I used a very stable version of TensorFlow and Keras. This model is not very good but provides the essential techniques for generating a tv script.  Any queries seeking detailed instructions for reproduceabilty precision will be discarded and immediately passed around for a laugh. 



