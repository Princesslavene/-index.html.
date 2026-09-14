<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Princess Lavene | Official Website</title>

<style>
:root{
  --ink:#f7f2ea;
  --cream:#151515;
  --beige:#24201c;
  --gold:#c6a15a;
  --line:rgba(255,255,255,.22);
}

*{box-sizing:border-box}

html{scroll-behavior:smooth}

body{
  margin:0;
  font-family:Arial,Helvetica,sans-serif;
  color:var(--ink);
  background:linear-gradient(135deg,#090909,#171513 48%,#0b0b0b);
  line-height:1.6;
}

header{
  padding:28px 18px;
  text-align:center;
  border-bottom:1px solid var(--line);
  background:rgba(18,18,18,.92);
  backdrop-filter:blur(8px);
  position:sticky;
  top:0;
  z-index:10;
}

.brand{
  font-family:Georgia,serif;
  letter-spacing:4px;
  font-size:28px;
  margin:0;
}

.tag{
  margin:4px 0 0;
  font-size:12px;
  letter-spacing:3px;
}

nav{
  display:flex;
  justify-content:center;
  gap:14px;
  flex-wrap:wrap;
  margin-top:15px;
}

nav a{
  color:var(--ink);
  text-decoration:none;
  font-size:12px;
  letter-spacing:1.5px;
  padding:7px 10px;
}

main{
  max-width:1050px;
  margin:auto;
  padding:24px 16px 60px;
}

.hero{
  text-align:center;
  padding:35px 16px 28px;
}

.hero h1{
  font-family:Georgia,serif;
  font-size:clamp(38px,8vw,72px);
  margin:0;
  letter-spacing:5px;
}

.hero p{
  font-size:14px;
  letter-spacing:3px;
  margin:8px 0;
}

.section{
  margin:22px 0;
  padding:24px;
  border:1px solid var(--line);
  border-radius:22px;
  background:rgba(245,238,226,.13);
  box-shadow:0 10px 30px rgba(70,55,35,.06);
}

.section h2{
  font-family:Georgia,serif;
  letter-spacing:2px;
  margin:0 0 16px;
  font-size:26px;
}

.lead{font-size:17px}

.buttons{
  display:flex;
  gap:12px;
  flex-wrap:wrap;
  margin:18px 0;
}

.btn{
  display:inline-block;
  padding:12px 18px;
  border:1px solid rgba(255,255,255,.38);
  border-radius:999px;
  color:var(--ink);
  text-decoration:none;
  background:rgba(245,238,226,.20);
  font-weight:bold;
  font-size:13px;
  letter-spacing:1px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(210px,1fr));
  gap:15px;
  margin-top:18px;
}

.card{
  padding:22px;
  border:1px solid var(--line);
  border-radius:18px;
  background:rgba(245,238,226,.14);
}

.card h3{
  font-family:Georgia,serif;
  margin-top:0;
}

.album{
  width:100%;
  max-width:750px;
  height:auto;
  display:block;
  margin:20px auto;
  border-radius:18px;
}

