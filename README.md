<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MultiTools - 100+ Free Online Tools</title>
    <meta name="description" content="Free online tools for developers, designers, SEO specialists and more. 100+ tools including converters, calculators, generators and utilities.">
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link href="assets/css/style.css" rel="stylesheet">
</head>
<body>
    <!-- Header will be loaded dynamically -->
    <div id="header-container"></div>
    
    <main class="container mt-4">
        <!-- Hero Section -->
        <section class="hero-section text-center py-5">
            <h1>100+ Free Online Tools</h1>
            <p class="lead">All the tools you need in one place - free, fast and easy to use!</p>
            
            <!-- Search Bar -->
            <div class="search-container mt-4 mb-5">
                <div class="input-group">
                    <input type="text" id="tool-search" class="form-control" placeholder="Search for tools...">
                    <button class="btn btn-primary" id="search-btn">Search</button>
                </div>
                <div id="search-results" class="mt-2"></div>
            </div>
        </section>
        
        <!-- Categories Navigation -->
        <section class="categories mb-5">
            <h2 class="text-center mb-4">Tool Categories</h2>
            <div class="category-buttons d-flex flex-wrap justify-content-center">
                <button class="btn btn-outline-primary m-2 category-btn" data-category="all">All Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="image">Image Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="seo">SEO Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="text">Text Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="dev">Developer Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="math">Math & Calculators</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="unit">Unit Converters</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="security">Security Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="social">Social Media Tools</button>
                <button class="btn btn-outline-primary m-2 category-btn" data-category="misc">Miscellaneous</button>
            </div>
        </section>
        
        <!-- Ad Banner -->
        <div class="ad-banner text-center mb-5">
            <!-- AdSense code would go here -->
            <div class="ad-placeholder">Advertisement</div>
        </div>
        
        <!-- Tools Grid -->
        <section class="tools-grid">
            <h2 class="text-center mb-4" id="current-category">All Tools</h2>
            <div class="row" id="tools-container">
                <!-- Tools will be loaded dynamically -->
            </div>
        </section>
    </main>
    
    <!-- Footer will be loaded dynamically -->
    <div id="footer-container"></div>
    
    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JS -->
    <script src="assets/js/header-footer.js"></script>
    <script src="assets/js/main.js"></script>
</body>
</html>
