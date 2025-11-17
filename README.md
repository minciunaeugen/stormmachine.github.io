# stormmachine.github.io


[welcome.html](https://github.com/user-attachments/files/23592150/welcome.html)
<h1>Welcome!</h1>
<html lang="en">
<body>
    <div class="container">
        <h1>Welcome!</h1>
        <p>This is your control panel (now static).</p>
        
        <hr>
        
        <h2>Navigation Menu</h2>
        <p>
            <a href="read_users.html">View User List & Administer</a> 
        </p>
        <p>
            <a href="register.html">Register New User</a>
        </p>
        
        <hr>
        
        <p><a href="login.html">Logout</a></p>
    </div>
</body>
</html>

[index.html](https://github.com/user-attachments/files/23592162/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>User Login</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    
    <div class="container">
        <h1>Login</h1>

        <form method="POST"> 
    </form>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="parola" required><br>

            <input type="submit" value="Login">
        
        
        <p style="text-align: center; margin-top: 20px;">
            <a href="register.html">Don't have an account? Register here</a>
        </p>
    </div>
</body>
</html>




[read_users.html](https://github.com/user-attachments/files/23592168/read_users.html)
<table class='users-table'>
            <tr><th>ID</th><th>Name</th><th>Email</th><th>Actions</th></tr>
            
            <tr>
                <td>1</td>
                <td>John Doe (Static)</td>
                <td>john.doe@example.com</td>
                <td>
                    <a href="#">Edit</a> | 
                    <a href="#">Delete</a> 
                </td>
            </tr>
            
            <tr>
                <td>2</td>
                <td>Jane Smith (Static)</td>
                <td>jane.smith@example.com</td>
                <td>
                    <a href="#">Edit</a> | 
                    <a href="#">Delete</a>
                </td>
            </tr>
            
        </table>
        
        <p style='margin-top: 20px;'><a href='welcome.html'>Back to Control Panel</a></p>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>User Administration Panel</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <div class="container">
        <h1>Registered Users List</h1>

       
    </div>
</body>
</html>



[Uploading register.html…]()
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Formular de Înregistrare</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Înregistrare Utilizator Nou</h1>

    <form method="POST"> 
    </form>
        <label for="nume">Nume Complet:</label><br>
        <input type="text" id="nume" name="nume" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="parola">Parolă:</label><br>
        <input type="password" id="parola" name="parola" required><br><br>

        <input type="submit" value="Înregistrează-te">
   

</body>
</html>


[Uploading style.css…]()
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh; /* Asigură că se centrează pe toată înălțimea paginii */
}

.container {
    background: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

h1 {
    text-align: center;
    color: #007bff;
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

input[type="text"],
input[type="email"],
input[type="password"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box; /* Include padding și border în lățimea totală */
}

input[type="submit"] {
    background-color: #007bff;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    width: 100%;
}

input[type="submit"]:hover {
    background-color: #0056b3;
}


/* Adaugă la finalul fișierului style.css */

.users-table {
    width: 100%;
    border-collapse: collapse; /* Înlătură spațiul dintre celule */
    margin-top: 20px;
}

.users-table th, .users-table td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

.users-table th {
    background-color: #007bff;
    color: white;
}

.users-table tr:nth-child(even) {
    background-color: #f2f2f2;
}
