<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Family Registration Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background: #f0f8ff;
    }
    form {
      max-width: 600px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      text-align: center;
    }
    label {
      display: block;
      margin-top: 15px;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .children input {
      margin-top: 5px;
    }
    button {
      margin-top: 20px;
      padding: 10px;
      background-color: #2e8b57;
      color: white;
      border: none;
      width: 100%;
      border-radius: 5px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <form action="My Family Form.html" method="get">
    <h2>Family Registration Form</h2>

    <label for="fatherName">Father's Name:</label>
    <input type="text" id="fatherName" name="fatherName" placeholder="fatherName"required>

    <label for="motherName">Mother's Name:</label>
    <input type="text" id="motherName" name="motherName" required>

    <label for="children">Children's Names:</label>
    <div class="children">
      <input type="text" name="child1" placeholder="Child 1 Name">
      <input type="text" name="child2" placeholder="Child 2 Name">
      <input type="text" name="child3" placeholder="Child 3 Name">
    </div>

    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email">

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone">

    <label for="address">Home Address:</label>
    <input type="text" id="address" name="address">

    <button type="submit">Register</button>
  </form>

</body>
</html>
