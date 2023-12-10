# Educational Timeline

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Work Experience Timeline</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    .timeline {
      position: relative;
      max-width: 400px;
      margin: 50px auto;
    }

    .timeline::before {
      content: '';
      position: absolute;
      top: 0;
      left: 50%;
      width: 2px;
      height: 100%;
      background-color: #333;
      transform: translateX(-50%);
    }

    .timeline-item {
      position: relative;
      margin-bottom: 50px;
    }

    .timeline-item::after {
      content: '';
      position: absolute;
      top: 50%;
      left: 50%;
      width: 20px;
      height: 20px;
      background-color: #333;
      border-radius: 50%;
      transform: translate(-50%, -50%);
    }

    .timeline-date {
      font-weight: bold;
      margin-bottom: 10px;
    }

    .timeline-content {
      margin-left: 30px;
    }

    h2 {
      margin-bottom: 5px;
    }

    p {
      margin: 0;
    }
  </style>
</head>
<body>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2020 - Present</div>
    <div class="timeline-content">
      <h2>Current Job Title</h2>
      <p>Job description and responsibilities go here.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2018 - 2020</div>
    <div class="timeline-content">
      <h2>Previous Job Title</h2>
      <p>Job description and responsibilities go here.</p>
    </div>
  </div>

  <!-- Add more timeline items as needed -->

</div>

</body>
</html>
