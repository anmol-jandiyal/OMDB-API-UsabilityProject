This project uses the OMDB API which uses the IMDB data. This OMBD api allow us to fetch the data related to the movies like - title, rating, genre, etc.

In order to integrate OMDB API to your project, follow the following steps-
1. Register yourself on the OMDB site https://www.omdbapi.com/ and then get your api key.
2. Once you get your api key, you can use different options to fetch the data.
      Options availabel =  fetching data using tilte of movie or its IMDB id
   let see how to fetch the data using the title

          "http://www.omdbapi.com/?apikey=[yourkey]&t=[movie title]"
  perform the fetch request (in case of Javascript) on above link, by replacing [yourKey] with your api key and [movie title] by title of movie.

eg:        fetch(http://www.omdbapi.com/?apikey=[yourkey]&t=[movie title]) 

Once you get the data you can use that as per your requirement in the project

checkout the project at : https://anmol-jandiyal.github.io/OMDB-API-UsabilityProject/