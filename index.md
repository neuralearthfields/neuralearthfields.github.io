---
layout: default
title:
---

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
      <p class="hero__details">24-hour overnight sprint · 5 teams · English</p>
      <div class="button-group">
        <a class="button" href="https://tally.so/r/VL6a7N" target="_blank" rel="noopener noreferrer"
           onclick="if(typeof gtag==='function'){gtag('event','apply_click',{link_url:'https://tally.so/r/VL6a7N',link_text:'Apply now →',location:'hero'});}">Apply now →</a>
        <a class="button button--secondary" href="#challenge">Learn more →</a>
      </div>
    </div>
  </div>
</section>

<aside class="supporter-ribbon" aria-label="Event supporters">
  <div class="container supporter-ribbon__inner">
    <a href="#supporters" aria-label="See all event supporters"><img src="{{ '/assets/images/supporters/impulse.svg' | relative_url }}" alt="IMPULSE House"></a>
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
  <div class="container" style="margin-top:2.5rem;">
    <aside class="question-box" aria-labelledby="research-question-title">
      <p class="eyebrow">Central research question</p>
      <h3 id="research-question-title">Can we fit the Earth into a neural network?</h3>
      <p>Build and benchmark neural representations that store geospatial information directly in their parameters.</p>
    </aside>
  </div>
</section>

<section class="content-section" id="challenge" aria-labelledby="challenge-title">
  <div class="container">
    <p class="eyebrow">The idea</p>
    <h2 id="challenge-title">Earth data as a continuous, queryable function</h2>
    <p class="section-intro">Interdisciplinary teams will build compact neural models that take longitude and latitude as input and reconstruct multiple global geospatial layers. You bring the architecture; we provide the data, an evaluation harness, and a starter kit to get you running from day one. Benchmark results and reproducible submissions remain publicly available after the event, contributing to an open ecosystem for the community.</p>

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

  </div>
</section>

<section class="content-section" id="event" aria-labelledby="event-title">
  <div class="container event-layout">
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
          <dd>A deliberately small cohort: 10 participants in 5 two-person teams, matched by the organizers across Geo and AI expertise</dd>
        </div>
        <div>
          <dt>Language</dt>
          <dd>English</dd>
        </div>
      </dl>
    </div>
  </div>
</section>

<section class="venue-section" id="venue" aria-labelledby="venue-title">
  <div class="container venue-layout">
    <div class="venue-copy">
      <img class="venue-logo" src="{{ '/assets/images/supporters_white/impulse-white.svg' | relative_url }}" alt="IMPULSE – House for Intellectual Innovation and Creativity">
      <p class="eyebrow">Event location</p>
      <h2 id="venue-title">A house built for exchanging ideas</h2>
      <p>IMPULSE is the University of Bonn’s House for Intellectual Innovation and Creativity—a place for inspiration, intellectual encounter, and creative collaboration.</p>
      <p>Its mission is grounded in the idea that academic work thrives through receiving and sharing impulses. As a dedicated hub for inter- and transdisciplinary innovation, it is a natural home for teams bringing geospatial science and AI together.</p>
      <p class="venue-address">Adenauerallee 131 · 53113 Bonn</p>
      <a class="text-link" href="https://www.impulse.uni-bonn.de/de" target="_blank" rel="noopener noreferrer">Learn more about IMPULSE ↗</a>
    </div>
    <figure class="venue-art" aria-hidden="true">
      <img src="{{ '/assets/images/impulse-house-watercolor.webp' | relative_url }}" alt="" loading="lazy" width="899" height="1350">
    </figure>
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
        <p class="card-kicker">Overnight · 16:00–08:00</p>
        <h3>Hackathon sprint</h3>
        <p>Code through the night with mentors on hand and the leaderboard live. Basic sleeping arrangements provided — bring a sleeping bag.</p>
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
    <p class="section-intro">We are looking for Master's students and PhD candidates with a background in either geospatial science or machine learning/AI — you don't need both. The organizers match participants into two-person teams across complementary expertise. Selection aims for disciplinary, international, and gender diversity.</p>
    <a class="button button--secondary" href="#contact" style="margin-top:0.5rem;display:inline-flex;">See full criteria and timeline →</a>
  </div>
</section>

