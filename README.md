# Static Website: Wine Festival Schedule

## Excursion Project

Simple static website showcasing Olivia Woodruff's portfolio.

In this project, you’ll create a web page which advertises a product called “Excursion.” You’ll use your growing toolset including HTML, CSS, Command Line Interface, Git, and GitHub. You’ll be proud of yourself when it all comes together!

The web page we’ll build advertises a mobile app which helps users record and share their experiences, so we’ll use video and landscape imagery to set the scene. A landing page is a vital tool in marketing a product these days, and the goal will be to entice potential customers into using the product.

We’ll work with Git and GitHub on our local machines, so if you haven’t yet, refer to the articles on Command Line Interface Setup and Git Setup.

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