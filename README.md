<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Portfolio</title>
  <link rel="stylesheet" href="main.css">
</head>

<body style="padding-top: 30px;">
  <nav>
    <div class="container">
      <h2><a class="a1" href="#">Portfolio</a></h2>
      <div class="hamburger" onclick="toggleMenu()">
        <span></span>
        <span></span>
        <span></span>
      </div>
      <ul class="nav-list" id="nav-list">
        <li class="nav-item"><a href="#menhaqimda">Men haqimda</a></li>
        <li class="nav-item"><a href="#skill">Mahoratlarim</a>
        <li class="nav-item"><a href="#contact">Bogʻlanish</a></li>
      </ul>
    </div>
  </nav>

  <main>
    <section class="section-1">
      <h3 class="h3.text1">Salom,Bu men</h3>
      <strong><h1 class="h1.text1">Otabek Umarov</h1></strong>
      <h3 class="h3.text2">Va Men <span class="changing-text">Fullstack Developerman</span></h3>
      <p>Men Frontend va Beckend dasturchiman</p>
      <button class="button-1" type="submit">Download CV</button>
    </section>

    <section class="section-3">
      <div class="image-1">
        <img src="/HTML-CSS/Myimage2.png" alt="image" />
      </div>
    </section>

    <section id="menhaqimda" class="section-4" style="padding:40px 20px 20px 20px;">
      <h2>Men <span>haqimda</span></h2>
      <p>Ismim Otabek 17 yoshdaman, Oʻzbekiston/Fargʻona/Rishton tumanida yashayman va 1-sonli politexnikumida oʻqiyman.Hozirda ingliz tilini oʻrganyapman albatta dasturchi boʻlish uchun, keyinroq Toshkenting "Najot taʼlim" oʻquv markazida Beckend + Fullstack kurslarida oʻqiyman</p>
      <button class="button-2" type="submit">Read More</button>
      <img src="/HTML-CSS/Myimage1.png" alt="" />
    </section>

    <div id="skill" class="container-box">
      <h1>Mening <span>mahoratlarim</span></h1>
      <ul class="ul-box">
        <li id="box-1" class="box">
          <h3>Muammoni Hal qilish</h3>
          <span>🧠</span>
          <p>Murakkab texnik muammolarni tahlil qilib, eng optimal yechimni topa olaman. Har qanday vaziyatda mantiqiy fikrlash va algoritmik yondashuv asosida ishlayman.</p>
          <button class="button-3">Read More</button>
        </li>
        <li id="box-2" class="box">
          <h3>Texnik koʻnikmalar</h3>
          <span>⚙️</span>
          <p>Zamonaviy dasturlash tillari va asboblari bilan ishlash tajribasiga egaman. Kod yozishdan tortib, loyihani boshqarishgacha barcha jarayonlarni professional darajada bajaraman.</p>
          <div class="button-4"><h4>Read More</h4></div>
        </li>
        <li id="box-3" class="box">
          <h3>Doimiy Oʻsish</h3>
          <span>🚀</span>
          <p>Texnologiya dunyosi tez o'zgaradi — men ham undan orqada qolmayman. Yangi bilimlarni tez o'zlashtirish va jamoada samarali hamkorlik qilish mening kuchli tomonim.</p>
          <button class="button-5">Read More</button>
        </li>
      </ul>
    </div>

    <div id="contact" class="contact">
      <div class="input-list">
        <h2>Men bilan <span>Aloqa</span></h2>
        <input style="background-color: #252a3a;" type="name" name="" id="name" value="" placeholder="Toʻliq ismingiz" />
        <input style="background-color: #252a3a;" type="email" name="email" id="email" placeholder="emailingiz">
        <input style="background-color: #252a3a;" type="tel" name="tel" id="tel" placeholder="Tel raqamingiz">
        <input style="background-color: #252a3a;" type="text" name="text" id="text" value="" placeholder="Sizning xabaringiz"/>
      </div>
      <button class="button-6">Xabarni joʻnatish</button>
    </div>
  </main>

  <footer class="footer">
    <code>Copyright©2026 by Otabek | allrights reserved.</code>
  </footer>
<script src="main.js"></script>
</body>

</html>

