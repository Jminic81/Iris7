# Learning Exercise:  Visualization of the Iris Dataset

This readme explains the origin and significance of the "Iris" dataset and why it is so popular for data visualization learning exercises.  The Jupyter Notebook file defines required libraries and explains code used to generate selected visualizations from the Kaggle kernel (Ref. 1).   

Although the readme typically is focused on software installation, examples, tests, etc. (see template example, Ref 2): , I've included more backstory for the dataset because this is the first learning exercise and we aren't yet creating original code.         

"Iris" is one of the most popular datasets for statistical analysis, data visualization and machine learning.  The data are real, clean, and sample size is small enough to be manageable but large enough to give depth to analyses.

The dataset first appeared in a 1936 paper by British statistician and geneticist Sir Ronald Aylmer Fisher; "_The Use of Multiple Measurements in Taxonomic Problems_."  For three different species of iris plants, 50 measurements were recorded for four flower attributes; sepal length, sepal width, petal length and petal width. Figure 1 helps distinguish between sepal and petal and shows how the measurements were taken. 

**Figure 1:  Iris Measurements** (Ref. 3)

![alt text](https://github.com/Jminic81/iris7/blob/master/picirismeas.png)                           

Why do this work at all?  Because classification of living organisms yields a way to identify new species, and allow scientists everywhere to communicate, identify relationships, and make advancements in many different areas.  For example, studying constrained movement in certain populations of the roundworm with genus and species name “_Caenorhabditis elegans_” (or _C. elegans_) led to understanding and better treating a very similar expression in humans; muscular distrophy.

In 1758, Carl Linneaus devised the system of classification (Figure 2) that is still used today.  There are millions of different types of living organisms on the planet and while each falls into a specific subset of the seven categories, all organisms are referred to by a unique genus and species name (we are “Homo sapiens or “H. sapiens”).  The Iris dataset is focused on three different species of the genus “Iris”.  Standard naming convention is to use the first letter of the genus name capitalized, and the species name in all lower case, and all in italics; hence the references to “_I. setosa_”, “_I. versicolor_”, and “_I. virginica_” in the Iris dataset.  

**Figure 2:  Classification System** (Ref. 4)  

![alt text](https://github.com/Jminic81/iris7/blob/master/picclasshierarchy.jpeg)                  

Fisher’s work with Iris plants is considered significant due the marked advancement in scientific method that would be leveraged by many to solve similar classification problems.  He is the originator of analysis or variance (ANOVA), a statistical method allowing multiple variables in an experiment. For “iris”, the data require further treatment than simply using average and standard deviation to declare statistical significance.  The most problematic area is highlighted in bold in the table below:

**Table 1:  Iris.csv File, Column "SepalLengthCm"**

|                   | Average  |  Std Dev | 
|-------------------|:--------:|:--------:|
| _I. setosa_       |   3.4    |    0.4   |
| _I. versicolor_   |   2.8    |    0.3   |
| _I. virginica_    |   3.0    |    0.3   | 

Figure 3 below also illustrates the need for alternate analysis and visualization as one species is clearly distinct from the other two which are somewhat co-mingled.  While it may have been tempting to find more attributes to measure to help differentiate between _I. versicolor_ and _I. virginica_, Fisher applied original statistical analysis to extract the answer from the existing dataset.  

**Figure 3:  "Iris" Dot Plot** (Ref. 5)     

![alt text](https://github.com/Jminic81/iris7/blob/master/picscatterplot.png)    

The Jupyter Notebook file explores codes used by the Kaggle kernel creator (Ref. 1) to show different views of the dataset.  The learning exercise included a few "Tweaks" of some of the analyses.     

**References**                                
1.  Kaggle kernel   https://www.kaggle.com/benhamner/python-data-visualizations 
2.  Readme template https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md)
3.  Figure 1        http://suruchifialoke.com/2016-10-13-machine-learning-tutorial-iris-classification/
4.  Figure 2        https://www.britannica.com/science/taxonomy
5.  Figure 3        https://www.kaggle.com/benhamner/python-data-visualizations (code input row 5)
