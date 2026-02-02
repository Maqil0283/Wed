<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aqil | Alya</title>

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
}

body{
  background:#f6f3ed;
}

/* FULL SCREEN FLORAL */
.section{
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:
    url("https://raw.githubusercontent.com/Maqil0283/assets/refs/heads/main/floral-bg.png.PNG")
    center/cover no-repeat;
}

/* CARD */
.card{
  background:rgba(255,255,255,0.88);
  width:86%;
  max-width:380px;
  padding:42px 26px;
  border-radius:16px;
  text-align:center;
}

/* TEXT */
.subtitle{
  font-size:12px;
  letter-spacing:3px;
  margin-bottom:26px;
}

/* MONOGRAM */
.monogram{
  display:flex;
  flex-direction:column;
  align-items:center;
  color:#6b7a3c;
  margin-bottom:18px;
}

.monogram .s{
  font-size:90px;
  line-height:1;
}

.monogram .a{
  font-size:58px;
  margin-top:-8px;
}

/* CONTENT */
.names{
  letter-spacing:4px;
  font-size:14px;
  margin:16px 0;
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
  font-size:13px;
  font-style:italic;
  line-height:1.6;
  margin-top:22px;
}

.hashtag{
  font-size:12px;
  opacity:0.7;
  margin-top:22px;
}
</style>
</head>

<body>

<section class="section">
  <div class="card" data-aos="zoom-in">

    <div class="subtitle">Engagement</div>

    <div class="monogram">
      <div class="s">S</div>
      <div class="a">A</div>
    </div>

    <div class="names">Aqil | Alya</div>

    <div class="date">
      30.05.2025
      <small>3 Jamadilawal 1447H</small>
    </div>

    <div class="ayat">
      “Dan Kami menciptakan kamu berpasang-pasangan”<br>
      <small>Surah An-Naba’ (78:8)</small>
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
