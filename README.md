<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Silent - Progetto Musicale</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
<style>
  html {
    scroll-behavior: smooth;
  }
  body {
    margin: 0; padding: 0;
    font-family: 'Poppins', Arial, sans-serif;
    background: #121212;
    color: #eee;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  header {
    background: #111;
    padding: 20px;
    font-weight: 700;
    font-size: 2rem;
    color: #00aaff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  nav a {
    color: #00aaff;
    text-decoration: none;
    margin-left: 20px;
    font-weight: 600;
    transition: color 0.3s ease;
    cursor: pointer;
  }
  nav a:hover {
    color: #66d9ff;
  }
  main {
    max-width: 960px;
    padding: 30px 20px;
    margin: 0 auto;
    flex-grow: 1;
  }
  section {
    margin-bottom: 80px;
  }
  h1 {
    font-weight: 700;
    font-size: 3rem;
    margin-bottom: 10px;
  }
  h2 {
    font-weight: 600;
    font-size: 2rem;
    margin-bottom: 15px;
  }
  p {
    font-size: 1.2rem;
    line-height: 1.6;
    margin-bottom: 20px;
  }
  .links-canzoni a {
    display: inline-block;
    background: #00aaff;
    color: #121212;
    padding: 10px 20px;
    margin: 6px 10px 6px 0;
    border-radius: 25px;
    font-weight: 600;
    text-decoration: none;
    transition: background-color 0.3s ease;
  }
  .links-canzoni a:hover {
    background: #66d9ff;
  }
  .social-links a {
    margin-right: 25px;
    font-size: 1.6rem;
    color: #00aaff;
    text-decoration: none;
  }
  .social-links a:hover {
    color: #66d9ff;
  }
  .video-instagram img {
    width: 100%;
    max-width: 480px;
    border-radius: 12px;
    cursor: pointer;
    margin-bottom: 30px;
  }
  footer {
    background: #111;
    color: #555;
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
  }
</style>
</head>
<body>
<header>
  <div>Silent</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#storia">La Mia Storia</a>
    <a href="#obiettivi">Obiettivi</a>
  </nav>
</header>
<main>
  <section id="home" tabindex="0">
    <h1>Silent - Progetto Musicale</h1>
    <p>Sono Silent, artista e produttore musicale con la passione di creare suoni unici e raccontare storie con la musica. Scopri le mie ultime canzoni e seguimi sui social per non perdere nessuna novità.</p>

    <div class="video-instagram">
      <a href="https://www.instagram.com/reel/DLsLGDZI1O8/" target="_blank" rel="noopener noreferrer" aria-label="Video Instagram Reel di Silent">
        <img src="https://instagram.fmxp1-1.fna.fbcdn.net/v/t51.2885-15/e35/302212916_1621514279964727_6390588788417100864_n.jpg?_nc_ht=instagram.fmxp1-1.fna.fbcdn.net&_nc_cat=111&_nc_ohc=GU09qPY9zocAX9nT9Nq&edm=ABZsPhsBAAAA&ccb=7-5&ig_cache_key=Mjg0OTgxMDk3NTA0NjkxMTIyOQ%3D%3D.2-ccb7-5&oh=11b2f5ffafbf3d2b598f6fca5541e164&oe=64A23047&_nc_sid=4efc9f" alt="Anteprima Instagram Reel Silent" />
      </a>
    </div>

    <div class="links-canzoni">
      <h2>Le mie canzoni</h2>
      <a href="https://youtu.be/O-32JAmqpQE" target="_blank" rel="noopener noreferrer">Video Promozionale</a>
    </div>

    <div class="social-links" aria-label="Link ai social media">
      <a href="https://instagram.com/silent" target="_blank" rel="noopener noreferrer" aria-label="Instagram">📸 Instagram</a>
    </div>
  </section>

  <section id="storia" tabindex="0">
    <h1>La Mia Storia</h1>
    <p>Sono Silent, una persona che non ha mai avuto paura di affrontare la realtà con sincerità e determinazione. La mia musica nasce dall’esperienza di vita, dalle sfide quotidiane e dalla voglia di trasmettere emozioni vere.</p>
    <p>Ho iniziato questo progetto musicale con l’obiettivo di fare la differenza, non solo con le parole ma anche con i suoni che creo. La mia filosofia è che nulla è regalato: tutto si conquista con impegno, lavoro e passione.</p>
    <p>Ogni brano è un pezzo di me, un racconto senza filtri, per chi ha voglia di ascoltare oltre le apparenze.</p>
  </section>

  <section id="obiettivi" tabindex="0">
    <h1>I miei Obiettivi</h1>
    <p>Il mio obiettivo principale è creare musica che possa ispirare e motivare chiunque ascolti, andando oltre la semplice melodia.</p>
    <p>Voglio costruire un progetto artistico solido e riconosciuto, ma senza mai perdere autenticità e sincerità.</p>
    <p>In futuro, sogno di ampliare la mia presenza anche a livello internazionale e collaborare con altri artisti per portare nuove idee e sonorità.</p>
  </section>
</main>
<footer>© 2025 Silent. Tutti i diritti riservati.</footer>
</body>
</html>
