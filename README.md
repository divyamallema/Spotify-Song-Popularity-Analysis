# Spotify-Song-Popularity-Analysis

Introduction 
- Building ML model that predicts if a Spotify song would be considered “popular” or not based on song features
- The key stakeholders for this project would include artists, record labels, and streaming platforms (like Spotify). 
- Record labels would be able to use these predictions in order to direct promotional activities improve their marketing strategies based on the best features
- Streaming platforms would be able to see what characteristics or attributes of a song tend to bring a larger audience. 
- Users of these platforms would also be able to predict more relevant recommendations based on past interests/liked features
- Our machine learning model would analyze different features of songs in a dataset, including danceability, instrumentalness, speechiness, loudness, etc.
- Making machine learning model would allow for our predictions to be more robust and adaptable as we train our set with different features compared to other methods which have more likelihood of inaccuracies in the data predictions.

Dataset 
- Kaggle - Spotify Tracks DB
- From the Spotify API 
- 10,000 songs per genre. 
- There are 26 genres with a total of 232,725 tracks.
- Features: genre, artist_name, track_name, track_id, popularity, acousticness, danceability, duration_ms, energy, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, time_signature, valence
- Observations: No missing values

  <img width="1003" alt="Screenshot 2024-03-06 at 2 16 14 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/b68117ca-6e32-42da-96dc-282ad2e3445a">
  <img width="1002" alt="Screenshot 2024-03-06 at 2 16 31 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/1a6d62df-9ded-4d7a-a0df-0937c54503e7">
  <img width="999" alt="Screenshot 2024-03-06 at 2 16 44 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/972ed557-bd60-4f2c-bb3b-ab97561a57ca">
  <img width="1004" alt="Screenshot 2024-03-06 at 2 17 10 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/264d9f68-8130-4372-acb2-2a2f3fe3f441">
  <img width="999" alt="Screenshot 2024-03-06 at 2 17 28 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/ea668274-3041-4088-a8d3-d7658a3c3954">
  <img width="1006" alt="Screenshot 2024-03-06 at 2 17 43 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/2e8ff8b5-d2f2-47b1-bce0-9cf4bc0a9d6b">
  <img width="1003" alt="Screenshot 2024-03-06 at 2 17 58 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/687259fa-a35d-4c4e-a8f6-7f6d533371e3">
  <img width="1006" alt="Screenshot 2024-03-06 at 2 18 13 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/4477ed7a-1809-4c70-93a1-13806976733f">
  <img width="1004" alt="Screenshot 2024-03-06 at 2 18 35 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/1c8faf72-940b-403f-9560-96821a1f7d67">
  <img width="1003" alt="Screenshot 2024-03-06 at 2 18 54 PM" src="https://github.com/divyamallema/Spotify-Song-Popularity-Analysis/assets/91154471/d8894f21-8383-4067-9bc9-cd404d4cb687">

Results and Conclusions 
- Logistic Regression seemed to be the best model to predict whether or not a song would be popular
- It had the highest accuracy without overfitting the data
- For genre exploration, we decided to use the same model that we used for predicting popularity of all songs together 
- The accuracies while predicting popularity of songs specific to the genres were different than the overall prediction accuracy
- As seen in the previous slide, we concluded that this was because of the difference in impact of features across different genres











