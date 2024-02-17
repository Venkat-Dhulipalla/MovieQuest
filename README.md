# MovieQuest 🎬 : Explore Your Movie Library (React / Redux)

Welcome to MovieQuest, a fast and user-friendly application for discovering movies. This app is built entirely with React Hooks and the Material UI library, providing a seamless user experience.

Powered by [The Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction), MovieQuest allows you to dive into the world of cinema with ease.

## Demo

Experience MovieQuest in action! [**TRY IT NOW!**](https://world-moviequest.netlify.app/)

## Features

Discover the world of cinema with MovieQuest. Here's what you can do:

- **Search**: Look up movies by title
- **Explore**: Get detailed information about each movie
- **Discover**: Find similar and recommended movies
- **Stay Updated**: Explore popular, trending, and upcoming movies
- **Favorites**: Save your favorite movies for later viewing
- **History**: Keep track of the movies you've visited

## Tech Features

MovieQuest harnesses the power of modern technologies to deliver a smooth user experience:

- **Material UI**: Provides beautiful and responsive UI components
- **React Hooks**: Offers efficient state management and component lifecycle handling
- **Redux Implementation**: Manages centralized state effectively
- **Custom Redux Middleware**: Handles async requests and action cancellation seamlessly
- **Async Requests**: Fetches movie data from the API asynchronously
- **Action Debouncing**: Optimizes search functionality for faster results
- **Lazy Loading**: Ensures efficient loading of resources for better performance
- **Client-Side Storage**: Stores user preferences and visited movies locally for a personalized experience

## Development

Get started with MovieQuest development:

1. **Clone the repository**:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

   ```bash
   cd MovieQuest
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. API Integration

To integrate The Movie Database API into MovieQuest, follow these steps:

A. **Create an API Key**: Sign up for an account on [The Movie Database](https://www.themoviedb.org/) website and generate an API key.

B. **Configure MovieQuest**: Open the `moviedb-api.js` file located at `MovieQuest/src/store/middlewares/moviedb-api.js`.

C. **Paste Your API Key**: Replace the placeholder API key in the `moviedb-api.js` file with your actual API key obtained from The Movie Database.

5. Run the development server:

   ```bash
   npm start
   ```

6. Open your browser and go to [http://localhost:3000](http://localhost:3000) to view the app.
