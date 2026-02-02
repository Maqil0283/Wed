<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A | A Engagement</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Great+Vibes&display=swap" rel="stylesheet">

<!-- AOS -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Playfair Display', serif;
  scroll-behavior: smooth;
}

body{
  background:#f6f3ed;
  overflow-x:hidden;
}

/* --------------------
GATE / PINTU GERBANG
-------------------- */
.gate-wrapper{
  position:relative;
  width:100%;
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:
    url("https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/floral-bg.png.PNG")
    center/cover no-repeat;
}

.gate{
  position:absolute;
  width:50%;
  height:100%;
  background:rgba(255,255,255,0.95);
  top:0;
  z-index:5;
  animation-fill-mode:forwards;
}

.gate.left{ left:0; animation: openLeft 1.5s ease forwards;}
.gate.right{ right:0; animation: openRight 1.5s ease forwards;}

@keyframes openLeft{ 0%{transform:translateX(0);} 100%{transform:translateX(-100%);} }
@keyframes openRight{ 0%{transform:translateX(0);} 100%{transform:translateX(100%);} }

/* --------------------
CARD INVITATION
-------------------- */
.card{
  z-index:1;
  opacity:0;
  animation: fadeInCard 0.5s ease forwards;
  animation-delay:1.5s;
  background:rgba(255,255,255,0.88);
  width:90%;
  max-width:500px;
  padding:40px 25px;
  border-radius:18px;
  text-align:center;
  box-shadow:0 10px 30px rgba(0,0,0,0.1);
  margin-bottom:30px;
}

@keyframes fadeInCard{ from{opacity:0;} to{opacity:1;} }

/* --------------------
TEXT
-------------------- */
.subtitle{
  font-size:13px;
  letter-spacing:3px;
  margin-bottom:26px;
  color:#6b7a3c;
}

/* MONOGRAM */
.monogram{
  display:flex;
  justify-content:center;
  margin-bottom:20px;
}

.monogram .interlock{
  font-family:'Great Vibes', cursive;
  font-size:80px;
  color:#6b7a3c;
  letter-spacing:-5px;
  line-height:1;
  text-shadow:1px 1px 2px rgba(0,0,0,0.2);
}

/* NAMES, DATE, AYAT, HASHTAG */
.names{
  letter-spacing:4px;
  font-size:15px;
  margin:16px 0;
  font-weight:600;
}

.date{
  font-size:15px;
  margin:22px 0;
}

.date small{ display:block; font-size:12px; margin-top:6px; }

.ayat{
  font-size:14px;
  font-style:italic;
  line-height:1.6;
  margin-top:22px;
}

.hashtag{
  font-size:12px;
  opacity:0.8;
  margin-top:22px;
}

/* --------------------
SECTION / PAGE 2
-------------------- */
.section{
  padding:40px 20px;
  display:flex;
  justify-content:center;
  align-items:center;
  flex-direction:column;
  background:
    url("https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/floral-bg.png.PNG")
    center/cover no-repeat;
}

/* LOCATION CARD */
.location-card{
  background:rgba(255,255,255,0.88);
  width:90%;
  max-width:500px;
  padding:40px 25px;
  border-radius:18px;
  text-align:center;
  box-shadow:0 10px 30px rgba(0,0,0,0.1);
  margin-bottom:30px;
}

.location-card h2{ font-size:18px; margin-bottom:16px; color:#6b7a3c; }
.location-card p{ font-size:14px; margin-bottom:25px; }

/* GOOGLE MAP */
.map-container{ width:100%; height:250px; margin-bottom:20px; border-radius:12px; overflow:hidden; }
.map-container iframe{ width:100%; height:100%; border:0; }

/* GALLERY */
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(120px, 1fr));
  gap:12px;
  justify-items:center;
}

.gallery img{
  width:100%;
  max-width:150px;
  aspect-ratio:1/1;
  object-fit:cover;
  border-radius:12px;
  transition: transform 0.3s ease;
  cursor:pointer;
}

.gallery img:hover{ transform: scale(1.1); }

/* RESPONSIVE */
@media(max-width:480px){
  .monogram .interlock{ font-size:60px; }
  .card, .location-card{ padding:30px 20px; }
  .names{ font-size:14px; }
  .date{ font-size:14px; }
  .ayat{ font-size:13px; }
  .map-container{ height:200px; }
}
</style>
</head>

<body>

<!-- PAGE 1: Engagement WITH GATE -->
<section class="gate-wrapper">
  <div class="gate left"></div>
  <div class="gate right"></div>

  <div class="card" data-aos="zoom-in">
    <div class="subtitle">Engagement</div>

    <div class="monogram">
      <div class="interlock">A&amp;A</div>
    </div>

    <div class="names">Aqil | Alya</div>

    <div class="date">
      30.05.2025
      <small>10:00 am</small>
    </div>

    <div class="ayat">
      “Dan Kami menciptakan kamu berpasang-pasangan”<br>
      <small>Surah An-Naba’ (78:8)</small>
    </div>

    <div class="hashtag">#AlyakeAqilhayat</div>
  </div>
</section>

<!-- PAGE 2: Location & Photos -->
<section class="section" id="location">
  <div class="location-card" data-aos="fade-up">
    <h2>Lokasi Majlis</h2>
    <p>Lot 2494, Jalan Joget 4, Taman Ria Jaya, 08000, Sungai Petani, Kedah</p>

    <div class="map-container">
      <iframe
        src="https://www.google.com/maps?q=Lot+2494,+Jalan+Joget+4,+Taman+Ria+Jaya,+08000,+Sungai+Petani,+Kedah&output=embed"
        allowfullscreen
        loading="lazy"
      ></iframe>
    </div>

    <h2>Kenangan Kami</h2>
    <div class="gallery">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/Foto%201.HEIC" alt="Foto 1">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/Foto3.JPG" alt="Foto 2">
    </div>

    <div class="hashtag">#AlyakeAqilhayat</div>
  </div>
</section>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
AOS.init({
  duration:1500,
  once:true
});
</script>

</body>
</html>
