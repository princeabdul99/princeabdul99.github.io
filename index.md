---
title: "Home"
---

<!-- Inline carousel-only styles (kept here so they don't clash with grid) -->
<style>
  .carousel { position: relative; overflow: hidden; }
  .carousel-track {
    display: flex;
    gap: 1rem;
    flex-wrap: nowrap;        /* keep in one row */
    overflow-x: auto;
    scroll-behavior: smooth;
    padding-bottom: .25rem;
    -ms-overflow-style: none; /* IE/Edge */
    scrollbar-width: none;    /* Firefox */
  }
  .carousel-track::-webkit-scrollbar { display: none; } /* WebKit */
  .carousel .card { flex: 0 0 300px; } /* slide width */
</style>

<section id="about" class="section">
  <div class="about-container">
    <img src="{{ '/assets/images/user-avatar.png' | relative_url }}" alt="A user avatar wearing a brown hat and glasses" class="profile-pic">

    <div class="about-text">
      <h1  class="heading-primary">Hello, I'm Abubakar Abdullahi</h1>
      <p class="hero-description"> <strong>Data Engineer</strong> | <strong>ETL/ELT Developer</strong> | <strong>Software Developer</strong> </p>
      <p class="hero-description">I build practical, production-like data engineering systems — orchestration, storage, transformations, serving, and observability — then explain the decisions behind them.</p>
      <!-- <p class="hero-description"><strong>Core skills:</strong> Python · SQL · DBT · Airflow · Spark · BigQuery · Docker · GCP · Snowflake</p> -->

      <p class="social-links">
        <a href="https://www.linkedin.com/in/abubakar-abdullahi" target="_blank" aria-label="LinkedIn">
          <!-- <i class="fa-brands fa-linkedin"></i> -->
          <ion-icon class="cta-link--icon" name="logo-linkedin"></ion-icon>
        </a>
        &nbsp; &#124; &nbsp;
        <a href="https://github.com/princeabdul99" target="_blank" aria-label="Github">
          <!-- <i class="fa-brands fa-github"></i> -->
          <ion-icon class="cta-link--icon" name="logo-github"></ion-icon>
        </a>
      </p>
    </div>
  </div>
</section>


<!-- ====================== Skills  ===================== -->

<section id="skills" class="section-skill">
  <div class="container">
    <h2 class="heading-secondary">Building Digital Experiences</h2>
    <p class="skill-description">
    I bring creativity and logic together to turn concepts into
    meaningful, functional solutions.
    </p>
    <div class="grid grid--3-cols">


      <div class="skill">
        <h3 class="heading-tertiary heading-title">
        <ion-icon class="icon" name="code-slash-outline"></ion-icon
        ><span>What I can do</span>
        </h3>
        <p class="skill-subheading">
        I can help develop solutions that will help you grow your
        business:
        </p>
        <ul class="list">
          <li class="list-item">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon
              ><span>Data Engineering</span>
          </li>
          <li class="list-item">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon
              ><span>ETL Workflow</span>
          </li>
          <li class="list-item">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon
              ><span>API Integration</span>
          </li>
          <li class="list-item">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon
              ><span>Fullstack Web Development</span>
          </li>
          <li class="list-item">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon
              ><span>Mobile App Development</span>
          </li>
        </ul>
      </div>



      <div class="skill">
        <h3 class="heading-tertiary heading-title">
        <ion-icon name="construct-outline"></ion-icon
        ><span>Tools I Use</span>
        </h3>
        <p class="skill-subheading">
        I use the latest tools and technologies to build functional and
        scalable products:
        </p>
        <ul class="list">
          <li class="list-item--tool">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon>
              <div>
              <span>Data Storage:</span>
              <p>Postgres, GCP, Snowflake, AWS, Azure</p>
              </div>
          </li>

          <li class="list-item--tool">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon>
              <div>
              <span>Orchestration:</span>
              <p>Apache Airflow</p>
              </div>
          </li>

          <li class="list-item--tool">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon>
              <div>
              <span>Data Ingestion & Transformation:</span>
              <p>DLT, DBT, Spark</p>
              </div>
          </li>

          <li class="list-item--tool">
              <ion-icon
              class="icon"
              name="checkmark-circle-outline"
              ></ion-icon>
              <div>
              <span>Others:</span>
              <p>Docker, Python, Power BI, Apache Superset</p>
              </div>
          </li>
        </ul>
      </div>


      <div class="skill">
        <h3 class="heading-tertiary heading-title">
        <ion-icon name="logo-buffer"></ion-icon
        ><span>Data Engineer</span>
        </h3>
        <p class="skill-subheading">
        I design and build efficient data solutions for accurate,
        scalable, and high-performance analytics:
        </p>
          <ul class="list">
            <li class="list-item">
                <ion-icon
                class="icon"
                name="checkmark-circle-outline"
                ></ion-icon
                ><span>Scalable ETL/ELT Pipelines</span>
            </li>
            <li class="list-item">
                <ion-icon
                class="icon"
                name="checkmark-circle-outline"
                ></ion-icon
                ><span>Data Modeling & Warehousing</span>
            </li>
            <li class="list-item">
                <ion-icon
                class="icon"
                name="checkmark-circle-outline"
                ></ion-icon
                ><span>Cloud Data Integration</span>
            </li>
            <li class="list-item">
                <ion-icon
                class="icon"
                name="checkmark-circle-outline"
                ></ion-icon
                ><span>Workflow Automation & Optimization</span>
            </li>
          </ul>
      </div>
    </div>
  </div>
</section>


<!-- ===================== Projects ===================== -->
<section id="projects" class="section">
  <div class="container">
    <div class="section-header">
      <h2 class="heading-secondary">🚀 Projects</h2>
      <a class="view-all" href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener">All repos →</a>
    </div>

  {% assign projects_count = site.data.projects | size %}
  {% if projects_count > 4 %}
    <div class="carousel">
      <button class="scroll-btn left" data-target="#projects-track" aria-label="Scroll projects left">‹</button>
      <div id="projects-track" class="carousel-track" role="region" aria-label="Projects list">
        {% for item in site.data.projects %}
        <article class="card">
          <a class="thumb" href="{{ item.link }}" target="_blank" rel="noopener" aria-label="Open project">
            <img src="{{ item.image | default: '/assets/images/placeholder_project.jpg' | relative_url }}"
                 alt="{{ item.title | escape }} thumbnail"
                 loading="lazy"
                 {% if item.preview_gif %}data-preview="{{ item.preview_gif | relative_url }}"{% endif %}>
          </a>
          <div class="card-body">
            <h3 class="card-title"><a href="{{ item.link }}" target="_blank" rel="noopener">{{ item.title }}</a></h3>
            <p class="card-text">{{ item.description }}</p>
            {% if item.stack %}<p class="card-tags">{{ item.stack }}</p>{% endif %}
            <div class="card-actions">
              {% if item.screenshot %}<a href="#" class="btn ghost" data-lightbox-src="{{ item.screenshot | relative_url }}">Preview</a>{% endif %}
              <a class="btn" href="{{ item.link }}" target="_blank" rel="noopener">Open</a>
            </div>
          </div>
        </article>
        {% endfor %}
      </div>
      <button class="scroll-btn right" data-target="#projects-track" aria-label="Scroll projects right">›</button>
    </div>
  {% else %}
    <div class="gallery">
      {% for item in site.data.projects %}
      <article class="card">
        <a class="thumb" href="{{ item.link }}" target="_blank" rel="noopener" aria-label="Open project">
          <img src="{{ item.image | default: '/assets/images/placeholder_project.jpg' | relative_url }}"
               alt="{{ item.title | escape }} thumbnail" loading="lazy">
        </a>
        <div class="card-body">
          <h3 class="card-title"><a href="{{ item.link }}" target="_blank" rel="noopener">{{ item.title }}</a></h3>
          <p class="card-text">{{ item.description }}</p>
          {% if item.stack %}<p class="card-tags">{{ item.stack }}</p>{% endif %}
          <div class="card-actions">
            {% if item.screenshot %}<a href="#" class="btn ghost" data-lightbox-src="{{ item.screenshot | relative_url }}">Preview</a>{% endif %}
            <a class="btn" href="{{ item.link }}" target="_blank" rel="noopener">Open</a>
          </div>
        </div>
      </article>
      {% endfor %}
    </div>
  {% endif %}

  </div>
</section>





<!-- Tiny helper script for arrow buttons -->
<script>
(function () {
  function init(btn) {
    var targetSel = btn.getAttribute('data-target');
    var track = document.querySelector(targetSel);
    if (!track) return;
    var step = Math.max(300, Math.floor(track.clientWidth * 0.9));

    btn.addEventListener('click', function () {
      track.scrollBy({ left: btn.classList.contains('left') ? -step : step, behavior: 'smooth' });
    });

    function update() {
      var max = track.scrollWidth - track.clientWidth - 1;
      var x = track.scrollLeft;
      var leftBtn = track.parentElement.querySelector('.scroll-btn.left');
      var rightBtn = track.parentElement.querySelector('.scroll-btn.right');
      if (leftBtn) leftBtn.disabled = x <= 0;
      if (rightBtn) rightBtn.disabled = x >= max;
    }
    track.addEventListener('scroll', update, { passive: true });
    window.addEventListener('resize', update);
    update();
  }
  document.querySelectorAll('.scroll-btn').forEach(init);
})();
</script>
