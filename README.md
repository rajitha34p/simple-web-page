<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      display: flex;
      height: 100vh;
    }
    .container {
      display: flex;
      width: 100%;
    }
    .left {
      flex: 1;
      background: url('suit-image.jpg') no-repeat center center/cover;
    }
    .right {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f4f4f4;
    }
    .login-form {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      width: 300px;
    }
    .login-form h2 {
      margin-bottom: 20px;
      text-align: center;
    }
    .login-form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    .login-form input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .login-form button {
      width: 100%;
      padding: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    .login-form button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="left"></div>
    <div class="right">
      <div class="login-form">
        <h2>Login</h2>
        <form>
          <label for="username">Username</label>
          <input type="text" id="username" name="username" placeholder="Enter your username">
          <label for="password">Password</label>
          <input type="password" id="password" name="password" placeholder="Enter your password">
          <button type="submit">Login</button>
        </form>
      </div>
    </div>
  </div>
</body>
</html>


