
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

      <div>
        <h1>Dr Arjun Thapa</h1>
        <p class="role">Assistant Professor of Wildlife Conservation</p>
        <p>
          Institute of Forestry, Hetauda Campus ·
          Tribhuvan University, Nepal
        </p>
        <p>
          I study the ecology and conservation of threatened wildlife
          in the Himalayas. My research combines field surveys,
          spatial modelling and conservation genetics to understand
          how environmental change affects species and their habitats.
        </p>
        <div class="buttons">
          <a class="button" href="mailto:arjun.thapa@hc.tu.edu.np">
            Email
          </a>
          <a class="button" href="#research">Research</a>
          <a class="button" href="#publications">Publications</a>
        </div>
      </div>
    </div>
  </section>

  <main>
    <section id="about">
      <div class="container">
        <h2>About Me</h2>
        <p>
          I am a wildlife ecologist and conservation researcher based
          at Tribhuvan University, Nepal. My work focuses on threatened
          mammals, particularly red pandas, and the conservation of
          Himalayan biodiversity.
        </p>
        <p>
          I completed my PhD in Ecology at the University of Chinese
          Academy of Sciences, conducting research at the Institute
          of Zoology. I subsequently undertook postdoctoral research
          at the Chinese Academy of Sciences through the President’s
          International Fellowship Initiative.
        </p>
        <p>
          Alongside research, I teach wildlife conservation,
          supervise students and contribute to conservation planning
          and community-based wildlife monitoring.
        </p>
      </div>
    </section>

    <section id="research">
      <div class="container">
        <h2>Research</h2>
        <div class="grid">
          <article class="card">
            <h3>Red Panda Conservation</h3>
            <p>
              Understanding distribution, habitat requirements,
              genetic diversity and conservation threats across
              the Himalayan region.
            </p>
          </article>
          <article class="card">
            <h3>Climate Change and Biodiversity</h3>
            <p>
              Assessing species vulnerability, potential range shifts
              and climate refugia under environmental change.
            </p>
          </article>
          <article class="card">
            <h3>Wildlife Corridors</h3>
            <p>
              Studying habitat occupancy, landscape connectivity
              and land-cover change to inform corridor conservation.
            </p>
          </article>
          <article class="card">
            <h3>Human–Wildlife Coexistence</h3>
            <p>
              Investigating wildlife conflict and practical mitigation
              approaches that support conservation and local livelihoods.
            </p>
          </article>
        </div>
      </div>
    </section>

    <section id="publications">
      <div class="container">
        <h2>Selected Publications</h2>

        <article class="publication">
          <strong>Thapa, A., Ma, T., Wei, F. &amp; Hu, Y. (2026).</strong>
          Low genetic diversity in climate change refugia threatens
          the endangered Himalayan red panda Ailurus fulgens.
          <em>Integrative Zoology.</em>
          <a href="https://doi.org/10.1111/1749-4877.70103">
            Read article
          </a>
        </article>

        <article class="publication">
          <strong>Thapa, A. and colleagues (2025).</strong>
          Differential vulnerability of key threatened mammals to
          climate and land cover changes in the Central Himalayas.
          <em>Ecosphere.</em>
          <a href="https://doi.org/10.1002/ecs2.70242">
            Read article
          </a>
        </article>

        <article class="publication">
          <strong>Hu, Y., Thapa, A. and colleagues (2020).</strong>
          Genomic evidence for two phylogenetic species and
          long-term population bottlenecks in red pandas.
          <em>Science Advances.</em>
          <a href="https://doi.org/10.1126/sciadv.aax5751">
            Read article
          </a>
        </article>

        <article class="publication">
          <strong>Thapa, A., Hu, Y. &amp; Wei, F. (2018).</strong>
          The endangered red panda (Ailurus fulgens):
          Ecology and conservation approaches across the entire range.
          <em>Biological Conservation.</em>
          <a href="https://doi.org/10.1016/j.biocon.2018.02.014">
            Read article
          </a>
        </article>
      </div>
    </section>

    <section id="teaching">
      <div class="container">
        <h2>Teaching and Supervision</h2>
        <p>My teaching experience includes:</p>
        <ul>
          <li>Conservation Biology</li>
          <li>Wildlife Biology and Ecology</li>
          <li>Human–Wildlife Interface Management</li>
          <li>Mammalogy and Ornithology</li>
          <li>Biodiversity Conservation and Management</li>
        </ul>
        <p>
          I have supervised MSc research on red panda habitat,
          leopard occupancy and conflict, Chinese pangolin distribution,
          hispid hare habitat and human–wildlife interactions.
        </p>
      </div>
    </section>

    <section id="service">
      <div class="container">
        <h2>Service and Recognition</h2>
        <ul>
          <li>
            Founding President, Small Mammals Conservation
            &amp; Research Foundation
          </li>
          <li>Member, IUCN SSC Lagomorph Specialist Group</li>
          <li>Dr. Pralad Yonzon Conservation Award, 2023</li>
        </ul>
      </div>
    </section>

    <section id="contact">
      <div class="container">
        <h2>Contact</h2>
        <p>
          I welcome enquiries about research collaboration,
          wildlife conservation and student research.
        </p>
        <p>
          <strong>Dr Arjun Thapa</strong><br>
          Institute of Forestry, Hetauda Campus<br>
          Tribhuvan University, Hetauda, Nepal
        </p>
        <p>
          <a href="mailto:arjun.thapa@hc.tu.edu.np">
            arjun.thapa@hc.tu.edu.np
          </a>
        </p>
      </div>
    </section>
  </main>

  <footer>Dr Arjun Thapa · Wildlife Ecology and Conservation</footer>
</body>
</html>

{% include navigation.html %}
