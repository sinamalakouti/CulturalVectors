<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <meta name="title" content="Learning Cultural Vectors for Cross-Cultural Generation">
  <meta name="description" content="Learning Cultural Vectors for Cross-Cultural Generation">
  <meta name="keywords" content="Cultural Generation, Text-to-Image Models, Diffusion Models, Cultural Vectors">
  <meta name="author" content="Sina Malakouti, Deepti Ghadiyaram, Boqing Gong, Adriana Kovashka">

  <title>Learning Cultural Vectors for Cross-Cultural Generation</title>

  <link rel="icon" type="image/x-icon" href="static/images/favicon.ico">

  <link rel="stylesheet" href="static/css/bulma.min.css">
  <link rel="stylesheet" href="static/css/index.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
</head>

<body>

<main id="main-content">

<!-- HERO -->
<section class="hero">
  <div class="hero-body">
    <div class="container is-max-desktop">
      <div class="columns is-centered">
        <div class="column has-text-centered">

          <h1 class="title is-1 publication-title">
            Learning Cultural Vectors for Cross-Cultural Generation
          </h1>

          <div class="is-size-5 publication-authors">
            <span class="author-block">
              <a href="https://sinamalakouti.github.io">Sina Malakouti</a>,
            </span>
            <span class="author-block">
              <a href="https://deeptigp.github.io/">Deepti Ghadiyaram</a>,
            </span>
            <span class="author-block">
              <a href="https://boqinggong.github.io/">Boqing Gong</a>,
            </span>
            <span class="author-block">
              <a href="https://people.cs.pitt.edu/~kovashka/">Adriana Kovashka</a>
            </span>
          </div>

          <div class="is-size-5 publication-authors">
            <span class="author-block">
              University of Pittsburgh and Boston University<br>
              The Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS), 2026
            </span>
          </div>

          <p class="is-size-5 has-text-grey" style="margin-top: 1.5rem;">
            this page is under development
          </p>

        </div>
      </div>
    </div>
  </div>
</section>


<!-- ABSTRACT -->
<section class="section hero is-light">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">

        <h2 class="title is-3">Abstract</h2>

        <div class="content has-text-justified">
          <p>
            We study cultural vectors as controllable representations of cultural knowledge in text-to-image diffusion models. First, we show that they can be learned effectively from synthetic data and that inference-time scaling controls the trade-off between cultural alignment and exaggeration. Second, we analyze their properties, including where cultural information is encoded in the U-Net and how cultural vectors behave in activation space. Third, we study their compositionality for multi-cultural behavior and cross-cultural generation, and show that naive composition introduces interference between cultural vectors. We then explore two complementary directions for improving composition, learning more independent cultural representations and using culturally aware merging.
          </p>
        </div>

      </div>
    </div>
  </div>
</section>


<!-- OVERVIEW IMAGE -->
<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered">
      <div class="column has-text-centered">

        <img
          src="static/images/intro.png"
          alt="Overview of Learning Cultural Vectors for Cross-Cultural Generation"
          loading="lazy"
        />

        <p class="subtitle has-text-centered">
          Overview of cultural vector learning, analysis, and cross-cultural composition.
        </p>

      </div>
    </div>
  </div>
</section>


<!-- BIBTEX
<section class="section" id="BibTeX">
  ...
</section>
-->

</main>

<footer class="footer">
  <div class="container">
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content has-text-centered">
          <p>
            This page was built using the Academic Project Page Template.
          </p>
        </div>
      </div>
    </div>
  </div>
</footer>

</body>
</html>
