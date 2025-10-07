# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Sports Day</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="college-header">
    <h1>Saveetha Engineering College</h1>
    <p>(Autonomous) | College Code: 1216</p>
    <div class="auth-buttons">
      <button>Log in</button>
      <button>Register</button>
    </div>
  </header>

  <section class="sports-event">
    <h2>SPORTS DAY EVENT</h2>
    <ul>
      <li>KHO KHO</li>
      <li>VOLLEY BALL</li>
      <li>FOOT BALL</li>
      <li>RUNNING</li>
      <li>HANDBALL</li>
      <li>HOCKEY</li>
    </ul>
  </section>

  <section class="registration-form">
    <h2>REGISTRATION FORM</h2>
    <form>
      <label for="name">NAME:</label>
      <input type="text" id="name" name="name" required>

      <label for="dept">DEPT:</label>
      <input type="text" id="dept" name="dept" required>

      <label for="sport">SPORT:</label>
      <select id="sport" name="sport">
        <option value="kho">KHO KHO</option>
        <option value="volley">VOLLEY BALL</option>
        <option value="football">FOOT BALL</option>
        <option value="running">RUNNING</option>
        <option value="handball">HANDBALL</option>
        <option value="hockey">HOCKEY</option>
      </select>

      <button type="submit">Submit</button>
    </form>
  </section>

  <section class="contact-us">
    <h2>Contact Us</h2>
    <p>Coordinator: Saiprasveen</p>
    <p>Mobile No: 9898989898</p>
  </section>
</body>
</html>
```
```
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
  color: #333;
}

header.college-header {
  background: #004080;
  color: white;
  text-align: center;
  padding: 20px;
}

.auth-buttons {
  margin-top: 10px;
}

.auth-buttons button {
  margin: 5px;
  padding: 10px 20px;
  background: #ffcc00;
  border: none;
  cursor: pointer;
  font-weight: bold;
}

section {
  margin: 20px;
  padding: 20px;
  background: white;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.sports-event h2 {
  color: #d9534f;
}

.sports-event ul {
  list-style: none;
  padding: 0;
}

.sports-event li {
  background: #e6f7ff;
  margin: 5px 0;
  padding: 10px;
  border-left: 5px solid #007acc;
}

.registration-form form {
  display: flex;
  flex-direction: column;
}

.registration-form label {
  margin-top: 10px;
  font-weight: bold;
}

.registration-form input,
.registration-form select {
  padding: 8px;
  margin-top: 5px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.registration-form button {
  margin-top: 15px;
  padding: 10px;
  background: #28a745;
  color: white;
  border: none;
  font-weight: bold;
  cursor: pointer;
}

.contact-us h2 {
  color: #5bc0de;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-10-07 160132.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
