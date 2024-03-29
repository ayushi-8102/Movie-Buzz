# Movie Buzz ✨

__Special Mention:__ [TMDB API](https://developers.themoviedb.org/3) for providing the amazing database of movies.
## Main Features
### Landing Page
The landing page gives us a brief introduction about this app. Anyone can Signup if its a new user or login if its an old one. The syling of all the pages inside the app is done using "styled-components". AOS library (animate on scroll) is used to animate the content while scrolling!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit1.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit2.JPG)


### Authentication
Firebase authentication service is used for signin and signup features using email, username and password .
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit5.JPG)

### Top Navbar
Once you are logged in, the top navbar will contain your username and three different buttons for navigation namely "Nomination", "Leaderboard" and "Logout".
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit6.JPG)

### Movie-List
All the logged in users are directed to the movie list page where you can browse different movies from different categories . The movie name, a short description and the release date is also visible in that card. All these results are fetched from "TMDB API". You can obviously nominate any movie using the nominate button and if its already nominated, you can remove it from your nominations. Once you nominate a movie the "movieID" and the "user" is registered into our mongoDb database. The same movie cannot be nominated twice, if anyone does that then a toast will get displayed showing "Already nominated"!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit7.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit9.JPG)

### Movie Tralier
Every movie card has a "Watch Traler" button using that you can view the trailer of that movie which is available on youtube . This feature is implemented using "movie-trailer" package.
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit8.JPG)

### Movie Search
You can search your favourite movie in the search box and nominate that as well!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit14.JPG)

### My Nominations
Every user is allowed to nominate atmost five movies and the nominated movies can be viewed in the "Nomination" Tab. If you try to nominate more than five movies then a toast is displayed showing "Already nominated". You can obviously remove those movies which you do not wish to have in that list. A toast appears every time you add or remove a movie .
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit11.JPG)

### Leaderboard
The leaderboard contains the top voted movies by our community which is sorted in descending order of votes.
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit12.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit13.JPG)




***
### Tech Stack and Concepts used:

<p align="left"> <a href="https://expressjs.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg" alt="express" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/html-5.png"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://img.icons8.com/color/48/000000/javascript.png"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" alt="mongodb" width="50" height="50"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://img.icons8.com/color/48/000000/nodejs.png"/> </a> <a href="https://postman.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.netlify.com" target="_blank"> <img src="https://www.netlify.com/img/press/logos/logomark.png" alt="Netlify" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1280px-React-icon.svg.png" alt="React" width="60" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank"> <img src="https://firebase.google.com/downloads/brand-guidelines/PNG/logo-logomark.png" alt="Firebase" width="30" height="40"/> </a> <a href="https://material-ui.com" target="_blank"> <img src="https://material-ui.com/static/logo.png" alt="Material UI" width="50" height="60"/> </a></p>
<br>

* __Frontend:__ Reactjs, Javascript, MaterialUI, Slick-Slider, HTML, CSS, Styled-components
* __Backend:__ Firebase, Nodejs, Expressjs
* __Databse:__ MongoDB
* __Deployment:__ Heroku, Netlify
* __Tools:__ Git

***

### Setting Up the Project 🔧

* __Frontend__

1. Clone the repo

   ```sh
   git clone https://github.com/ayushi-8102/Rate-It.git
   ```
2. Install NPM packages

   ```sh
   npm install
   ```
3. Create a .env file using the template .env.template and add values accordingly.

* __Backend__

1. Clone the repo 

   ```sh
   git clone https://github.com/ayushi-8102/Rate-It-Backend.git
   ```
2. Install NPM packages

   ```sh
   npm install
   ```
3. Create a .env file using the template .env.template and add values accordingly.
   
### Usage

1.  Switch to the Backend folder and run the backend server

    ```sh 
    npm start 
    ```
    
2.  Switch to the Frontend folder and run the frontend server

    ```sh 
    npm start 
    ```
    
    Make sure you start the Backend server before the Frontend server to avoid unnecessary errors.
***

