# Spicy_Herby.github.io
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>spicy_herby — Moroccan blends & natural cosmetics</title>
  <meta name="description" content="Handcrafted Moroccan spice blends, herbal infusions, natural pigments and luxury cosmetics. Small-batch, ethically sourced." />
  <style>
    :root{
      --accent:#C96B2B;
      --accent2:#B4873E;
      --green:#3A6B44;
      --bg:#F5EDE3;
      --text:#2B2B2B;
      --card:#fff;
      --maxw:1100px;
    }
    *{box-sizing:border-box}
    body{
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      margin:0;background:var(--bg);color:var(--text);-webkit-font-smoothing:antialiased;
    }
    .container{max-width:var(--maxw);margin:0 auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:56px;height:56px;border-radius:8px;background:linear-gradient(135deg,var(--accent),var(--accent2));display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-family: "Playfair Display", serif}
    nav a{margin-left:18px;color:var(--text);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:24px;align-items:center;margin:28px 0}
    .hero h1{font-family:"Playfair Display", serif;font-size:40px;margin:0 0 12px}
    .hero p{margin:0 0 18px;line-height:1.5}
    .ctas{display:flex;gap:12px}
    .btn{padding:12px 18px;border-radius:8px;border:0;cursor:pointer;font-weight:700}
    .btn-primary{background:var(--green);color:white}
    .btn-ghost{background:transparent;border:2px solid rgba(0,0,0,0.06)}
    .card{background:var(--card);border-radius:12px;padding:16px;box-shadow:0 6px 18px rgba(43,43,43,0.06)}
    .featured-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:20px}
    .product{padding:12px;border-radius:10px;background:linear-gradient(180deg,#fff,#fff);display:flex;flex-direction:column;gap:8px}
    .product img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    .product h4{margin:0;font-size:16px}
    .product p{margin:0;font-size:13px;color:#555}
    footer{margin:40px 0 20px;padding:20px 0;border-top:1px solid rgba(0,0,0,0.06)}
    .grid-2{display:grid;grid-template-columns:1fr 320px;gap:24px}
    @media (max-width:900px){
      .hero{grid-template-columns:1fr; text-align:center}
      nav{display:none}
      .featured-grid{grid-template-columns:repeat(2,1fr)}
      .grid-2{grid-template-columns:1fr}
    }
    @media (max-width:520px){
      .featured-grid{grid-template-columns:1fr}
      .logo{width:46px;height:46px}
      .hero h1{font-size:28px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">sh</div>
        <div>
          <div style="font-weight:800">spicy_herby</div>
          <div style="font-size:12px;color:#666">artisan Moroccan botanics</div>
        </div>
      </div>
      <nav>
        <a href="#shop">Shop</a>
        <a href="#about">About</a>
        <a href="#journal">Journal</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <h1>Moroccan spice blends, herbal infusions & ritual beauty</h1>
        <p>Small-batch spice blends, fragrant herbal infusions, natural pigments, luxury argan cosmetics, and hand-rolled incense — sustainably sourced and blended with care.</p>
        <div class="ctas">
          <button class="btn btn-primary" onclick="location.href='#shop'">Shop Bestsellers</button>
          <button class="btn btn-ghost" onclick="location.href='#about'">Our Story</button>
        </div>

        <div class="card" style="margin-top:20px">
          <strong>Free shipping</strong> on orders over $75 • Fresh batches every week
        </div>
      </div>

      <div class="card" style="text-align:center">
        <img src="https://via.placeholder.com/380x230.png?text=Featured+Product" alt="featured" style="width:100%;border-radius:8px;margin-bottom:12px">
        <h3 style="margin:0 0 8px">Ras el Hanout — Signature</h3>
        <p style="margin:0 0 12px">A floral, warm blend perfect for tagines and roasts.</p>
        <button class="btn btn-primary" onclick="location.href='#shop'">View product</button>
      </div>
    </section>

    <section id="shop">
      <h2 style="font-family:'Playfair Display', serif">Featured blends</h2>
      <div class="featured-grid" style="margin-top:12px">
        <div class="product card">
          <img src="https://via.placeholder.com/400x300.png?text=Ras+el+Hanout" alt="">
          <h4>Ras el Hanout — Signature</h4>
          <p>Warm, floral blend for tagines and stews. 50g</p>
          <div style="margin-top:auto;display:flex;justify-content:space-between;align-items:center">
            <strong>$12</strong><button class="btn btn-primary" style="padding:8px 10px">Add</button>
          </div>
        </div>

        <div class="product card">
          <img src="https://via.placeholder.com/400x300.png?text=Rose+Infusion" alt="">
          <h4>Rose & Verbena Infusion</h4>
          <p>Soothing herbal infusion, 30g</p>
          <div style="margin-top:auto;display:flex;justify-content:space-between;align-items:center">
            <strong>$9</strong><button class="btn btn-primary" style="padding:8px 10px">Add</button>
          </div>
        </div>

        <div class="product card">
          <img src="https://via.placeholder.com/400x300.png?text=Argan+Oil" alt="">
          <h4>Argan & Rose Night Elixir</h4>
          <p>Hydrating facial oil, 30ml</p>
          <div style="margin-top:auto;display:flex;justify-content:space-between;align-items:center">
            <strong>$28</strong><button class="btn btn-primary" style="padding:8px 10px">Add</button>
          </div>
        </div>
      </div>
    </section>

    <section style="margin-top:32px" id="about">
      <div class="grid-2">
        <div>
          <h2 style="font-family:'Playfair Display', serif">About spicy_herby</h2>
          <p>We blend in small batches using botanicals sourced from Moroccan cooperatives. From culinary spices to ritual incense and luxury cosmetics, we honor tradition — and the people who make it possible.</p>
          <ul>
            <li>Small-batch freshness</li>
            <li>Traceable sourcing</li>
            <li>Sustainable packaging</li>
          </ul>
        </div>
        <div class="card">
          <h3>Newsletter</h3>
          <p>Get recipes, rituals, and 10% off your first order.</p>
          <form onsubmit="event.preventDefault(); alert('Thanks — we will email you!')">
            <input placeholder="email address" style="width:100%;padding:10px;border-radius:8px;border:1px solid #ddd;margin-bottom:8px">
            <button class="btn btn-primary" style="width:100%">Subscribe</button>
          </form>
        </div>
      </div>
    </section>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap">
        <div>
          <strong>spicy_herby</strong><br>
          Moroccan botanics • handcrafted
        </div>
        <div style="color:#666">© <span id="year"></span> spicy_herby</div>
      </div>
    </footer>
  </div>

  <script>document.getElementById('year').textContent = new Date().getFullYear()</script>
</body>
</html>
