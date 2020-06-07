Supervised Learning Project

Classification:

Classsifcation is an common machine learning problem where computer needed to separate objects into common groups. Say suppose you had
gone to a bar and bartender asked you to select alcohol variery like beer, wine ,whiskey, brandy based on color choices.

What an human will do will see the color of each color first and record as beer,whiskey,wine etc. Then bartender will do  a test and show
some bottle and asked which are type of alcoholic beverage. Huan will choosed based on his experience and tell which bottle is which is 
which alcoholic beverage.

Same computer will also do but to do it needed to first feeded with lots of data so that whner unknown data is presented it will choose 
the nearby answer as humans do.

**To perform classsification there are lots of alogithm present some famous are:**

    1. Logistic regression
    2. KNN- K- nearest neighbours
    3. SVM - Support vector machine
    4. Decision trees
    5. Random forest classifier
    
Here we will evaluate the KNN on iris dataset. Let understand KNN first:
    
The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.
    
    
Notice in the image above that most of the time, similar data points are close to each other. The KNN algorithm hinges on this assumption being true enough for the algorithm to be useful. KNN captures the idea of similarity (sometimes called distance, proximity, or closeness) with some mathematics we might have learned in our childhood— calculating the distance between points on a graph.

There are other ways of calculating distance, and one way might be preferable depending on the problem we are solving. However, the straight-line distance (also called the Euclidean distance) is a popular and familiar choice.

Source: https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761

Lets understand the IRIS dataset:
Source:

Creator:

R.A. Fisher

Donor:

Michael Marshall (MARSHALL%PLU '@' io.arc.nasa.gov)

Data Set Information:

This is perhaps the best known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. (See Duda & Hart, for example.) The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.

Predicted attribute: class of iris plant.

This is an exceedingly simple domain.

This data differs from the data presented in Fishers article (identified by Steve Chadwick, spchadwick '@' espeedaz.net ). The 35th sample should be: 4.9,3.1,1.5,0.2,"Iris-setosa" where the error is in the fourth feature. The 38th sample: 4.9,3.6,1.4,0.1,"Iris-setosa" where the errors are in the second and third features.

Attribute Information:

sepal length in cm
sepal width in cm
petal length in cm
petal width in cm
class: -- Iris Setosa -- Iris Versicolour -- Iris Virginica
Relevant Papers:

Fisher,R.A. "The use of multiple measurements in taxonomic problems" Annual Eugenics, 7, Part II, 179-188 (1936); also in "Contributions to Mathematical Statistics" (John Wiley, NY, 1950). [Web Link]

Duda,R.O., & Hart,P.E. (1973) Pattern Classification and Scene Analysis. (Q327.D83) John Wiley & Sons. ISBN 0-471-22361-1. See page 218. [Web Link]

Dasarathy, B.V. (1980) "Nosing Around the Neighborhood: A New System Structure and Classification Rule for Recognition in Partially Exposed Environments". IEEE Transactions on Pattern Analysis and Machine Intelligence, Vol. PAMI-2, No. 1, 67-71. [Web Link]

Gates, G.W. (1972) "The Reduced Nearest Neighbor Rule". IEEE Transactions on Information Theory, May 1972, 431-433. [Web Link]

See also: 1988 MLC Proceedings, 54-64.
