 <html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A | A Engagement</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&display=swap" rel="stylesheet">

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
}

/* SECTION BASE */
.section{
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:
    url("https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/floral-bg.png.PNG")
    center/cover no-repeat;
  flex-direction:column;
  padding:40px 20px;
}

/* CARD BASE */
.card, .location-card{
  background:rgba(255,255,255,0.88);
  width:90%;
  max-width:500px;
  padding:40px 25px;
  border-radius:18px;
  text-align:center;
  box-shadow:0 10px 30px rgba(0,0,0,0.1);
  margin-bottom:30px;
}

/* TEXT */
.subtitle{
  font-size:13px;
  letter-spacing:3px;
  margin-bottom:26px;
  color:#6b7a3c;
}

.monogram{
  display:flex;
  flex-direction:column;
  align-items:center;
  color:#6b7a3c;
  margin-bottom:20px;
}

.monogram .s{
  font-size:90px;
  line-height:1;
}

.monogram .a{
  font-size:58px;
  margin-top:-10px;
}

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

.date small{
  display:block;
  font-size:12px;
  margin-top:6px;
}

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

/* LOCATION SECTION */
.location-card h2{
  font-size:18px;
  margin-bottom:16px;
  color:#6b7a3c;
}

.location-card p{
  font-size:14px;
  margin-bottom:25px;
}

/* GOOGLE MAP */
.map-container{
  width:100%;
  height:250px;
  margin-bottom:20px;
  border-radius:12px;
  overflow:hidden;
}

.map-container iframe{
  width:100%;
  height:100%;
  border:0;
}

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

.gallery img:hover{
  transform: scale(1.1);
}

/* RESPONSIVE */
@media(max-width:480px){
  .monogram .s{ font-size:70px; }
  .monogram .a{ font-size:45px; }
  .card, .location-card{ padding:30px 20px; }
  .names{ font-size:14px; }
  .date{ font-size:14px; }
  .ayat{ font-size:13px; }
  .map-container{ height:200px; }
}
</style>
</head>

<body>

<!-- PAGE 1: Engagement -->
<section class="section" id="engagement">
  <div class="card" data-aos="zoom-in">

    <div class="subtitle">Engagement</div>

    <div class="monogram">
      <div class="s">A</div>
      <div class="a">A</div>
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
        src="https://www.google.com/maps/embed/v1/place?key=YOUR_API_KEY&q=Lot+2494,+Jalan+Joget+4,+Taman+Ria+Jaya,+08000,+Sungai+Petani,+Kedah" 
        allowfullscreen>
      </iframe>
    </div>

    <h2>Kenangan Kami</h2>
    <div class="gallery">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/Foto%201.HEIC" alt="Foto 1">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/photo2.png" alt="Foto 2">
      <img src="https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/photo3.png" alt="Foto 3">
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
