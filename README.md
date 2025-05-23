

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" /
<title>Eleven Fanonts.googleapis.com/css2family=Orbitron:wght@700&family=Roboto:wght@400;700&dsplay=swap')
    a8a;
    --secondary-color: #fbbf24;
    --accent-color: #ef4444;
    --background-color: #0f172a;
    --text-color-light: #f9fafb;
    --text-color-dark: #111827;
  }

  body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background-color: var(--background-color);
    color: var(--text-color-light);
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }

  header {
    background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
    padding: 1.5rem 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    box-shadow: 0 4px 8px rgba(0,0,0,0.5);
  }

  .logo-container {
    display: flex;
    align-items: center;
  }

  .logo-container img {
    height: 60px;
    margin-right: 15px;
    border-radius: 8px;
  }

  .logo {
    font-family: 'Orbitron', sans-serif;
    font-size: 2.4rem;
    font-weight: 700;
    letter-spacing: 0.12em;
    color: var(--text-color-light);
    text-shadow: 0 0 12px var(--secondary-color);
  }

  nav a {
    color: var(--text-color-light);
    text-decoration: none;
    font-weight: 700;
    margin-left: 1.6rem;
    font-size: 1.1rem;
    transition: color 0.3s ease;
  }

  nav a:hover {
    color: var(--accent-color);
  }

  main {
    flex-grow: 1;
    padding: 3rem 2rem;
    max-width: 900px;
    margin: 0 auto;
    text-align: center;
  }

  main h1 {
    font-family: 'Orbitron', sans-serif;
    font-size: 3rem;
    margin-bottom: 0.5rem;
    color: var(--secondary-color);
    text-shadow: 0 0 12px var(--secondary-color);
  }

  .lead {
    font-size: 1.4rem;
    margin: 1rem auto 2rem;
    color: #d1d5db;
    max-width: 600px;
  }

  .team-info {
    background: #1e293b;
    border-radius: 10px;
    padding: 2rem;
    box-shadow: 0 4px 10px rgba(255, 191, 36, 0.3);
    margin-bottom: 3rem;
  }

  .team-info h2 {
    font-family: 'Orbitron', sans-serif;
    font-size: 2rem;
    margin-bottom: 1rem;
    color: var(--primary-color);
    text-shadow: 0 0 10px var(--primary-color);
  }

  .team-stats {
    display: flex;
    justify-content: space-around;
    margin-top: 1rem;
    flex-wrap: wrap;
  }

  .stat {
    background: #111827;
    border: 2px solid var(--secondary-color);
    border-radius: 8px;
    padding: 1rem 2rem;
    margin: 0.7rem;
    flex: 1 1 150px;
    box-shadow: 0 0 12px var(--secondary-color);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .stat:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px var(--accent-color);
  }

  .stat h3 {
    font-size: 1.6rem;
    margin-bottom: 0.4rem;
    color: var(--accent-color);
  }

  .stat p {
    font-size: 1.1rem;
    color: #e0e0e0;
  }

  ul.player-list {
    list-style: none;
    padding: 0;
    font-size: 1.2rem;
    line-height: 1.8;
    color: #e0e0e0;
  }

  footer {
    background: #111827;
    text-align: center;
    padding: 1.4rem 1rem;
    color: #94a3b8;
    font-size: 0.95rem;
    box-shadow: inset 0 1px 3px rgba(255, 255, 255, 0.05);
    user-select: none;
  }

  @media (max-width: 600px) {
    header {
      flex-direction: column;
      align-items: flex-start;
    }
    nav {
      margin-top: 0.8rem;
    }
    nav a {
      margin-left: 0;
      margin-right: 1.6rem;
      display: inline-block;
    }
    .team-stats {
      flex-direction: column;
      align-items: center;
    }
    .stat {
      max-width: 300px;
    }
  }
</style>
</head>
<body>
<header>
  <div class="logo-container">
    <img src="team-logo.jpg" alt="Team Logo" />
    <div class="logo">Eleven Fanatics</div>
  </div>
  <nav>
    <a href="#about">About</a>
    <a href="#team">Team</a>
    <a href="#players">Players</a>
    <a href="#contact">Contact</a>
  </nav>
</header>
<main>
  <h1>Welcome to Eleven Fanatics</h1>
  <p class="lead">The passionate cricket team that lives and breathes the sport. Join us in celebrating the spirit of cricket, team unity, and big wins on the field!</p>

  <section id="about" class="team-info">
    <h2>About Us</h2>
    <p>Eleven Fanatics is a dynamic cricket team founded by enthusiasts for enthusiasts. We strive to excel in every match with passion, skill, and teamwork.</p>
  </section>

  <section id="team" class="team-info">
    <h2>Team Highlights</h2>
    <div class="team-stats">
      <div class="stat">
        <h3>Matches Played</h3>
        <p>150+</p>
      </div>
      <div class="stat">
        <h3>Victories</h3>
        <p>95</p>
      </div>
      <div class="stat">
        <h3>Top Batsman Runs</h3>
        <p>4,380</p>
      </div>
      <div class="stat">
        <h3>Top Bowler Wickets</h3>
        <p>320</p>
      </div>
    </div>
  </section>

  <section id="players" class="team-info">
    <h2>Meet the Players</h2>
    <ul class="player-list">
      <li>Owais</li>
      <li>Kashif</li>
      <li>Zayan</li>
      <li>Hammad</li>
      <li>Yahya</li>
      <li>Uzair</li>
      <li>Saheem</li>
      <li>Inam</li>
      <li>Muzamil</li>
      <li>Anas</li>
      <li>Aariz</li>
    </ul>
  </section>

  <section id="contact" class="team-info">
    <h2>Contact Us</h2>
    <p>For team inquiries, sponsorship, or to join the Eleven Fanatics family, email us at <a href="mailto:contact@elevenfanatics.com" style="color: var(--secondary-color); text-decoration: underline;">contact@elevenfanatics.com</a>.</p>
  </section>
</main>

<footer>
  &copy; 2024 Eleven Fanatics Cricket Team. All rights reserved.
</footer>
</body>
</html>



