# IamBATMAN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Input Form</title>
    <h1 style="font-size:50px; text-align:center; color:black;">CareerCanva</b></h1>
    <img style="width: 33%;" src="C:\Users\manvi\OneDrive\Desktop\careercanvalogo.jpg">
</head>
<hr>
<body>

<style>
        .container {
            text-align: center;
            color: white;
        }

        .bg-image {
            width: 100%;
            height: auto;
            z-index: -1;
        }

        .form-container {
            position: absolute;
            top: 50%;
            left: 50%;
            right: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(0, 0, 0.8, 0.7);
            padding: 20px;
            border-radius: 10px;
            max-width: 400px;
            width: 90%;
            color: lavender;
        }

        form {
            color: lavender;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: none;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>


    <div class="container">
        <img class="bg-image" src="C:\Users\manvi\OneDrive\Desktop\64f5cf540c42dde192fd695b_Rectangle (32).svg" alt="Background Image">
        <div class="form-container">
            <h1>Profile</h1>
            
            <form action="submit_form.php" method="POST" style="background-color: rgba(0, 0, 0, 0.7); padding: 20px; border-radius: 10px; max-width: 400px; margin: 0 auto; margin-top: 50px;">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

           <label for="message">Message:</label><br>
           <textarea id="message" name="message" rows="4" required></textarea><br><br>

           <input type="submit" value="Submit" style="background-color: #007bff; color: #fff; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; transition: background-color 0.3s;">
           </form>
        </div>
    </div>
</body>
</html>
