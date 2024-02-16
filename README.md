# Movie-Recommendation-System-using-Cosine-Similarity-Content-Based-Filtering
This project implements a movie recommendation system that suggests movies based on the similarity of their genres. The system uses cosine similarity to find movies with similar genres to the one searched by the user.
<br><br>
## Features
### Genre-Based Recommendations: 
Users can search for a movie, and the system will suggest 10 other movies with similar genres.
### Support for Hollywood and Bollywood Movies: 
The system is trained on a dataset containing both Hollywood and Bollywood movies, providing recommendations from both industries.
<br><br>
## How It Works
### Data Collection: 
The system uses a dataset containing information about movies, including their titles and genres, from both Hollywood and Bollywood.
### Data Preprocessing: 
The dataset is preprocessed to clean and normalize the data for further processing.
### Cosine Similarity Calculation: 
For a given movie title entered by the user, the system calculates the cosine similarity between the genres of the input movie and all other movies in the dataset.
### Recommendation Generation: 
Based on the cosine similarity scores, the system selects the top 10 movies with the highest similarity scores and recommends them to the user.
<br><br>
## Dataset Used
### The dataset used for this project contains a mix of Hollywood and Bollywood movies to provide diverse recommendations.
<br><br>
## Technologies Used
### Python
### Pandas
### Scikit-learn
<br><br>
