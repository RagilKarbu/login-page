<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1,0">
        <title>Login Page</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="login-box">
            <div class="login-header">
                <header>Login</header>
            </div>
            <div class="input-box">
                <input type="text" class="input-field" placeholder="Name" autocomplete="off" required>
            </div>
            <div class="input-box">
                <input type="password" class="input-field" placeholder="Password" autocomplete="off" required>
            </div>
            <div class="forgot">
                <selection>
                    <input type="checkbox" id="check">
                    <label for="check">remember me</label>
                </selection>
                <selection>
                    <a href="*">Forgot Password</a>
                </selection>
            </div>
            <div class="input-submit">
                <button class="submit-btn" value="login" id="submit" onclick="login()"></button>
                <label for="submit"><a href="alogin.html">Sign In</a></label>
            </div>
            <div>
                <p>kalo gatau brati bukan buat kamu hehehe</p>
            </div>
        </div>
    </body>
</html>
