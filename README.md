# Recipe Finder 🍳

A clean and responsive web application for discovering delicious recipes using TheMealDB API. Search for your favorite dishes or get surprised with random recipe suggestions!

## Features

- **Recipe Search**: Search for recipes by name or ingredient
- **Random Recipe**: Get random recipe suggestions with a single click
- **Detailed View**: View complete recipe details including ingredients, instructions, and cooking videos
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean interface with smooth animations and hover effects
- **External Links**: Direct links to YouTube videos and original recipe sources

## Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS Grid, Flexbox, and custom properties
- **Vanilla JavaScript** - ES6+ features with async/await for API calls
- **TheMealDB API** - Free recipe database API
- **Google Fonts** - Poppins font family for typography

## Getting Started

### Prerequisites

- A modern web browser
- Internet connection (for API calls)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/recipe-finder.git
   ```

2. Navigate to the project directory:
   ```bash
   cd recipe-finder
   ```

3. Open `index.html` in your web browser or serve it using a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

4. Visit `http://localhost:8000` in your browser

## Usage

1. **Search Recipes**: Enter a recipe name or ingredient in the search box and click "Search"
2. **Random Recipe**: Click the "Get Random Recipe" button for a surprise recipe
3. **View Details**: Click on any recipe card to see detailed information in a modal
4. **Watch Videos**: Click on YouTube links to watch cooking tutorials
5. **View Source**: Access original recipe sources when available

## API Reference

This project uses [TheMealDB API](https://www.themealdb.com/api.php):

- **Search by name**: `https://www.themealdb.com/api/json/v1/1/search.php?s={MEAL_NAME}`
- **Random meal**: `https://www.themealdb.com/api/json/v1/1/random.php`
- **Lookup by ID**: `https://www.themealdb.com/api/json/v1/1/lookup.php?i={MEAL_ID}`

## Project Structure

```
recipe-finder/
│
├── index.html          # Main HTML file
├── style.css           # CSS styles and responsive design
├── main.js             # JavaScript functionality and API calls
└── README.md           # Project documentation
```


## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Acknowledgments

- [TheMealDB](https://www.themealdb.com/) for providing the free recipe API
- [Google Fonts](https://fonts.google.com/) for the Poppins font family
- Icons and inspiration from various open-source projects

