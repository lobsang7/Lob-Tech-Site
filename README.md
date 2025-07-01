# Lob-Tech-Site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lobsang Tech Channel</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f0f0f;
      color: #fff;
    }
    header {
      background-color: #1f1f1f;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    .content {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    iframe {
      width: 100%;
      height: 200px;
      border: none;
      border-radius: 10px;
    }
    .how-to-access {
      background-color: #222;
      padding: 20px;
      margin-top: 40px;
      border-radius: 10px;
    }
    .how-to-access h3 {
      margin-top: 0;
    }
    footer {
      text-align: center;
      padding: 10px;
      font-size: 0.9em;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Lobsang Tech Channel</h1>
    <p>Latest Tech Videos, Tutorials & Reviews</p>
  </header>
  <div class="content">
    <h2>Latest Videos</h2>
    <div class="video-grid">
      <iframe src="https://www.youtube.com/embed?listType=user_uploads&list=@lobsang8905" allowfullscreen></iframe>
      <iframe src="https://www.youtube.com/embed/videoseries?list=UU7OeJMHXsqhODAvdEdvYP3A" allowfullscreen></iframe>
    </div>

    <div class="how-to-access">
      <h3>🔓 How to Access This Site</h3>
      <ol>
        <li>Save this HTML file to your computer as <code>index.html</code>.</li>
        <li>Open it by double-clicking — it will open in your web browser.</li>
        <li>To make it public, upload it to a free service like <strong>GitHub Pages</strong>, <strong>Netlify</strong>, or <strong>Vercel</strong>.</li>
        <li>Once uploaded, the site will automatically show your latest YouTube videos.</li>
      </ol>
    </div>
  </div>
  <footer>
    &copy; 2025 Lobsang Tech Channel. All rights reserved.
  </footer>
</body>
</html>
