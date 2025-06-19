<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Responsive Page</title>
  <style>
    /* Base styles */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      max-width: 1000px;
      margin-left: auto;
      margin-right: auto;
      padding: 0 20px;
    }

    header, nav, main, footer {
      padding: 20px;
    }

    nav a {
      margin-right: 15px;
      text-decoration: none;
      color: #333;
    }

    /* Link hover/active */
    nav a:hover,
    nav a:active {
      color: #FF6565;
    }

    /* Button styles */
    button {
      padding: 10px 20px;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    /* Button hover/active */
    button:hover,
    button:active {
      opacity: 0.9;
    }

    /* Responsive styles */
    @media (max-width: 480px) {
      nav, header, main, footer {
        text-align: center;
        padding: 15px;
      }

      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>My Responsive Web Page</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <h2>Welcome!</h2>
    <p>This page automatically adapts to smaller screens using media queries.</p>
    <button>Click Me</button>
  </main>

  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>
</body>
</html>
