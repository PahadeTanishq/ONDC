<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ONDC Platform</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navigation Bar -->
  <header>
    <div class="navbar">
      <h1>ONDC Platform</h1>
      <input type="search" placeholder="Search for products or stockists..." id="search-bar">
    </div>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Banner Section -->
    <section class="banner">
      <h2>Welcome to ONDC Platform</h2>
      <p>Explore the best stockists and buy the products you need from your trusted sellers.</p>
    </section>

    <!-- Categories Section -->
    <section class="categories">
      <h2>Categories</h2>
      <div class="category-list">
        <button class="category">Electronics</button>
        <button class="category">Fashion</button>
        <button class="category">Groceries</button>
        <button class="category">Home Appliances</button>
        <button class="category">Health & Wellness</button>
      </div>
    </section>

    <!-- Recommended Shops Section -->
    <section class="recommended-shops">
      <h2>Recommended Stockists</h2>
      <div id="shop-container" class="shop-list">
        <!-- Shops will be populated here dynamically via JavaScript -->
      </div>
    </section>

    <!-- Stockist List Section -->
    <section class="stockist-list">
      <h2>Top Stockists</h2>
      <div id="stockist-container" class="stockist-list">
        <!-- Stockists will be populated here dynamically via JavaScript -->
      </div>
    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>
