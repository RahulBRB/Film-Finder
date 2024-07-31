# Film Finder

Film Finder is a web application that recommends random movies based on genre selection. It uses the TMDB (The Movie Database) API to fetch movie data and provide personalized movie suggestions.

![Snapshot](image.png)
## Features

- Genre selection from a dropdown menu
- Random movie recommendations based on selected genre
- Display of movie details including title, poster, and overview
- Option to like or dislike a movie to get new suggestions

## How It Works

1. The app fetches a list of genres from the TMDB API and populates a dropdown menu.
2. When a user selects a genre, the app fetches a list of movies in that genre.
3. A random movie is selected from the list and its details are fetched.
4. The movie information is displayed on the page.
5. Users can like or dislike the movie to get a new suggestion.

## Technologies Used

- HTML
- CSS
- JavaScript
- TMDB API

## Setup

1. Clone this repository.
2. Obtain an API key from [The Movie Database (TMDB)](https://www.themoviedb.org/).
3. Replace `YOUR_API_KEY` in the `script.js` file with your actual TMDB API key.
4. Open `index.html` in a web browser.



## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)