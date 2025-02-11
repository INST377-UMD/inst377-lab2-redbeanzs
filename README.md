[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LHOh9PUe)
# INST377-Lab

# Name (Please Input your name): Stina Drill[Uploading lab2.html…]()

<html>
<head>
    <title>Newsletter Sign-Up</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
        }

        button[type="submit"] {
            background-color: aquamarine;
            color: #333;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            margin-top: 20px;
            font-size: 16px;
            transition: background-color 0.3s;
        }

        button[type="submit"]:hover {
            background-color: #00b7b7;
        }


        .form-input {
            margin: 10px 0;
        }

        .form-input input {
            padding: 10px;
            font-size: 16px;
            width: 100%;
            box-sizing: border-box;
        }

        label {
            font-size: 18px;
            display: block;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <h1>Sign Up for Our Newsletter!</h1>
    <form name="newsletterForm" method="get" action="thank.html">
        <!-- Textbox with Required Field -->
        <div class="form-input">
            <label for="firstName">First Name:</label>
            <input type="text" id="firstName" name="firstName" required>
        </div>
        
        <!-- Textbox with Required Field -->
        <div class="form-input">
            <label for="lastName">Last Name:</label>
            <input type="text" id="lastName" name="lastName" required>
        </div>

        <!-- Email Input -->
        <div class="form-input">
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required>
        </div>

        <hr>

        <label for="frequency">How often would you like to receive updates?</label>
        <div class="form-input">
            <input type="radio" name="frequency" value="daily"> Daily Updates <br>
            <input type="radio" name="frequency" value="weekly"> Weekly Digest <br>
            <input type="radio" name="frequency" value="monthly"> Monthly Summary <br>
        </div>

        <button type="submit">Subscribe</button>
    </form>
</body>
</html>

[Uploading thank.html…]()
<html>
    <head>
        <title>Thank You</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                background-color: #dcdcdc;
            }
            h1 {
                text-align: center;
                font-size: 36px;
                color: #333;
            }
            .content {
                text-align: center;
                font-size: 18px;
                color: #333;
                padding: 20px;
            }
            img {
                width: 50%; 
                display: block;
                margin: 20px auto;
            }
        </style>
    </head>
    <body>
        <h1>Thank You for Subscribing!</h1>
        <div class="content">
            <p>We appreciate your subscription! Stay tuned for exciting news and updates!</p>
        </div>

        <!-- Image Section -->
        <img src="Thankya.jpg" alt="Thank You Image">

    </body>
</html>


![Thankya](https://github.com/user-attachments/assets/76686745-5d35-4a19-a17e-82d4d6ae8301)
# Comments: 

