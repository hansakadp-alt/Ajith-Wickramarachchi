[Ajith Wickramaarachchi.html](https://github.com/user-attachments/files/24686847/Ajith.Wickramaarachchi.html)
<!DOCTYPE html>
<html lang="si">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>අජිත් වික්‍රමාරච්චි | Online ශිෂ්‍යත්ව පන්තිය</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {box-sizing:border-box;}
    body {
      margin:0;
      font-family:'Poppins', Arial, Helvetica, sans-serif;
      line-height:1.7;
      color:#333;
      background:#ffffff;
    }

    /* Animations */
    @keyframes fadeUp {
      from {opacity:0; transform:translateY(30px);} 
      to {opacity:1; transform:translateY(0);} 
    }
    @keyframes zoomIn {
      from {opacity:0; transform:scale(0.9);} 
      to {opacity:1; transform:scale(1);} 
    }

    header {
      background:linear-gradient(90deg,#0b5ed7,#0d6efd);
      color:#fff;
      padding:15px 40px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      flex-wrap:wrap;
      animation:fadeUp 1s ease;
    }
    header h1 {margin:0;font-size:22px;font-weight:600;}

    nav a {
      color:#fff;
      margin-left:20px;
      text-decoration:none;
      font-weight:500;
      position:relative;
    }
    nav a::after {
      content:'';
      position:absolute;
      left:0;bottom:-4px;
      width:0;height:2px;
      background:#ffc107;
      transition:.3s;
    }
    nav a:hover::after {width:100%;}

    .hero {
      background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
      url('https://images.unsplash.com/photo-1524995997946-a1c2e315a42f');
      background-size:cover;
      background-position:center;
      color:#fff;
      padding:110px 40px;
      text-align:center;
    }
    .hero h2 {
      font-size:42px;
      margin-bottom:20px;
      animation:fadeUp 1.2s ease;
    }
    .hero p {
      font-size:18px;
      max-width:850px;
      margin:auto;
      animation:fadeUp 1.5s ease;
    }

    .btn {
      display:inline-block;
      margin-top:30px;
      padding:14px 32px;
      background:#ffc107;
      color:#000;
      text-decoration:none;
      font-weight:600;
      border-radius:30px;
      transition:.3s;
      animation:zoomIn 1.8s ease;
    }
    .btn:hover {
      background:#ffb300;
      transform:translateY(-3px);
      box-shadow:0 10px 20px rgba(0,0,0,.2);
    }

    .section {
      padding:80px 40px;
      max-width:1200px;
      margin:auto;
      animation:fadeUp 1s ease;
    }
    .section h3 {
      text-align:center;
      font-size:34px;
      margin-bottom:50px;
      color:#0b5ed7;
    }

    .cards {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:30px;
    }
    .card {
      background:#fff;
      border-radius:16px;
      padding:35px 25px;
      text-align:center;
      box-shadow:0 15px 35px rgba(0,0,0,.08);
      transition:.35s;
    }
    .card:hover {
      transform:translateY(-10px);
      box-shadow:0 25px 45px rgba(0,0,0,.15);
    }
    .card h4 {margin-top:0;color:#0b5ed7;font-size:22px;}

    .about {background:#f8f9ff;}

    footer {
      background:#0b5ed7;
      color:#fff;
      text-align:center;
      padding:30px 20px;
      font-size:14px;
    }

    /* Responsive */
    @media(max-width:768px){
      .hero h2 {font-size:30px;}
      nav {margin-top:10px;}
      nav a {margin-left:12px;}
    }
  </style>
</head>
<body>

<header>
  <h1>අජිත් වික්‍රමාරච්චි</h1>
  <nav>
    <a href="#">මුල් පිටුව</a>
    <a href="#services">පන්ති</a>
    <a href="#about">අප ගැන</a>
    <a href="#contact">සම්බන්ධ වන්න</a>
  </nav>
</header>

<section class="hero">
  <h2>2026 වර්ෂයට 3️⃣, 4️⃣, 5️⃣ ශ්‍රේණි සඳහා නවක සිසුන් බඳවා ගනු ලැබේ</h2>
  <p>මුළු දිවයිනම ආවරණය කරන, Zoom තාක්ෂණය ඔස්සේ පවත්වාගෙන යන විශිෂ්ට Online ශිෂ්‍යත්ව පන්තිය.</p>
  <a href="https://wa.me/94702405031?text=මගේ%20දරුවා%20ලියාපදිංචි%20කරගන්න%20කැමතියි.%0A%0Aදරුවාගේ%20නම%3A%0Aශ්‍රේණිය%20%283%2F4%2F5%29%3A%0Aනගරය%2Fප්‍රදේශය%3A" target="_blank" class="btn">දැන්ම ලියාපදිංචි වන්න</a>
</section>

<section class="section" id="services">
  <h3>අපගේ පන්ති</h3>
  <div class="cards">
    <div class="card">
      <h4>3 ශ්‍රේණිය</h4>
      <p>සරල ඉගැන්වීම් ක්‍රම සහ මූලික චින්තන පුහුණුව.</p>
    </div>
    <div class="card">
      <h4>4 ශ්‍රේණිය</h4>
      <p>ඉලක්කගත ප්‍රශ්නෝත්තර සාකච්ඡා සහ නවීණ අධ්‍යාපන ක්‍රම.</p>
    </div>
    <div class="card">
      <h4>5 ශ්‍රේණිය</h4>
      <p>විභාගයට සූදානම් කරන සම්පූර්ණ ශිෂ්‍යත්ව පුහුණුව.</p>
    </div>
  </div>
</section>

<section class="section about" id="about">
  <h3>අප ගැන</h3>
  <p style="max-width:900px;margin:auto;text-align:center;">
    වසරක් පාසා දිවයිනේ විශිෂ්ටයන් බිහි කරන Online ශිෂ්‍යත්ව පන්තියකි.<br><br>
    ✔️ සරල ඉගැන්වීමේ ක්‍රම<br>
    ✔️ ඉලක්කගත ප්‍රශ්නෝත්තර සාකච්ඡා<br>
    ✔️ Zoom ඔස්සේ විභාගය දක්වාම ඉගැන්වීම්<br>
    ✔️ අතපසු වන පාඩම් සඳහා Recording<br><br>
    <strong>ප්‍රවීණ ශිෂ්‍යත්ව දේශක – අජිත් වික්‍රමාරච්චි</strong>
  </p>
</section>

<section class="section" id="contact">
  <h3>සම්බන්ධ වන්න</h3>
  <p style="text-align:center;">
    📧 ajithwickramarachchi879@gmail.com<br>
    ☎️ +94 70 240 5031
  </p>
</section>

<footer>
  <p>© 2026 අජිත් වික්‍රමාරච්චි | සියලු හිමිකම් ඇවිරිණි</p>
</footer>

</body>
</html>
