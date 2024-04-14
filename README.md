# Movie-Recommender-System <!-- omit in toc -->

> A web application to recommend 5 most similar movies to the one entered.


## Details

> * Vectorizer used - Bag of words(count vectorizer)
> * Similarity calculator used - cosine similarity(between movie vectors)
> * API used - tmdb api(to get posters of movies from movie_id)

## Steps followed  

> * Input movie name
> * Get index of movie
> * Using similarity vector of that index get the id's of 5 most similar movies
> * Using tmdb API fetch the posters of the movies from movie_id
> * Display the movie names along with there posters 

## To use this web application follow below steps: 

> * Download above zip file and extract all the files in it
> * Enter the following command to install required libraries

       pip install -r requirements.txt

> * Run the following command to host application in your local host

      streamlit run app.py
      
> * Enter the movie name in the text box to find the 5 most similar movies.

> * **Note** : To clone and use the repository you need to set up the Git LFS using the below commands in the git bash of your repository(pkl files are in Git LFS)

      git lfs install

      git lfs track "*.pkl"
      

## Sample input and output images:  

- 5 most similar movies to the 'Superman'

![spam_sample](https://github.com/MahithaKancharla/SMS-Spam-Classifier/assets/98204725/21554de5-3af1-4e5d-91d2-a6469737ed76)

- 5 most similar movies to the 'The Avengers'

![notspam_sample](https://github.com/MahithaKancharla/SMS-Spam-Classifier/assets/98204725/9eca7697-b262-4777-801c-e06156579db9)
