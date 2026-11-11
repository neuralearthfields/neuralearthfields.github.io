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
      <div class="hero__details">
        <ul>
          <li>7–8 December 2026</li>
          <li>University of Bonn</li>
        </ul>
        <ul>
          <li>24-hour overnight sprint</li>
          <li>6 teams</li>
          <li>English</li>
        </ul>
      </div>
      <div class="button-group">
        <span class="button button--disabled" aria-disabled="true">Applications closed</span>
      </div>
    </div>
  </div>
</section>

<aside class="supporter-ribbon" aria-label="Event supporters">
  <div class="container supporter-ribbon__inner">
    <a href="https://www.impulse.uni-bonn.de/de" target="_blank" rel="noopener noreferrer" aria-label="IMPULSE House (opens in a new tab)"><img src="{{ '/assets/images/supporters/impulse.svg' | relative_url }}" alt="IMPULSE House"></a>
    <a href="https://www.uni-bonn.de/en/research-and-teaching/research-profile/transdisciplinary-research-areas" target="_blank" rel="noopener noreferrer" aria-label="TRA Modelling (opens in a new tab)"><img src="{{ '/assets/images/supporters/tra-modelling.webp' | relative_url }}" alt="TRA Modelling"></a>
    <a href="https://www.uni-bonn.de/en" target="_blank" rel="noopener noreferrer" aria-label="University of Bonn (opens in a new tab)"><img src="{{ '/assets/images/supporters/university-bonn.svg' | relative_url }}" alt="University of Bonn"></a>
    <a href="https://meo-lab.com" target="_blank" rel="noopener noreferrer" aria-label="MEO Lab (opens in a new tab)"><img class="supporter-ribbon__meo-logo" src="{{ '/assets/images/supporters/Meo_Lab_white.svg' | relative_url }}" alt="MEO Lab"></a>
    <a href="https://taylorgeospatial.org/" target="_blank" rel="noopener noreferrer" aria-label="Taylor Geospatial (opens in a new tab)"><img src="{{ '/assets/images/supporters/taylor-geospatial.svg' | relative_url }}" alt="Taylor Geospatial"></a>
    <a href="https://asterisk.coop/" target="_blank" rel="noopener noreferrer" aria-label="Asterisk Labs (opens in a new tab)"><img src="{{ '/assets/images/supporters/asterisk-labs.png' | relative_url }}" alt="Asterisk Labs"></a>
    <a href="https://www.isprs.org/" target="_blank" rel="noopener noreferrer" aria-label="ISPRS (opens in a new tab)"><img src="{{ '/assets/images/supporters/isprs.png' | relative_url }}" alt="ISPRS"></a>
  </div>
</aside>

