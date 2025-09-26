<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital DreamWorks by Punya Ramchandani</title>
  <!-- Font Awesome for social media icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    h1 {
      background: #333;
      color: #fff;
      padding: 20px;
      margin: 0;
    }

    /* Introductory line */
    .intro-text {
      margin: 25px 20px 10px;
      font-size: 1.2em;
      color: #333;
    }

    .links {
      margin-top: 20px;
      display: flex;               /* flex container */
      flex-wrap: wrap;             /* allow wrap on small screens */
      justify-content: center;     /* center items horizontally */
      align-items: center;         /* align vertically */
      gap: 20px;                   /* space between buttons */
    }

    .social-btn, .dropbtn {
      display: inline-block;
      padding: 15px 30px;
      border-radius: 8px;
      font-size: 1.2em;
      color: #fff;
      text-decoration: none;
      transition: transform 0.2s, opacity 0.2s;
      cursor: pointer;
    }

    .social-btn i, .dropbtn i {
      margin-right: 10px;
    }

    .social-btn:hover, .dropbtn:hover {
      transform: scale(1.05);
      opacity: 0.9;
    }

    /* Brand colors */
    .whatsapp  { background: #25D366; }
    .email     { background: #6c757d; }
    .instagram { background: radial-gradient(circle at 30% 30%, #f58529, #dd2a7b, #8134af, #515bd4); }
    .linkedin  { background: #0077b5; }
    .tiktok    { background: #000000; }
    .pinterest { background: #c8232c; }
    .youtube   { background: #ff0000; }

    /* Dropdown container */
    .dropdown {
      position: relative;
      display: inline-block;
    }

    /* Dropdown content (hidden by default) */
    .dropdown-content {
      display: none;
      position: absolute;
      top: 100%;
      left: 50%;
      transform: translateX(-50%);
      background-color: #fff;
      min-width: 250px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      border-radius: 8px;
      padding: 10px 0;
      z-index: 1;
      text-align: left;
      white-space: nowrap;
    }

    .dropdown-content a {
      color: #333;
      padding: 10px 20px;
      text-decoration: none;
      display: block;
      font-size: 1em;
    }

    .dropdown-content a:hover {
      background-color: #f1f1f1;
    }

    /* Show the dropdown menu on hover */
    .dropdown:hover .dropdown-content {
      display: block;
    }
  </style>
</head>
<body>

  <h1>Digital DreamWorks by Punya Ramchandani</h1>

  <!-- Friendly intro line -->
  <div class="intro-text">
    Click below to explore and connect with us across our platforms!
  </div>

  <div class="links">

    <!-- WhatsApp -->
    <a class="social-btn whatsapp" href="https://wa.me/971503173383" target="_blank">
      <i class="fab fa-whatsapp"></i> WhatsApp Business
    </a>

    <!-- Email -->
    <a class="social-btn email" href="mailto:Digtaldreamworksbypunya@gmail.com" target="_blank">
      <i class="fas fa-envelope"></i> Email
    </a>

    <!-- Instagram dropdown with 4 links -->
    <div class="dropdown">
      <div class="dropbtn instagram">
        <i class="fab fa-instagram"></i> Instagram
      </div>
      <div class="dropdown-content">
        <a href="https://www.instagram.com/digital_dreamworks_by_punya/" target="_blank">Digital DreamWorks by Punya</a>
        <a href="https://www.instagram.com/digistartips/" target="_blank">DigiStart Tips</a>
        <a href="https://www.instagram.com/fun_fridays_with_clicksy/" target="_blank">Fun Fridays with Clicksy</a>
        <a href="https://www.instagram.com/printspiration_thursdays/" target="_blank">Printspiration Thursdays</a>
      </div>
    </div>

    <!-- LinkedIn -->
    <a class="social-btn linkedin" href="https://www.linkedin.com/in/punya-ramchandani-211021318/" target="_blank">
      <i class="fab fa-linkedin"></i> LinkedIn
    </a>

    <!-- TikTok -->
    <a class="social-btn tiktok" href="https://www.tiktok.com/@digitaldreamworksbypunya?_t=ZS-8zqEdRSnjFP&_r=1" target="_blank">
      <i class="fab fa-tiktok"></i> TikTok
    </a>

    <!-- Pinterest -->
    <a class="social-btn pinterest" href="https://www.pinterest.com/DigitalDreamworksByPunya/" target="_blank">
      <i class="fab fa-pinterest"></i> Pinterest
    </a>

    <!-- YouTube -->
    <a class="social-btn youtube" href="https://www.youtube.com/@DigitalDreamworksByPunya" target="_blank">
      <i class="fab fa-youtube"></i> YouTube
    </a>

  </div>

</body>
</html>
