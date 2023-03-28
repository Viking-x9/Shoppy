<html>
<head>
    <title>Login Page</title>
    <style>
        .container {
            width: 400px;
            margin: 0 auto;
            border: 1px solid black;
            padding: 20px;
        }

        .form-group {
            margin-bottom: 10px;
        }

        .form-label {
            display: block;
            font-weight: bold;
        }

        .form-input {
            display: block;
            width: 100%;
            padding: 5px;
        }

        .form-button {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: blue;
            color: white;
            border: none;
        }

        .form-error {
            color: red;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Login Page</h1>
        <form id="login-form" method="post" action="login.php">
            <div class="form-group">
                <label class="form-label" for="email">Email Address</label>
                <input class="form-input" type="email" id="email" name="email" required>
                <span class="form-error" id="email-error"></span>
            </div>
            <div class="form-group">
                <label class="form-label" for="phone">Phone Number</label>
                <input class="form-input" type="tel" id="phone" name="phone" required>
                <span class="form-error" id="phone-error"></span>
            </div>
            <div class="form-group">
                <label class="form-label" for="password">Password</label>
                <input class="form-input" type="password" id="password" name="password" required>
                <span class="form-error" id="password-error"></span>
            </div>
            <div class="form-group">
                <button class="form-button" type="submit" id="submit">Login</button>
            </div>
        </form>
    </div>

    <!-- This script handles the email verification logic -->
    <script>

        // Get the form elements
        var form = document.getElementById("login-form");
        var email = document.getElementById("email");
        var phone = document.getElementById("phone");
        var password = document.getElementById("password");
        var submit = document.getElementById("submit");
        var emailError = document.getElementById("email-error");
        var phoneError = document.getElementById("phone-error");
        var passwordError = document.getElementById("password-error");

        // Add an event listener to the form submit
        form.addEventListener("submit", function(event) {

            // Prevent the default form submission
            event.preventDefault();

            // Clear any previous errors
            emailError.textContent = "";
            phoneError.textContent = "";
            passwordError.textContent = "";

            // Validate the email address
            if (!validateEmail(email.value)) {
                // Display an error message
                emailError.textContent = "Please enter a valid email address.";
                return;
            }

            // Validate the phone number
            if (!validatePhone(phone.value)) {
                // Display an error message
                phoneError.textContent = "Please enter a valid phone number.";
                return;
            }

            // Validate the password
            if (!validatePassword(password.value)) {
                // Display an error message
                passwordError.textContent = "Please enter a strong password.";
                return;
            }

            // Send an email verification code to the user
            sendEmailVerification(email.value, function(code) {

                // Prompt the user to enter the code
                var userCode = prompt("Please enter the verification code sent to your email.");

                // Check if the code matches
                if (userCode === code) {
                    // Submit the form
                    form.submit();
                } else {
                    // Display an error message
                    alert("The verification code is incorrect. Please try again.");
                }
                
            });

            
        });

        // A function to validate an email address using a regular expression
        function validateEmail(email) {
            
           var regex = /^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$/;

           return regex.test(email);
            
        }

        // A function to validate a phone number using a regular expression
        function validatePhone(phone) {

           var regex = /^\d{10}$/;

           return regex.test