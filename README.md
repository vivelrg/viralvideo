# viralvideo\
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VIRAL VIDEO</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Poppins', sans-serif; background: #0d0d0d; color: #fff; line-height: 1.6; }
    header { background: #1a1a1a; padding: 20px 0; text-align: center; }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.1rem; color: #ccc; }
    nav { background: #111; display: flex; justify-content: center; gap: 30px; padding: 10px 0; }
    nav a { color: #fff; text-decoration: none; font-weight: 600; transition: color 0.3s; }
    nav a:hover { color: #ff4b2b; }
    section { padding: 60px 20px; max-width: 900px; margin: auto; }
    h2 { margin-bottom: 20px; font-size: 2rem; border-bottom: 2px solid #444; padding-bottom: 10px; }
    .video-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
    iframe { width: 100%; aspect-ratio: 16 / 9; border: none; }
    form { display: flex; flex-direction: column; gap: 15px; }
    input, textarea { padding: 10px; border-radius: 5px; border: none; background: #222; color: #fff; }
    button { background: #ff4b2b; color: #fff; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer; }
    footer { text-align: center; padding: 20px; background: #111; color: #777; }
  </style>
</head>
<body>
  <header>
    <h1>VIRAL VIDEO</h1>
    <p>Every Video, A Step Toward Success.</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#videos">Videos</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to VIRAL VIDEO</h2>
    <p>Your destination for inspiring, trending, and viral content. Subscribe to stay updated with our latest uploads!</p>
    <a href="https://www.youtube.com/channel/UCYGyBptZez9oDyaTYjJuyqw" target="_blank">
      <button>🎥 Visit YouTube Channel</button>
    </a>
  </section>

  <section id="about">
    <h2>About</h2>
    <p>VIRAL VIDEO is a growing YouTube platform dedicated to sharing powerful stories, amazing facts, creative videos, and much more. Every video is crafted to inspire, entertain, and inform our viewers.</p>
  </section>

  <section id="videos">
    <h2>Latest Videos</h2>
    <div class="video-grid">
      <iframe src="https://www.youtube.com/embed?listType=user_uploads&list=UCYGyBptZez9oDyaTYjJuyqw" allowfullscreen></iframe>
      <!-- You can add more videos manually like below -->
      <!-- <iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe> -->
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 VIRAL VIDEO. All rights reserved.</p>
  </footer>
</body>
</html>

"Every Video, A Step Toward Success."
