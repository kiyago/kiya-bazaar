# kiya-bazaar<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kiya Shop</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f5f5f5; }
    header, footer { background-color: #2a2a2a; color: white; padding: 1em; text-align: center; }
    nav input[type="text"] { padding: 0.5em; width: 50%; margin: 1em auto; display: block; border-radius: 5px; border: 1px solid #ccc; }
    .products { display: flex; flex-wrap: wrap; justify-content: center; gap: 1em; padding: 1em; }
    .product { background: white; border-radius: 8px; width: 200px; padding: 1em; box-shadow: 0 0 10px rgba(0,0,0,0.1); text-align: center; }
    .product img { width: 100%; height: 150px; object-fit: cover; border-radius: 5px; }
    .order-form, .about, .contact { background: white; padding: 1em; max-width: 700px; margin: 2em auto; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .order-form input, .order-form select { width: 100%; padding: 0.5em; margin: 0.5em 0; border-radius: 5px; border: 1px solid #ccc; }
    .dual-lang { display: flex; justify-content: space-between; padding: 0 1em; }
    h2 { border-bottom: 2px solid #ccc; padding-bottom: 0.5em; }
  </style>
</head>
<body>
  <header>
    <h1>Kiya Shop</h1>
    <div class="dual-lang">
      <span>Online Store (English)</span>
      <span>ኦንላይን መደብር (Amharic)</span>
    </div>
    <p>Welcome to Kiya Shop – Find the best products for you! / እንኳን ወደ Kiya Shop በደህና መጡ – ምርቶቻችንን ይመልከቱ!</p>
  </header>  <nav>
    <input type="text" placeholder="Search products... / የምርቶችን ፈልግ..." />
  </nav>  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200?text=Eye+Glass" alt="Eye Glass" />
      <h3>Eye Glass / የዓይን መነጽር</h3>
      <p>New men brand glass</p>
      <p>Price: 500 ETB</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200?text=Airpod" alt="Airpod" />
      <h3>Airpod / አየር ፖድ</h3>
      <p>Wireless Bluetooth Earbuds</p>
      <p>Price: 1200 ETB</p>
    </div>
    <!-- 8 more products can be added here -->
  </section>  <section class="about">
    <h2>About Us / ስለ እኛ</h2>
    <p>Kiya Shop is your trusted online store for electronics, fashion, and more. We provide quality and affordable products across Ethiopia. / Kiya Shop ታማኝ የኦንላይን መደብርዎ ነው። ከኤሌክትሮኒክስ እስከ ፋሽን ድረስ ዘመናዊና ተመጣጣኝ ዋጋ ያላቸው ምርቶችን እንዲደርሱላችሁ እንደምንሰራ ታውቃላችሁ።</p>
  </section>  <section class="order-form">
    <h2>Order Now / አሁን ትዕዛዝ አስገባ</h2>
    <form>
      <input type="text" placeholder="Full Name / ሙሉ ስም" required />
      <input type="tel" placeholder="Phone Number / ስልክ ቁጥር" required />
      <select required>
        <option value="">Select Product / ምርት ይምረጡ</option>
        <option>Eye Glass</option>
        <option>Airpod</option>
      </select>
      <input type="number" placeholder="Quantity / ብዛት" required />
      <select required>
        <option value="">Payment Method / የመክፈያ ዘዴ</option>
        <option value="telebirr">Telebirr</option>
        <option value="awash">Awash Bank</option>
      </select>
      <input type="file" accept="image/*" required />
      <input type="submit" value="Place Order / ትዕዛዝ አስገባ" />
    </form>
  </section>  <section class="contact">
    <h2>Contact Us / አግኙን</h2>
    <p>Phone: +251-900-000000</p>
    <p>Email: kiya@shop.com</p>
    <p>Facebook: facebook.com/KiyaShop</p>
  </section>  <footer>
    <p>&copy; 2025 Kiya Shop | All rights reserved</p>
  </footer>
</body>
</html>
