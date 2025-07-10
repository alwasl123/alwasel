<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>روابطي</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #e8f0fe;
      margin: 0;
      padding: 0;
      direction: rtl;
      text-align: center;
    }

    header {
      background-color: #1a73e8;
      color: white;
      padding: 1rem 0;
      font-size: 1.8rem;
      font-weight: bold;
    }

    .container {
      padding: 2rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
      margin: auto;
    }

    .link-card {
      background-color: white;
      padding: 1rem 2rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: 0.3s;
      text-decoration: none;
      color: #1a1a1a;
      font-size: 1.2rem;
    }

    .link-card:hover {
      background-color: #d2e3fc;
      transform: scale(1.02);
    }
  </style>
</head>
<body>

  <header>
    مرحبًا بك في صفحة الروابط
  </header>

  <div class="container">
    <a class="link-card" href="https://www.google.com" target="_blank">اذهب إلى جوجل</a>
    <a class="link-card" href="https://www.youtube.com" target="_blank">اذهب إلى يوتيوب</a>
    <a class="link-card" href="https://www.aliexpress.com" target="_blank">تسوق من علي إكسبرس</a>
    <a class="link-card" href="https://chat.openai.com" target="_blank">دردشة ChatGPT</a>
  </div>

</body>
</html>
