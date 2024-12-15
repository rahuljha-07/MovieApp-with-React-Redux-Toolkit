
# Movie App with React and Redux Toolkit

This project is a **Movie Search Application** built with **React.js** and **Redux Toolkit**. The app allows users to search for movies and TV shows using the **OMDb API** and displays the results with a clean and responsive UI.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [API Integration](#api-integration)
- [Folder Structure](#folder-structure)

---

## Features

1. **Movie and TV Show Search**  
   - Users can search for movies and TV shows using keywords.
2. **Detailed Information**  
   - View detailed information about a specific movie or show.
3. **Responsive UI**  
   - A clean and responsive user interface that works on all devices.
4. **Redux Toolkit Integration**  
   - State management using Redux Toolkit for scalability and efficiency.
5. **Error Handling**  
   - User-friendly error messages for invalid searches or network issues.

---

## Technologies Used

- **React.js**: Front-end library for building UI components.
- **Redux Toolkit**: State management for asynchronous API calls.
- **React-Slick**: Carousel slider for displaying movies and shows.
- **SCSS**: Styling with modular SCSS for clean and reusable styles.
- **OMDb API**: API for fetching movie and TV show data.

---

## Installation

### Prerequisites
Ensure you have the following installed:
- **Node.js** (>= 14.x and <=20.18.0)
- **npm** or **Yarn**

### Steps to Run the Project

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/movie-app-react-redux.git
   cd movie-app-react-redux
   ```

2. **Install Dependencies**  
   ```bash
   npm install
   ```

3. **Setup Environment Variables**  
   Create a `.env` file in the project root and add your OMDb API key:
   ```env
   REACT_APP_OMDB_API_KEY=your_api_key_here
   REACT_APP_BASE_URL=your_base_url
   ```

4. **Run the Application**  
   ```bash
   npm start
   ```

5. Open the app in your browser at:  
   ```
   http://localhost:3000
   ```

---

## API Integration

The app uses the **OMDb API** to fetch movie and TV show data. Sign up for a free API key at [OMDb API](http://www.omdbapi.com/).

Example API requests:
- Search Movies:  
  `https://www.omdbapi.com/?apiKey=YOUR_API_KEY&s=movie_title&type=movie`
- Search Shows:  
  `https://www.omdbapi.com/?apiKey=YOUR_API_KEY&s=show_title&type=series`

---

## Folder Structure

```
/public
   favicon.ico
   index.html
/src
   App.js
   index.js
   common/
      apis/
         movieApi.js
         MovieApiKey.js
      settings.js
   components/
      Header/
      Footer/
      Home/
      MovieListing/
      MovieCard/
      MovieDetail/
      PageNotFound/
   features/
      movies/
         movieSlice.js
      store.js
   images/
      user.png
      pnf.jpg
```

---