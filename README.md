<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Primary Meta Tags -->
  <meta name="title" content="Learning Cultural Vectors for Cross-Cultural Generation - Sina Malakouti, Deepti Ghadiyaram, Boqing Gong, Adriana Kovashka">
  <meta name="description" content="Learning controllable cultural representations in text-to-image diffusion models through cultural vectors, with analysis of scaling, synthetic data, representation structure, compositionality, and cross-cultural generalization.">
  <meta name="keywords" content="Cultural Generation, Text-to-Image Models, Diffusion Models, Cultural Vectors, Task Vectors, Model Merging, Cross-Cultural Generation">
  <meta name="author" content="Sina Malakouti, Deepti Ghadiyaram, Boqing Gong, Adriana Kovashka">

  <title>Learning Cultural Vectors for Cross-Cultural Generation</title>

  <link rel="icon" type="image/x-icon" href="static/images/favicon.ico">

  <!-- CSS -->
  <link rel="stylesheet" href="static/css/bulma.min.css">
  <link rel="stylesheet" href="static/css/index.css">
  <link rel="stylesheet" href="static/css/fontawesome.all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- JS -->
  <script defer src="static/js/fontawesome.all.min.js"></script>
  <script defer src="static/js/index.js"></script>
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

<p class="is-size-6 has-text-grey" style="margin-bottom: 1rem;">
this page is under development
</p>

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

<div class="column has-text-centered">
<div class="publication-links">

<span class="link-block">
<a href="https://github.com/sinamalakouti/CulturalVectors" target="_blank"
class="external-link button is-normal is-rounded is-dark">
<span class="icon"><i class="fab fa-github"></i></span>
<span>Code</span>
</a>
</span>

<span class="link-block">
<a href="https://openreview.net/forum?id=opG4m2U0Oo" target="_blank"
class="external-link button is-normal is-rounded is-dark">
<span class="icon"><i class="fas fa-file-pdf"></i></span>
<span>Paper</span>
</a>
</span>

<span class="link-block">
<a href="https://arxiv.org/abs/2511.05681" target="_blank"
class="external-link button is-normal is-rounded is-dark">
<span class="icon"><i class="ai ai-arxiv"></i></span>
<span>arXiv</span>
</a>
</span>

</div>
</div>

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


<!-- INTRO / METHOD OVERVIEW -->
<section class="section">
<div class="container is-max-desktop">
<div class="columns is-centered">
<div class="column has-text-centered">

<img src="static/images/intro.png"
     alt="Overview of Learning Cultural Vectors for Cross-Cultural Generation"
     loading="lazy"/>

<p class="subtitle has-text-centered">
Overview of cultural vector learning, analysis, and cross-cultural composition.
</p>

</div>
</div>
</div>
</section>


<!-- BIBTEX -->
<!--
<section class="section" id="BibTeX">
<div class="container is-max-desktop content">

<div class="bibtex-header">
<h2 class="title">BibTeX</h2>
</div>

<pre><code>@inproceedings{
malakouti2026culturalvectors,
title={Learning Cultural Vectors for Cross-Cultural Generation},
author={Sina Malakouti and Deepti Ghadiyaram and Boqing Gong and Adriana Kovashka},
booktitle={The Fortieth Annual Conference on Neural Information Processing Systems},
year={2026}
}</code></pre>

</div>
</section>
-->

</main>


<footer class="footer">
<div class="container">
<div class="columns is-centered">
<div class="column is-8">
<div class="content">
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
