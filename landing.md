<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Welcome Freshies | FYSSA</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" />

  <style>
    /* Body & Background */
    body {
      min-height: 100vh;
      margin: 0;
      overflow-x: hidden;
      position: relative;
      font-family: "Poppins", sans-serif;
      color: #fff;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url("bg.png") no-repeat center center/cover;
      filter: blur(4px) brightness(40%);
      z-index: -1;
    }

    /* Sidebar */
    .sidebar {
      width: 250px;
      background-color: rgba(57, 78, 37, 0.95);
      color: #fff;
      position: fixed;
      top: 0;
      left: 0;
      height: 100%;
      padding: 20px 0;
      z-index: 999;
      display: flex;
      flex-direction: column;
    }

    .sidebar h4 {
      text-align: center;
      margin-bottom: 20px;
      font-weight: 600;
    }

    .sidebar a {
      color: white;
      text-decoration: none;
      display: block;
      padding: 12px 20px;
      transition: background 0.3s;
    }

    .sidebar a:hover,
    .sidebar a.active {
      background-color: #7ba950;
      border-radius: 5px;
    }

    hr {
      margin: 20px;
      border-color: rgba(255, 255, 255, 0.3);
    }

    /* Content */
    .content {
      margin-left: 250px;
      padding: 100px 40px;
      text-align: center;
    }

    .content h2 {
      font-weight: 700;
      font-size: 3rem;
      text-shadow: 0 4px 10px rgba(0, 0, 0, 0.7);
      color: #f8f9fa;
    }

    .content p {
      font-size: 1.2rem;
      color: #e8e8e8;
      max-width: 600px;
      margin: 0 auto;
      text-shadow: 0 2px 5px rgba(0, 0, 0, 0.6);
    }
  </style>
</head>

<body>
  <!-- Sidebar -->
  <div class="sidebar">
    <h4>FYSSA</h4>

    <a href="profile_page.html" class="active"><i class="bi bi-person-circle me-2"></i>Profile</a>
    <a href="study tips.html"><i class="bi bi-lightbulb me-2"></i>Study Tips</a>
    <a href="Calendar.html"><i class="bi bi-calendar-event me-2"></i>Calendar</a>
    <a href="Reminder.html"><i class="bi bi-bell me-2"></i>Reminder</a>
    <a href="Mentor.html"><i class="bi bi-mortarboard me-2"></i>Mentor</a>
    <a href="Peer_group.html"><i class="bi bi-people me-2"></i>Peer Group</a>

    <hr />

    <a href="#"><i class="bi bi-gear me-2"></i>Settings</a>
    <a href="Login.html"><i class="bi bi-box-arrow-right me-2"></i>Logout</a>
  </div>

  <!-- Main Content -->
  <div class="content container">
    <h2>Welcome Freshies!</h2>
    <p>Start exploring your dashboard using the sidebar menu. Your success begins here at FYSSA.</p>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