<section class="content-section" id="about" aria-labelledby="about-title">
  <div class="container">
    <div class="carousel-header">
      <div>
        <p class="eyebrow">About</p>
        <h2 id="about-title">The challenge</h2>
      </div>
      <div class="slide-tabs" aria-label="About sections">
        <button type="button" class="slide-tab" data-slide="0">Mission</button>
        <button type="button" class="slide-tab" data-slide="1">Research question</button>
        <button type="button" class="slide-tab" data-slide="2">The idea</button>
        <button type="button" class="slide-tab" data-slide="3">Benchmark</button>
      </div>
    </div>

    <div class="carousel-stage">
      <button type="button" class="carousel-button" data-direction="-1" aria-label="Previous">‹</button>
      <div class="carousel-track" tabindex="0" aria-label="Mission, research question, idea, and benchmark">
        <article class="slide-card slide-card--centered" id="mission" aria-labelledby="mission-title">
          <div class="content-grid">
            <div>
              <p class="eyebrow">Mission</p>
              <h3 id="mission-title">Rethinking how we represent the Earth</h3>
            </div>
            <div class="prose">
              <p>Most geospatial information is stored as rasters, grids, vector layers, or other discrete formats. These representations are powerful, but often resolution-dependent, storage-intensive, and difficult to combine across heterogeneous data sources.</p>
              <p>Neural Earth Fields explores a different paradigm: encoding geospatial information in neural-network parameters and querying it continuously from geographic coordinates.</p>
            </div>
          </div>
        </article>

        <article class="slide-card slide-card--centered" id="research-question" aria-labelledby="research-question-title">
          <div class="content-grid">
            <div>
              <p class="eyebrow">Central research question</p>
              <h3 id="research-question-title">Can we fit the Earth into a neural network?</h3>
            </div>
            <div class="prose">
              <p>Build and benchmark neural representations that store geospatial information directly in their parameters.</p>
            </div>
          </div>
        </article>

        <article class="slide-card" id="idea" aria-labelledby="idea-title">
          <div class="content-grid">
            <div>
              <p class="eyebrow">The idea</p>
              <h3 id="idea-title">Earth data as a continuous, queryable function</h3>
            </div>
            <div class="prose">
              <p>Interdisciplinary teams will build compact neural models that take longitude and latitude as input and reconstruct multiple global geospatial layers.</p>
              <p>You bring the architecture; we provide the data, an evaluation harness, and a starter kit to get you running from day one.</p>
              <p>Benchmark results and reproducible submissions remain publicly available after the event, contributing to an open ecosystem for the community.</p>
            </div>
          </div>
          <ol class="slide-steps">
            <li>
              <p class="card-kicker">01</p>
              <h4>Represent</h4>
              <p>Store diverse geospatial fields implicitly in neural-network weights.</p>
            </li>
            <li>
              <p class="card-kicker">02</p>
              <h4>Query</h4>
              <p>Reconstruct information continuously at geographic coordinates.</p>
            </li>
            <li>
              <p class="card-kicker">03</p>
              <h4>Compare</h4>
              <p>Evaluate reconstruction quality together with parameter efficiency.</p>
            </li>
          </ol>
        </article>

        <article class="slide-card" id="benchmark" aria-labelledby="benchmark-title">
          <div class="content-grid">
            <div>
              <p class="eyebrow">Benchmark</p>
              <h3 id="benchmark-title">Diverse Earth data</h3>
            </div>
            <div class="prose">
              <p>Every team receives the same curated global dataset and a common evaluation framework. The initial benchmark brings together three complementary views of the planet.</p>
            </div>
          </div>
          <ul class="slide-steps">
            <li>
              <p class="card-kicker">Physical Earth</p>
              <h4>Water storage anomaly</h4>
              <p>A time series of total water storage anomaly maps derived from gravity observations.</p>
            </li>
            <li>
              <p class="card-kicker">Earth observation</p>
              <h4>ESA WorldCover</h4>
              <p>A high-resolution global land-cover map representing discrete surface classes.</p>
            </li>
            <li>
              <p class="card-kicker">Living Earth</p>
              <h4>iNaturalist</h4>
              <p>Biodiversity observations describing the spatial distribution of species.</p>
            </li>
          </ul>
        </article>
      </div>
      <button type="button" class="carousel-button" data-direction="1" aria-label="Next">›</button>
    </div>
  </div>
</section>

<section class="content-section section--alt" id="participants" aria-labelledby="participants-title">
  <div class="container">
    <p class="eyebrow">Meet the participants</p>
    <h2 id="participants-title">Participants</h2>
    <div class="participants-layout">
      <div class="participant-carousel">
        <div class="carousel-stage">
          <button type="button" class="carousel-button" data-direction="-1" aria-label="Previous participant">‹</button>
          <div class="carousel-track participant-track" tabindex="0" aria-label="Participant profiles">
            {% for participant in site.data.participants %}
            <article class="organizer-card participant-card" data-participant="{{ participant.name | slugify: 'latin' }}" aria-labelledby="participant-{{ forloop.index }}">
              {% if participant.image %}
              <img src="{{ participant.image | relative_url }}" alt="{{ participant.name | escape }}" class="organizer-img participant-img" loading="lazy" width="144" height="144">
              {% else %}
              <div class="organizer-img participant-placeholder" aria-hidden="true">{{ participant.initials }}</div>
              {% endif %}
              <h3 class="organizer-name participant-name" id="participant-{{ forloop.index }}">{{ participant.name | escape }}</h3>
              <p class="organizer-affil participant-bio">{{ participant.bio | escape }}</p>
              <p class="participant-research">{{ participant.research | escape }}</p>
            </article>
            {% endfor %}
          </div>
          <button type="button" class="carousel-button" data-direction="1" aria-label="Next participant">›</button>
        </div>
        <p class="carousel-status" aria-live="polite"><span class="carousel-current">1</span> / {{ site.data.participants | size }}</p>
      </div>
      <figure class="participants-map-wrap">
        {% include participants-map.svg %}
      </figure>
    </div>
  </div>
</section>


