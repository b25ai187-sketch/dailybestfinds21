<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>dailybestfinds21 | Best Online Deals</title>
<meta name="description" content="dailybestfinds21 – Discover hot deals and best products every day.">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: Arial, sans-serif;
}

body{
  background:#f1f3f6;
}

/* Header */
header{
  background:#131921;
  padding:15px;
  display:flex;
  align-items:center;
  gap:15px;
}

.logo{
  color:#fff;
  font-size:24px;
  font-weight:bold;
}

.logo span{
  color:#ff9900;
}

header input{
  flex:1;
  padding:10px;
  border:none;
  border-radius:4px;
}

/* Products */
.products{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
  padding:20px;
}

.product{
  position:relative;
  background:#fff;
  padding:15px;
  border-radius:6px;
  text-align:center;
  box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

.product img{
  width:100%;
  height:200px;
  object-fit:cover;
}

/* Deal badges */
.badge{
  position:absolute;
  top:10px;
  left:10px;
  padding:6px 10px;
  color:#fff;
  font-size:12px;
  font-weight:bold;
  border-radius:4px;
  z-index:10;
}

.hot{
  background:#ff0000;
  animation:pulse 1.2s infinite;
}

.best{
  background:#28a745;
  animation:bounce 1.5s infinite;
}

@keyframes pulse{
  0%{transform:scale(1); box-shadow:0 0 0 rgba(255,0,0,0.7);}
  50%{transform:scale(1.1); box-shadow:0 0 15px rgba(255,0,0,0.9);}
  100%{transform:scale(1);}
}

@keyframes bounce{
  0%,100%{transform:translateY(0);}
  50%{transform:translateY(-6px);}
}

.product h3{
  font-size:16px;
  margin:10px 0;
}

.price{
  color:green;
  font-size:18px;
  margin-bottom:8px;
}

button{
  width:100%;
  padding:10px;
  background:#ff9f00;
  border:none;
  border-radius:4px;
  font-weight:bold;
  cursor:pointer;
}

button:hover{
  background:#fb641b;
  color:#fff;
}

.note{
  font-size:12px;
  color:#555;
  margin-top:6px;
}

/* Footer */
footer{
  background:#131921;
  color:#fff;
  text-align:center;
  padding:10px;
  font-size:14px;
}
</style>
</head>

<body>

<header>
  <div class="logo">daily<span>bestfinds21</span></div>
  <input type="text" placeholder="Search hot deals...">
</header>

<section class="products">

  <!-- HOT DEAL PRODUCT -->
  <div class="product">
    <div class="badge hot">🔥 HOT DEAL</div>
    <img src="images/product1.jpg" alt="Hot Deal Product">
    <h3>Trending Gadget of the Day</h3>
    <p class="price">₹1,499</p>
    <a href="https://amzn.to/YOUR_SHORT_LINK" target="_blank">
      <button>Buy on Amazon App</button>
    </a>
    <p class="note">📌 App opens if installed. If not, tap ⋮ → Open in browser</p>
  </div>

  <!-- BEST DEAL PRODUCT -->
  <div class="product">
    <div class="badge best">⭐ BEST DEAL</div>
    <img src="images/product2.jpg" alt="Best Deal Product">
    <h3>Best Value Product</h3>
    <p class="price">₹2,999</p>
    <a href="https://amzn.to/YOUR_SHORT_LINK" target="_blank">
      <button>Buy on Amazon App</button>
    </a>
    <p class="note">📌 App opens if installed</p>
  </div>

  <!-- NORMAL PRODUCT -->
  <div class="product">
    <img src="images/product3.jpg" alt="Daily Best Find">
    <h3>Daily Best Find</h3>
    <p class="price">₹1,199</p>
    <a href="https://amzn.to/YOUR_SHORT_LINK" target="_blank">
      <button>Buy on Amazon App</button>
    </a>
    <p class="note">📌 App opens if installed</p>
  </div>

</section>

<footer>
© 2026 dailybestfinds21 | Affiliate Disclosure: We may earn commission from qualifying purchases.
</footer>

</body>
</html>
