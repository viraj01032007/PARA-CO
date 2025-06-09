<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Coliving Space</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* Navigation bar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      background-color: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .navbar .logo {
      font-weight: bold;
      font-size: 22px;
    }

    .navbar .nav-links a {
      margin-left: 25px;
      text-decoration: none;
      color: #333;
      font-size: 16px;
    }

    /* Hero Section */
    .hero {
      background-image: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1400&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 50px;
    }

    .hero h1 {
      font-size: 48px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      max-width: 500px;
    }

    .search-box {
      margin-top: 20px;
    }

    .search-box input[type="text"] {
      padding: 10px;
      width: 250px;
      border: none;
      border-radius: 5px;
    }

    .search-box button {
      padding: 10px 15px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      margin-left: 5px;
      cursor: pointer;
    }

    /* Furniture Section */
    .furniture-section {
      display: flex;
      justify-content: space-around;
      align-items: flex-start;
      padding: 50px 40px;
      background-color: #f9f9f9;
      flex-wrap: wrap;
      gap: 20px;
    }

    /* States Section */
    .states-section {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
      padding: 40px 20px;
      background-color: #fff;
      max-width: 1300px;
      margin: 0 auto;
    }

    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .card img {
      width: 100%;
      border-radius: 8px;
      height: 200px;
      object-fit: cover;
      margin-bottom: 15px;
    }

    .card h2 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    .card p {
      font-size: 14px;
      color: #555;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <div class="navbar">
    <div class="logo">PARA-CO</div>
    <div class="nav-links">
      <a href="#">Explore</a>
      <a href="#">List your space</a>
      <a href="#">Help</a>
    </div>
  </div>

  <!-- Hero Section -->
  <div class="hero">
    <h1>Find Your Co-living Space</h1>
    <p>Discover fully-furnished, beautifully designed spaces to live and work in comfort.</p>
    <div class="search-box">
      <input type="text" placeholder="Search for locations..." />
      <button>Search</button>
    </div>
  </div>

  <!-- Furniture Section -->
  <div class="furniture-section">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80" alt="Modern Living Room" />
      <h2>Modern Living Room</h2>
      <p>Spacious room with natural light and minimalist furniture style.</p>
    </div>

    <div class="card">
      <img src="https://media.designcafe.com/wp-content/uploads/2020/04/17160430/cozy-bedroom-for-your-home.jpg" alt="Cozy Bedroom" />
      <h2>Cozy Bedroom</h2>
      <p>A peaceful, cozy space with warm tones and soft bedding.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?auto=format&fit=crop&w=600&q=80" alt="Stylish Dining Area" />
      <h2>Stylish Dining Area</h2>
      <p>Elegant dining with modern table, chairs and ambient lighting.</p>
    </div>
  </div>

  <!-- Indian States Section -->
  <div class="states-section">

    <div class="card">
      <img src="https://s7ap1.scene7.com/is/image/incredibleindia/varaha-lakshmi-narasimha-temple-buddhist-complex-visakhapatnam-andhra-pradesh-1-attr-hero?qlt=82&ts=1726744344834" alt="Andhra Pradesh - Tirupati Temple" />
      <h2>Andhra Pradesh</h2>
      <p>Tirumala Venkateswara Temple</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Ahilya_Ghat_by_the_Ganges%2C_Varanasi.jpg" alt="Bihar - Mahabodhi Temple" />
      <h2>Bihar</h2>
      <p>Mahabodhi Temple, Bodh Gaya</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Abbey_Falls_2014.jpg" alt="Karnataka - Abbey Falls" />
      <h2>Karnataka</h2>
      <p>Abbey Falls, Coorg</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Gateway_of_India_Mumbai_03-2016_img3.jpg" alt="Maharashtra - Gateway of India" />
      <h2>Maharashtra</h2>
      <p>Gateway of India, Mumbai</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Meenakshi_Temple_Palace_Entrance_View_2010.jpg" alt="Tamil Nadu - Meenakshi Temple" />
      <h2>Tamil Nadu</h2>
      <p>Meenakshi Temple, Madurai</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Fatehpur_Sikri_2007.jpg" alt="Uttar Pradesh - Fatehpur Sikri" />
      <h2>Uttar Pradesh</h2>
      <p>Fatehpur Sikri</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/54/Hawa_Mahal_Palace%2C_Jaipur.jpg" alt="Rajasthan - Hawa Mahal" />
      <h2>Rajasthan</h2>
      <p>Hawa Mahal, Jaipur</p>
    </div>

    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Sabarmati_Ashram_-_panoramio.jpg" alt="Gujarat - Sabarmati Ashram" />
      <h2>Gujarat</h2>
      <p>Sabarmati Ashram, Ahmedabad</p>
    </div>

  </div>

</body>
</html>
