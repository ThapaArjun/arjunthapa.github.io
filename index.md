
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dr Arjun Thapa | Wildlife Ecologist</title>
  <meta name="description"
        content="Dr Arjun Thapa, wildlife ecologist at Tribhuvan University, Nepal. Research in Himalayan biodiversity and conservation.">

  <style>
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; scroll-padding-top: 100px; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #24343b;
      line-height: 1.75;
      background: #f5f8f8;
    }
    a { color: #096f69; }
    a:focus-visible {
      outline: 3px solid #d99b24;
      outline-offset: 5px;
    }
    .container {
      width: min(1120px, 90%);
      margin: auto;
    }
    header {
      position: sticky;
      top: 0;
      z-index: 10;
      background: white;
      border-bottom: 1px solid #e3ebeb;
    }
    .navigation {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
      padding: 18px 0;
    }
    .brand {
      font-size: 21px;
      font-weight: bold;
      text-decoration: none;
      color: #24343b;
      white-space: nowrap;
    }
    nav { display: flex; flex-wrap: wrap; gap: 20px; }
    nav a {
      color: #52616a;
      font-weight: bold;
      text-decoration: none;
    }
    nav a:hover { color: #087c73; }

    .hero {
      background: linear-gradient(120deg, #105d58, #10766d, #124e59);
      color: white;
      padding: 85px 0;
    }
    .hero-inner {
      display: grid;
      grid-template-columns: 240px 1fr;
      gap: 45px;
      align-items: center;
    }
    .portrait {
      width: 240px;
      height: 290px;
      object-fit: cover;
      border: 5px solid #d5eae6;
      border-radius: 22px;
    }
    h1 {
      margin: 0 0 10px;
      font-size: clamp(36px, 5vw, 54px);
      line-height: 1.15;
    }
    .role {
      color: #d8fff2;
      font-size: 22px;
      font-weight: bold;
      margin: 18px 0;
    }
    .hero p { font-size: 18px; }
    .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 26px;
    }
    .button {
      display: inline-block;
      padding: 10px 20px;
      border: 1px solid #8bc2ba;
      border-radius: 30px;
      background: #ffffff12;
      color: white;
      font-weight: bold;
      text-decoration: none;
    }
    .button:hover { background: #ffffff26; }

    main section { padding: 55px 0; }
    main section:nth-child(even) { background: white; }
    h2 {
      color: #105f59;
      font-size: 30px;
      margin: 0 0 22px;
    }
    h3 { margin-top: 0; }
    .grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 22px;
    }
    .card {
      background: white;
      border: 1px solid #dce7e5;
      border-radius: 12px;
      padding: 25px;
    }
    .card p { margin-bottom: 0; }
    .publication {
      padding: 18px 0;
      border-bottom: 1px solid #dce7e5;
    }
    footer {
      padding: 25px;
      text-align: center;
      background: #104f4c;
      color: white;
    }

    @media (max-width: 760px) {
      .navigation { flex-direction: column; align-items: flex-start; }
      nav { gap: 8px 16px; font-size: 14px; }
      header { position: static; }
      .hero { padding: 45px 0; }
      .hero-inner { grid-template-columns: 1fr; gap: 25px; }
      .portrait { width: 190px; height: 230px; }
      .grid { grid-template-columns: 1fr; }
    }
    @media (prefers-reduced-motion: reduce) {
      html { scroll-behavior: auto; }
    }
  </style>
</head>

<body>
  <header>
    <div class="container navigation">
      <a class="brand" href="#home">Dr Arjun Thapa</a>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="#teaching">Teaching</a>
        <a href="#service">Service</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section class="hero" id="home">
    <div class="container hero-inner">
      <!-- Upload your photograph as profile.jpg -->
      <img class="portrait" src="profile.jpg"
           alt="Portrait of Dr Arjun Thapa">

      

  <footer>Dr Arjun Thapa · Wildlife Ecology and Conservation</footer>
</body>
</html>

{% include navigation.html %}
