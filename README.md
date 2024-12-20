<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Miles Nelson - Resume</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      padding: 50px;
    }

    .container {
      display: flex;
      max-width: 1000px;
      margin: 0 auto;
    }

    .left-section {
      flex: 1;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 10px;
      box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
      background-color: #f9f9f9;
    }

    .right-section {
      flex: 2;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 10px;
      box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
      margin-left: 20px;
    }

    .profile-photo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    .header {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-bottom: 20px;
    }

    .header h1 {
      font-size: 2.5rem;
      font-weight: bold;
      color: #333;
      margin: 0;
    }

    .header h3 {
      font-size: 1.5rem;
      font-weight: normal;
      color: #555;
    }

    .section-title {
      font-size: 1.5rem;
      font-weight: bold;
      color: #2c3e50;
      margin-bottom: 10px;
      border-bottom: 2px solid #3498db;
      padding-bottom: 5px;
      margin-top: 20px;
    }

    .section-content {
      margin-bottom: 20px;
    }

    .contact-info {
      font-size: 1.1rem;
      color: #555;
    }

    .contact-info a {
      text-decoration: none;
      color: #3498db;
    }

    .experience-item, .achievement-item {
      margin-bottom: 10px;
    }

    .experience-item ul, .achievement-item ul {
      margin-left: 20px;
    }

    .section {
      margin-bottom: 30px;
    }

    .left-section {
      background-color: #ecf0f1;
    }

    .right-section {
      background-color: #ffffff;
    }

    .section-title {
      color: #2980b9;
    }

    .contact-info a:hover {
      color: #1abc9c;
    }

    .achievement-item p {
      color: #16a085;
    }
    
    footer {
      text-align: center;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Left Section: Profile Info and Photo -->
    <div class="left-section">
      <div class="header">
        <!-- Replace the URL below with the actual hosted image URL -->
        <img src="Photos/thumbnail_IMG_4906.jpg" alt="Headshot of Miles Nelson" class="profile-photo" onerror="this.src='https://via.placeholder.com/150';">
        <h1>Miles Nelson</h1>
        <h3>Accounting Major</h3>
      </div>

      <div class="section">
        <h2 class="section-title">Profile Info</h2>
        <p>A motivated accounting student with a passion for finance, leadership, and problem-solving. With experience in customer service and a background in professional sports, I excel in dynamic environments and look forward to applying my skills in accounting and finance.</p>
      </div>

      <div class="section">
        <h2 class="section-title">Languages</h2>
        <ul>
          <li>English: Native</li>
          <li>Spanish: Fluent</li>
        </ul>
      </div>

      <div class="section">
        <h2 class="section-title">Contact Info</h2>
        <p>Phone: <a href="tel:+19257862354">925-786-2354</a></p>
        <p>Email: <a href="mailto:milesnelson25@gmail.com">milesnelson25@gmail.com</a></p>
      </div>
    </div>

    <!-- Right Section: Education, Experience, and Skills -->
    <div class="right-section">
      <div class="section">
        <h2 class="section-title">Education</h2>
        <p><strong>2021:</strong> High School Diploma, Monte Vista High School</p>
        <p><strong>2022 - Present:</strong> Bachelor of Science in Accounting, Brigham Young University</p>
      </div>

      <div class="section">
        <h2 class="section-title">Skills</h2>
        <ul>
          <li>Accounting Principles</li>
          <li>Financial Analysis</li>
          <li>Tax Preparation</li>
          <li>Customer Service</li>
          <li>Leadership & Management</li>
        </ul>
      </div>

      <div class="section">
        <h2 class="section-title">Experience</h2>
        <div class="experience-item">
          <p><strong>2024 - Present:</strong> Server, La Jolla Groves</p>
          <ul>
            <li>Provide excellent customer service, ensuring a positive dining experience for all guests.</li>
            <li>Collaborate with team members to ensure efficient service and restaurant operations.</li>
            <li>Assist with training new staff and maintaining high-quality service standards.</li>
          </ul>
        </div>
        <div class="experience-item">
          <p><strong>2022 - 2024:</strong> Professional Boxer</p>
          <ul>
            <li>Competed at a professional level, honing discipline, strategy, and focus.</li>
            <li>Managed training schedules, fitness routines, and professional commitments.</li>
            <li>Developed a high level of physical endurance and resilience under pressure.</li>
          </ul>
        </div>
      </div>

      <div class="section">
        <h2 class="section-title">Achievements</h2>
        <div class="achievement-item">
          <p><strong>2023:</strong> Awarded 'Employee of the Month' at La Jolla Groves for outstanding service.</p>
        </div>
        <div class="achievement-item">
          <p><strong>2018 - 2020:</strong> Completed over 50 successful matches in the professional boxing circuit.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer with GitHub link -->
  <footer>
    <p>Check out the source code on <a href="https://github.com/milesn02/surfingforbeginners" target="_blank">GitHub</a></p>
  </footer>
</body>
</html>
