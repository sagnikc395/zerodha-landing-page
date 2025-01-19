<script>
  import "./app.css";

  // You would typically import these from your public directory
  const logo = "/logo.svg";
  const landingImage = "/landing-page-image.png";
</script>

<svelte:head>
  <title
    >Zerodha - Online stock trading at lowest prices from India's biggest stock
    broker – Zerodha</title
  >
</svelte:head>

<nav>
  <img src={logo} alt="Zerodha Logo" width="150" height="30" />
  <div class="nav-links">
    <a href="#signup">Sign Up</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#pricing">Pricing</a>
    <a href="#support">Support</a>
  </div>
</nav>

<main>
  <div class="hero-image">
    <img src={landingImage} alt="Landing page illustration" width="800" />
  </div>

  <div class="content">
    <h1>Invest in everything</h1>
    <h3>
      Online platform to invest in stocks, derivatives, mutual funds, and more
    </h3>
    <button class="signup-button">Sign up now</button>
  </div>
</main>
