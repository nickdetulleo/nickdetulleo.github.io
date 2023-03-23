# Capstone Project
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <section class="photo-grid">
      <div class="photo">
        <img src="img/photo1.jpg" alt="Photo 1">
        <h2>Photo 1</h2>
      </div>
      <div class="photo">
        <img src="img/photo2.jpg" alt="Photo 2">
        <h2>Photo 2</h2>
      </div>
      <div class="photo">
        <img src="img/photo3.jpg" alt="Photo 3">
        <h2>Photo 3</h2>
      </div>
      <div class="photo">
        <img src="img/photo4.jpg" alt="Photo 4">
        <h2>Photo 4</h2>
      </div>
      <div class="photo">
        <img src="img/photo5.jpg" alt="Photo 5">
        <h2>Photo 5</h2>
      </div>
      <div class="photo">
        <img src="img/photo6.jpg" alt="Photo 6">
        <h2>Photo 6</h2>
      </div>
    </section>
    body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
}

header {
  background-color: #222;
  color: #fff;
  padding: 20px;
  text-align: center;
}

.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 20px;
  margin: 20px;
}

.photo {
  position: relative;
  overflow: hidden;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.photo img {
  display: block;
  width: 100%;
  height: auto;
}

.photo h2 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 10px;
  margin: 0;
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  font-size: 16px;
  font-weight: 400;
  text-align: center;
}

  </body>
</html>
