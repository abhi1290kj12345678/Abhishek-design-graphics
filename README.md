<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abhishek Design Graphics</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f4f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #881818;
      color: #fff;
      padding: 15px 20px;
      text-align: center;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      margin: 0 12px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff9800;
    }

    section {
      padding: 40px 20px;
      display: none;
    }

    section.active {
      display: block;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #222;
    }

    .design-list {
      list-style: none;
      padding: 0;
      margin: 15px 0;
    }

    .design-list li {
      padding: 8px;
      margin-bottom: 5px;
      background: #fff;
      border-left: 5px solid #ff9800;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(247, 5, 5, 0.952);
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #0f0f0f;
      color: #fff;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <img width="150px" src="C:\Users\asd\Desktop\file_0000000061a862309c7969d2b0a1fcf8.png" alt="Abhishek Design Graphics Logo">
    <h1>✨ Abhishek Design Graphics ✨</h1>
    <p id="welcomeUser"></p>

    <nav>
      <a href="#" id="homeBtn">Home</a>
      <a href="#" id="designsBtn">Designs</a>
      <a href="#" id="offerBtn">Offers</a>
      <a href="#" id="contactBtn">Contact</a>
    </nav>
  </header>

  <!-- Home -->
  <section id="homePage" class="active">
    <h2>Welcome to Abhishek Design Graphics</h2>
    <p style="text-align:center;">Creative Hub for Logos, Posters, and Branding Designs.</p>
  </section>

  <!-- Designs -->
  <section id="designsSection">
    <h2>✅ Major Types of Graphic Design</h2>

    <h3>Visual Identity Design (Branding)</h3>
    <ul class="design-list">
      <li>Logo Design</li>
      <li>Brand Colors, Typography</li>
      <li>Business Card, Letterhead</li>
      <li>👉 Example: Coca-Cola ka logo aur brand identity</li>
    </ul>

    <h3>Marketing & Advertising Design</h3>
    <ul class="design-list">
      <li>Posters, Flyers</li>
      <li>Social Media Posts (Instagram, Facebook Ads)</li>
      <li>Banners, Brochures</li>
      <li>👉 Example: Flipkart, Amazon ads graphics</li>
    </ul>

    <h3>User Interface (UI) Design</h3>
    <ul class="design-list">
      <li>Mobile Apps</li>
      <li>Website Layouts</li>
      <li>Dashboard / Software UI</li>
      <li>👉 Example: Swiggy / Zomato app ka clean interface</li>
    </ul>

    <h3>Publication Design</h3>
    <ul class="design-list">
      <li>Magazines, Books</li>
      <li>Newspapers</li>
      <li>E-books</li>
      <li>👉 Example: Fashion Magazines (Vogue, Femina)</li>
    </ul>

    <h3>Packaging Design</h3>
    <ul class="design-list">
      <li>Product Wrapping, Boxes</li>
      <li>Labels, Stickers</li>
      <li>👉 Example: Pepsi Bottle ka label, Chips Packet design</li>
    </ul>

    <h3>Motion Graphics Design</h3>
    <ul class="design-list">
      <li>Animated Ads</li>
      <li>YouTube Intro / Outro</li>
      <li>Logo Animation</li>
      <li>👉 Example: Netflix ka “N” animation</li>
    </ul>

    <h3>Environmental Design</h3>
    <ul class="design-list">
      <li>Hoardings, Billboards</li>
      <li>Sign Boards</li>
      <li>Event & Exhibition Design</li>
      <li>👉 Example: Metro station wall graphics, Mall banners</li>
    </ul>

    <h3>Art & Illustration for Design</h3>
    <ul class="design-list">
      <li>Digital Painting</li>
      <li>Vector Art</li>
      <li>Character Design</li>
      <li>👉 Example: Cartoon characters, Mascots</li>
    </ul>

    <h3>📌 Simple Summary:</h3>
    <ul class="design-list">
      <li>Branding ke liye → Visual Identity</li>
      <li>Business Growth ke liye → Marketing Design</li>
      <li>Tech ke liye → UI/UX</li>
      <li>Print ke liye → Publication</li>
      <li>Products ke liye → Packaging</li>
      <li>Video ke liye → Motion Graphics</li>
    </ul>
  </section>



 <!-- Offers -->
  <section id="offerSection">
    <h2>🔥 Special Offers</h2>

    <h3>Visual Identity Design (Branding)</h3>
    <ul class="design-list">
      <li>🎨 <h3>2D Design</h3><p>Clean & modern 2D graphics starting at ₹199.</p></li>
      <li>🖌️ <h3>3D Design</h3><p>Realistic 3D logos & visuals starting at ₹299.</p></li>
    <li>✨ <h3>Logo Design</h3><p>Premium logo pack with mockups at ₹399.</p></li>
      <li>📢 <h3>Banner Design</h3><p>Attractive banners & posters starting at ₹249.</p></li>
     <li> 🎬 <h3>Video Editing</h3><p>Creative video editing packages from ₹499.</p></li>
  
     </ul></section>




<!-- Contact -->
  <section id="contact">
    <h2>📞 Contact Us</h2>
    <p style="text-align:center;">WhatsApp: 9335830569 | Email: info@designgraphics.com</p>
  </section>

  <footer>
    <p>© 2025 Abhishek Design Graphics. All Rights Reserved.</p>
  </footer>

  <script>
    // Navigation Tabs Handling
    function showSection(sectionId){
      document.querySelectorAll("section").forEach(sec => sec.classList.remove("active"));
      document.getElementById(sectionId).classList.add("active");
      window.scrollTo({ top: 0, behavior: "smooth" });
    }

    document.getElementById("homeBtn").addEventListener("click", e => { e.preventDefault(); showSection("homePage"); });
    document.getElementById("designsBtn").addEventListener("click", e => { e.preventDefault(); showSection("designsSection"); });
    document.getElementById("offerBtn").addEventListener("click", e => { e.preventDefault(); showSection("offerSection"); });
    document.getElementById("contactBtn").addEventListener("click", e => { e.preventDefault(); showSection("contact"); });
  </script>
</body>
</html>
