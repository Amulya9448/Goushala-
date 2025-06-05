# Goushala-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Goshala Labor Management</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f6f3;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      background-color: #2e8b57;
      color: white;
      width: 100%;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
    }

    .container {
      margin-top: 40px;
      display: flex;
      flex-direction: column;
      gap: 20px;
      width: 90%;
      max-width: 400px;
    }

    .btn {
      padding: 15px;
      background-color: #4caf50;
      color: white;
      text-align: center;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      text-decoration: none;
    }

    .btn:hover {
      background-color: #388e3c;
    }

    footer {
      margin-top: 60px;
      padding: 20px;
      text-align: center;
      color: #777;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Goshala App</h1>
    <p>Labor and Volunteer Management</p>
  </header>

  <div class="container">
    <a class="btn" href="add_labour.html">Add Labour</a>
    <a class="btn" href="view_labours.html">View Labours</a>
    <a class="btn" href="register_volunteer.html">Register Volunteer</a>
    <a class="btn" href="admin_panel.html">Admin Panel</a>
  </div>

  <footer>
    &copy; 2025 Goshala Management System
  </footer>

</body>
</html>

/* Reset and Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f2f6f3;
  color: #333;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
}

/* Header */
header {
  background-color: #2e8b57;
  color: white;
  width: 100%;
  padding: 30px 20px;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
  font-size: 2rem;
  margin-bottom: 8px;
}

header p {
  font-size: 1rem;
  font-weight: 300;
}

/* Intro Section */
.intro {
  margin: 30px auto;
  max-width: 800px;
  padding: 10px 20px;
  text-align: center;
}

.intro h2 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

.intro p {
  font-size: 1rem;
  line-height: 1.6;
  color: #444;
}

/* Navigation Buttons */
.navigation {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin: 30px auto;
  width: 90%;
  max-width: 400px;
  padding: 0 10px;
}

.btn {
  padding: 15px;
  background-color: #4caf50;
  color: white;
  text-align: center;
  border: none;
  border-radius: 10px;
  font-size: 18px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s ease;
  text-decoration: none;
}

.btn:hover {
  background-color: #388e3c;
  transform: translateY(-2px);
}

/* Footer */
footer {
  margin-top: auto;
  padding: 20px;
  text-align: center;
  color: #777;
  font-size: 0.9rem;
  background-color: #eaeaea;
  width: 100%;
}
