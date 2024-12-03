/catalogo-videos
├── index.html
├── style.css
└── assets/
    └── images/ (imagens das miniaturas)
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catálogo de Vídeos</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Catálogo de Vídeos</h1>
  </header>

  <main class="video-catalog">
    <div class="video-card">
      <img src="assets/images/video1.jpg" alt="Miniatura do vídeo 1">
      <h2>Vídeo 1</h2>
    </div>

    <div class="video-card">
      <img src="assets/images/video2.jpg" alt="Miniatura do vídeo 2">
      <h2>Vídeo 2</h2>
    </div>

    <div class="video-card">
      <img src="assets/images/video3.jpg" alt="Miniatura do vídeo 3">
      <h2>Vídeo 3</h2>
    </div>

    <div class="video-card">
      <img src="assets/images/video4.jpg" alt="Miniatura do vídeo 4">
      <h2>Vídeo 4</h2>
    </div>
  </main>

  <footer>
    <p>Desenvolvido por [Seu Nome]</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  color: #333;
}

header {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
}

h1 {
  font-size: 2rem;
}

.video-catalog {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  padding: 2rem;
}

.video-card {
  background-color: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  width: 300px;
  transition: transform 0.3s;
}

.video-card:hover {
  transform: translateY(-10px);
}

.video-card img {
  width: 100%;
  height: 170px;
  object-fit: cover;
}

.video-card h2 {
  padding: 1rem;
  font-size: 1.5rem;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  color: #333;
}

header {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
}

h1 {
  font-size: 2rem;
}

.video-catalog {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  padding: 2rem;
}

.video-card {
  background-color: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  width: 300px;
  transition: transform 0.3s;
}

.video-card:hover {
  transform: translateY(-10px);
}

.video-card img {
  width: 100%;
  height: 170px;
  object-fit: cover;
}

.video-card h2 {
  padding: 1rem;
  font-size: 1.5rem;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}
