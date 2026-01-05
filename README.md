# dnx-group-of-company  </div>

  /* ---------- GLOBAL ---------- */
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family: "Poppins", sans-serif; background:#f7fafd; color:#333; }
a { text-decoration:none; }

/* ---------- HEADER & NAV ---------- */
header { background:#0b3d91; padding:15px 0; text-align:center; }
header nav a { color:#fff; margin:0 15px; font-weight:600; }
header nav a:hover { color:#ffd700; }

/* ---------- BUTTON ---------- */
.btn { display:inline-block; padding:10px 22px; background:#0b3d91; color:#fff; border-radius:5px; font-weight:600; margin-top:15px; }
.btn:hover { background:#063271; }

/* ---------- CONTAINER ---------- */
.container { width:90%; max-width:1100px; margin:auto; padding:30px 0; text-align:center; }

/* ---------- HEADINGS ---------- */
h1 { margin-bottom:10px; color:#0b3d91; }
h2 { margin:12px 0; color:#0b3d91; }

/* ---------- FORMS ---------- */
form { max-width:400px; margin:auto; padding:20px; background:#fff; border-radius:8px; box-shadow:0 2px 6px rgba(0,0,0,0.15);}
form input { width:100%; padding:10px; margin:8px 0; border:1px solid #ccc; border-radius:4px; }
form button { width:100%; padding:10px; background:#0b3d91; color:#fff; border:none; border-radius:4px; font-weight:600; cursor:pointer; }
form button:hover { background:#063271; }

/* ---------- DASHBOARD CARD ---------- */
.card { background:#fff; padding:18px; margin:12px 0; border-radius:8px; box-shadow:0 2px 6px rgba(0,0,0,0.15); }
.card h3 { color:#0b3d91; }

/* ---------- RESPONSIVE ---------- */
@media(max-width:768px){ .container { width:95%; } header nav { font-size:14px; } }

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>DNx Group of Company</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="login.html">Login</a>
  </nav>
</header>

<div class="container">
  <h1>DNx Group of Company</h1>
  <h2>Grow Together. Succeed Together.</h2>
  <p>Welcome to our modern marketing and growth platform.</p>
  <a href="register.html" class="btn">Register Now</a>
  <a href="login.html" class="btn">Login</a>
</div>
</body>
</html>
