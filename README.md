<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Fleepzon Softech</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      display: flex;
      min-height: 100vh;
      background-color: #f9f9f9;
    }

    /* Sidebar */
    .sidebar {
      width: 250px;
      background-color: #111827;
      color: white;
      padding: 30px 20px;
      display: flex;
      flex-direction: column;
      position: fixed;
      height: 100%;
    }

    .brand {
      font-size: 24px;
      font-weight: bold;
      color: #00d4ff;
      margin-bottom: 50px;
    }

    .nav-menu {
      list-style: none;
    }

    .nav-menu li {
      margin: 20px 0;
      cursor: pointer;
      transition: 0.3s;
    }

    .nav-menu li:hover {
      color: #00d4ff;
    }

    /* Main content */
    .main-content {
      margin-left: 250px;
      padding: 40px;
      flex: 1;
    }

    .hero {
      padding: 60px 20px;
      background-color: #ffffff;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .hero h1 {
      font-size: 36px;
      color: #111827;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      color: #444;
      margin-bottom: 0;
    }

    .services {
      margin-top: 50px;
    }

    .service-item {
      background: white;
      padding: 20px;
      border-left: 5px solid #00d4ff;
      margin-bottom: 20px;
      border-radius: 5px;
      box-shadow: 0 1px 6px rgba(0,0,0,0.05);
      transition: transform 0.2s ease;
    }

    .service-item:hover {
      transform: translateY(-5px);
    }

    .service-item h3 {
      margin-bottom: 10px;
      color: #111827;
    }

    .service-item p {
      color: #444;
    }

    /* Responsive Design */
    @media screen and (max-width: 768px) {
      .sidebar {
        position: relative;
        width: 100%;
        height: auto;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        padding: 20px;
      }

      .nav-menu {
        display: flex;
        flex-direction: row;
        gap: 15px;
      }

      .main-content {
        margin-left: 0;
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <!-- Sidebar -->
  <div class="sidebar">
    <div class="brand">Fleepzon Softech</div>
    <ul class="nav-menu">
      <li>Web Design</li>
      <li>Logo Design</li>
      <li>Android Apps</li>
      <li>Gmail Setup</li>
      <li>Payment Gateway</li>
    </ul>
  </div>

  <!-- Main Content -->
  <div class="main-content">
    <!-- Hero Section -->
    <section class="hero">
      <h1>Welcome to Fleepzon Softech</h1>
      <p>We provide cutting-edge IT solutions for modern businesses. From websites to apps, and everything in between – we’ve got you covered.</p>
    </section>

    <!-- Services -->
    <section class="services">
      <div class="service-item">
        <h3>Web Design</h3>
        <p>Modern, responsive, and beautiful websites that drive traffic and sales.</p>
      </div>
      <div class="service-item">
        <h3>Logo Design</h3>
        <p>Professional and memorable logo designs to strengthen your brand identity.</p>
      </div>
      <div class="service-item">
        <h3>Android App Development</h3>
        <p>Custom mobile apps built for performance, speed, and reliability.</p>
      </div>
      <div class="service-item">
        <h3>Professional Gmail Setup</h3>
        <p>Setup branded Gmail accounts for your business: you@yourcompany.com</p>
      </div>
      <div class="service-item">
        <h3>Payment Gateway Integration</h3>
        <p>Secure payment solutions for your eCommerce and online services.</p>
      </div>
    </section>
  </div>

</body>
</html>

