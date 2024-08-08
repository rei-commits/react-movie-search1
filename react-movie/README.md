# React Movie Search App

This is a simple React application that allows users to search for movies and display their information using the OMDB API.

## Features

- Search for movies by title.
- Display movie details including title, genre, poster, and release year.
- Utilizes React hooks (`useState`, `useEffect`) for state management and API calls.

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- **Node.js** and **npm**: Make sure you have Node.js and npm installed. You can download them from [nodejs.org](https://nodejs.org/).

##Usage
- Enter a movie title into the search input field.
-Click the "submit" button to perform the search.
-The application will display the movie's details if available.
-Code Structure

src/components/MovieDisplay.js: Responsible for displaying the movie details.
src/components/Form.js: Contains the input form for entering search terms.
src/App.js: The main component managing state and API interactions.
API Setup

This application uses the OMDB API to retrieve movie data.

Obtaining an API Key
Visit OMDB API to register and receive an API key.
Replace the API key placeholder in src/App.js with your key:
javascript
Copy code
const apiKey = "YOUR_OWN_API_KEY";

Acknowledgments

Thanks to the OMDB API for providing access to movie data.
Inspired by the React documentation and tutorials.


### Installation

   ```bash
   git clone https://github.com/your-username/react-movie-search-app.git
   cd react-movie-search-app
   npm install
   npm start

