<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Irenita.com</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background-color: #fff1f5;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }

    .container {
      text-align: center;
      padding: 20px;
    }

    .title {
      font-size: 3rem;
      color: #ec4899;
      margin-bottom: 1rem;
      animation: fadeInDown 0.6s ease-out;
    }

    .subtitle {
      color: #be185d;
      max-width: 400px;
      margin: 0 auto 2rem;
      animation: fadeIn 1s ease-out;
    }

    .card {
      background: white;
      border: 2px solid #f9a8d4;
      border-radius: 16px;
      padding: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      max-width: 300px;
      margin: 0 auto;
      animation: zoomIn 0.6s ease-out;
    }

    .sparkles {
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }

    .card h2 {
      color: #ec4899;
      margin-bottom: 0.5rem;
    }

    .card p {
      font-size: 0.9rem;
      color: #7f1d1d;
      margin-bottom: 1rem;
    }

    button {
      background-color: #ec4899;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 999px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #db2777;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes zoomIn {
      from { opacity: 0; transform: scale(0.8); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <main class="container">
    <h1 class="title">Welcome to Irenita.com!</h1>
    <p class="subtitle">
      A sweet and sparkly place where dreams, cookies, and cuteness collide.
    </p>

    <div class="card">
      <div class="sparkles">✨</div>
      <h2>Meet Irenita!</h2>
      <p>
        I'm a creative soul spreading joy one sparkle at a time.
        Stay tuned for cute projects, sweet treats, and magical surprises!
      </p>
      <button>Join the Sparkle Club</button>
    </div>
  </main>
</body>
</html>

