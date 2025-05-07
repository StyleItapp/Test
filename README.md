<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StyleIt – Style Your Real Wardrobe</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&family=Fira+Sans:wght@300;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTTXREp2GjWEH0X2z0+pzLluyFZrU7AxEIPFyc/S9UueZZFVdIWhRgpb4AaK5rU7Ib9HtfY6EA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    body {
      margin: 0;
      font-family: 'Fira Sans', sans-serif;
      background: #000000;
      color: #ffffff;
    }
    nav {
      background: #111111;
      padding: 15px 30px;
      box-shadow: 0 2px 10px rgba(255,255,255,0.1);
      position: sticky;
      top: 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: magenta;
      font-weight: bold;
    }
    nav .buttons a {
      background: magenta;
      color: white;
      padding: 8px 16px;
      border-radius: 5px;
    }
    header {
      background: linear-gradient(120deg, #ff69b4, #8e44ad);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 48px;
      margin: 0;
      font-family: 'Poppins', sans-serif;
    }
    header p {
      font-size: 18px;
      margin-top: 10px;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }
    .cta {
      margin-top: 30px;
    }
    .cta input[type=email] {
      padding: 10px;
      border: none;
      border-radius: 5px;
      width: 250px;
      margin-right: 10px;
    }
    .cta button {
      padding: 10px 20px;
      background: white;
      color: #ff69b4;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .features, .stats {
      display: grid;
      gap: 30px;
    }
    .feature, .stat {
      background: #1c1c1c;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(255,255,255,0.1);
      text-align: center;
    }
    .feature i, .stat i {
      font-size: 40px;
      margin-bottom: 10px;
      color: #f39c12;
    }
    .joinwaitlist {
      text-align: center;
      margin-top: 50px;
    }
    footer {
      background: #111111;
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
    @media(max-width: 768px) {
      .cta input[type=email] {
        display: block;
        margin: 10px auto;
      }
      .cta button {
        display: block;
        margin: 0 auto;
      }
    }
  </style>
</head>
<body>
  <nav>
    <div>
      <a href="#features">Features</a>
      <a href="#pricing">Pricing</a>
      <a href="#join">Join Waitlist</a>
      <a href="#about">About Us</a>
    </div>
    <div class="buttons">
      <a href="#download">Free Download</a>
    </div>
  </nav>

  <header>
    <div style="padding: 60px 20px;">
      <h1>StyleIt</h1>
    <p>Style your real clothes with AI. Create magazine-style outfits, plan your week, and pack smarter — all in one beautifully customizable app.</p>
    <div class="cta">
      <form action="https://formspree.io/f/your-form-id" method="POST">
        <input type="email" name="email" placeholder="Enter your email to join wishlist" required />
        <button type="submit">Join Wishlist</button>
      </form>
    </div>
      </div>
  </header>

  <section id="features">
    <h2 style="text-align: center;">Features</h2>
    <div class="features">
      <div class="feature">
        <i class="fas fa-camera"></i>
        <h3>AI Wardrobe Scanner</h3>
        <p>Import your actual clothes in seconds using camera or AI image generation.</p>
      </div>
      <div class="feature">
        <i class="fas fa-magic"></i>
        <h3>Magazine-style Outfit Creator</h3>
        <p>Collage your real pieces into stunning outfits with drag-and-drop ease.</p>
      </div>
      <div class="feature">
        <i class="fas fa-lightbulb"></i>
        <h3>Smart Outfit Suggestions</h3>
        <p>Let our AI stylist create looks for you based on mood, weather, or occasion.</p>
      </div>
      <div class="feature">
        <i class="fas fa-calendar-alt"></i>
        <h3>Calendar + Packing Tools</h3>
        <p>Plan what to wear, get smart packing lists, and track cost-per-wear.</p>
      </div>
    </div>
  </section>

  <section id="stats">
  <div class="features" style="display: flex; justify-content: space-around; background: #111; border-radius: 12px; padding: 20px; text-align: center;">
    <div style="flex: 1;">
      <p style="color: magenta; font-size: 26px; font-weight: bold; margin: 0;">1000+</p>
      <small style="color: #ccc; text-transform: uppercase; font-size: 12px;">Survey Approvals</small>
    </div>
    <div style="flex: 1;">
      <p style="color: magenta; font-size: 26px; font-weight: bold; margin: 0;">97%</p>
      <small style="color: #ccc; text-transform: uppercase; font-size: 12px;">Beta Test Satisfaction</small>
    </div>
    <div style="flex: 1;">
      <p style="color: magenta; font-size: 26px; font-weight: bold; margin: 0;">Jun. 2025</p>
      <small style="color: #ccc; text-transform: uppercase; font-size: 12px;">Expected Launch</small>
    </div>
  </div>
</section>

<section id="pricing">
  <h2 style="text-align: center;">Pricing</h2>
  <div class="features" style="display: flex; justify-content: space-between; align-items: stretch; gap: 30px; flex-wrap: wrap;">
    <div style="flex: 1; min-width: 280px; background: #8e44ad; border-radius: 12px; padding: 30px; text-align: center; color: white;">
      <h3 style="font-size: 32px; font-weight: bold;">$4.99 <span style="font-size: 18px; font-weight: normal;">/mo</span></h3>
      <p style="margin: 10px 0; color: #000; background: #fff; padding: 5px 10px; border-radius: 5px; display: inline-block; font-size: 12px; font-weight: bold;">Full Access</p>
      <p>Access advanced styling, AI-powered outfits, and wardrobe insights monthly.</p>
      <a href="#" style="display: inline-block; margin-top: 30px; padding: 10px 20px; background: black; color: white; border: none; border-radius: 5px; text-decoration: none;">Launching Soon...</a>
    </div>
    <div style="flex: 1; min-width: 280px; background: #4b004f; border-radius: 12px; padding: 30px; text-align: center; color: white; opacity: 0.5;">
      <h3 style="font-size: 32px; font-weight: bold;">$9.99 <span style="font-size: 18px; font-weight: normal;">/mo</span></h3>
      <p style="margin: 10px 0; background: magenta; color: white; padding: 5px 10px; border-radius: 5px; display: inline-block; font-size: 12px; font-weight: bold;">100/100 spots left</p>
      <p>Exclusive perks and early access. Reserved for founding users only.</p>
      <a href="#" style="display: inline-block; margin-top: 30px; padding: 10px 20px; background: #6a006a; color: white; border: none; border-radius: 5px; text-decoration: none;">Sold Out</a>
    </div>
  </div>
</section>

  <section id="join">
    <div class="joinwaitlist">
      <h2 style="text-align: center;">Join the Waitlist</h2>
      <p>Sign up to get notified when StyleIt launches. Be among the first to style smarter.</p>
      <form action="https://formspree.io/f/your-form-id" method="POST">
        <input type="email" name="email" placeholder="Your Email Address" required />
        <button type="submit">Notify Me</button>
      </form>
      <p><strong>Signed up so far:</strong> <span id="signupCount">[hidden from public]</span></p>
    </div>
  </section>

  
<section id="about">
  <h2 style="text-align: center;">About Us</h2>
  <div class="features">
    <div class="feature">
      <i class="fas fa-users"></i>
      <h3>Our Team</h3>
      <p>We’re a small, passionate team building a smarter way to style your wardrobe.</p>
    </div>
  </div>
</section>

  <section id="download">
    <h2 style="text-align: center;">Coming Soon</h2>
    <p style="text-align: center;">StyleIt is expected to launch in <strong>June 2025</strong>. Sign up now and be the first to know!</p>
  </section>

  <footer>
    <p>&copy; 2025 StyleIt. Made with love for your wardrobe. Private signups tracked separately by admin.</p>
  </footer>
</body>
</html>
