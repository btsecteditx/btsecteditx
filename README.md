<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BTS Ect EditX</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 0;
      padding: 20px;
    }
    header {
      text-align: center;
      padding: 20px;
      background-color: #7f5af0;
      color: white;
      border-radius: 10px;
    }
    h1 {
      margin: 0;
    }
    .section {
      margin: 30px 0;
    }
    .playlist, .video-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    iframe {
      width: 100%;
      border-radius: 10px;
    }
    a {
      text-decoration: none;
      color: #7f5af0;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <h1>BTS Ect EditX চ্যানেল</h1>
    <p>এখানে তুমি পাবে সুন্দর ভিডিও এডিট, BTS এর ভালোবাসার মুহূর্ত, প্লেলিস্ট এবং আরও অনেক কিছু!</p>
  </header>

  <div class="section">
    <h2>🎥 ভিডিও লিস্ট</h2>
    <div class="video-list">
      <div class="card">
        <iframe src="https://www.youtube.com/embed/VIDEO_ID_1" frameborder="0" allowfullscreen></iframe>
        <p><a href="https://www.youtube.com/watch?v=VIDEO_ID_1" target="_blank">ভিডিও ১</a></p>
      </div>
      <div class="card">
        <iframe src="https://www.youtube.com/embed/VIDEO_ID_2" frameborder="0" allowfullscreen></iframe>
        <p><a href="https://www.youtube.com/watch?v=VIDEO_ID_2" target="_blank">ভিডিও ২</a></p>
      </div>
      <!-- আরও ভিডিও চাইলে এখানেই কপি করে বসাও -->
    </div>
  </div>

  <div class="section">
    <h2>📁 প্লে-লিস্ট</h2>
    <div class="playlist">
      <div class="card">
        <a href="https://youtube.com/playlist?list=PLID1" target="_blank">BTS Emotion Edits</a>
      </div>
      <div class="card">
        <a href="https://youtube.com/playlist?list=PLID2" target="_blank">Funny Moments Collection</a>
      </div>
      <!-- আরও প্লেলিস্ট চাইলে এখানেও বসাও -->
    </div>
  </div>

  <footer style="text-align:center; margin-top: 40px; font-size: 14px; color: #666;">
    © 2025 BTS Ect EditX. All rights reserved.
  </footer>

</body>
</html>
