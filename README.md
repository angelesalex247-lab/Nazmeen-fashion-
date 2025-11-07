<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Luxury Haven Fashion — Designer Dresses</title>
  <meta name="description" content="Luxury Haven Fashion — designer abayas, kaftans and ladies dresses. Shop online, contact via WhatsApp or email."/>
  <style>
    :root{
      --accent:#b88f4b;
      --dark:#111;
      --muted:#888;
      --bg:#faf9f7;
      --card:#fff;
      --radius:12px;
      font-family: "Helvetica Neue", Arial, sans-serif;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--dark);-webkit-font-smoothing:antialiased}
    a{color:inherit;text-decoration:none}
    header{background:#fff;border-bottom:1px solid #eee;position:sticky;top:0;z-index:60}
    .topbar{display:flex;gap:12px;align-items:center;justify-content:space-between;padding:.6rem 1rem;font-size:14px}
    .topbar .left{display:flex;gap:10px;align-items:center;color:var(--muted)}
    .topbar .right{display:flex;gap:10px;align-items:center}
    .container{max-width:1100px;margin:0 auto;padding:0 16px}
    .nav{display:flex;align-items:center;justify-content:space-between;padding:.75rem 0}
    .brand{font-weight:700;font-size:24px;letter-spacing:1px}
    .nav-actions{display:flex;gap:14px;align-items:center}
    .menu-toggle{display:none;font-size:22px;background:none;border:0}
    nav ul{display:flex;gap:18px;list-style:none;margin:0;padding:0;align-items:center}
    nav a{padding:.35rem .5rem;border-radius:8px}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center;background:linear-gradient(180deg,#fff0 0,#fff 60%);padding:22px 0}
    .hero-inner{display:flex;flex-direction:column;gap:18px;align-items:flex-start}
    .hero h1{font-size:32px;margin:0;line-height:1.05}
    .hero p{margin:0;color:var(--muted)}
    .hero .cta{display:inline-block;margin-top:8px;background:var(--dark);color:#fff;padding:10px 16px;border-radius:8px}
    .hero img{width:100%;max-width:520px;border-radius:14px;object-fit:cover;box-shadow:0 6px 22px rgba(17,17,17,0.08)}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:20px 0}
    .card{background:var(--card);border-radius:12px;padding:12px;box-shadow:0 6px 18px rgba(17,17,17,0.04);display:flex;flex-direction:column;gap:10px}
    .card img{width:100%;height:260px;object-fit:cover;border-radius:10px}
    .price{font-weight:700}
    .muted{color:var(--muted);font-size:14px}
    .btn{display:inline-block;padding:8px 12px;border-radius:8px;background:var(--accent);color:#fff;border:0;cursor:pointer}
    footer{margin-top:34px;background:#fff;padding:18px 0;border-top:1px solid #eee}
    .footer-grid{display:flex;justify-content:space-between;gap:12px;align-items:center;flex-wrap:wrap}
    .contact-buttons{display:flex;gap:10px}
    .pill{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:999px;background:#f3f3f3}
    /* cart modal */
    .cart-modal{position:fixed;right:20px;bottom:20px;background:var(--card);border-radius:14px;box-shadow:0 20px 50px rgba(17,17,17,0.2);width:320px;max-height:80vh;overflow:auto;padding:12px;z-index:80;display:none}
    .cart-row{display:flex;gap:10px;align-items:center;border-bottom:1px dashed #eee;padding:10px 0}
    .cart-row img{width:64px;height:64px;object-fit:cover;border-radius:8px}
    .cart-actions{display:flex;gap:8px;align-items:center}
    .qty{width:36px;text-align:center;border-radius:8px;padding:6px;border:1px solid #eee}
    .cart-footer{display:flex;justify-content:space-between;align-items:center;padding-top:10px}
    /* responsive */
    @media (max-width:900px){
      .grid{grid-template-columns:repeat(2,1fr)}
      .hero{padding:16px 0}
    }
    @media (max-width:650px){
      .nav ul{display:none}
      .menu-toggle{display:block}
      .hero{grid-template-columns:1fr;gap:12px}
      .grid{grid-template-columns:1fr}
      .topbar{font-size:13px;padding:.5rem 12px}
      .hero h1{font-size:26px}
    }
  </style>
</head>
<body>

<header>
  <div class="topbar container">
    <div class="left">
      <span>📞 +92 312 2555142</span>
      <span>✉️ princtariqmirani@gmail.com</span>
    </div>
    <div class="right">
      <span class="muted">Visit our store in Karachi — Online Orders Open</span>
    </div>
  </div>

  <div class="container nav" aria-label="Main navigation">
    <div class="brand">Luxury Haven Fashion</div>
    <button class="menu-toggle" aria-expanded="false" aria-controls="main-menu">☰</button>
    <nav>
      <ul id="main-menu">
        <li><a href="#shop">Shop</a></li>
        <li><a href="#new">New</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="nav-actions">
      <button id="wishlistBtn" title="Wishlist">♡</button>
      <button id="cartBtn" title="Cart">🛒 <span id="cartCount" style="font-weight:700;margin-left:6px">0</span></button>
    </div>
  </div>
</header>

<main class="container">
  <section class="hero" aria-labelledby="hero-title">
    <div class="hero-inner">
      <h1 id="hero-title">Designer Abayas & Kaftans — New Collection</h1>
      <p class="muted">Limited time — Free shipping UAE & Pakistan on orders over $80. Elegant fabrics, handcrafted details.</p>
      <div>
        <a href="#shop" class="cta">Explore Now</a>
        <a href="https://wa.me/9231225555142?text=Hello%20Luxury%20Haven%20Fashion%20I%20need%20help%20with%20an%20order" target="_blank" class="pill" style="margin-left:8px">WhatsApp Us</a>
      </div>
    </div>
    <img src="https://images.unsplash.com/photo-1520975911777-8b39e4a2f35f?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=9e9b3f4c6d70a5a7c6b9b3df6f7e3a0a" alt="Model wearing designer kaftan">
  </section>

  <h2 id="shop" style="margin-top:8px">Featured Products</h2>

  <section class="grid" id="productsGrid" aria-live="polite">
    <!-- Product cards (template will populate) -->
  </section>

  <section id="about" style="margin:28px 0;padding:18px;background:#fff;border-radius:12px;box-shadow:0 8px 24px rgba(17,17,17,0.03)">
    <h3>Welcome to Luxury Haven Fashion</h3>
    <p class="muted">We craft women's dresses with premium fabrics and detailed embroidery. Shop our selection of abayas, kaftans and designer dresses made for comfort and elegance.</p>
  </section>
</main>

<!-- Cart Modal -->
<div id="cartModal" class="cart-modal" role="dialog" aria-modal="true" aria-label="Shopping cart">
  <h3>My Cart</h3>
  <div id="cartItems"></div>
  <div class="cart-footer">
    <strong>Total: $<span id="cartTotal">0.00</span></strong>
    <div>
      <button id="checkoutBtn" class="btn">Checkout</button>
    </div>
  </div>
</div>

<footer>
  <div class="container footer-grid">
    <div>
      <div style="font-weight:700">Luxury Haven Fashion</div>
      <div class="muted">Designer abaya & kaftan • Online orders</div>
    </div>
    <div class="contact-buttons">
      <a class="pill" href="mailto:princtariqmirani@gmail.com">✉ Email</a>
      <a class="pill" href="https://wa.me/9231225555142?text=Hello%20I%20want%20to%20inquire%20about%20your%20collection" target="_blank">💬 WhatsApp</a>
      <a class="pill" href="#shop">🛍 Shop</a>
    </div>
  </div>
</footer>

<script>
  /***********************
   * Simple product data
   ***********************/
  const products = [
    {id:1,title:"Silk Kaftan — Citrus Print",price:49.00,src:"https://images.unsplash.com/photo-1514996937319-344454492b37?q=80&w=900&auto=format&fit=crop&ixlib=rb-4.0.3&s=1a0f1b9b6b2a7f7b7f7d9e5b5d6a4d1c"},
    {id:2,title:"Embroidered Abaya — Ivory",price:79.00,src:"https://images.unsplash.com/photo-1549179960-84c6a5a6b77b?q=80&w=900&auto=format&fit=crop&ixlib=rb-4.0.3&s=6e8e6c1bcf3f9f4b60f5b1c7c1d2a9a3"},
    {id:3,title:"Evening Gown — Pearl Lace",price:129.00,src:"https://images.unsplash.com/photo-1520975911777-8b39e4a2f35f?q=80&w=900&auto=format&fit=crop&ixlib=rb-4.0.3&s=9e9b3f4c6d70a5a7c6b9b3df6f7e3a0a"},
    {id:4,title:"Casual Kaftan — Garden Print",price:39.00,src:"https://images.unsplash.com/photo-1520975924935-1c7b8f7b3a97?q=80&w=900&auto=format&fit=crop&ixlib=rb-4.0.3&s=2a3b4c5d6e7f8a9b0c1d2e3f4a5b6c7d"},
    {id:5,title:"Luxury Abaya — Midnight",price:99.00,src:"https://images.unsplash.com/photo-1495121605193-b116b5b09b2a?q=80&w=900&auto=format&fit=crop&ixlib=rb-4.0.3&s=cf9e9b9a7e3d4f6c2b5a1e0f7d3c9b2a"},
    {id:6,title:"Resort Dress — Soft Satin",price:59.00,src:"https://images.unsplash.com/photo-1520975924935-3b2d4f7a9c4a?q=80&w=900&auto=format&fit=crop&ixlib=rb-4.0.3&s=5b6c7d8a9b0c1d2e3f4a5b6c7d8e9f0a"}
  ];

  /***********************
   * Render products
   ***********************/
  const grid = document.getElementById('productsGrid');
  products.forEach(p=>{
    const card = document.createElement('article');
    card.className = 'card';
    card.innerHTML = `
      <img src="${p.src}" alt="${p.title}">
      <div style="display:flex;justify-content:space-between;align-items:center">
        <div style="flex:1">
          <div style="font-weight:700">${p.title}</div>
          <div class="muted">Limited stock</div>
        </div>
        <div style="text-align:right">
          <div class="price">$${p.price.toFixed(2)}</div>
          <button class="btn addBtn" data-id="${p.id}" style="margin-top:8px">Add</button>
        </div>
      </div>
    `;
    grid.appendChild(card);
  });

  /***********************
   * Cart logic (simple)
   ***********************/
  let cart = {}; // {productId: qty}
  const cartBtn = document.getElementById('cartBtn');
  const cartModal = document.getElementById('cartModal');
  const cartItemsEl = document.getElementById('cartItems');
  const cartCountEl = document.getElementById('cartCount');
  const cartTotalEl = document.getElementById('cartTotal');
  const checkoutBtn = document.getElementById('checkoutBtn');

  function updateCartCount(){
    const total = Object.values(cart).reduce((s,q)=>s+q,0);
    cartCountEl.textContent = total;
  }

  function renderCart(){
    cartItemsEl.innerHTML = '';
    let total = 0;
    if(Object.keys(cart).length === 0){
      cartItemsEl.innerHTML = '<p class="muted">Your cart is empty.</p>';
    } else {
      for(const idStr of Object.keys(cart)){
        const id = parseInt(idStr,10);
        const qty = cart[id];
        const prod = products.find(p=>p.id===id);
        const row = document.createElement('div');
        row.className = 'cart-row';
        row.innerHTML = `
          <img src="${prod.src}" alt="${prod.title}">
          <div style="flex:1">
            <div style="font-weight:700">${prod.title}</div>
            <div class="muted">$${prod.price.toFixed(2)} x ${qty}</div>
          </div>
          <div class="cart-actions">
            <button class="qtyMinus" data-id="${id}">-</button>
            <div class="qty">${qty}</div>
            <button class="qtyPlus" data-id="${id}">+</button>
            <button class="removeItem" data-id="${id}" title="Remove">✕</button>
          </div>
        `;
        cartItemsEl.appendChild(row);
        total += prod.price * qty;
      }
    }
    cartTotalEl.textContent = total.toFixed(2);
    updateCartCount();
  }

  // Add buttons
  document.querySelectorAll('.addBtn').forEach(btn=>{
    btn.addEventListener('click', e=>{
      const id = parseInt(e.currentTarget.dataset.id,10);
      if(!cart[id]) cart[id]=0;
      cart[id]++;
      renderCart();
      cartModal.style.display = 'block';
      setTimeout(()=>cartModal.scrollIntoView({behavior:'smooth',block:'end'}),100);
    });
  });

  // Cart open/close
  cartBtn.addEventListener('click', ()=> {
    cartModal.style.display = cartModal.style.display === 'block' ? 'none' : 'block';
    renderCart();
  });

  // Delegate cart modal clicks
  cartItemsEl.addEventListener('click', (e)=>{
    if(e.target.matches('.qtyPlus')){
      const id = parseInt(e.target.dataset.id,10);
      cart[id] = (cart[id]||0) + 1;
      renderCart();
    } else if(e.target.matches('.qtyMinus')){
      const id = parseInt(e.target.dataset.id,10);
      cart[id] = Math.max(0,(cart[id]||0)-1);
      if(cart[id] === 0) delete cart[id];
      renderCart();
    } else if(e.target.matches('.removeItem')){
      const id = parseInt(e.target.dataset.id,10);
      delete cart[id];
      renderCart();
    }
  });

  // Checkout button (demo)
  checkoutBtn.addEventListener('click', ()=>{
    if(Object.keys(cart).length===0){
      alert("Your cart is empty.");
      return;
    }
    // Build order summary
    let summary = "Order summary:\\n";
    let total = 0;
    for(const idStr of Object.keys(cart)){
      const id = parseInt(idStr,10);
      const qty = cart[id];
      const prod = products.find(p=>p.id===id);
      summary += `${prod.title} — $${prod.price.toFixed(2)} x ${qty} = $${(prod.price*qty).toFixed(2)}\\n`;
      total += prod.price * qty;
    }
    summary += `\\nTotal: $${total.toFixed(2)}\\n\\nWe will contact you on WhatsApp to complete the order.`;
    // Use WhatsApp link to send the order (opens WhatsApp)
    const waText = encodeURIComponent(summary + "\\n\\nName: \\nPhone: ");
    const waLink = `https://wa.me/9231225555142?text=${waText}`;
    window.open(waLink, '_blank');
  });

  // menu toggle for small screens
  document.querySelector('.menu-toggle').addEventListener('click', function(){
    const menu = document.getElementById('main-menu');
    const expanded = this.getAttribute('aria-expanded') === 'true';
    this.setAttribute('aria-expanded', String(!expanded));
    menu.style.display = expanded ? 'flex' : 'flex';
    menu.style.flexDirection = window.innerWidth < 650 ? 'column' : 'row';
    menu.style.gap = '12px';
  });

  // small UX: close cart if clicked outside
  document.addEventListener('click', function(e){
    const isClickInside = cartModal.contains(e.target) || cartBtn.contains(e.target);
    if(!isClickInside){
      // keep cart open only if it contains items (optional)
      // cartModal.style.display = 'none';
    }
  });

  // initial render
  renderCart();
</script>
