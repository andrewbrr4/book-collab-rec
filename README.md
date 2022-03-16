# book-collab-rec

Here we have created a recommendation system to predict how a user will rate a book. The source data is a list of ratings given by users to books they have read. We pivot the data to create a df of users and ratings, then apply a KNN model to predict how a user will rate an unseen book. To improve performance issues caused by data sparsity, we apply matrix factorization.
