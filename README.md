<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta http-equiv="X-UA-Compatible" content="ie=edge"/>
  <title>Mantas Krutulis Portfolio</title>
  <style>
    body {
      font-family: sans-serif;
      background: #0B132B;
      color: #ffffff;
      margin: 0;
      padding: 0;
    }

    nav {
      background: #1C2541;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .nav-left a.name {
      color: #ffffff;
      font-family: 'Times New Roman', Times, serif;
      font-size: 32px;
      text-decoration: none;
    }

    .nav-left h2 {
      margin: 0;
      font-size: 18px;
      color: #ffffff;
    }

    .nav-right {
      display: flex;
      gap: 1.5rem;
    }

    .nav-right a {
      color: #ffffff;
      font-size: 18px;
      text-decoration: none;
    }

    .nav-right a:hover {
      opacity: 0.7;
    }

    .section-header {
      text-align: center;
      padding: 3rem 1rem 1rem;
    }

    .section-header h2 {
      font-size: 36px;
      color: #5BC0BE;
      margin-bottom: 1rem;
    }

    .video-section {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
      padding: 2rem;
    }

    .video-card {
      text-align: center;
      max-width: 320px;
    }

    .video-card span {
      display: block;
      font-size: 20px;
      color: #ffffff;
      margin-bottom: 0.5rem;
    }

    .video-card img {
      width: 100%;
      height: auto;
      border-radius: 15%;
      transition: transform 0.3s ease;
    }

    .video-card img:hover {
      transform: scale(1.05);
    }

    .code-section {
      padding: 3rem 2rem;
      max-width: 800px;
      margin: 0 auto;
      text-align: center;
    }

    .code-links a {
      display: block;
      margin-bottom: 1.5rem;
      font-size: 22px;
      color: #5BC0BE;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .code-links a:hover {
      color: #6FFFE9;
    }

    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        align-items: flex-start;
      }

      .nav-right {
        margin-top: 1rem;
        flex-direction: column;
        gap: 0.5rem;
      }

      .video-section {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>

<body>

  <nav>
    <div class="nav-left">
      <a class="name" href="https://kubas-13.github.io/Portfolio/"><strong>Mantas Krutulis</strong></a>
      <h2>Game Developer</h2>
    </div>
    <div class="nav-right">
    <a href="https://kubas-13.github.io/Portfolio/">HOME</a>
      <a href="https://kubas-13.github.io/Demo/">DEMOS</a>
      <a href="https://kubas-13.github.io/Games/">GAMES</a>
      <a href="https://kubas-13.github.io/Contact/">CONTACT</a>
    </div>
  </nav>

  <section class="section-header">
    <h2><strong>DEMOS</strong></h2>
  </section>

  <section class="video-section">
    <div class="video-card">
      <span><strong>Movement System</strong></span>
      <a href="https://youtu.be/HlMUO7bk6Ik" target="_blank">
        <img src="Photos/movement.png" alt="Movement Video">
      </a>
    </div>
    <div class="video-card">
      <span><strong>Lockpicking System</strong></span>
      <a href="https://youtu.be/9pSvBBJEInI" target="_blank">
        <img src="Photos/lock.png" alt="Lockpicking Video">
      </a>
    </div>
  </section>

  <section class="code-section">
    <div class="section-header">
      <h2><strong>CODE</strong></h2>
    </div>
    <div class="code-links">
      <a href="https://github.com/kubas-13/mantaskrutulis.github.io/tree/main/Code%20Examples/MovemetSystem" target="_blank">
        ➤ Movement System Code Example
      </a>
      <a href="https://github.com/kubas-13/mantaskrutulis.github.io/tree/main/Code%20Examples/LockpickingSystem/LootBox" target="_blank">
        ➤ Lockpicking System Code Example
      </a>
    </div>
  </section>

</body>
</html>
