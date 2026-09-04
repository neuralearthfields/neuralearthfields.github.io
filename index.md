---
layout: default
title:
---

<aside class="construction-notice" role="note" aria-label="Website status">
  <div class="container">
    <strong>Website under construction.</strong>
    Content is preliminary and may change until the event is publicly announced.
  </div>
</aside>

<section class="hero" aria-labelledby="hero-title">
  <div class="container hero__inner">
    <div class="hero__content">
      <p class="eyebrow">Benchmark &amp; Hackathon</p>
      <h1 id="hero-title">Neural<br>Earth Fields</h1>
      <div class="hero__visual" aria-hidden="true">
        <img src="{{ '/assets/images/earth-transformation.png' | relative_url }}" alt="" class="hero__transform-img" loading="eager">
      </div>
      <p class="hero__subtitle">Learning continuous representations of our planet.</p>
      <p class="hero__details">7–8 December 2026 · University of Bonn</p>
      <div class="button-group">
        <a class="button" href="https://tally.so/r/VL6a7N" target="_blank" rel="noopener noreferrer">Apply →</a>
        <a class="button button--secondary" href="#challenge">Learn more →</a>
      </div>
    </div>
  </div>
</section>

<div class="transform-strip">
  <div class="container">
    <ol class="transform-steps">
      <li class="transform-step"><strong>Observation</strong><span>Real-world sensing</span></li>
      <li class="transform-arrow">→</li>
      <li class="transform-step"><strong>Data</strong><span>Structured geospatial features</span></li>
      <li class="transform-arrow">→</li>
      <li class="transform-step"><strong>Embedding</strong><span>Learned representations</span></li>
      <li class="transform-arrow">→</li>
      <li class="transform-step"><strong>Neural Field</strong><span>Continuous spatial function</span></li>
    </ol>
  </div>
</div>

<aside class="supporter-ribbon" aria-label="Event supporters">
  <div class="container supporter-ribbon__inner">
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/tra-modelling.webp' | relative_url }}" alt="TRA Modelling"></a>
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/university-bonn.webp' | relative_url }}" alt="University of Bonn"></a>
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/meo-lab.png' | relative_url }}" alt="MEO Lab"></a>
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/taylor-geospatial.svg' | relative_url }}" alt="Taylor Geospatial Institute"></a>
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/asterisk-labs.png' | relative_url }}" alt="Asterisk Labs"></a>
    {% comment %}Temporarily hidden pending formal ISPRS approval.
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/isprs.jpg' | relative_url }}" alt="ISPRS"></a>
    {% endcomment %}
  </div>
</aside>

<section class="content-section" id="about" aria-labelledby="about-title">
  <div class="container content-grid">
    <div>
      <p class="eyebrow">Mission</p>
      <h2 id="about-title">Rethinking how we represent the Earth</h2>
    </div>
    <div class="prose">
      <p>Most geospatial information is stored as rasters, grids, vector layers, or other discrete formats. These representations are powerful, but often resolution-dependent, storage-intensive, and difficult to combine across heterogeneous data sources.</p>
      <p>Neural Earth Fields explores a different paradigm: encoding geospatial information in neural-network parameters and querying it continuously from geographic coordinates.</p>
    </div>
  </div>
</section>

<section class="content-section" id="challenge" aria-labelledby="challenge-title">
  <div class="container">
    <p class="eyebrow">The idea</p>
    <h2 id="challenge-title">Earth data as a continuous, queryable function</h2>
    <p class="section-intro">Interdisciplinary teams will build compact neural models that take longitude and latitude as input and reconstruct multiple global geospatial layers. The hackathon launches an open benchmark ecosystem for comparing architectures, coordinate encodings, training strategies, and parameter budgets.</p>

    <div class="card-grid card-grid--three">
      <article class="info-card">
        <p class="card-number">01</p>
        <h3>Represent</h3>
        <p>Store diverse geospatial fields implicitly in neural-network weights.</p>
      </article>
      <article class="info-card">
        <p class="card-number">02</p>
        <h3>Query</h3>
        <p>Reconstruct information continuously at geographic coordinates.</p>
      </article>
      <article class="info-card">
        <p class="card-number">03</p>
        <h3>Compare</h3>
        <p>Evaluate reconstruction quality together with parameter efficiency.</p>
      </article>
    </div>
  </div>
</section>

<section class="content-section" id="benchmark" aria-labelledby="benchmark-title">
  <div class="container">
    <p class="eyebrow">Benchmark</p>
    <h2 id="benchmark-title">One model, diverse Earth data</h2>
    <p class="section-intro">Every team receives the same curated global dataset and a common evaluation framework. The initial benchmark brings together three complementary views of the planet.</p>

    <div class="card-grid card-grid--three">
      <article class="info-card">
        <p class="card-kicker">Physical Earth</p>
        <h3>Water storage anomaly</h3>
        <p>A time series of total water storage anomaly maps derived from gravity observations.</p>
      </article>
      <article class="info-card">
        <p class="card-kicker">Earth observation</p>
        <h3>ESA WorldCover</h3>
        <p>A high-resolution global land-cover map representing discrete surface classes.</p>
      </article>
      <article class="info-card">
        <p class="card-kicker">Living Earth</p>
        <h3>iNaturalist</h3>
        <p>Biodiversity observations describing the spatial distribution of species.</p>
      </article>
    </div>

    <aside class="question-box" aria-labelledby="research-question-title">
      <p class="eyebrow">Central research question</p>
      <h3 id="research-question-title">Which neural-network architecture and training algorithm can most effectively store large amounts of geospatial information in a single model?</h3>
      <p>Submissions will be compared through a public leaderboard that balances reconstruction performance and model size.</p>
    </aside>
  </div>
