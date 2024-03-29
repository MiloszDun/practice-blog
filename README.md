### What is it
Blog app displaying & filtering posts from a mock API.

It allows the user to...
- (1) See short versions of posts (with images, excerpts and dates)
- (2) Filter posts by category
- (3) Sort posts by date.

![Blog filtering](src/screenshoots/Filtering-posts.png?raw=true "Filtering Blog Posts")

The mock API is inside `server.js`.

It's designed to occasionally misfire – this allows us to test error handling:

![Error handling](src/screenshoots/Error-Handling.png?raw=true "Error handling")

For styling, the app uses Material UI.

### Mock API instructions

To run the mock API, use `$ node server.js`.

API will listen on `port 6010`. To connect, use either `/articles/music` or `/articles/books`.

There is a 10% chance, that the server will return a 500 error, to allow for testing error handling.

### Run

First start the server using `$ node server.js`. Then, run the app with `npm start`.