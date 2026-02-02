 Marriage-
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Vishnudhar ❤️ Nidhi | Wedding</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: linear-gradient(to bottom, #fff8e1, #fce4ec);
      text-align: center;
      color: #4a2c2a;
    }

    header {
      background: linear-gradient(to right, #7b1fa2, #c2185b);
      color: gold;
      padding: 50px 20px;
    }

    header h1 {
      font-size: 42px;
      margin: 10px 0;
    }

    header p {
      font-size: 18px;
      color: #fff3cd;
    }

    .ganesh img {
      width: 120px;
      margin-bottom: 15px;
    }

    section {
      padding: 40px 20px;
    }

    h2 {
      color: #8e0038;
      margin-bottom: 20px;
    }

    .countdown {
      font-size: 22px;
      font-weight: bold;
    }

    .events {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 20px;
      max-width: 900px;
      margin: auto;
    }

    .event {
      background: white;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
      border: 2px solid gold;
    }

    .gallery img {
      width: 90%;
      max-width: 260px;
      border-radius: 15px;
      margin: 10px;
      border: 3px solid gold;
    }

    footer {
      background: #7b1fa2;
      color: #fff3cd;
      padding: 15px;
      font-size: 14px;
    }

    audio {
      display: none;
    }
  </style>
</head>

<body>

<header>
  <div class="ganesh">
    <img src="https://i.imgur.com/3ZQ3ZQZ.png" alt="Shri Ganesh Ji">
  </div>

  <h1>Vishnudhar 💖 Nidhi</h1>
  <p>With the blessings of families</p>
  <p>Request your gracious presence</p>
  <p>📍 Kunda, Pratapgarh</p>
</header>

<section>
  <h2>Wedding Countdown ⏳</h2>
  <div class="countdown" id="countdown"></div>
</section>

<section>
  <h2>Wedding Ceremonies 🕉️</h2>
  <div class="events">
    <div class="event">💍 Sagai<br>15 February</div>
    <div class="event">🌼 Haldi</div>
    <div class="event">🌿 Mehendi</div>
    <div class="event">🔥 Wedding<br>19 February</div>
    <div class="event">🎉 Reception</div>
  </div>
</section>

<section>
  <h2>Our Memories 📸</h2>
  <div class="gallery">
    <img src="photo1.jpg">
    <img src="photo2.jpg">
    <img src="photo3.jpg">
  </div>
</section>

<footer>
  || वक्रतुंड महाकाय सूर्यकोटि समप्रभ ||
  <br>
  || निर्विघ्नं कुरु मे देव सर्वकार्येषु सर्वदा ||
</footer>

<!-- Background Music -->
<audio autoplay loop>
  <source src="music.mp3" type="audio/mpeg">
</audio>

<script>
  const weddingDate = new Date("Feb 19, 2026 00:00:00").getTime();

  setInterval(() => {
    const now = new Date().getTime();
    const distance = weddingDate - now;

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    document.getElementById("countdown").innerHTML =
      `${days} Days ${hours} Hours ${minutes} Minutes ${seconds} Seconds`;
  }, 1000);
</script>

</body>
</html>