<section class="content-section" id="event" aria-labelledby="event-title">
  <div class="container">
    <div class="carousel-header">
      <div>
        <p class="eyebrow">Event</p>
        <h2 id="event-title">24 hours in Bonn</h2>
      </div>
      <div class="slide-tabs" aria-label="Event details">
        <button type="button" class="slide-tab" data-slide="0">Overview</button>
        <button type="button" class="slide-tab" data-slide="1">Program</button>
        <button type="button" class="slide-tab" data-slide="2">Venue</button>
      </div>
    </div>

    <div class="carousel-stage">
      <button type="button" class="carousel-button" data-direction="-1" aria-label="Previous">‹</button>
      <div class="carousel-track" tabindex="0" aria-label="Event overview, program, and venue">
        <article class="slide-card" aria-labelledby="event-overview-title">
          <h3 id="event-overview-title">At a glance</h3>
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
              <dd><a href="https://www.impulse.uni-bonn.de/de" target="_blank" rel="noopener noreferrer">IMPULSE – House for Intellectual Innovation and Creativity</a><br>University of Bonn · Adenauerallee 131 · Bonn</dd>
            </div>
            <div>
              <dt>Participants</dt>
              <dd>A deliberately small cohort: 12 participants in 6 two-person teams, matched by the organizers across Geo and AI expertise</dd>
            </div>
            <div>
              <dt>Language</dt>
              <dd>English</dd>
            </div>
            <div>
              <dt>Awards</dt>
              <dd>Top teams receive a certificate and a commemorative trophy. All reproducible submissions remain on the public benchmark leaderboard after the event.</dd>
            </div>
          </dl>
        </article>

        <article class="slide-card" id="program" aria-labelledby="program-title">
          <h3 id="program-title">Learn, build, present</h3>
          <ol class="slide-steps">
            <li>
              <p class="card-kicker">Day 1 · 12:00–16:00</p>
              <h4>Kickoff</h4>
              <p>Introductory modules, benchmark briefing, team formation, and technical setup.</p>
            </li>
            <li>
              <p class="card-kicker">Overnight · 16:00–08:00</p>
              <h4>Hackathon sprint</h4>
              <p>Code through the night with mentors on hand and the leaderboard live. Basic sleeping arrangements provided — bring a sleeping bag.</p>
            </li>
            <li>
              <p class="card-kicker">Day 2 · 09:00–12:00</p>
              <h4>Finals</h4>
              <p>Consolidation, team presentations, jury review, awards, and closing.</p>
            </li>
          </ol>
        </article>

        <article class="slide-card venue-slide" id="venue" aria-labelledby="venue-title">
          <div class="venue-copy">
            <img class="venue-logo" src="{{ '/assets/images/supporters_white/impulse-white.svg' | relative_url }}" alt="IMPULSE – House for Intellectual Innovation and Creativity">
            <h3 id="venue-title">A house built for exchanging ideas</h3>
            <p>IMPULSE is the University of Bonn’s House for Intellectual Innovation and Creativity—a place for inspiration, intellectual encounter, and creative collaboration.</p>
            <p>Its mission is grounded in the idea that academic work thrives through receiving and sharing impulses. As a dedicated hub for inter- and transdisciplinary innovation, it is a natural home for teams bringing geospatial science and AI together.</p>
            <p class="venue-address">Adenauerallee 131 · 53113 Bonn</p>
            <a class="text-link" href="https://www.impulse.uni-bonn.de/de" target="_blank" rel="noopener noreferrer">Learn more about IMPULSE ↗</a>
          </div>
          <figure class="venue-art" aria-hidden="true">
            <img src="{{ '/assets/images/impulse-house-watercolor.webp' | relative_url }}" alt="" loading="lazy" width="899" height="1350">
          </figure>
        </article>
      </div>
      <button type="button" class="carousel-button" data-direction="1" aria-label="Next">›</button>
    </div>
  </div>
</section>

