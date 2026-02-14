# wah-imperium-royal-artisan-empire
Official AI-powered global artisan ecosystem platform for WAH IMPERIUM ROYAL ARTISAN EMPIRE GLOBAL LIMITED.
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WAH Imperium Royal Artisan Empire Global Limited</title>
  <style>
    /* Reset & Base */
    * { margin:0; padding:0; box-sizing:border-box; font-family: 'Segoe UI', sans-serif; }
    body { background-color: #000; color: #FFD700; }
    a { color: #FFD700; text-decoration: none; }/* Loading Screen */
#loading { position: fixed; top:0; left:0; width:100%; height:100%; background:#000; display:flex; justify-content:center; align-items:center; flex-direction:column; z-index:9999; }
#loading img { width:120px; height:120px; margin-bottom:20px; }
#loading h1 { font-size: 1.5rem; color: #FFD700; text-align:center; }

/* Header */
header { display:flex; justify-content:space-between; align-items:center; padding: 1rem 2rem; background-color: #111; border-bottom: 2px solid #FFD700; }
header h1 { font-size: 1.4rem; }

/* Categories */
.categories { display:flex; flex-wrap: wrap; justify-content: center; padding: 2rem; gap:1rem; }
.category { background-color: #111; border: 1px solid #FFD700; padding:1rem 1.5rem; border-radius:8px; cursor:pointer; transition: all 0.3s ease; min-width:200px; }
.category:hover { background-color: #222; }

/* Subcategories */
.subcategory-list { display:none; margin-top:10px; padding-left: 1rem; }
.subcategory { padding:5px 0; border-bottom:1px dashed #FFD700; }

/* Footer */
footer { text-align:center; padding: 1rem; border-top:2px solid #FFD700; margin-top:2rem; }

  </style>
</head>
<body>  <!-- Loading Screen -->  <div id="loading">
    <img src="logo.png" alt="WAH Imperium Royal Artisan Empire Global Limited Logo">
    <h1>WAH Imperium Royal Artisan Empire Global Limited</h1>
  </div>  <!-- Main Content -->  <header>
    <h1>WAH Imperium Royal Artisan Empire Global Limited</h1>
  </header>  <section class="categories">
    <div class="category" onclick="toggleSub(this)">Video Construction
      <div class="subcategory-list">
        <div class="subcategory">Carpentry</div>
        <div class="subcategory">Bricklaying</div>
        <div class="subcategory">Welding</div>
      </div>
    </div><div class="category" onclick="toggleSub(this)">Livestock
  <div class="subcategory-list">
    <div class="subcategory">Cattle</div>
    <div class="subcategory">Goats</div>
    <div class="subcategory">Poultry</div>
  </div>
</div>

<div class="category" onclick="toggleSub(this)">Fashion & Design
  <div class="subcategory-list">
    <div class="subcategory">Tailoring</div>
    <div class="subcategory">Textiles</div>
  </div>
</div>

<div class="category" onclick="toggleSub(this)">Technical & Beauty
  <div class="subcategory-list">
    <div class="subcategory">Electrical</div>
    <div class="subcategory">Plumbing</div>
    <div class="subcategory">Hair & Makeup</div>
  </div>
</div>

<div class="category" onclick="toggleSub(this)">Mechanic Engineering
  <div class="subcategory-list">
    <div class="subcategory">Automobile Repair</div>
    <div class="subcategory">Machinery</div>
  </div>
</div>

<div class="category" onclick="toggleSub(this)">Agents / Buy & Sell
  <div class="subcategory-list">
    <div class="subcategory">Materials Seller</div>
    <div class="subcategory">Livestock Seller</div>
    <div class="subcategory">Property Transactions</div>
  </div>
</div>

<div class="category" onclick="toggleSub(this)">Properties / Real Estate
  <div class="subcategory-list">
    <div class="subcategory">Houses for Rent</div>
    <div class="subcategory">Land Sales</div>
  </div>
</div>

<div class="category" onclick="toggleSub(this)">Training & Skills
  <div class="subcategory-list">
    <div class="subcategory">Primary School</div>
    <div class="subcategory">Secondary School</div>
    <div class="subcategory">University Level</div>
    <div class="subcategory">Adults / Online Training</div>
  </div>
</div>

  </section>  <footer>
    &copy; 2026 WAH Imperium Royal Artisan Empire Global Limited. All rights reserved.
  </footer>  <script>
    // Hide loading after 2 seconds
    window.addEventListener('load', () => {
      setTimeout(() => { document.getElementById('loading').style.display = 'none'; }, 2000);
    });

    // Toggle subcategories
    function toggleSub(element) {
      const subList = element.querySelector('.subcategory-list');
      if(subList.style.display === 'block') subList.style.display = 'none';
      else subList.style.display = 'block';
    }
  </script></body>
</html>
