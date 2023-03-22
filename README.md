Recommendation system
This project is all about recommendation system. Recommendation systems are built to predict what users might like, especially when there are lots of choices available. They can explicitly offer those recommendations to users or they might work behind the scenes to choose which content to surface without giving the user a choice. A book recommendation system is designed to recommend books of interest to the buyer. Our first recommender is popularity based where we have most popular books, Author and Publisher. The recommendation was built using different algorithms such as Collaborative filtering-based recommendation, User-based filtering, Item based filtering, Model Based Collaborative Filtering Recommender. SVD was used in Model based collaborative filtering.
Singular Value Decomposition (SVD) is a powerful matrix factorization technique used in many applications, including recommendation systems. In recommendation systems, SVD can be used to make personalized recommendations by predicting the ratings that a user would give to items that they have not yet rated.

The basic idea of using SVD in recommendation systems is to represent the ratings matrix as the product of three matrices: U, S, and V. The U matrix represents the user's preferences, the S matrix contains singular values, which represent the importance of the latent features, and the V matrix represents the item's characteristics.

The SVD technique can be used to identify latent features that are not explicitly represented in the data, but that can help to explain the observed patterns in the data. By identifying these latent features, SVD can provide a more accurate representation of the underlying structure of the data and make better recommendations.

The use of SVD in recommendation systems involves the following steps:

Construct a ratings matrix, where each row represents a user, each column represents an item, and each cell represents the user's rating of the item.

Apply SVD to the ratings matrix to obtain the U, S, and V matrices.

Calculate the predicted ratings for each user-item combination by multiplying the corresponding rows and columns of the U, S, and V matrices.

Sort the predicted ratings and recommend the items with the highest predicted ratings to the user.

One of the advantages of SVD-based recommendation systems is that they can handle sparse and missing data, which is common in real-world datasets. SVD can also be used in combination with other techniques, such as collaborative filtering and content-based filtering, to further improve the accuracy of recommendations.
