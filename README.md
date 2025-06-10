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

    .states-section {
      padding: 40px 20px;
      background-color: #fff;
    }

    .states-carousel-wrapper {
      overflow-x: auto;
      display: flex;
      gap: 20px;
      scroll-behavior: smooth;
      -webkit-overflow-scrolling: touch;
    }

    .states-carousel-wrapper::-webkit-scrollbar {
      display: none;
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
 

  

  <!-- WhatsApp Button -->
  <a href="https://wa.me/919423421979" target="_blank" class="whatsapp-button">
    <img src="https://img.icons8.com/ios-filled/50/ffffff/whatsapp.png" alt="WhatsApp" />
  </a>


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


 
 
<body>

<!-- City Slider Section -->
<div class="city-slider">
  <h2>Available in Cities</h2>
  <div class="slider-container" style="display:flex; align-items:center;">
    <button class="arrow-button" id="scroll-left" aria-label="Scroll Left" style="font-size:24px;">&#8592;</button>
    <div class="city-scroll" id="city-scroll" style="overflow-x:auto; white-space: nowrap; scroll-behavior: smooth; margin: 0 10px; flex-grow:1;">
      <button class="city-button active" data-city="Panvel" style="display:inline-block; margin-right:10px; padding:8px 16px; cursor:pointer;">Panvel</button>
      <button class="city-button" data-city="Nerul" style="display:inline-block; margin-right:10px; padding:8px 16px; cursor:pointer;">Nerul</button>
      <button class="city-button" data-city="Kharghar" style="display:inline-block; margin-right:10px; padding:8px 16px; cursor:pointer;">Kharghar</button>
      <button class="city-button" data-city="Vashi" style="display:inline-block; margin-right:10px; padding:8px 16px; cursor:pointer;">Vashi</button>
      <!-- Add more cities if needed -->
    </div>
    <button class="arrow-button" id="scroll-right" aria-label="Scroll Right" style="font-size:24px;">&#8594;</button>
  </div>

  <!-- Properties display -->
  <div id="properties-list" style="margin-top:20px;">
    <!-- Properties will be dynamically inserted here -->
  </div>
</div>

<script>
  const scrollContainer = document.getElementById('city-scroll');
  const btnLeft = document.getElementById('scroll-left');
  const btnRight = document.getElementById('scroll-right');
  const cityButtons = document.querySelectorAll('.city-button');
  const propertiesList = document.getElementById('properties-list');

  // Sample data for properties available in each city
  const propertiesData = {
    "Panvel": [
      { name: "Sunrise Residency", type: "2 BHK Apartment", price: "₹15,000/month" },
      { name: "Green Meadows", type: "1 BHK Studio", price: "₹10,000/month" }
    ],
    "Nerul": [
      { name: "Ocean View Towers", type: "3 BHK Apartment", price: "₹25,000/month" },
      { name: "Palm Residency", type: "2 BHK Apartment", price: "₹18,000/month" }
    ],
    "Kharghar": [
      { name: "Lakeview Heights", type: "1 BHK Studio", price: "₹12,000/month" },
      { name: "Central Park Homes", type: "2 BHK Apartment", price: "₹16,000/month" }
    ],
    "Vashi": [
      { name: "Skyline Residency", type: "3 BHK Apartment", price: "₹22,000/month" },
      { name: "Palm Grove", type: "1 BHK Studio", price: "₹11,000/month" }
    ]
  };

  // Scroll left by 150px
  btnLeft.addEventListener('click', () => {
    scrollContainer.scrollBy({ left: -150, behavior: 'smooth' });
  });

  // Scroll right by 150px
  btnRight.addEventListener('click', () => {
    scrollContainer.scrollBy({ left: 150, behavior: 'smooth' });
  });

  function showProperties(city) {
    propertiesList.innerHTML = ""; // Clear previous

    const props = propertiesData[city];
    if (!props || props.length === 0) {
      propertiesList.innerHTML = `<p>No properties available in ${city}.</p>`;
      return;
    }

    const list = document.createElement('ul');
    list.style.listStyleType = 'none';
    list.style.padding = '0';

    props.forEach(property => {
      const item = document.createElement('li');
      item.style.padding = '10px';
      item.style.marginBottom = '10px';
      item.style.border = '1px solid #ccc';
      item.style.borderRadius = '8px';

      item.innerHTML = `
        <strong>${property.name}</strong><br/>
        Type: ${property.type}<br/>
        Price: <span style="color:green;">${property.price}</span>
      `;
      list.appendChild(item);
    });

    propertiesList.appendChild(list);
  }

  // Initial show for default active city
  const defaultCity = document.querySelector('.city-button.active').dataset.city;
  showProperties(defaultCity);

  // Handle city button clicks
  cityButtons.forEach(btn => {
    btn.addEventListener('click', () => {
      cityButtons.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');

      const city = btn.dataset.city;
      showProperties(city);
    });
  });
</script>

<style>
  .city-button.active {
    background-color: #5e2ca5;
    color: white;
    border-radius: 20px;
  }
  .city-button {
    background-color: #eee;
    border: none;
    border-radius: 20px;
    transition: background-color 0.3s;
  }
  .city-button:hover {
    background-color: #ccc;
  }
  .arrow-button {
    background-color: transparent;
    border: none;
    cursor: pointer;
    user-select: none;
  }
</style>

<footer>
  <!-- Team Members Section -->
<div class="team-section" style="padding: 50px 20px; background-color: #f0f0f0; text-align: center;">
  <h2 style="font-size: 32px; margin-bottom: 30px;">Meet Our Team</h2>
  <div style="display: flex; justify-content: center; gap: 30px; flex-wrap: wrap;">
    
    <div class="team-card" style="width: 250px; background: #fff; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 20px;">
      <img src="https://randomuser.me/api/portraits/men/31.jpg" alt="Shreyansh Chaubey" style="width: 100%; border-radius: 50%; height: 200px; object-fit: cover; margin-bottom: 15px;">
      <h3 style="margin: 10px 0 5px;">Shreyansh Chaubey</h3>
      <p style="color: #555;">Operations Head</p>
    </div>

    <div class="team-card" style="width: 250px; background: #fff; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 20px;">
      <img src="https://randomuser.me/api/portraits/men/33.jpg" alt="Jayesh Bhosle" style="width: 100%; border-radius: 50%; height: 200px; object-fit: cover; margin-bottom: 15px;">
      <h3 style="margin: 10px 0 5px;">Jayesh Bhosle</h3>
      <p style="color: #555;">Technical Lead</p>
    </div>

    <div class="team-card" style="width: 250px; background: #fff; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 20px;">
      <img src="https://randomuser.me/api/portraits/men/34.jpg" alt="Viraj Rajput" style="width: 100%; border-radius: 50%; height: 200px; object-fit: cover; margin-bottom: 15px;">
      <h3 style="margin: 10px 0 5px;">Viraj Rajput</h3>
      <p style="color: #555;">Founder & CEO</p>
    </div>

    <!-- New Members Below -->
    <div class="team-card" style="width: 250px; background: #fff; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 20px;">
      <img src="https://randomuser.me/api/portraits/women/45.jpg" alt="Priya Mehta" style="width: 100%; border-radius: 50%; height: 200px; object-fit: cover; margin-bottom: 15px;">
      <h3 style="margin: 10px 0 5px;">Priya Mehta</h3>
      <p style="color: #555;">Marketing Manager</p>
    </div>

    <div class="team-card" style="width: 250px; background: #fff; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 20px;">
      <img src="https://randomuser.me/api/portraits/men/44.jpg" alt="Ankit Sharma" style="width: 100%; border-radius: 50%; height: 200px; object-fit: cover; margin-bottom: 15px;">
      <h3 style="margin: 10px 0 5px;">Ankit Sharma</h3>
      <p style="color: #555;">Finance Analyst</p>
    </div>

    <div class="team-card" style="width: 250px; background: #fff; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 20px;">
      <img src="https://randomuser.me/api/portraits/women/40.jpg" alt="Neha Gupta" style="width: 100%; border-radius: 50%; height: 200px; object-fit: cover; margin-bottom: 15px;">
      <h3 style="margin: 10px 0 5px;">Neha Gupta</h3>
      <p style="color: #555;">Product Designer</p>
    </div>

  </div>
</div>


</footer>


</body>
</html>


