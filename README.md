# dnx-group-of-company


/* ---------- GLOBAL ---------- */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Poppins", sans-serif;
  line-height: 1.6;
  background-color: #f7fafd;
  color: #333;
}

/* ---------- NAVIGATION ---------- */
header {
  background: #0b3d91;
  padding: 15px 0;
  text-align: center;
}

header nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
  font-weight: 600;
}

header nav a:hover {
  color: #ffd700;
}

/* ---------- BUTTONS ---------- */
.btn {
  display: inline-block;
  padding: 10px 22px;
  background: #0b3d91;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 600;
  margin-top: 15px;
}

.btn:hover {
  background: #063271;
}

/* ---------- MAIN SECTIONS ---------- */
.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 30px 0;
}

h1 {
  margin-bottom: 10px;
  color: #0b3d91;
}

h2 {
  margin: 12px 0;
  color: #0b3d91;
}

/* ---------- FORMS ---------- */
form {
  max-width: 400px;
  margin: auto;
  padding: 20px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
}

form input {
  width: 100%;
  padding: 10px;
  margin: 8px 0;
  border: 1px solid #ccc;
  border-radius: 4px;
}

form button {
  width: 100%;
  padding: 10px;
  background: #0b3d91;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-weight: 600;
}

form button:hover {
  background: #063271;
}

/* ---------- DASHBOARD CARD ---------- */
.card {
  background: #fff;
  padding: 18px;
  margin: 12px 0;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
}

.card h3 {
  color: #0b3d91;
}


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

<div class="container" style="text-align:center; padding-top:30px;">
  <h1>DNx Group of Company</h1>
  <h2>Grow Together. Succeed Together.</h2>
  <p>Welcome to our modern marketing and growth platform.</p>
  <a href="register.html" class="btn">Register Now</a>
  <a href="login.html" class="btn">Login</a>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About DNx</title>
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
  <h1>About Us</h1>
  <p>DNx Group of Company is a forward‑thinking marketing platform dedicated to your success.</p>
  <p>We help entrepreneurs grow online with tools, support, and opportunities.</p>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact DNx</title>
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
  <h1>Contact Us</h1>
  <p>Phone: +91 7338395625</p>
  <p>Email: tgshadab1255@gmail.com</p>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Register - DNx</title>
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
  <h1>Register</h1>
  <form>
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button>Register</button>
  </form>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login - DNx</title>
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
  <h1>Login</h1>
  <form action="dashboard.html">
    <input type="email" placeholder="Email" required>
    <input type="password" placeholder="Password" required>
    <button>Login</button>
  </form>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dashboard - DNx</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="login.html">Logout</a>
  </nav>
</header>

<div class="container">
  <h1>Your Dashboard</h1>
  
  <div class="card">
    <h3>Referral Link</h3>
    <p>https://dnxgroup.com/ref=USER123</p>
  </div>
  
  <div class="card">
    <h3>Total Earnings</h3>
    <p>₹0.00</p>
  </div>
</div>

</body>
</html>
