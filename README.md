>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #444;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ffcc00;
    }
    .hero {
      background-color: #555;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    main {
      display: flex;
      padding: 20px;
    }
    .main-content {
      flex: 3;
      padding: 20px;
      background: white;
    }
    .main-content img {
      width: 100%;
      max-width: 500px;
      height: auto;
      margin-top: 10px;
      border-radius: 8px;
    }
    .side-content {
      flex: 1;
      padding: 20px;
      background: #ddd;
      margin-left: 20px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h2>Discover Amazing Content</h2>
    <p>Your journey to learning and exploration starts here!</p>
  </section>

  <main>
    <div class="main-content">
      <h2>Main Content</h2>
      <p>This is where the main content goes.</p>
      <img src=" /storage/emulated/0/Download/images (1).jpeg" alt="Sample Image">
    </div>
    <div class="side-content">
      <h3>Side Content</h3>
      <p>This is where you can put extra info or links.</p>
    </div>
  </main>

  <footer>
    &copy; 2025 My Website. All rights reserved.
  </footer>

</body>
</html>
