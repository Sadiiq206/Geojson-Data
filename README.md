# Richard Peet's Life

This is a web application that showcases the key events in the life of Richard Peet, a renowned geographer. The application provides an interactive map and a table displaying chronological information about Richard Peet's life events.

## Features

- Interactive Map: The map visualizes the locations associated with important events in Richard Peet's life.
- Sortable Table: The table presents the events in chronological order, allowing users to sort them by year.
- Responsive Design: The application is responsive and adapts to different screen sizes, providing an optimal viewing experience on both desktop and mobile devices.

## Technologies Used

- HTML5: Markup language for structuring the web application.
- CSS3: Stylesheet language for styling the application components.
- JavaScript: Programming language for interactivity and data manipulation.
- Mapbox GL JS: JavaScript library for rendering the interactive map.
- Fetch API: JavaScript API for making asynchronous HTTP requests and retrieving JSON data.

## Usage

To use the application, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/richard-peet-life.git`
2. Open the project folder.
3. Open the `index.html` file in a web browser.
4. Explore the map and the table to learn about Richard Peet's life events.
5. Click the "Sort by Year" button to sort the events in chronological order.

## Configuration

To configure the application, you need to provide your own Mapbox access token. Follow these steps:

1. Sign up for a free Mapbox account at https://www.mapbox.com/.
2. Generate an access token in your Mapbox account dashboard.
3. Replace `'YOUR_MAPBOX_ACCESS_TOKEN'` with your actual Mapbox access token in the `index.html` file.

```javascript
mapboxgl.accessToken = 'YOUR_MAPBOX_ACCESS_TOKEN';
