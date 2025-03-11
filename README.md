# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Example Page</title>
</head>
<body>
  <!-- Ordered List with Roman Numerals -->
  <h1>Ordered List</h1>
  <ol type="I">
    <li>First Item</li>
    <li>Second Item</li>
    <li>Third Item</li>
  </ol>

  <!-- External Image from Pexels -->
  <h1>External Image</h1>
  <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Sample Image from Pexels" width="400">

  <!-- Table of 5 Contacts -->
  <h1>Contact Table</h1>
  <table border="1">
    <thead>
      <tr>
        <th>Name</th>
        <th>Address</th>
        <th>Mobile</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>John Doe</td>
        <td>123 Main St</td>
        <td>123-456-7890</td>
        <td>john@example.com</td>
      </tr>
      <tr>
        <td>Jane Smith</td>
        <td>456 Elm St</td>
        <td>987-654-3210</td>
        <td>jane@example.com</td>
      </tr>
      <tr>
        <td>Bob Johnson</td>
        <td>789 Oak St</td>
        <td>456-789-0123</td>
        <td>bob@example.com</td>
      </tr>
      <tr>
        <td>Alice Brown</td>
        <td>321 Pine St</td>
        <td>654-321-0987</td>
        <td>alice@example.com</td>
      </tr>
      <tr>
        <td>Charlie White</td>
        <td>654 Maple St</td>
        <td>789-012-3456</td>
        <td>charlie@example.com</td>
      </tr>
    </tbody>
  </table>

  <!-- Registration Form -->
  <h1>Registration Form</h1>
  <form action="#" method="post">
    <!-- Name Field -->
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
    
    <!-- Email Field -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
    
    <!-- Password Field -->
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
    
    <!-- Date Field -->
    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required><br><br>
    
    <!-- Dropdown -->
    <label for="gender">Gender:</label>
    <select id="gender" name="gender" required>
      <option value="">Select</option>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select><br><br>
    
    <!-- Radio Buttons -->
    <label>Subscription:</label><br>
    <input type="radio" id="free" name="subscription" value="free" required>
    <label for="free">Free</label><br>
    <input type="radio" id="premium" name="subscription" value="premium">
    <label for="premium">Premium</label><br><br>
    
    <!-- Checkboxes -->
    <label>Hobbies:</label><br>
    <input type="checkbox" id="sports" name="hobbies" value="sports">
    <label for="sports">Sports</label><br>
    <input type="checkbox" id="music" name="hobbies" value="music">
    <label for="music">Music</label><br>
    <input type="checkbox" id="reading" name="hobbies" value="reading">
    <label for="reading">Reading</label><br><br>

    <!-- Submit Button -->
    <button type="submit">Register</button>
  </form>
</body>
</html>

