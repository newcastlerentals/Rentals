<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>New Castle PA Rentals | Pet-Friendly Homes</title>
  <meta name="description" content="Pet-friendly rentals in New Castle, Pennsylvania with real 24/7 customer service. Call or text 516-313-7299.">
  <style>
    :root {
      --ink: #17212b;
      --muted: #5d6875;
      --line: #d9e0e7;
      --paper: #f7f9fb;
      --white: #ffffff;
      --green: #0c6b4f;
      --green-dark: #084934;
      --shadow: 0 18px 45px rgba(23, 33, 43, 0.13);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      color: var(--ink);
      background: var(--paper);
      line-height: 1.55;
    }

    a { color: inherit; }

    .topbar {
      position: sticky;
      top: 0;
      z-index: 10;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      padding: 14px clamp(18px, 5vw, 56px);
      background: rgba(255, 255, 255, 0.93);
      border-bottom: 1px solid var(--line);
      backdrop-filter: blur(14px);
    }

    .brand {
      font-weight: 800;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 18px;
      color: var(--muted);
      font-size: 0.95rem;
    }

    .nav-links a {
      text-decoration: none;
    }

    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 44px;
      padding: 12px 18px;
      border-radius: 8px;
      border: 1px solid transparent;
      background: var(--green);
      color: var(--white);
      font-weight: 800;
      text-decoration: none;
      box-shadow: 0 10px 24px rgba(12, 107, 79, 0.18);
    }

    .button:hover {
      background: var(--green-dark);
    }

    .button.secondary {
      background: var(--white);
      color: var(--green);
      border-color: rgba(12, 107, 79, 0.24);
      box-shadow: none;
    }

    .hero {
      display: grid;
      grid-template-columns: minmax(0, 1.05fr) minmax(300px, 0.95fr);
      gap: clamp(28px, 5vw, 70px);
      align-items: center;
      padding: clamp(44px, 7vw, 86px) clamp(18px, 5vw, 56px);
      background:
        linear-gradient(135deg, rgba(12, 107, 79, 0.1), rgba(243, 178, 60, 0.12)),
        var(--white);
    }

    .eyebrow {
      margin: 0 0 12px;
      color: var(--green);
      font-size: 0.82rem;
      font-weight: 900;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    h1, h2, h3 {
      margin: 0;
      line-height: 1.08;
    }

    h1 {
      max-width: 780px;
      font-size: clamp(2.35rem, 6vw, 5.15rem);
    }

    h2 {
      font-size: clamp(1.8rem, 3vw, 2.7rem);
    }

    h3 {
      font-size: 1.25rem;
    }

    .lead {
      max-width: 650px;
      margin: 20px 0 0;
      color: var(--muted);
      font-size: clamp(1.05rem, 1.5vw, 1.25rem);
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 28px;
    }

    .quick-card {
      padding: clamp(22px, 4vw, 34px);
      border: 1px solid var(--line);
      border-radius: 8px;
      background: var(--white);
      box-shadow: var(--shadow);
    }

    .quick-card h2 {
      margin-bottom: 18px;
      font-size: clamp(1.45rem, 2vw, 2rem);
    }

    .checks {
      display: grid;
      gap: 12px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .checks li {
      display: flex;
      gap: 10px;
      align-items: flex-start;
      color: var(--muted);
    }

    .checks strong {
      color: var(--ink);
    }

    .checkmark {
      display: inline-grid;
      flex: 0 0 26px;
      width: 26px;
      height: 26px;
      place-items: center;
      border-radius: 50%;
      background: rgba(12, 107, 79, 0.11);
      color: var(--green);
      font-weight: 900;
    }

    section {
      padding: clamp(44px, 7vw, 82px) clamp(18px, 5vw, 56px);
    }

    .section-heading {
      display: flex;
      align-items: end;
      justify-content: space-between;
      gap: 24px;
      margin-bottom: 28px;
    }

    .section-heading p {
      max-width: 470px;
      margin: 0;
      color: var(--muted);
    }

    .features {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 16px;
      background: var(--green-dark);
      color: var(--white);
    }

    .feature {
      padding: 22px;
      border: 1px solid rgba(255, 255, 255, 0.16);
      border-radius: 8px;
    }

    .feature p {
      margin: 8px 0 0;
      color: rgba(255, 255, 255, 0.78);
    }

    .property-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 20px;
    }

    .property-card {
      overflow: hidden;
      border: 1px solid var(--line);
      border-radius: 8px;
      background: var(--white);
      box-shadow: 0 12px 28px rgba(23, 33, 43, 0.08);
    }

    .property-card img {
      display: block;
      width: 100%;
      aspect-ratio: 4 / 3;
      object-fit: cover;
      background: linear-gradient(135deg, #dfe8ee, #f7f9fb);
    }

    .property-body {
      padding: 20px;
    }

    .rent-price {
      margin: 10px 0 0;
      color: var(--green);
      font-size: 1.35rem;
      font-weight: 900;
      line-height: 1.1;
    }

    .rent-price span {
      color: var(--muted);
      font-size: 0.9rem;
      font-weight: 800;
    }

    .property-body p {
      margin: 12px 0 18px;
      color: var(--muted);
    }

    .tag-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 14px;
    }

    .tag {
      padding: 6px 9px;
      border-radius: 999px;
      background: rgba(12, 107, 79, 0.09);
      color: var(--green-dark);
      font-size: 0.82rem;
      font-weight: 800;
    }

    .zillow-link {
      color: var(--green);
      font-weight: 900;
      text-decoration: none;
    }

    .contact {
      display: grid;
      grid-template-columns: minmax(0, 1fr) minmax(290px, 420px);
      gap: 28px;
      align-items: center;
      background: var(--white);
    }

    .contact-panel {
      padding: clamp(22px, 4vw, 34px);
      border-radius: 8px;
      background: var(--ink);
      color: var(--white);
    }

    .contact-panel p {
      margin: 0 0 16px;
      color: rgba(255, 255, 255, 0.78);
    }

    .contact-list {
      display: grid;
      gap: 12px;
      margin-top: 20px;
    }

    .contact-list a {
      color: var(--white);
      font-size: 1.12rem;
      font-weight: 900;
      text-decoration: none;
    }

    footer {
      padding: 28px clamp(18px, 5vw, 56px);
      color: var(--muted);
      background: var(--paper);
      border-top: 1px solid var(--line);
      font-size: 0.93rem;
    }

    @media (max-width: 900px) {
      .hero, .contact {
        grid-template-columns: 1fr;
      }

      .features, .property-grid {
        grid-template-columns: 1fr;
      }

      .section-heading {
        display: block;
      }

      .section-heading p {
        margin-top: 12px;
      }
    }

    @media (max-width: 620px) {
      .topbar {
        position: static;
        align-items: flex-start;
        flex-direction: column;
      }

      .nav-links {
        width: 100%;
        justify-content: space-between;
      }

      .nav-links a:not(.button) {
        display: none;
      }

      .button {
        width: 100%;
      }

      .hero-actions .button,
      .nav-links .button {
        width: auto;
      }
    }
  </style>
</head>
<body>
  <header class="topbar">
    <div class="brand">New Castle PA Rentals</div>
    <nav class="nav-links" aria-label="Main navigation">
      <a href="#rentals">Rentals</a>
      <a href="#contact">Contact</a>
      <a class="button" href="tel:5163137299">Call 516-313-7299</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div>
        <p class="eyebrow">Pet-friendly rentals in New Castle, Pennsylvania</p>
        <h1>Rent from responsive local property management.</h1>
        <p class="lead">Tour available homes, get quick answers, and reach a real person any time. Pets are welcome with no added pet fees.</p>
        <div class="hero-actions">
          <a class="button" href="tel:5163137299">Call or text now</a>
          <a class="button secondary" href="#rentals">View rentals</a>
        </div>
      </div>

      <aside class="quick-card" aria-label="Rental benefits">
        <h2>Why renters choose us</h2>
        <ul class="checks">
          <li><span class="checkmark">✓</span><span><strong>No added pet fees.</strong> Bring your pet without surprise monthly charges.</span></li>
          <li><span class="checkmark">✓</span><span><strong>Real 24/7 support.</strong> Call or text and reach a human when you need help.</span></li>
          <li><span class="checkmark">✓</span><span><strong>Homes with space.</strong> Larger rentals with practical features like garages, yards, balconies, and laundry.</span></li>
        </ul>
      </aside>
    </section>

    <section class="features" aria-label="Service highlights">
      <div class="feature">
        <h3>Pet-friendly</h3>
        <p>Pets are welcome at no additional pet fee across available rentals.</p>
      </div>
      <div class="feature">
        <h3>Fast communication</h3>
        <p>Call or text directly instead of waiting on a slow ticket system.</p>
      </div>
      <div class="feature">
        <h3>New Castle homes</h3>
        <p>Available rental houses in New Castle with room for everyday life.</p>
      </div>
    </section>

    <section id="rentals" class="listings">
      <div class="section-heading">
        <div>
          <p class="eyebrow">Available rentals</p>
          <h2>Homes ready to view</h2>
        </div>
        <p>See a home you like? Call or text for the fastest response, or open the Zillow listing for more photos and details.</p>
      </div>

      <div class="property-grid">
        <article class="property-card">
          <img src="IMG_0438.jpeg" alt="29 W Miller St rental in New Castle, PA">
          <div class="property-body">
            <h3>29 W Miller St<br>New Castle, PA 16102</h3>
            <div class="rent-price">$1,100<span>/mo</span></div>
            <div class="tag-row" aria-label="Property features">
              <span class="tag">2 bed</span>
              <span class="tag">1 bath</span>
              <span class="tag">Massive garage</span>
              <span class="tag">Available now</span>
            </div>
            <p>Available immediately with a massive garage and practical everyday space.</p>
            <a class="zillow-link" href="https://www.zillow.com/b/29-w-miller-st-new-castle-pa-9PRpDq/" target="_blank" rel="noopener">View on Zillow</a>
          </div>
        </article>

        <article class="property-card">
          <img src="IMG_0234.jpeg" alt="613 Countyline St Unit 1 rental in New Castle, PA">
          <div class="property-body">
            <h3>613 Countyline St, Unit 1<br>New Castle, PA 16101</h3>
            <div class="rent-price">$900<span>/mo</span></div>
            <div class="tag-row" aria-label="Property features">
              <span class="tag">Unit 1</span>
              <span class="tag">Available rental</span>
              <span class="tag">Pet-friendly</span>
              <span class="tag">No pet fee</span>
            </div>
            <p>Clean, straightforward rental option at a strong monthly price. Call or text for current availability and showing times.</p>
            <a class="zillow-link" href="https://www.zillow.com/homedetails/613-Countyline-St-UNIT-1-New-Castle-PA-16101/452273130_zpid/" target="_blank" rel="noopener">View on Zillow</a>
          </div>
        </article>

        <article class="property-card">
          <img src="IMG_0708.jpeg" alt="413 Bartram Ave rental in New Castle, PA">
          <div class="property-body">
            <h3>413 Bartram Ave<br>New Castle, PA 16101</h3>
            <div class="rent-price">$1,500<span>/mo</span></div>
            <div class="tag-row" aria-label="Property features">
              <span class="tag">5 bed</span>
              <span class="tag">1 bath</span>
              <span class="tag">Central air</span>
              <span class="tag">Pets OK</span>
            </div>
            <p>Gorgeous, massive 5-bedroom house with laundry hookups, off-street parking, and pets welcome for free.</p>
            <a class="zillow-link" href="https://www.zillow.com/homedetails/413-Bartram-Ave-New-Castle-PA-16101/93630034_zpid/" target="_blank" rel="noopener">View on Zillow</a>
          </div>
        </article>
      </div>
    </section>

    <section id="contact" class="contact">
      <div>
        <p class="eyebrow">Contact</p>
        <h2>Call, text, or email to schedule a showing.</h2>
        <p class="lead">A real person will answer. Ask about availability, application steps, and move-in timing.</p>
      </div>

      <div class="contact-panel">
        <p>Fastest way to reach us:</p>
        <div class="contact-list">
          <a href="tel:5163137299">516-313-7299</a>
          <a href="sms:5163137299">Text 516-313-7299</a>
          <a href="mailto:newcastleparentals@gmail.com">newcastleparentals@gmail.com</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <span>New Castle PA Rentals</span> - Pet-friendly rentals with real 24/7 customer service.
  </footer>
</body>
</html>
