<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>National scholarship portal</title>
</head>
<style>
    /* General Styles */
body {
    font-family: 'Arial', sans-serif;
    background-color: #efefef;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    flex-direction: column;
}

/* Image Styling */
.india {
    width: 300px;
    height: auto;
    margin-bottom: 20px;
    margin-top: 160px;
}

/* Form Container */
.form-container {
    background-color: #ffffff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 80%;
    max-width: 400px;
}

h2 {
    text-align: center;
    color: #333333;
    margin-bottom: 0px;
    font-size: 24px;
}

h3 {
    text-align: center;
    color: #333333;
    margin-top: 2px;
    margin-bottom: 20px;
    font-size: 15px;
}

/* Form Labels */
label {
    display: block;
    font-weight: bold;
    margin-bottom: 8px;
    color: #555555;
}

/* Form Inputs */
input[type="text"],
input[type="date"],
input[type="email"],
input[type="tel"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #cccccc;
    border-radius: 5px;
    font-size: 16px;
    box-sizing: border-box;
    transition: border-color 0.3s ease;
}

input[type="text"]:focus,
input[type="date"]:focus,
input[type="email"]:focus,
input[type="tel"]:focus
{
    border-color: #007bff;
    outline: none;
}

/* Buttons */
.button-group {
    display: flex;
    justify-content: space-between;
    gap: 10px;
}

input[type="submit"],
input[type="reset"] {
    flex: 1;
    padding: 12px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

input[type="submit"] {
    background-color: #007bff;
    color: #ffffff;
}

input[type="submit"]:hover {
    background-color: hsl(211, 100%, 35%);
}

input[type="reset"] {
    background-color: #f44336;
    color: #ffffff;
}

input[type="reset"]:hover {
    background-color: #d32f2f;
}

/* Footer */
.footer {
    text-align: center;
    margin-top: 20px;
    color: #777777;
    font-size: 14px;
}

button {
    background-color: #007bff;
    color: #ffffff;
    width: 100%;
    padding: 10px;
    border: 1px solid #cccccc;
    border-radius: 5px;
    font-size: 16px;
    box-sizing: border-box;
    transition: border-color 0.3s ease;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    cursor: pointer;
}
    /* Style the dropdown */
select {
width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #cccccc;
    border-radius: 5px;
    font-size: 16px;
    box-sizing: border-box;
    transition: border-color 0.3s ease;
}

/* Style the options */
option {
padding: 10px;
background-color: #e0e0e0;
}

option:hover {
background-color: #ccc;
}
</style>
<body>
    <div class="main-container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Government_of_India_logo.svg/640px-Government_of_India_logo.svg.png" alt="Government of India Logo" class="india">
    </div>
    <div class="form-container">
        <h2>Scholarship Application Form</h2>
        <h3>National Scholarship Portal</h3>

        <form method="POST" action="https://script.google.com/macros/s/AKfycbxkncPSovemDMWIsTrwHDRmdvx9fgoJDTaP7wlFgvD5b-P_dGnW4rPRfNXNZV4jIJQd/exec">
            <label for="firstName">First Name:</label>
            <input type="text" id="firstName" name="First Name" placeholder="Enter your first name" required aria-label="First Name">

            <label for="lastName">Last Name:</label>
            <input type="text" id="lastName" name="Last Name" placeholder="Enter your last name" required aria-label="Last Name">

            <label for="College Name:">College Name:</label>
            <input type="text" id="clg" name="College Name" required aria-label="College Name" placeholder="Enter your college name">

            <label for="Course">Choose your course pursuing</label>
            <select id="Course" name="Course">
            <option value="select">select</option>   
            <option value="CSE">CSE/specializations</option>
            <option value="ECE">ECE</option>
            <option value="EEE">EEE</option>
            <option value="MECH">MECH</option>
            <option value="CIVIL">CIVIL</option>
            </select>

            <!-- <label for="email">Course:</label>
            <input type="text" id="Course" name="Course" placeholder="Enter your course pursuing" required aria-label="Course"> -->

            <label for="mobile">Mobile Number:</label>
            <input type="tel" id="mobile" name="Mobile" placeholder="Enter your mobile number" pattern="[0-9]{10}" required aria-label="Mobile Number">

            <div class="button-group">
                <input type="submit" value="Submit">
                <input type="reset" value="Reset">
            </div>
        </form>
    </div>
    <div class="footer">
        <p style="margin-bottom: 2px;">© 2025 National Scholarship Portal</p>
        <p style="margin-top: 2px;">NSRIET</p>
    </div>
</body>
</html>
