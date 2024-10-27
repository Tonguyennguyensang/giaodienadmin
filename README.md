<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đăng nhập</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
        }
        .login-container {
            width: 400px;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .login-container h2 {
            color: #2a2a5a;
        }
        .login-container p {
            color: #666;
            margin-bottom: 20px;
        }
        .input-field {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        .checkbox-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 14px;
            color: #666;
        }
        .login-btn {
            width: 100%;
            padding: 12px;
            background-color: #2a2a5a;
            color: #ffffff;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
        }
        .login-btn:hover {
            background-color: #1d1d47;
        }
        .forgot-password {
            text-decoration: none;
            color: #666;
        }
        .forgot-password:hover {
            color: #333;
        }
    </style>
</head>
<body>

<div class="login-container">
    <h2>Login</h2>
    <p>Chào!</p>
    <form>
        <input type="email" class="input-field" placeholder="nhập email">
        <input type="password" class="input-field" placeholder="nhập mật khẩu">
        
        <div class="checkbox-container">
            <label><input type="checkbox"> Remember Password</label>
            <a href="#" class="forgot-password">Quên mật khẩu</a>
        </div>

        <button type="submit" class="login-btn">Login</button>
    </form>
</div>

</body>
</html>