<section class="content-section section--alt" id="apply" aria-labelledby="apply-title">
  <div class="container">
    <div class="apply-header">
      <div>
        <p class="eyebrow">Applications</p>
        <h2 id="apply-title">Interested in Neural Earth Fields?</h2>
      </div>
      <span class="button button--disabled" aria-disabled="true">Applications closed</span>
    </div>

    <div class="apply-columns">
      <div class="apply-main">
        <h3 class="apply-heading">Who should apply?</h3>
        <p class="apply-lead">Build a Geo + AI team</p>
        <p class="apply-text">We are looking for early-career researchers — Master's students and PhD candidates at any stage — with strong expertise in <strong>either</strong> geospatial science or machine learning/AI. You don't need both: the organizers match participants into two-person teams across complementary expertise. Selection aims for disciplinary, international, and gender diversity.</p>
        <h3 class="apply-lead apply-lead--spaced">Good candidates bring</h3>
        <ul class="apply-list">
          <li>Domain knowledge in geodesy, geography, Earth observation, geoinformatics, or a related field; <strong>or</strong> experience in ML, deep learning, computer vision, or applied mathematics</li>
          <li>Genuine curiosity about neural representations of geospatial data</li>
          <li>Readiness to work through an intensive overnight coding sprint with your team</li>
          <li>Their own laptop — software tools and a starter kit will be provided</li>
        </ul>
        <h3 class="apply-lead apply-lead--spaced">What we cover</h3>
        <ul class="apply-list">
          <li>Travel costs within Europe (train preferred)</li>
          <li>All food and drinks throughout the event (day and night)</li>
          <li>Very basic rest and sleeping arrangements at IMPULSE House — the sprint runs through the night; bring a sleeping bag and prepare for little sleep</li>
          <li>Networking opportunities with fellow participants, mentors, and organizers</li>
        </ul>
      </div>
      <div class="apply-timeline">
        <h3 class="apply-heading">Timeline</h3>
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
    </div>
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
        <span class="organizer-affil">Taylor Geospatial</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/kyle_gao.jpeg' | relative_url }}" alt="Kyle Gao" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Kyle Gao</strong>
        <span class="organizer-affil">Aalto University</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/arjun_rao.jpg' | relative_url }}" alt="Arjun Rao" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Arjun Rao</strong>
        <span class="organizer-affil">University of British Columbia</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/gabriele.jpeg' | relative_url }}" alt="Gabrielė Tijūnaitytė" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Gabrielė Tijūnaitytė</strong>
        <span class="organizer-affil">University of Bonn</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/sawssen.png' | relative_url }}" alt="Sawssen Hannachi" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Sawssen Hannachi</strong>
        <span class="organizer-affil">University of Bonn</span>
      </div>
      <div class="organizer-card">
        <img src="{{ '/assets/images/organizers/sirui.jpg' | relative_url }}" alt="Sirui Hu" class="organizer-img" loading="lazy">
        <strong class="organizer-name">Sirui Hu</strong>
        <span class="organizer-affil">University of Bonn</span>
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
      <a class="supporter-card" href="https://www.uni-bonn.de/en/research-and-teaching/research-profile/transdisciplinary-research-areas" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/tra-modelling.webp' | relative_url }}" alt="TRA Modelling" loading="lazy">
        <span>TRA Modelling <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://www.uni-bonn.de/en" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/university-bonn.svg' | relative_url }}" alt="University of Bonn" loading="lazy">
        <span>University of Bonn <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://meo-lab.com" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/Meo_Lab_white.svg' | relative_url }}" alt="Machine Learning in Earth Observation Lab" loading="lazy">
        <span>MEO Lab <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://taylorgeospatial.org/" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/taylor-geospatial.svg' | relative_url }}" alt="Taylor Geospatial" loading="lazy">
        <span>Taylor Geospatial <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://asterisk.coop/" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/asterisk-labs.png' | relative_url }}" alt="Asterisk Labs" loading="lazy">
        <span>Asterisk Labs <span aria-hidden="true">↗</span></span>
      </a>
      <a class="supporter-card" href="https://www.isprs.org/" target="_blank" rel="noopener noreferrer">
        <img src="{{ '/assets/images/supporters/isprs.png' | relative_url }}" alt="International Society for Photogrammetry and Remote Sensing" loading="lazy">
        <span>ISPRS <span aria-hidden="true">↗</span></span>
      </a>
    </div>
  </div>
</section>

