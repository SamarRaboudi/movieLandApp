# MovieLand 🎥  
A simple and interactive React application that allows users to search for movies and view their details. The app fetches movie data from the OMDB API and displays it in a visually appealing layout.

## Features 🌟
- **Search Movies**: Search for movies by entering a title.
- **Dynamic Movie Display**: Displays movie details including the title, year, poster, and type.
- **Fallback Support**: Displays a placeholder image if a movie poster is not available.
- **Responsive Design**: Adjusts well to various screen sizes.

## Installation 🚀
Follow these steps to get MovieLand running on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/SamarRaboudi/movieLandApp.git
    cd movieLandApp
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the app:
    ```bash
    npm start
    ```


## Technologies Used 🛠️
- **React**: Frontend library for building UI components.
- **CSS**: Styling for the app.
- **OMDB API**: For fetching movie data.

## How It Works ⚙️
1. **Search Functionality**: Users can search for movies by typing a title in the search bar and clicking the search icon. 
2. **Dynamic Rendering**: When a search is performed, the app fetches data from the OMDB API and updates the UI with the search results.
3. **Fallback Mechanism**: If a movie does not have a poster, a default placeholder image is displayed.

## API Key 🔑
The app uses the OMDB API to fetch movie data. Replace the `f4b9bd56` API key in the code with your own if needed:
```javascript
const API_URL = 'http://www.omdbapi.com/?apikey=YOUR_API_KEY';

