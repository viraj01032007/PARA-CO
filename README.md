<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Coliving Space - PARA-CO</title>
  <style>
   <body>{
      margin: 0;
      font-family: Arial, sans-serif;
    }

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
      position: relative;
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

    .ceo-info {
      position: absolute;
      bottom: 20px;
      right: 30px;
      text-align: right;
      color: rgba(255, 255, 255, 0.85);
      font-size: 12px;
      font-family: 'Georgia', serif;
    }

    .ceo-title {
      font-size: 13px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .ceo-name {
      font-size: 16px;
      font-style: italic;
      font-weight: bold;
    }

    .furniture-section {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      padding: 50px 40px;
      background-color: #f9f9f9;
      gap: 20px;
    }

    .card {
      width: 300px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      flex-shrink: 0;
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

    .city-slider {
      padding: 40px 20px;
      background-color: #fff;
    }

    .slider-container {
      display: flex;
      align-items: center;
    }

    .city-scroll {
      overflow-x: auto;
      white-space: nowrap;
      scroll-behavior: smooth;
      -webkit-overflow-scrolling: touch;
      margin: 0 10px;
      flex-grow: 1;
    }

    .city-scroll::-webkit-scrollbar {
      display: none;
    }

    .city-button {
      display: inline-block;
      margin-right: 10px;
      padding: 8px 16px;
      cursor: pointer;
      border: 1px solid #ccc;
      border-radius: 5px;
      background: #eee;
    }

    .city-button.active {
      background-color: #007bff;
      color: white;
    }

    .arrow-button {
      font-size: 24px;
      background: none;
      border: none;
      cursor: pointer;
    }

    .whatsapp-button {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: white;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
      z-index: 1000;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
    }

    .whatsapp-button img {
      width: 30px;
      height: 30px;
    }
  </style>
</head>
</body>

  <!-- WhatsApp Button -->
  <a href="https://wa.me/919423421979" target="_blank" class="whatsapp-button">
    <img src="https://img.icons8.com/ios-filled/50/ffffff/whatsapp.png" alt="WhatsApp" />
  </a>

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
    <h1>Find Your Coliving Space</h1>
    <p>Discover fully-furnished, beautifully designed spaces to live and work in comfort.</p>
    <div class="search-box">
      <input type="text" placeholder="Search for locations..." />
      <button>Search</button>
    </div>
    <div class="ceo-info">
      <div class="ceo-title">Founder & CEO</div>
      <div class="ceo-name">Viraj Rajput</div>
    </div>
  </div>

  <!-- Furniture Section -->
  <div class="furniture-section">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80" />
      <h2>Modern Living Room</h2>
      <p>Spacious room with natural light and minimalist furniture style.</p>
    </div>
    <div class="card">
      <img src="https://media.architecturaldigest.com/photos/5eac5fa22105f13b72dede45/4:3/w_1420,h_1065,c_limit/111LexowAve_Aug18-1074.jpg" />
      <h2>Cozy Bedroom</h2>
      <p>A peaceful, cozy space with warm tones and soft bedding.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?auto=format&fit=crop&w=600&q=80" />
      <h2>Stylish Dining Area</h2>
      <p>Elegant dining with modern table, chairs and ambient lighting.</p>
    </div>
  </div>

  <!-- City Slider Section -->
  <div class="city-slider">
    <h2>Available in Cities</h2>
    <div class="slider-container">
      <button class="arrow-button" id="scroll-left">&#8592;</button>
      <div class="city-scroll" id="city-scroll">
        <button class="city-button active" data-city="Panvel">Panvel</button>
        <button class="city-button" data-city="Nerul">Nerul</button>
        <button class="city-button" data-city="Kharghar">Kharghar</button>
        <button class="city-button" data-city="Vashi">Vashi</button>
      </div>
      <button class="arrow-button" id="scroll-right">&#8594;</button>
    </div>
    <div id="properties-list" style="margin-top:20px;"></div>
  </div>

  <script>
    const scrollContainer = document.getElementById('city-scroll');
    const btnLeft = document.getElementById('scroll-left');
    const btnRight = document.getElementById('scroll-right');
    const cityButtons = document.querySelectorAll('.city-button');
    const propertiesList = document.getElementById('properties-list');

    const propertiesData = {
      "Panvel": [
        { name: "Sunrise Residency", type: "2 BHK Apartment", price: "₹15,000/month" },
        { name: "Green Meadows", type: "1 BHK Studio", price: "₹10,000/month" }
      ],
      "Nerul": [
        { name: "Palm Residency", type: "Studio Apartment", price: "₹12,000/month" }
      ],
      "Kharghar": [
        { name: "Elite Homes", type: "3 BHK Flat", price: "₹20,000/month" }
      ],
      "Vashi": [
        { name: "City View", type: "2 BHK Apartment", price: "₹18,000/month" }
      ]
    };

    function showProperties(city) {
      propertiesList.innerHTML = "";
      const list = propertiesData[city] || [];
      list.forEach(property => {
        const div = document.createElement("div");
        div.style.marginBottom = "10px";
        div.innerHTML = `<strong>${property.name}</strong> - ${property.type} - ${property.price}`;
        propertiesList.appendChild(div);
      });
    }

    cityButtons.forEach(btn => {
      btn.addEventListener("click", () => {
        cityButtons.forEach(b => b.classList.remove("active"));
        btn.classList.add("active");
        showProperties(btn.dataset.city);
      });
    });

    btnLeft.addEventListener("click", () => {
      scrollContainer.scrollBy({ left: -200, behavior: 'smooth' });
    });

    btnRight.addEventListener("click", () => {
      scrollContainer.scrollBy({ left: 200, behavior: 'smooth' });
    });

    // Initial load
    showProperties("Panvel");
  </script>
</body>
</html>