<script>
  var carousels = [];
  var reducedMotion = window.matchMedia('(prefers-reduced-motion: reduce)');

  // ← / → move the focused carousel, or else the one that is mostly on screen
  document.addEventListener('keydown', function (event) {
    if (event.key !== 'ArrowLeft' && event.key !== 'ArrowRight') return;
    if (event.altKey || event.ctrlKey || event.metaKey || event.shiftKey) return;
    if (event.target.closest('input, textarea, select, [contenteditable]')) return;

    var carousel = carousels.find(function (c) { return c.root.contains(document.activeElement); });
    if (!carousel) {
      var best = 0;
      carousels.forEach(function (c) {
        var rect = c.stage.getBoundingClientRect();
        var visible = Math.min(rect.bottom, window.innerHeight) - Math.max(rect.top, 0);
        var ratio = visible / rect.height;
        if (ratio > best) { best = ratio; carousel = c; }
      });
      if (best < 0.5) return;
    }

    event.preventDefault();
    carousel.step(event.key === 'ArrowLeft' ? -1 : 1);
  });

  // Card carousel: one slide at a time, ‹ › buttons wrap around.
  // onChange(index) runs whenever a different slide becomes current.
  function initCarousel(root, onChange) {
    var track = root.querySelector('.carousel-track');
    var slides = Array.prototype.slice.call(track.children);
    var count = slides.length;
    var active = -1;
    var target = null;
    var settle;
    var idle;

    // Copies of the last and first slide sit at either end, so wrapping
    // around is one ordinary slide; once it lands we swap to the real slide.
    function copyOf(slide) {
      var copy = slide.cloneNode(true);
      copy.removeAttribute('id');
      copy.removeAttribute('aria-labelledby');
      copy.querySelectorAll('[id]').forEach(function (el) { el.removeAttribute('id'); });
      copy.setAttribute('aria-hidden', 'true');
      copy.inert = true;
      return copy;
    }
    track.insertBefore(copyOf(slides[count - 1]), slides[0]);
    track.appendChild(copyOf(slides[0]));

    function position() { return Math.round(track.scrollLeft / track.clientWidth); }
    function jumpTo(pos) { track.scrollTo({ left: pos * track.clientWidth, behavior: 'auto' }); }

    function show(index) {
      if (index === active) return;
      active = index;
      onChange(index);
    }

    // index may run one past either end; that lands on a copy
    function goTo(index) {
      var real = (index + count) % count;
      target = real;
      show(real);
      clearTimeout(settle);
      settle = setTimeout(function () { target = null; }, 800);
      track.scrollTo({
        left: (index + 1) * track.clientWidth,
        behavior: reducedMotion.matches ? 'auto' : 'smooth'
      });
    }

    function leaveCopy() {
      var pos = position();
      if (pos === 0) jumpTo(count);
      else if (pos === count + 1) jumpTo(1);
    }

    root.querySelectorAll('.carousel-button').forEach(function (button) {
      button.addEventListener('click', function () {
        goTo(active + Number(button.dataset.direction));
      });
    });

    track.addEventListener('scroll', function () {
      clearTimeout(idle);
      idle = setTimeout(leaveCopy, 120);
      var index = (position() - 1 + count) % count;
      // Ignore the slides passed on the way while a button-driven scroll runs
      if (target !== null) {
        if (index === target) target = null;
        return;
      }
      show(index);
    }, { passive: true });

    carousels.push({
      root: root,
      stage: root.querySelector('.carousel-stage'),
      step: function (direction) { goTo(active + direction); }
    });

    jumpTo(1);
    show(0);
    return function (index) { goTo(index); };
  }

  (function () {
    var section = document.getElementById('participants');
    var cards = section.querySelectorAll('.participant-card');
    var current = section.querySelector('.carousel-current');
    var map = section.querySelector('.participants-map');

    var goTo = initCarousel(section, function (index) {
      var key = cards[index].dataset.participant;
      current.textContent = index + 1;
      map.classList.add('has-active');
      map.querySelectorAll('[data-participant]').forEach(function (el) {
        var match = el.dataset.participant === key;
        el.classList.toggle('is-active', match);
        // Draw the active line above the others
        if (match && el.classList.contains('map-link')) el.parentNode.appendChild(el);
      });
    });

    map.querySelectorAll('.map-site').forEach(function (site) {
      site.addEventListener('click', function () {
        cards.forEach(function (card, i) {
          if (card.dataset.participant === site.dataset.participant) goTo(i);
        });
      });
    });
  })();

  ['about', 'event'].forEach(function (id) {
    var section = document.getElementById(id);
    var tabs = section.querySelectorAll('.slide-tab');

    var goTo = initCarousel(section, function (index) {
      tabs.forEach(function (tab, i) {
        tab.classList.toggle('is-active', i === index);
        tab.setAttribute('aria-current', i === index ? 'true' : 'false');
      });
    });

    tabs.forEach(function (tab) {
      tab.addEventListener('click', function () { goTo(Number(tab.dataset.slide)); });
    });
  });
</script>
