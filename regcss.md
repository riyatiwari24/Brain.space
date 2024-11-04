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

.registration-form{
    width: 50%;
    margin: 2rem auto;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.registration-form h2{
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
    gap: 1rem;
}

form input[type="text"],
form input[type="email"],
form input[type="password"],
form input[type="date"],
form textarea{
    flex: 1;
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 3px;
}

form textarea{
    resize: none;
    height: 80px;
}

form label{
    display: flex;
    align-items: center;
    gap: 0.5rem;
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

form button[type="submit"]:hover{
    background-color: #45a049;
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
