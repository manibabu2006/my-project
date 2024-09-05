<!DOCTYPE html>
<html>
<head>
    <title>FOOD STALLS</title>
    <style>
        body {font-family: Arial, sans-serif;background-color: #f8f5f5;margin: 0;padding: 0;}
        header, footer {background-color: #f2eeeb;color: rgb(15, 14, 14);text-align: center;padding: 1em 0;}
        nav {margin: 0;padding: 1em;background-color: #100f0f;}
        nav a {color: white;margin: 0 15px;text-decoration: none;}
        main {padding: 20px;}
        .search-container {display: flex;justify-content: center;margin-top: 20px;}
        .search-container input[type="text"] {padding: 10px;font-size: 17px;border: 1px solid #ccc;width: 300px;}
        .search-container button {padding: 10px;font-size: 17px;border: 1px solid #ccc;background-color: #333;color: white;cursor: pointer;
        }.search-container button:hover {background-color: #555;}
    </style>
</head>
<body>
    <header>
        <style>.logo {position: absolute; right: 0; top: 0;}</style>
         <img src="lpu-logo.png" alt="logo" class="logo" height="110" width="110">
        <h1 style="font-size: 500; text-align: left; font-style: inherit;">Welcome to LPU FOOD STALLS</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <footer>
        <p>© 2024 My Website</p>
    </footer>
    <div class="search-container">
        <input type="text" placeholder="Search...">
        <button type="submit">Search</button>
    </div><br><br>
    <div class="slides">
      <marquee behavior="" direction="right"> <img src="mani1.jpg"height="300" width=2000" alt="Photo 1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <img src="mani2.jpg"height="300" width=200" alt="Photo 2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <img src="mani3.jpg"height="300" width=200" alt="Photo 3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <img src="mani4.jpg"height="300" width=200" alt="Photo 4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <img src="mani5.jpg"height="300" width=200" alt="Photo 5">    </marquee>
  </div>
<main>
  <h2>Home</h2>
  <p>This is the home page of LPU food stalls.</p>
  <h2 id="about">About</h2>
  <p>This section contains information about the website.</p>
  <h2>Contact</h2>
  <style>.phone-link {color: blue;text-decoration: none;font-weight: bold;}.phone-link:hover {text-decoration: underline;}</style>
  <p>Call us at: <a href="tel:+7989079035" class="phone-link">+91 7989079035</a></p>
  <p>Email us at: <a href="mailto:komanapallimanibabu2006@gmail.com?subject=Inquiry&cc=cc@example.com&body=Hello, I have a question about...">komanapallimanibabu2006@gmail.com</a></p>
  <L class="titlelayer"></L><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d8378.783567098482!2d75.69865990735815!3d31.255468399639426!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x391a5fb3d3115dbf%3A0x435618b146461dca!2sDepartment%20of%20Education%2C%20LPU!5e1!3m2!1sen!2sin!4v1725123219843!5m2!1sen!2sin" width="1550" height="700" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></p>
  <script>([31.25068, 75.70058]).addTo(myMap)
                    L.bindPopup('1.')
                    L.openPopup();</script>
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>My Map</title>
      <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css">
      <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
      <div id="map" style="height: 400px;"></div>
          </head>
        <body>
            
            <div id="map" style="height: 400px;"></div>
            <script>
                var myMap = L.map('map').setView([51.505, -0.09], 13);
                L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'}).addTo(myMap);
                L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap contributors</a>',maxZoom: 18,}).addTo(myMap);
                // Add a marker at your desired location
                L.marker([31.25068, 75.70058]).addTo(myMap)
                    .bindPopup('1.')
                    .openPopup();
                L.marker([31.25064, 75.70058]).addTo(myMap)
                    .bindPopup('2.')
                    .openPopup();
                    L.marker([31.25060, 75.70058]).addTo(myMap)
                    .bindPopup('3.')
                    .openPopup();
                    L.marker([31.25057, 75.70058]).addTo(myMap)
                    .bindPopup('4.')
                    .openPopup();
                    L.marker([31.25054, 75.70058]).addTo(myMap)
                    .bindPopup('5.')
                    .openPopup();
                    L.marker([31.25051, 75.70059]).addTo(myMap)
                    .bindPopup('6.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    L.marker([31.25047, 75.70059]).addTo(myMap)
                    .bindPopup('7.')
                    .openPopup();
                    
var createError = require('http-errors');
var express = require('express');
var path = require('path');
var cookieParser = require('cookie-parser');
var logger = require('morgan');

var indexRouter = require('./routes/index');
var usersRouter = require('./routes/users');

var app = express();

// view engine setup
app.set('views', path.join(__dirname, 'views'));
app.set('view engine', 'pug');

app.use(logger('dev'));
app.use(express.json());
app.use(express.urlencoded({ extended: false }));
app.use(cookieParser());
app.use(express.static(path.join(__dirname, 'public')));

app.use('/', indexRouter);
app.use('/users', usersRouter);

// catch 404 and forward to error handler
app.use(function(req, res, next) {
  next(createError(404));
});

// error handler
app.use(function(err, req, res, next) {
  // set locals, only providing error in development
  res.locals.message = err.message;
  res.locals.error = req.app.get('env') === 'development' ? err : {};

  // render the error page
  res.status(err.status || 500);
  res.render('error');
});
module.exports = app;


            </script>
    </main>
</body>
</html>
