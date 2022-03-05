Python Machine learning Iris flower data set

Iris flower data set:

From Wikipedia - The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced 
by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements 
in taxonomic problems as an example of linear discriminant analysis. It is sometimes called Anderson's Iris 
data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of 
three related species. Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, 
and picked on the same day and measured at the same time by the same person with the same apparatus"

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. 
Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other.


Basic - Iris flower data set

1-	Write a Python program to load the iris data from a given csv file into a dataframe and print the shape of the data, type of the data and first 3 rows.
2-	Write a Python program using Scikit-learn to print the keys, number of rows-columns, feature names and the description of the Iris data.

3-	Write a Python program to get the number of observations, missing values and nan values.

4-	Write a Python program to create a 2-D array with ones on the diagonal and zeros elsewhere. Now convert the NumPy array to a SciPy sparse matrix in CSR format.         (In numerical analysis and scientific computing, a sparse matrix or sparse array is a matrix in which most of the elements are zero. By contrast, if most of the elements are nonzero, then the matrix is considered dense. The number of zero-valued elements divided by the total number of elements (e.g., m x n for an m x n matrix) is called the sparsity of the matrix (which is equal to 1 minus the density of the matrix). Using those definitions, a matrix will be sparse when its sparsity is greater than 0.5.)

5-	Write a Python program to view basic statistical details like percentile, mean, std etc. of iris data.

6-	Write a Python program to get observations of each species (setosa, versicolor, virginica) from iris data

7-	Write a Python program to access first four cells from a given Dataframe using the index and column labels. Call iris.csv to create the Dataframe






Visualization - Iris flower data set

1-	Write a Python program to create a plot to get a general Statistics of Iris data.

2-	Write a Python program to create a Bar plot to get the frequency of the three species of the Iris data.

3-	Write a Python program to create a Pie plot to get the frequency of the three species of the Iris data. 

4-	Write a Python program to create a graph to find relationship between the sepal length and width.

5-	Write a Python program to create a graph to find relationship between the petal length and width.

6-	Write a Python program to create a graph to see how the length and width of SepalLength, SepalWidth, PetalLength, PetalWidth are distributed.  


7-	Write a Python program to create a joinplot to describe individual distributions on the same plot between Sepal length and Sepal width  Note: joinplot - Draw a plot of two variables with bivariate and univariate graphs.

8-	Write a Python program to create a joinplot using "hexbin" to describe individual distributions on the same plot between Sepal length and Sepal width 
Note:The bivariate analogue of a histogram is known as a "hexbin" plot, because it shows the counts of observations that fall within hexagonal bins. This plot works best with relatively large datasets. It's available through the matplotlib plt.hexbin function and as a style in jointplot(). It looks best with a white background.

9-	Write a Python program to create a joinplot using "kde" to describe individual distributions on the same plot between Sepal length and Sepal width. 
Note: The kernel density estimation (kde) procedure visualize a bivariate distribution. In seaborn, this kind of plot is shown with a contour plot and is available as a style in jointplot().

10-	Write a Python program to create a joinplot and add regression and kernel density fits using "reg" to describe individual distributions on the same plot between Sepal length and Sepal width.

11-	Write a Python program to draw a scatterplot, then add a joint density estimate to describe individual distributions on the same plot between Sepal length and Sepal width.
 
12-	Write a Python program to create a joinplot using "kde" to describe individual distributions on the same plot between Sepal length and Sepal width and use '+' sign as marker.  
Note: The kernel density estimation (kde) procedure visualize a bivariate distribution. In seaborn, this kind of plot is shown with a contour plot and is available as a style in jointplot().

13-	Write a Python program to create a pairplot of the iris data set and check which flower species seems to be the most separable.

14-	Write a Python program using seaborn to Create a kde (Kernel Density Estimate ) plot of sepal_length versus sepal width for setosa species of flower.

15-	Write a Python program using seaborn to Create a kde (Kernel Density Estimate ) plot of petal_length versus petal width for setosa species of flower. 

16-	Write a Python program using seaborne to create a kde (Kernel Density Estimate) plot of two shaded bivariate densities of Sepal Width and Sepal Length.

17-	Write a Python program to find the correlation between variables of iris data. Also create a hitmap using Seaborn to present their relations.

18-	Write a Python program to create a box plot (or box-and-whisker plot) which shows the distribution of quantitative data in a way that facilitates comparisons between variables or across levels of a categorical variable of iris dataset. Use seaborn.

19-	Write a Python program to create a Principal component analysis (PCA) of iris dataset.

Note: Principal component analysis (PCA) is a statistical procedure that uses an orthogonal transformation to convert a set of observations of possibly correlated variables (entities each of which takes on various numerical values) into a set of values of linearly uncorrelated variables called principal components. This transformation is defined in such a way that the first principal component has the largest possible variance (that is, accounts for as much of the variability in the data as possible), and each succeeding component in turn has the highest variance possible under the constraint that it is orthogonal to the preceding components. The resulting vectors (each being a linear combination of the variables and containing n observations) are an uncorrelated orthogonal basis set. PCA is sensitive to the relative scaling of the original variables. 

