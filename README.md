NEXTFLIX: Movie Recommendations Using MovieLens Dataset
-------------------------------------------------------

Dataset 
-------
MovieLens 1M dataset
1,000,209 anonymous ratings
3,900 movies
6,040 users who joined in the year 2000
Users File
UserID::Gender::Age::Occupation::Zip-code
Ratings file
UserID::MovieID::Rating::Timestamp
Movies file
MovieID::Title::Genres


Our approaches to movie recommendations 
---------------------------------------

1. Content-Based
  a.  Recommend items similar to one you liked
  b.  Can take into account genre, actors/actresses, director, etc.
  c.  If you liked Star Wars, you might like Star Trek
  
2. Collaborative Filtering
  a. Based on past behavior and not context.
  b. Similarity in preferences, tastes, and choices of two users
  c. User-based and Item-based(more on this later) as well as Memory and Model Based

3. Deep Learning
  a.Can determine the preferences of user by a small number of hidden factors called Embeddings
  b.Learn embeddings



