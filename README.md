<!doctype html>
<html lang="en">
<head>
  <h1 style="font-size:60px;">Heading 1</h1>
  <meta charset="utf-8">
  <title>Services | La Calle Catering</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Mexican catering services: drop-off, buffet, and chef-attended stations. Dietary-friendly, locally sourced. Book your date.">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header aria-label="Site header">
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html" aria-current="page">Services</a>
      <a href="menu.html">Menu</a>
      <a href="gallery.html">Gallery</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main id="content">
    <section aria-labelledby="hero-title" class="hero">
      <h1 id="hero-title">Chef-led Mexican Catering, Zero Stress</h1>
      <p>From boardrooms to bodas—drop-off trays, buffet lines, and sizzling chef stations tailored to your crowd.</p>
      <a class="btn" href="contact.html">Check availability</a>
      <a class="btn btn-outline" href="assets/sample-menus.pdf">Download sample menus (PDF)</a>
    </section>

    <section aria-labelledby="packages-title">
      <h2 id="packages-title">Our Service Packages</h2>
      <div class="cards">
        <article class="card" itemscope itemtype="https://schema.org/Service">
          <h3 itemprop="name">Drop-Off Platters</h3>
          <p itemprop="description">Hot, labeled trays with compostable serveware. Great for meetings and study nights.</p>
          <p><strong>$14–$19</strong> per guest • <em>Order min: 20</em></p>
          <ul>
            <li>Delivered hot in disposable pans</li>
            <li>Includes plates, napkins, utensils</li>
            <li>Setup guidance & reheating tips</li>
          </ul>
        </article>

        <article class="card" itemscope itemtype="https://schema.org/Service">
          <h3 itemprop="name">Buffet Service</h3>
          <p itemprop="description">We set, staff, and steward the line so you can actually enjoy your own event.</p>
          <p><strong>$22–$29</strong> per guest • <em>Order min: 40</em></p>
          <ul>
            <li>Chafers, fuel, and buffet signage</li>
            <li>Staffing: 1 server per 25 guests</li>
            <li>Setup & breakdown included</li>
          </ul>
        </article>

        <article class="card" itemscope itemtype="https://schema.org/Service">
          <h3 itemprop="name">Chef-Attended Stations</h3>
          <p itemprop="description">Live al pastor carving or quesabirria on a plancha—interactive and unforgettable.</p>
          <p><strong>$28–$38</strong> per guest • <em>Order min: 60</em></p>
          <ul>
            <li>On-site chef + equipment</li>
            <li>Power 120V outlet required</li>
            <li>Great for weddings & galas</li>
          </ul>
        </article>
      </div>
    </section>

    <section aria-labelledby="build-title">
      <h2 id="build-title">Build-Your-Own Taco Bar</h2>
      <p>Pick 2 proteins, 2 salsas, 3 toppings, and 2 sides. We’ll recommend quantities for your guest count.</p>
      <form aria-describedby="calc-help">
        <label for="guests">Guests</label>
        <input id="guests" type="number" min="10" max="500" placeholder="e.g., 75">
        <button type="button" onclick="calc()">Estimate Portions</button>
        <p id="calc-help">This gives a quick planning estimate—final numbers come with your quote.</p>
        <output id="calc-result" aria-live="polite"></output>
      </form>
      <div class="legend">
        <strong>Salsa Heat:</strong> Mild = Verde • Medium = Roja • Hot = Morita 🌶️
      </div>
    </section>

    <section aria-labelledby="events-title">
      <h2 id="events-title">Events We Cater</h2>
      <ul class="event-types">
        <li><strong>Corporate</strong> – 40–400 guests, 45-min setup, zero-mess teardown.</li>
        <li><strong>Weddings</strong> – late-night quesabirria, signature salsa bars, rentals handled.</li>
        <li><strong>Tailgates</strong> – high-volume taco lines, grab-and-go burrito boxes.</li>
        <li><strong>Nonprofits</strong> – discounted packages for registered 501(c)(3)s.</li>
      </ul>
    </section>

    <section aria-labelledby="diet-title">
      <h2 id="diet-title">Dietary & Allergen Care</h2>
      <p>Vegan tinga, gluten-free corn tortillas, nut-free kitchen. Separate utensils & labeled pans minimize cross-contact.</p>
    </section>

    <section aria-labelledby="area-title">
      <h2 id="area-title">Service Area & Minimums</h2>
      <p>Greater Lafayette + 30 miles. Travel fee beyond 15 miles. Minimums: Drop-Off 20, Buffet 40, Chef-Attended 60.</p>
    </section>

    <section aria-labelledby="pricing-title">
      <h2 id="pricing-title">Pricing, Deposits & Policies</h2>
      <ul>
        <li>Typical range: <strong>$14–$38</strong> per guest depending on service level</li>
        <li>25% deposit to hold your date; final headcount due 7 days prior</li>
        <li>Free reschedule ≥14 days; see <a href="policies.html">full policy</a></li>
      </ul>
    </section>

    <section aria-labelledby="testimonials-title">
      <h2 id="testimonials-title">What Clients Say</h2>
      <blockquote>
        “The al pastor station was a showstopper—people are still talking about it.” — A. Rivera, wedding
      </blockquote>
    </section>

    <section aria-labelledby="faq-title">
      <h2 id="faq-title">FAQ</h2>
      <details>
        <summary>How far in advance should we book?</summary>
        <p>2–4 weeks for drop-off, 6–8 weeks for staffed events, earlier in peak season.</p>
      </details>
      <details>
        <summary>Do you provide rentals?</summary>
        <p>Yes—chafers, tables, linens, and decor available as add-ons.</p>
      </details>
    </section>

    <section class="cta">
      <h2>Ready to plan?</h2>
      <a class="btn" href="contact.html">Get a quote</a>
    </section>
  </main>

  <footer>
    <address>
      La Calle Catering • 123 Market St, Lafayette, IN • <a href="tel:+17655551234">(765) 555-1234</a> •
      <a href="mailto:hello@lacalle.example">hello@lacalle.example</a>
    </address>
    <small>Licensed & insured • We reply within 24h M–F</small>
  </footer>

  <script>
    function calc() {
      const g = parseInt(document.getElementById('guests').value || '0', 10);
      if (!g || g < 10) { document.getElementById('calc-result').textContent = 'Enter 10+ guests.'; return; }
      const tortillas = Math.ceil(g * 2.5);
      const proteinLb = Math.ceil(g * 0.25); // ~1/4 lb per guest
      const salsaCups = Math.ceil(g * 0.15);
      document.getElementById('calc-result').textContent =
        `Plan ~${tortillas} tortillas, ${proteinLb} lb protein, ${salsaCups} cups salsa.`;
    }
  </script>
</body>
</html>
