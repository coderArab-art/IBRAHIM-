<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GitHub Profile</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #0f172a;
      color: #e2e8f0;
      padding: 20px;
    }

    .container {
      max-width: 800px;
      margin: auto;
      background-color: #1e293b;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
    }

    .profile {
      text-align: center;
    }

    .profile img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #38bdf8;
      margin-bottom: 15px;
    }

    .profile h1 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    .profile p {
      color: #94a3b8;
      font-size: 1rem;
      margin-bottom: 20px;
    }

    .social-links a {
      margin: 0 10px;
      color: #38bdf8;
      text-decoration: none;
      font-weight: bold;
    }

    .projects {
      margin-top: 30px;
    }

    .projects h2 {
      margin-bottom: 15px;
      color: #f1f5f9;
    }

    .project {
      background-color: #334155;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .project h3 {
      margin-bottom: 5px;
      color: #facc15;
    }

    .project p {
      color: #cbd5e1;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }

      .profile h1 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile">
      <img src="https://avatars.githubusercontent.com/u/000000?v=4" alt="Profile Picture" />
      <h1>اسمك الكامل</h1>
      <p>مبرمج مهتم بالذكاء الاصطناعي وتطوير الأدوات البرمجية</p>
      <div class="social-links">
        <a href="https://github.com/username" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/username" target="_blank">LinkedIn</a>
        <a href="https://x.com/username" target="_blank">X</a>
      </div>
    </div>

    <div class="projects">
      <h2>📁 المشاريع المميزة</h2>

      <div class="project">
        <h3>🔧 مشروع أداة ذكاء اصطناعي</h3>
        <p>أداة تقوم بتحليل النصوص باستخدام التعلم الآلي بلغة Python وScikit-learn</p>
      </div>

      <div class="project">
        <h3>🌐 موقع شخصي تفاعلي</h3>
        <p>مبني باستخدام Next.js وTailwind CSS ويحتوي على مدونة ومعرض أعمال</p>
      </div>
    </div>
  </div>
</body>
</html>
