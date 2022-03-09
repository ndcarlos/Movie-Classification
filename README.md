# Movie-Classification

I worked on this project with a partner in Data 8 at UC Berkeley.

Primary emphasis was to build a k-nearest-neighbors classifier and test the classifier on data.

--Part 1--

The first section required some exploratory data analysis with linear regression, familiarization with word stemming, and lastly splitting the dataset into a test set and training set for the classifier.  This process involved getting a grasp on how the data was structured in order to conclude appropriate methods to conduct our analysis.

--Part 2--

The next step was establishing our Euclidean distance function to evaluating nearest neighbors and running through some test examples to confirm its functionality.

--Part 3--

Now we extended our Euclidean distance function in order to take on two feature arrays of distance n. Starting with analyzing the word frequency graph for 'comedy' and 'thriller' movie genres and the properties of words in relation to their positioning on the graph.  After testing our intuition and creating our own chosen features array, we then computed a 7-nearest-neighbors classification which guessed the genre of the first movie in our test set based upon the 7 nearest neighbors  within our training set. Once we completed this process, we generated a single classifier function which encapsulated the entire process of classification.

Lastly, we made a new classification function which used our chosen features array as well as a 15-nearest-neighbors approximation and evaluate the accuracy to find the proportion correct to be 0.76.

--Part 4--

The project concluded with creating a new classifier to find the genre of movies and using a new features array with only 5 features. In our attempt of trying to choose polarized features which we had hoped would have little overlap between genres, our new classifier was not as accurate as our first, evaluating a proportion of 0.5945 correctly.
