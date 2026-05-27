index.html
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muhammed Arslan</title>

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <header>
    <h1>Muhammed Arslan</h1>

    <p>Web geliştirme ve tasarlama yapıyorum.</p>

    <a href="about.html">
      <button>Projelerim</button>
    </a>
  </header>

</body>
</html>

<style> 
body {
  margin: 0;
  height: 100vh;

  display: flex;
  justify-content: center;
  align-items: center;

  background: #0f0f0f;
  color: white;

  font-family: Arial;
}

header {
  text-align: center;
}

h1 {
  font-size: 60px;
  margin-bottom: 10px;
}

p {
  font-size: 20px;
  color: #bdbdbd;
}

button {
  margin-top: 20px;

  padding: 15px 35px;

  border: none;
  border-radius: 10px;

  background: #2563eb;
  color: white;

  font-size: 16px;

  cursor: pointer;

  transition: 0.3s;
}

button:hover {
  background: #1d4ed8;

  transform: scale(1.05);
} 
