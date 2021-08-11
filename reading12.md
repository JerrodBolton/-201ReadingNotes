# The Past, Present, and Future of Local Storage for Web Applications

- Before there was was HTML5 there wasn't a lot of space in the for computer.

- **userData** allows web pages to store up to 64 KB of data per domain

## So what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser

- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

- With HTML5 stores we can same process that have been done on a webpage.

  - Let’s see HTML5 Storage in action. Recall the Halma game we constructed in the canvas chapter. There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself.

  - This is how a game keep track of where you have been in the things you have done in your game.
