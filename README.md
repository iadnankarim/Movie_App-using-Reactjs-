# Movie App

This React project consists of several components that together create a movie app where users can view a list of movies, rate them, mark them as favorite, and add them to a cart. Below is an explanation of the code along with instructions on how to install and run the project.

## Project Structure

- **App.js**: This is the main component of the application that manages the state and renders the `Navbar` and `MovieList` components.
- **MovieList.js**: This component receives a list of movies as props and renders a list of `MovieCard` components.
- **MovieCard.js**: This component represents an individual movie card, displaying movie details and allowing users to interact with the movie (rate, favorite, add to cart).
- **Navbar.js**: This component represents the navigation bar, which includes the title and the cart icon with the number of items in the cart.
- **moviesData.js**: This file presumably contains the list of movies as an array of objects (not provided in your code).
- **styles.css**: This file contains the CSS styles for the components.

## Code Explanation

### App.js

This is the main component that holds the state of the application and defines the methods to manipulate the movie list and cart count.

- **State**: The `state` object contains the list of movies and the cart count.
- **Methods**:
  - `handleAddStars`: Increases the star rating of a movie.
  - `handleDecStars`: Decreases the star rating of a movie.
  - `handleToggleFav`: Toggles the favorite status of a movie.
  - `handleAddToCart`: Toggles the cart status of a movie and updates the cart count.
- **Render**: Renders the `Navbar` and `MovieList` components, passing down the state and methods as props.

### MovieList.js

This component receives the list of movies and methods as props and renders a list of `MovieCard` components.

- **Render**: Maps over the list of movies and renders a `MovieCard` for each movie.

### MovieCard.js

This component represents an individual movie card, displaying movie details and allowing users to interact with it.

- **Render**:
  - Displays movie details like title, plot, poster, price, and rating.
  - Allows users to increase or decrease the star rating.
  - Allows users to mark the movie as favorite.
  - Allows users to add or remove the movie from the cart.

### Navbar.js

This component represents the navigation bar.

- **Render**: Displays the title of the app and the cart icon with the number of items in the cart.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
