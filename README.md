# Static Website: Wine Festival Schedule

Simple static website showcasing Olivia Woodruff's portfolio.

![image](https://github.com/abemsq/excursions-website/blob/master/image.png)

## HTML
```
<!doctype html>
<html>
  <head>
    <link rel="stylesheet" href="resources/css/style.css">
  </head>
  <body>

    <!-- Landing section -->

    <h1>Discover hidden places in the world around you</h1>
    <p><a class="cta" href="#">Download Excursion (Coming soon!)</a></p>
    <video autoplay muted loop>
      <source src="resources/videos/excursion.mp4" type="video/mp4">
    </video>

    <!-- Information Section -->

    <h2>Your personal travel guide</h2>
    <p>Excursion remembers places you like, and recommends new points of interest around you.</p>
    <p><img src="resources/images/camp.jpg"></p>

    <!-- Coming Soon Section -->

    <p><img class="app" src="resources/images/phone.png"></p>
    <h2>Coming Soon for iPhone and Android</h2>
    <p><a class="cta" href="#">Download Excursion (Coming soon!)</a></p>

    <!-- Footer -->
    
    <div class="footer">
      <p>&copy; Excursion</p>
    </div>

  </body>
</html>
```

## CSS
```
body {
  background-color: black;
  text-align: center;
  font-family: "Verdana", sans-serif;
  color: white;
}

.cta {
  color: aquamarine;
  font-size: 16px;
}

h1 {
  font-size: 50px;
  font-weight: normal;
}

h2 {
  font-size: 42px;
  font-weight: 300;
}

p {
  font-size: 21px;
  color: gray;
}

.footer {
  text-align: right;
} 
```