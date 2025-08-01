<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fff;
      color: #333;
    }

    header {
      background-color: #182b0aff;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #182b0aff;
      display: flex;
      align-items: center;
      padding: 10px 20px;
      gap: 20px;
    }

    nav a, .dropbtn {
      color: white;
      font-weight: bold;
      text-decoration: none;
      background: none;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    .dropdown {
      position: relative;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #253012;
      min-width: 160px;
      z-index: 1;
      top: 100%;
      left: 0;
      border-radius: 4px;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
    }

    .dropdown-content a {
      display: block;
      padding: 10px;
      color: white;
      text-decoration: none;
    }

    .dropdown-content a:hover {
      background-color: #3b4a21;
    }

    .hero {
      padding: 60px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 5em;
      font-weight: 400;
      margin-bottom: 10px;
      color: #182b0aff;
      font-family: 'Merriweather', serif;
    }

    .hero p {
      font-size: 1.2em;
      color: #666;
    }

    .features {
      display: flex;
      justify-content: center;
    }

    .feature {
      display: flex;
      align-items: center;
      max-width: 1000px;
      background: #7f9759ff;
      margin: 20px;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: left;
    }

    .feature h2 {
      font-size: 2em;
      color: white;
      margin: 0;
    }

    .feature img {
      width: 650px;
      height: 200px;
      border-radius: 8px;
      margin-right: 40px;
    }

    footer {
      background: #182b0aff;
      font-family: 'Courier New', Courier, monospace;
      color: white;
      text-align: left;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
  </header>

  <nav>
    <div class="dropdown">
      <button class="dropbtn">Articles</button>
      <div class="dropdown-content" id="dropdownContent">
        <a href="#">Illusion of Luxury</a>
        <a href="#">Best Beginner Investment Watches in India (2025 Guide)</a>
      </div>
    </div>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h1>SmartRupee</h1>
    <p>Your gateway to smart financial choices</p>
  </section>

  <section class="features">
    <div class="feature">
      <img src="your-image-url.jpg" alt="Feature Image">
      <div>
        <h2>Sell Fridges? The illusion of Luxury: When Influencers Fake It and Brands Look Away</h2>
      </div>
    </div>
  </section>

  <footer>
    &copy; COPYRIGHT © 2025 SMARTRUPEE - ALL RIGHTS RESERVED
  </footer>

  <script>
    const dropbtn = document.querySelector('.dropbtn');
    const dropdown = document.getElementById('dropdownContent');

    dropbtn.addEventListener('click', function (e) {
      e.stopPropagation();
      dropdown.style.display = dropdown.style.display === 'block' ? 'none' : 'block';
    });

    document.addEventListener('click', function () {
      dropdown.style.display = 'none';
    });
  </script>

</body>
</html>