</section>

<section class="content-section" id="event" aria-labelledby="event-title">
  <div class="container content-grid">
    <div>
      <p class="eyebrow">Event</p>
      <h2 id="event-title">24 hours in Bonn</h2>
    </div>
    <div>
      <dl class="event-facts">
        <div>
          <dt>Date</dt>
          <dd>7–8 December 2026</dd>
        </div>
        <div>
          <dt>Format</dt>
          <dd>Noon-to-noon, overnight hackathon</dd>
        </div>
        <div>
          <dt>Location</dt>
          <dd><a href="https://www.impulse.uni-bonn.de/de">IMPULSE – House for Intellectual Innovation and Creativity</a><br>University of Bonn · Adenauerallee 131 · Bonn</dd>
        </div>
        <div>
          <dt>Participants</dt>
          <dd>10 participants · 5 interdisciplinary teams</dd>
        </div>
      </dl>
    </div>
  </div>
</section>

<section class="content-section" id="program" aria-labelledby="program-title">
  <div class="container">
    <p class="eyebrow">Program</p>
    <h2 id="program-title">Learn, build, present</h2>
    <div class="card-grid card-grid--three">
      <article class="info-card">
        <p class="card-kicker">Day 1 · 12:00–16:00</p>
        <h3>Kickoff</h3>
        <p>Introductory modules, benchmark briefing, team formation, and technical setup.</p>
      </article>
      <article class="info-card">
        <p class="card-kicker">Day 1 · 16:00–Day 2 · 08:00</p>
        <h3>Hackathon sprint</h3>
        <p>Overnight model development with mentoring and live leaderboard submissions.</p>
      </article>
      <article class="info-card">
        <p class="card-kicker">Day 2 · 09:00–12:00</p>
        <h3>Finals</h3>
        <p>Consolidation, team presentations, jury review, awards, and closing.</p>
      </article>
    </div>
  </div>
</section>

<section class="content-section" id="organizers" aria-labelledby="organizers-title">
  <div class="container">
    <p class="eyebrow">Who should apply?</p>
    <h2 id="organizers-title">Build a Geo + AI team</h2>
    <p class="section-intro">The open call is aimed primarily at MSc students, early PhD researchers, and applicants with equivalent technical experience from across Europe. We welcome participants in geodesy, geography, geoinformation, Earth observation, machine learning, computer science, mathematics, physics, and related fields.</p>
    <p class="section-intro">Participants will be matched into two-person teams combining complementary geospatial-domain and AI expertise. Selection will aim for disciplinary, international, and gender diversity.</p>
  </div>
</section>

<section class="content-section" id="faq" aria-labelledby="faq-title">
  <div class="container">
    <p class="eyebrow">What comes next</p>
    <h2 id="faq-title">An open benchmark ecosystem</h2>
    <p class="section-intro">The NEF Starter Kit will bring together curated datasets, baseline models, notebooks, evaluation scripts, documentation, and a public leaderboard. Selected models and reproducible submissions will remain openly available after the event.</p>
  </div>
</section>

<section class="content-section" id="contact" aria-labelledby="contact-title">
  <div class="container">
    <p class="eyebrow">Applications</p>
    <h2 id="contact-title">Interested in Neural Earth Fields?</h2>
    <p class="section-intro">Application details and the full open call will be published here soon.</p>
  </div>
</section>

<section class="supporters-section" id="supporters" aria-labelledby="supporters-title">
  <div class="container">
    <p class="eyebrow">Supported by</p>
    <h2 id="supporters-title">Partners supporting Neural Earth Fields</h2>
    <p class="section-intro">The benchmark and hackathon are made possible by partners across the University of Bonn and the international geospatial research community.</p>
    <div class="supporter-grid">
      <a class="supporter-card" href="https://www.transdisciplinary-research-area.uni-bonn.de/en/research-area-1" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/tra-modelling.webp' | relative_url }}" alt="TRA Modelling" loading="lazy">
        <span>TRA Modelling <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://www.uni-bonn.de/en" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/university-bonn.webp' | relative_url }}" alt="University of Bonn" loading="lazy">
        <span>University of Bonn <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://www.ilr1.uni-bonn.de/en/research/research-groups" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/meo-lab.png' | relative_url }}" alt="Machine Learning in Earth Observation Lab" loading="lazy">
        <span>MEO Lab <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://taylorgeospatial.org/" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/taylor-geospatial.svg' | relative_url }}" alt="Taylor Geospatial Institute" loading="lazy">
        <span>Taylor Geospatial Institute <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://asterisk.coop/" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/asterisk-labs.png' | relative_url }}" alt="Asterisk Labs" loading="lazy">
        <span>Asterisk Labs <span aria-hidden="true">↗</span></span>
      </a>
      {% comment %}Temporarily hidden pending formal ISPRS approval.
      <a class="supporter-card" href="https://www.isprs.org/" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/isprs.jpg' | relative_url }}" alt="International Society for Photogrammetry and Remote Sensing" loading="lazy">
        <span>ISPRS <span aria-hidden="true">↗</span></span>
      </a>
      {% endcomment %}
    </div>
  </div>
</section>
