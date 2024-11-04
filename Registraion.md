```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stanley's Pharmacy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="navbar">
            <h1>Stanley Pharmacy</h1>
            <div class="auth-buttons">
                <a href="index.html">Sign Up</a>
                <a href="login.html">Log In</a>
            </div>
        </div>
    </header>

    <section class="registration-form">
        <h2>New User Registration</h2>
        <form action="login.html" method="get">
            <div class="form-group">
                <input type="text" name="firstname" id="" placeholder="First Name">
                <input type="text" name="firstname" id="" placeholder="Last Name">
            </div>
            <div class="form-group">
                <input type="email" name="email" id="" placeholder="Email ID">
            </div>
            <div class="form-group">
                <input type="password" name="newpassword" id="" placeholder="New password">
                <input type="password" name="conpassword" id="" placeholder="Confirm password">
            </div>
            <div class="form-group">
                <label >
                    <input type="radio" name="gender" id="" value="Male">Male
                </label>
                <label >
                    <input type="radio" name="gender" id="" value="Female">Female
                </label>
                <input type="date" name="DOB" id="" placeholder="Date of Birth">
            </div>
            <div class="form-group">
                <input type="text" name="Cont" id="" placeholder="Contact No">
                <input type="text" name="city" id="" placeholder="City">
            </div>
            <div class="form-group">
                <textarea name="Health" placeholder="Health Information"></textarea>
            </div>
            <div class="form-group">
                <label >
                    <input type="checkbox" name="checkbox" >I agree to the terms and conditions
                </label>
                <button type="submit">Save</button>
            </div>
        </form>
    </section>
    <script src="script.js"></script>
</body>
</html>
```
