<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Login</title>
    <style>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f5f5f5;
}

.container {
    background-color: #fff;
    padding: 30px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    text-align: center;
}

.container img {
    width: 100px;
    margin-bottom: 20px;
}

h1 {
    font-size: 24px;
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
    width: 100%;
}

.form-group {
    margin-bottom: 15px;
}

label {
    display: block;
    margin-bottom: 5px;
}

input[type="text"], input[type="password"] {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
    font-size: 16px;
}

button {
    background-color: #387ef5;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 3px;
    font-size: 16px;
    cursor: pointer;
    margin-top: 15px;
}

a {
    color: #387ef5;
    text-decoration: none;
    margin-top: 5px;
    display: block;
}
</style>
</head>
<body>
    <div class="container">
        <img src="images/instagram-logo.png" alt="Instagram logo">
        <h1>Welcome back</h1>
        <form action="#">
            <div class="form-group">
                <label for="username">Username</label>
                <input type="text" id="username" name="username" placeholder="Enter your username">
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" placeholder="Enter your password">
            </div>
            <button type="submit">Log In</button>
            <a href="#">Forgot password?</a>
        </form>
        <p>Don't have an account? <a href="#">Sign up</a></p>
    </div>
</body>
</html>
