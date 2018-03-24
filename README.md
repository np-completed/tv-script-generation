# TV Script Generation
In this project, I generate a [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV script using a recursive neural network (RNN).  The model uses part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data)  scripts from 27 seasons.  The RNN generates a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).

## Get the Data
The data is available at links posted above.  I use a subset of the original dataset.  It consists of only the scenes in Moe's Tavern.  This doesn't include other versions of the tavern, like "Moe's Cavern", "Flaming Moe's", "Uncle Moe's Family Feed-Bag", etc..

## Software Suite

* TensorFlow  
* Keras  
* Python 3.6

For more detailed list of python packages the requirements file is accurate (ha ha maybe, good luck). TensorFlow is a new technology so expect changes regularly, i.e. every week this model will need some updates. To avoid problems and show repeatibility of results I used a very stable version of TensorFlow and Keras. This model is not very good but provides the essential techniques for generating a tv script.  Any queries seeking detailed instructions for reproduceabilty precision will be discarded and immediately passed around for a laugh. 

## Getting Project Files

git clone https://github.com/udacity/deep-learning.git


Stay up to date with any changes we make by pulling the changes to your local repository with git pull.

source activate tf_tvScript		## Activate anaconda environment
jupyter notebook				## open jupyter notebook


## GitHub 
##
`echo "# tv-script-generation" >> README.md`  
`git init`
`touch .gitignore`
`git add -A`
`git commit -m "first commit"`

**Only need `remote add` for the first time connecting to git**   
`git remote add origin https://github.com/prfrl/tv-script-generation.git `

`git push -u origin master`

**Refresh .gitignore cache**  Do not forget period at end of cached.  
`git rm -r --cached .`


### Submitting Project to Udacity

Package the "dlnd_tv_script_generation.ipynb", "helper.py", "problem_unittests.py", and the HTML file into a zip archive, or push the files from your GitHub repo.
