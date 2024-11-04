```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    font-family: Arial, Helvetica, sans-serif;
}

.navbar{
    background-color: #4CAF50;
    color: white;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar h1{
    font-size: 1.5rem;
}
.auth-buttons button{
    background-color: white;
    border: none;
    color: #4CAF50;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

form button[type="submit"]{
    background-color: #4CAF50;
    color: white;
    padding: 0.7rem;
    border: none;
    border-radius: 3px;
    cursor: pointer;
    font-size: 1rem;
}

.loginform{

        width: 50%;
        margin: 2rem auto;
        padding: 1rem;
        border: 1px solid #ddd;
        border-radius: 5px;
    
}

.loginform h2{
    color: #4CAF50;
    text-align: center;
    margin-bottom: 1rem;
}

form{
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.form-group{
    display: flex;
    
}

form input[type="email"],
form input[type="password"]{
    width: 100%;
    padding: 0.5rem;
    border: 1px solid #ccc;
    cursor: pointer;
    font-size: 1rem;
    border-radius: 3px;
}

form button[type="submit"]:hover{
    background-color: #45a049;
    color: white;
    padding: 0.7rem;
    border: none;
    border-radius: 3px;
    cursor: pointer;
    font-size: 1rem;
 }

 .auth-buttons a{
    background-color: #fff;
    color: #4CAF50;
    padding: 0.5rem 1rem;
    text-decoration: none;
    margin-left: 0.5rem;
    border-radius: 3px;
 }

 .auth-buttons a :hover{
    background-color: #45a049;
    color: white;
 }
```
