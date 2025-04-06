<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sunidhi Prasad | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #fdfbff;
      color: #1e1e1e;
    }
    header {
      background-color: #1e1e1e;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }
    h1 {
      font-size: 2.5rem;
      margin: 0;
    }
    nav {
      background-color: #fff;
      padding: 1rem;
      text-align: center;
      border-bottom: 1px solid #ddd;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #1e1e1e;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      color: #6e2ca9;
      border-bottom: 2px solid #6e2ca9;
      padding-bottom: 0.5rem;
      margin-bottom: 2rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 1.5rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 1rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #1e1e1e;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sunidhi Prasad</h1>
    <p>Design Student • Ghatam Artist</p>
  </header>
  <nav>
    <a href="#styrofoam">Styrofoam</a>
    <a href="#pop">POP</a>
    <a href="#abhram">Abhram</a>
    <a href="#vyoma">Vyoma</a>
    <a href="#interior">Interior</a>
    <a href="#ghatam">Ghatam</a>
    <a href="#graphic">Graphic</a>
  </nav>

  <section id="styrofoam">
    <h2>Styrofoam Works</h2>
    <div class="gallery">
      <img src="images/styrofoam.png" alt="Styrofoam work">
    </div>
  </section>

  <section id="pop">
    <h2>POP</h2>
    <div class="gallery">
      <img src="images/pop.png" alt="POP work">
    </div>
  </section>

  <section id="abhram">
    <h2>Abhram</h2>
    <div class="gallery">
      <img src="images/abhram.png" alt="Abhram design">
    </div>
  </section>

  <section id="vyoma">
    <h2>Vyoma</h2>
    <div class="gallery">
      <img src="images/vyoma1.png" alt="Vyoma part 1">
      <img src="images/vyoma2.png" alt="Vyoma part 2">
    </div>
  </section>

  <section id="interior">
    <h2>Interior Design Moodboards</h2>
    <div class="gallery">
      <img src="images/interior1.png" alt="Interior 1">
      <img src="images/interior2.png" alt="Interior 2">
    </div>
  </section>

  <section id="ghatam">
    <h2>Ghatam</h2>
    <div class="gallery">
      <img src="images/ghatam1.png" alt="Ghatam 1">
      <img src="images/ghatam2.png" alt="Ghatam 2">
    </div>
  </section>

  <section id="graphic">
    <h2>Graphic Design</h2>
    <div class="gallery">
      <img src="images/graphic.png" alt="Graphic Design">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Sunidhi Prasad</p>
  </footer>
</body>
</html>
