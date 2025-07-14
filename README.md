# insta--sign_up-page

---------------First HTML code---------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="try.css">
</head>
<body>

     <div class="container">

    <!-- Language Selector -->
    

    <!-- Login Box -->
    <div class="login-box">
        <div class="language-bar">
      <select>
        <option>English</option>
        <option>Hindi</option>
        <option>Español</option>
        <option>Français</option>
      </select>
    </div>
      <h1 class="logo">Instagram</h1>

      <input type="text" placeholder="Email or Phone Number" class="input-field">
      <input type="password" placeholder="Password" class="input-field">

      <div class="forgot-password">
        <a href="#">Forgotten password?</a>
      </div>

      <div class="create-account">
        <button>Create Account</button>
      </div>
       <div class="meta-text">
      Meta
    </div>
    </div>

    <!-- Footer -->
   
  </div>
   
</body>
</html>


--------------------First CSS code--------------------

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.container {
  text-align: center;
  width: 300px;
}

.language-bar {
  margin-bottom: 20px;
  display: flex;
  justify-content: center;
}

.language-bar select {
  padding: 8px;
  border: none;
  border-radius: 6px;
  font-size: 14px;
  background-color: #222;
  color: #fff;
  width: 200px; /* Optional fixed width */
  text-align: center;
}


.login-box {
  background-color: #111;
  padding: 30px 20px;
  border-radius: 10px;
  color: #fff;
}

.logo {
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 20px;
}

.input-field {
  width: 100%;
  padding: 10px;
  margin-bottom: 12px;
  border: none;
  border-radius: 10px;
  background-color: #222;
  color: #fff;
}

.input-field::placeholder {
  color: #aaa;
}

.forgot-password {
  margin-bottom: 20px;
}

.forgot-password a {
  color: #aaa;
  text-decoration: none;
  font-size: 14px;
}

.create-account button {
  width: 100%;
  padding: 10px;
  border: 2px solid #0095f6;
  background-color: transparent;
  color: #0095f6;
  border-radius: 20px;
  font-weight: bold;
  cursor: pointer;
  transition: background-color 0.3s;
}

.create-account button:hover {
  background-color: #0095f6;
  color: white;
}

.meta-text {
  margin-top: 20px;
  color: #aaa;
  font-size: 14px;
}


