<section class="content-section" id="contact" aria-labelledby="contact-title">
  <div class="container">
    <p class="eyebrow">Applications</p>
    <h2 id="contact-title">Interested in Neural Earth Fields?</h2>
    <p class="section-intro">We are looking for early-career researchers — Master's students and PhD candidates at any stage — with strong expertise in <strong>either</strong> geospatial science or machine learning/AI. Teams are intentionally matched across both domains, so you do not need to cover both.</p>

    <div class="apply-grid">
      <div class="apply-col">
        <h3 class="apply-heading">Good candidates bring</h3>
        <ul class="apply-list">
          <li>Domain knowledge in geodesy, geography, Earth observation, geoinformatics, or a related field; <strong>or</strong> experience in ML, deep learning, computer vision, or applied mathematics</li>
          <li>Genuine curiosity about neural representations of geospatial data</li>
          <li>Readiness to work through an intensive overnight coding sprint with your team</li>
          <li>Their own laptop — software tools and a starter kit will be provided</li>
        </ul>
      </div>
      <div class="apply-col">
        <h3 class="apply-heading">What we cover</h3>
        <ul class="apply-list">
          <li>Travel costs within Europe (train preferred)</li>
          <li>All food and drinks throughout the event (day and night)</li>
          <li>Very basic rest and sleeping arrangements at IMPULSE House — the sprint runs through the night; bring a sleeping bag and prepare for little sleep</li>
          <li>Networking opportunities with fellow participants, mentors, and organizers</li>
        </ul>
      </div>
    </div>

    <p class="apply-note">Top teams receive a certificate and a commemorative trophy. All reproducible submissions remain on the public benchmark leaderboard after the event.</p>

    <a class="button" href="https://tally.so/r/VL6a7N" target="_blank" rel="noopener noreferrer" style="margin-top:1.5rem;display:inline-flex;"
       onclick="if(typeof gtag==='function'){gtag('event','apply_click',{link_url:'https://tally.so/r/VL6a7N',link_text:'Apply now →',location:'apply_section'});}">Apply now →</a>

    <ol class="timeline">
      <li class="timeline-item">
        <span class="timeline-date">16 October 2026</span>
        <strong class="timeline-label">Application Deadline</strong>
      </li>
      <li class="timeline-item">
        <span class="timeline-date">30 October 2026</span>
        <strong class="timeline-label">Acceptance Notification</strong>
      </li>
      <li class="timeline-item">
        <span class="timeline-date">Early November 2026</span>
        <strong class="timeline-label">On-boarding Meeting <span class="timeline-note">Online</span></strong>
      </li>
      <li class="timeline-item timeline-item--highlight">
        <span class="timeline-date">7–8 December 2026</span>
        <strong class="timeline-label">Event — University of Bonn</strong>
      </li>
    </ol>
  </div>
</section>

<section class="content-section" id="team" aria-labelledby="team-title">
  <div class="container">
    <p class="eyebrow">Team</p>
    <h2 id="team-title">Organizers</h2>
    <div class="organizer-grid">
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/marc_russwurm.jpg' | relative_url }}" alt="Marc Rußwurm" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Marc Rußwurm</strong>
        <span class="organizer-affil">University of Bonn</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/Juergen_Gall.jpeg' | relative_url }}" alt="Jürgen Gall" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Jürgen Gall</strong>
        <span class="organizer-affil">University of Bonn</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/Juergen_Kusche.webp' | relative_url }}" alt="Jürgen Kusche" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Jürgen Kusche</strong>
        <span class="organizer-affil">University of Bonn</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/konstantin_klemmer.webp' | relative_url }}" alt="Konstantin Klemmer" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Konstantin Klemmer</strong>
        <span class="organizer-affil">UCL</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/alistair_francis.jpg' | relative_url }}" alt="Alistair Francis" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Alistair Francis</strong>
        <span class="organizer-affil">Asterisk Labs</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/isaac_corley.jpg' | relative_url }}" alt="Isaac Corley" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Isaac Corley</strong>
        <span class="organizer-affil">Taylor Geospatial Institute</span>
      </div>
    </div>
  </div>
</section>

<section class="supporters-section" id="supporters" aria-labelledby="supporters-title">
  <div class="container">
    <p class="eyebrow">Supported by</p>
    <h2 id="supporters-title">Partners supporting Neural Earth Fields</h2>
    <p class="section-intro">The benchmark and hackathon are made possible by partners across the University of Bonn and the international geospatial research community.</p>
    <div class="supporter-grid">
      <a class="supporter-card" href="https://www.impulse.uni-bonn.de/de" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/impulse.svg' | relative_url }}" alt="IMPULSE – House for Intellectual Innovation and Creativity" loading="lazy">
        <span>IMPULSE House <span aria-hidden="true">↗</span></span>
      </a>
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
