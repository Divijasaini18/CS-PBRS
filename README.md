1. Name and title of the Project :

Computer Science / Programming Book Recommendation System


2. Statement about the Problem :

Today the amount of information in the internet grows very rapidly and people need some instrument to find and access appropriate information . One such tool is called recommendation system. A computer science / programming book recommendation system helps readers to find appropriate books related to computer science or programming. They can navigate quickly and receive necessary information. It helps to quickly access relevant book without searching the web manually.


3. Why the particular project is chosen?

The online recommendation system has become a trend. Now a days rather than going out and buying items for themselves, people choose to buy items online. Reason being, online recommendation provides an easier and quicker way to buy items. Moreover, transactions are also quick when it is done online. Recommendation systems are powerful new technology and it helps users to find items which they want to buy. A recommendation system is broadly used to recommend products to the end users that are most appropriate. Online book selling Web sites now-a-days are competing with each other by considering many attributes. A recommendation system is one of the strongest tools to increase profits and retaining buyer. The existing systems lead to extraction of irrelevant information and lead to lack of user satisfaction. Also, as the craze of Programming is increasing day by day, there are lot of books available online. Choosing a good book among those books could be a hectic task. The Computer Science / Programming Book Recommendation System (CS/PBRS) is based on combined features of content based filtering (CBF), collaborative filtering (CF) and association rule mining to produce efficient and effective recommendation. It recommends the book based on the buyer's interest in computer science field and hence, helps in buying a good book without much effort.

4. Objective and Scope of the Project :
The aim of this Book Recommendation System is to provide useful programming book recommendations to the user. The challenge with book recommendations is the vast amount of book titles available and the time investment for each of the books. Book recommenders are especially useful for the kind of readers that go into bookstores (physical or virtual) without a book title in mind. If a reader has rated highly “Core Java” it may not come as a surprise he/she will also like “Advance Java”. While the book recommendation system may provide a higher accuracy by predicting this title, it may not be very useful to the user of the system. Likewise, there is a trend for popular books to be recommended based on popularity. This can be seen in most large bookstores where the top-selling books are displayed in the front. These are sold the most, which then re-enforces the popularity and sales. Again, while the book recommendation engine may provide a higher accuracy by recommending “Clean Code”, it may not provide a rich insight to the user of the system. The aim of the book recommender is not to provide a high accuracy, instead, difficult to quantify insightful book recommendations. 


5. Hardware and Software to be used :

•	Hardware: 

        RAM: 8 GB DDR4 RAM

•	Software :

        IDE: PyCharm

        Libraries used:

o	Pandas
o	Numpy
o	Stopwords from nltk
o	Linear_kernel from sklearn
o	CountVectorizer from sklearn
o	TfidVectorizer from sklearn
o	RegexpTokenizer from nltk
o	Re
o	String
o	Random
o	Requests
o	BytesIO from io
o	Matplotlib.pyplot

          Data Collected From:  Kaggle

6.Testing Technologies Used:

Following testing technologies are used in the project:
Pearson’s R Coefficient: Pearson’s R correlation coefficient is used to measure the linear correlation between two variables, in this case, the ratings for two books.

K Nearest Neighbors: k-NN is a machine learning algorithm to find clusters of similar users based on common book ratings, and make predictions using the average rating of top k-nearest neighbors. 
For example, we first presented ratings in a matrix with the matrix having one row for each item (book) and one column for each user. We then find the k item that has the most similar user engagement vectors. Starting from the original data set, we looked at the popular books. In order to find out which books are popular, we combined books data with ratings data. We then grouped book titles and created a new column for total rating count. We combined the rating data with the total rating count data, this gives us exactly what we need to find out which books are popular and filter out lesser-known books.
We used unsupervised algorithms with sklearn.neighbors. The algorithm we used to compute the nearest neighbors is “brute”, and we specified “metric=cosine” so that the algorithm calculates the cosine similarity between rating vectors. Finally, we fit the model.
In this step, the kNN algorithm measures distance to determine the “closeness” of instances. It then classifies an instance by finding its nearest neighbors, and picks the most popular class among the neighbors.

Matrix Factorization: Matrix Factorization is simply a mathematical tool for playing around with matrices. The Matrix Factorization techniques are usually more effective, because they allow users to discover the latent (hidden) features underlying the interactions between users and items (books). 
We use singular value decomposition (SVD) — one of the Matrix Factorization models for identifying latent factors.

7.What contribution would the project  make :

This book recommender provides the user with an original, simple to use, book recommendation system emphasizing on interest book recommendations.
Datasets containing over ratings for 270 books with ratings and 270 different tags from over 5300 readers were used to build a recommendation engine that provides a user with a list of top 5 book recommendations.
In order to do this, the dataset was simplified, while minimizing information loss, by requesting the user to rate 60 carefully selected books identified through K-means clustering; comparing the user against 50 other similar readers that may yield highly rated books applying user-user collaborative filtering techniques; and carrying out a final classification to match the user-provided genres of interest with 39 options to choose from.
The recommendation engine provided a 12% which is good considering the stringent matching criteria applied to provide the user with a list of the user's most highly rated books from a possible number of 1000.
The proof of the book is in the reading. Reading is a very personal experience, and a user feedback will provide a better insight on the success of the recommendation engine than any statistical measures.




