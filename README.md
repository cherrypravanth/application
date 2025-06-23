<!DOCTYPE html>
<html lang="en">
<head>
  <title>Table layout</title>
  <meta charset="UTF-8">
  <title>Bus Pass Application Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      padding: 20px;
    }
    .container {
      background-color: #fff;
      padding: 25px;
      border-radius: 8px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
      text-align: center;
    }
    label {
      display: block;
      margin: 10px 0 5px;
    }
    input[type="text"],
    input[type="email"],
    input[type="date"],
    select,
    textarea {
      width: 100%;
      padding: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
      font-size: 16px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Bus Pass Application Form</h2>
    <form action="#" method="post">
      <label for="fullName">Full Name</label>
      <input type="text" id="fullName" name="fullName" required>

      <label for="dob">Date of Birth</label>
      <input type="date" id="dob" name="dob" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number</label>
      <input type="text" id="phone" name="phone" required>

      <label for="address">Address</label>
      <textarea id="address" name="address" rows="3" required></textarea>

      <label for="route">Route (From - To)</label>
      <input type="text" id="route" name="route" placeholder="e.g. City Center to University" required>

      <label for="passType">Pass Type</label>
      <select id="passType" name="passType" required>
        <option value="">--Select Pass Type--</option>
        <option value="daily">Daily</option>
        <option value="monthly">Monthly</option>
        <option value="student">Student</option>
        <option value="senior">Senior Citizen</option>
      </select>

      <label for="idProof">ID Proof Number</label>
      <input type="text" id="idProof" name="idProof" required>

      <button type="submit">Submit Application</button>
    </form>
  </div>
</body>
</html>
