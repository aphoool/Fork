<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Responsive Layout</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background: #4CAF50;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    .container {
      display: grid;
      grid-template-columns: 1fr 3fr;
      gap: 10px;
      padding: 10px;
    }

    aside {
      background: #eee;
      padding: 20px;
    }

    main {
      background: #f9f9f9;
      padding: 20px;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px;
    }

    /* Tablet View */
    @media (max-width: 768px) {
      .container {
        grid-template-columns: 1fr 2fr;
      }
    }

    /* Mobile View */
    @media (max-width: 480px) {
      .container {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>My Responsive Website</header>
  <div class="container">
    <aside>Sidebar Menu</aside>
    <main>Main Content</main>
  </div>
  <footer>© 2025 My Layout</footer>
</body>
</html>  
