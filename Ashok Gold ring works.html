<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gold Rings by Your Brand</title>

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      background: #f5f3ee;
      font-family: 'Poppins', sans-serif;
      color: #2f2f2f;
      overflow-x: hidden;
    }

    header {
      background: url('hero-bg.jpg') center/cover no-repeat;
      height: 70vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
      position: relative;
    }

    header::after {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.45);
    }

    header h1 {
      position: relative;
      font-family: 'Playfair Display', serif;
      font-size: 3.5rem;
      margin: 0;
    }

    header p {
      position: relative;
      font-size: 1.2rem;
      margin-top: 10px;
      max-width: 600px;
    }

    #gold-price {
      position: relative;
      margin-top: 20px;
      padding: 10px 18px;
      background: rgba(255,255,255,0.9);
      color: #333;
      border-radius: 8px;
      font-weight: 500;
      display: inline-block;
      font-size: 1.1rem;
    }

    .gallery-container {
      padding: 60px 8%;
    }

    .section-title {
      text-align: center;
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      margin-bottom: 40px;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
    }

    .product-card {
      background: white;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.4s ease;
    }

    .product-card:hover {
      transform: translateY(-10px);
    }

    .product-card img {
      width: 100%;
      height: 280px;
      object-fit: cover;
    }

    .product-info {
      padding: 20px;
    }

    .product-info h3 {
      font-weight: 600;
      font-size: 1.3rem;
      margin: 0 0 10px;
    }

    .product-info p {
      font-size: 0.95rem;
      opacity: 0.8;
    }

    footer {
      background: #111;
      color: #ccc;
      text-align: center;
      padding: 30px;
      font-size: 0.9rem;
      margin-top: 50px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Nava-Ratna</h1>
    <p>Handcrafted luxury pieces designed with precision and passion — each ring tells a story of elegance.</p>
    <div id="gold-price">Fetching live gold price...</div>
  </header>

  <section class="gallery-container">
    <h2 class="section-title">Our Collection</h2>

    <div class="gallery-grid">

      <div class="product-card">
        <img src="ring1.jpg" alt="Royal Gold Ring">
        <div class="product-info">
          <h3>Nava-Ratna</h3>
          <p>22K handcrafted gold ring with premium engraving detail.</p>
        </div>
      </div>

      <div class="product-card">
        <img src="ring1.jpg" alt="Elegant Ring">
        <div class="product-info">
          <h3>Elegant Bloom Ring</h3>
          <p>A beautifully carved floral ring with a timeless charm.</p>
        </div>
      </div>

      <div class="product-card">
        <img src="ring1.jpg" alt="Classic Band">
        <div class="product-info">
          <h3>Imperial Classic Band</h3>
          <p>Minimalistic, bold, and designed for everyday royalty.</p>
        </div>
      </div>

    </div>
  </section>

  <footer>
    © 2025 Your Brand Name — Fine Gold Jewelry
  </footer>

  <!-- Live Gold Price Script -->
  <script>
    async function loadGoldPrice() {
      const url = "https://api.gold-api.com/price/XAU";  // Correct endpoint

      try {
        const res = await fetch(url);
        const data = await res.json();

        if (!data.price) {
          document.getElementById("gold-price").textContent =
            "Live gold price unavailable";
          return;
        }

        // USD per ounce
        const usdPerOz = data.price;

        // USD → INR conversion rate
        const USD_TO_INR = 88.69;

        // Ounce → Gram
        const pricePerGramINR = (usdPerOz * USD_TO_INR) / 31.1035;

        document.getElementById("gold-price").textContent =
          `Gold Price: ₹${pricePerGramINR.toFixed(2)} per gram (updated live)`;

      } catch (err) {
        document.getElementById("gold-price").textContent =
          "Error loading gold price";
      }
    }

    // Load immediately
    loadGoldPrice();

    // Refresh every 10 seconds
    setInterval(loadGoldPrice, 10000);
  </script>

</body>
</html>
