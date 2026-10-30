HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="registration.html">Register</a></li>
            </ul>
        </nav>
        <h1>Student Registration Portal</h1>
        <p>Please fill out the form below to register for the upcoming academic semester.</p>
    </header>

    <main>
        <!-- Student Registration Form -->
        <section>
            <form action="#" method="POST">
                
                <!-- Full Name Field -->
                <div>
                    <label for="fullname">Full Name:</label><br>
                    <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required>
                </div>
                <br>

                <!-- Email Field -->
                <div>
                    <label for="email">Email Address:</label><br>
                    <input type="email" id="email" name="email" placeholder="student@example.com" required>
                </div>
                <br>

                <!-- Password Field -->
                <div>
                    <label for="password">Password:</label><br>
                    <input type="password" id="password" name="password" placeholder="Create a secure password" required>
                </div>
                <br>

                <!-- Phone Number Field -->
                <div>
                    <label for="phone">Phone Number:</label><br>
                    <input type="tel" id="phone" name="phone" placeholder="123-456-7890" required>
                </div>
                <br>

                <!-- Age Field -->
                <div>
                    <label for="age">Age:</label><br>
                    <input type="number" id="age" name="age" min="16" max="100" placeholder="18" required>
                </div>
                <br>

                <!-- Submit Button -->
                <div>
                    <button type="submit">Register Now</button>
                </div>

            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Student Portal. All rights reserved.</p>
    </footer>

</body>
</html>
Steps to Complete Your Submission:
Save the File: Copy the code above and save it inside your project folder under the exact name registration.html.

Test in Browser: Double-click registration.html to open it in your web browser. Check that:

Every input field has a properly linked <label>.

Correct input types (text, email, password, tel, number) function as expected.

Attempting to click "Register Now" with empty fields triggers the browser's required validation warning.

Take a Screenshot: Take a clean browser screenshot showing your working registration form.

Final Submission: Submit both your registration.html file and your browser screenshot!