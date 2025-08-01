Sign Up Android App
📱 Overview
This is a simple Android application built with Kotlin and ConstraintLayout.
The app allows users to:

Enter a username and password

Confirm password

Sign up (with validation)

Open external links (Google, Twitter, Facebook)

The app is designed with a clean UI and basic navigation for beginners learning Android development.

✨ Features
Custom UI using ConstraintLayout

EditText fields with custom background

Password confirmation check

Buttons to open external links:

Google

Twitter (X)

Facebook

Toast messages for validation feedback

🛠 Tech Stack
Language: Kotlin

IDE: Android Studio

UI: XML Layout with ConstraintLayout

Architecture: Single Activity

📂 Project Structure
activity_main.xml
Contains the UI layout:

ImageView, TextView, EditText, and Button.

MainActivity.kt
Handles:

Button click listeners

Password confirmation validation

Opening URLs using Intent

🚀 How It Works
User enters:

Username

Password

Confirm Password

Click Sign Up:

If passwords don’t match → Show a Toast message.

Click on Google/Twitter/Facebook buttons:

Opens the respective website in the browser.

📷 Screens
<img width="392" height="822" alt="image" src="https://github.com/user-attachments/assets/8102f72a-59bb-417d-b706-1a153fb89686" />


🔮 Future Improvements
Add Firebase authentication.

Add form validations (email format, password strength).

Improve UI with Material Design.

👩‍💻 Author
Developed by Basmala Mohamed

