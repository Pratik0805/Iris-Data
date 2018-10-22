# Iris-Data
Data Science Projects

# import load_iris function from datasets
from sklearn.datasets import load_iris

# save object containing iris dataset and its attributes
iris = load_iris()
type(iris)

# print the iris data
print(iris.data)

# print the names of the four features
print(iris.feature_names)

# print integers representing the species of each observation
print(iris.target)
# print the encoding scheme for species: 0 = setosa, 1 = versicolor, 2 = virginica
print(iris.target_names)

# check the types of the features
print(type(iris.data))
print(type(iris.target))

# check the shape of the features 
print(iris.data.shape)

# check the shape of the response
print(iris.target.shape)

# store feature in "X"
X = iris.data

# store response in "y"
y = iris.target