a{color:#e2c27d}

.email-box{
  display:flex;
  gap:12px;
  flex-wrap:wrap;
  margin-top:18px;
}

.email-box input{
  flex:1;
  min-width:220px;
  padding:14px 16px;
  border-radius:999px;
  border:1px solid rgba(255,255,255,.38);
  background:rgba(245,238,226,.14);
  color:white;
  font-size:14px;
}

.email-box input::placeholder{
  color:rgba(255,255,255,.75);
}

footer{
  text-align:center;
  padding:35px 16px;
  border-top:1px solid var(--line);
  font-size:12px;
  letter-spacing:2px;
}

.small{
  font-size:13px;
  opacity:.8;
}

@media(max-width:600px){
  .section{padding:18px}
  .brand{font-size:22px}
  nav{gap:4px}
}
</style>
</head>

<body>

<header>
  <div class="brand">👑 PRINCESS LAVENE</div>
  <div class="tag">THE OFFICIAL WEBSITE</div>

  <nav>
    <a href="#home">HOME</a>
    <a href="#music">OFFICIAL MUSIC CHANNEL</a>
    <a href="#discography">DISCOGRAPHY</a>
    <a href="#contact">CONTACT</a>
  </nav>
</header>

<main id="home">

<section class="hero">
  <h1>PRINCESS LAVENE</h1>
  <p>RAPPER • TREND SETTER • ARTIST</p>
  <p>BIG DREAMS • REAL MOVES • GLOBAL VISION</p>
</section>

<section class="section">
  <h2>🏠 HEADQUARTERS</h2>

  <p class="lead">
    <strong>👑 PRINCESS LAVENE // OFFICIAL WEBSITE</strong>
  </p>

  <p>
    Welcome to the official Princess Lavene headquarters.
    Pre-save music, explore the discography, follow the official
    accounts, and stay ready for every new drop.
  </p>
</section>

<section class="section" id="music">

  <h2>🚨 PRE-ORDER NEXT ALBUM: "8 NUMBERS"</h2>

  <p class="lead">
    The Highly Talked About 8-Track Project From Princess Lavene
    📅 <strong>DROPPING WORLDWIDE: NOVEMBER 1, 2026</strong> 🎵
  </p>

  <p>
    <strong>Pre-Save Now Here:</strong>
    <a href="https://shorturl.at/ZhLmb"
       target="_blank"
       rel="noopener">
       https://shorturl.at/ZhLmb
    </a>
  </p>

  <div class="buttons">
    <a class="btn"
       href="https://shorturl.at/ZhLmb"
       target="_blank"
       rel="noopener">
       PRE-SAVE MUSIC
    </a>

    <a class="btn" href="#contact">
      PRE-ORDER VINYL
    </a>
  </div>

  <p>
    Make sure the album drops straight into your library on release day.
    Pre-save on the Princess Lavene Spotify Artist Page.
  </p>

</section>

<section class="section">

  <h2>🎨 8 NUMBERS — VISUALS</h2>

  <!-- Replace the image URL below with your uploaded album image
       if your GitHub repository contains the image file. -->

  <img
    class="album"
    src="album_current.jpg"
    alt="Princess Lavene 8 Numbers album artwork"
  >

</section>

<section class="section">

  <h2>💿 PHYSICAL RELEASE</h2>

  <p>
    Be the first to own the physical history of
    <strong>8 NUMBERS</strong>.
    Vinyl is coming soon on launch day, and CDs will be available
    on launch day — <strong>November 1, 2026.</strong>
  </p>

  <div class="grid">

    <div class="card">
      <h3>🎨 Limited Edition Vinyl</h3>
      <p>
        12" heavyweight gatefold vinyl.
        Includes exclusive colored edition pressing and
        printed lyric booklet.
        <strong>COMING SOON ON LAUNCH DAY.</strong>
      </p>
      <a href="#contact">VINYL DETAILS</a>
    </div>

    <div class="card">
      <h3>💿 Compact Disc (CD)</h3>
      <p>
        Jewel case edition with full-color insert artwork.
        <strong>
          AVAILABLE ON LAUNCH DAY — NOVEMBER 1, 2026.
        </strong>
      </p>
      <a href="#contact">CD DETAILS</a>
    </div>

    <div class="card">
      <h3>👕 Official Launch Apparel</h3>
      <p>
        "8 Numbers" limited pre-order graphic streetwear
        tees and hoodies. Coming Soon.
      </p>
      <a href="#contact">PRE-ORDER MERCH</a>
    </div>

  </div>

</section>

<section class="section" id="discography">

  <h2>💿 THE DISCOGRAPHY</h2>

  <p>
    Stream Princess Lavene's official releases while you wait
    for the new project to land.
  </p>

  <div class="grid">

    <div class="card">
      <h3>🌟 BILLION DOLLAR (Album)</h3>
      <p>
        Fan Favorite — All Eyes ON Me.
        Stream on Spotify 🔥
      </p>
    </div>

    <div class="card">
      <h3>GODLY (Album)</h3>
      <p>Stream on Spotify ✨</p>
    </div>

    <div class="card">
      <h3>REBORN (Album Project)</h3>
      <p>
        Featuring hits like Remember, Banger,
        My Time, and Hop In.
      </p>
    </div>

  </div>

  <p>
    <a href="https://open.spotify.com/artist/23ReJJ4hfu2EWL4nFbeifW"
       target="_blank"
       rel="noopener">
       🟢 Spotify — Follow Princess Lavene
    </a>
  </p>

  <p>
    <a href="https://music.apple.com/ng/album/bow-down-single/1734580129"
       target="_blank"
       rel="noopener">
       🍎 Apple Music — Listen on Apple Music
    </a>
  </p>

</section>

<section class="section">

  <h2>🎵 HIT SINGLES</h2>

  <div class="grid">

    <div class="card">
      <h3>❄️ Ice No Kingdom</h3>
      <p>Ice No Kingdom (Extended Remix)</p>
    </div>

    <div class="card">
      <h3>🌎 WORLD STAR ONLY ME</h3>
    </div>

    <div class="card">
      <h3>🎃 Spooky</h3>
    </div>

    <div class="card">
      <h3>🍀 LUCKY CLOVER</h3>
    </div>

    <div class="card">
      <h3>👑 Bow Down</h3>
    </div>

  </div>

  <p>
    <a href="https://open.spotify.com/artist/23ReJJ4hfu2EWL4nFbeifW"
       target="_blank"
       rel="noopener">
       STREAM & FOLLOW PRINCESS LAVENE
    </a>
  </p>

</section>

<section class="section">

  <h2>📸 OFFICIAL PHOTOS</h2>

  <p>
    Follow Princess Lavene across the official social platforms
    for new visuals, music, fashion, and updates.
  </p>

</section>

<section class="section" id="contact">

  <h2>📩 CONTACT / BOOKINGS</h2>

  <p>
    For bookings, business inquiries, collaborations,
    media, and opportunities:
  </p>

  <p>
    <strong>Email:</strong>
    <a href="mailto:Girlbossgirlyshit@gmail.com">
      Girlbossgirlyshit@gmail.com
    </a>
  </p>

  <div class="buttons">

    <a class="btn"
       href="https://www.tiktok.com/@princesslavenesreact"
       target="_blank"
       rel="noopener">
       TIKTOK
    </a>

    <a class="btn"
       href="https://x.com/princessLReacts"
       target="_blank"
       rel="noopener">
       X
    </a>

  </div>

</section>

<!-- EMAIL SIGNUP -->

<section class="section" id="email-list">

  <h2>👑 JOIN THE PRINCESS LAVENE LIST</h2>

  <p class="lead">
    Get exclusive music updates, release announcements,
    visuals, and first access to what's next.
  </p>

  <form
    action="https://formspree.io/f/YOUR_FORM_ID"
    method="POST"
    class="email-box"
  >

    <input
      type="email"
      name="email"
      placeholder="Enter your email address"
      required
    >

    <button class="btn" type="submit">
      JOIN THE LIST
    </button>

  </form>

  <p class="small">
    By signing up, you agree to receive emails from
    Princess Lavene. You can unsubscribe anytime.
  </p>

</section>

</main>

<footer>
  © 2026 PRINCESS LAVENE. ALL RIGHTS RESERVED.
</footer>

</body>
</html>
