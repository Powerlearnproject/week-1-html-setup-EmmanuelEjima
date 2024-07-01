[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Dr_CRy30)
# Introduction to HTML

## Description:
In this week, you will set up a basic HTML template for the Expense Tracker Application interface. You will begin by gaining an understanding of web development fundamentals. This serves as a foundational step in the development process and will provide you with hands-on experience in building web interfaces for real-world applications.

### Assignment: Create a Basic HTML Template:
        Design a basic HTML template for the Expense Tracker Application interface.
        Your page should include the below:

        1. title
        2. meta tag for display
        3. meta tag for character set
        4. header
        5. heading
        6. paragraph
        7. basic registration form
        8. table displaying common user information: name, email, phone number.
        9. an image
        10. an external link to https://google.com
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Tracker Application</title>
</head>
<body>
    <header>
        <h1>Welcome to the Expense Tracker Application</h1>
    </header>

    <section>
        <h2>Track Your Expenses Efficiently</h2>
        <p>Use this application to keep a detailed log of your expenses and manage your budget effectively.</p>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="username">Username:</label><br>
            <input type="text" id="username" name="username"><br><br>
            
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>
            
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password"><br><br>
            
            <input type="submit" value="Register">
        </form>
    </section>

    <section>
        <h2>User Information</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Phone Number</th>
            </tr>
            <tr>
                <td>Ejima Emmanuel</td>
                <td>emmanuelejima12@gmail.com</td>
                <td>08109801337</td>
            </tr>
            <tr>
                <td>Musa John</td>
                <td>musajohn12@gmail.com</td>
                <td>090-765-4321</td>
            </tr>
        </table>
    </section>

    <section>
        <h2>Application Image</h2>
        <img src="https://via.placeholder.com/150" alt="Expense Tracker">
    </section>

    <footer>
        <p>For more information, visit <a href="https://google.com" target="_blank">Google</a>.</p>
    </footer>
</body>
</html>


### Submission:
        When you push and commit changes to the index.html file, your submission will be received for evaluation.

