---
layout: about
title: about
permalink: /
subtitle: DPhil student · University of Oxford

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular

selected_papers: false
social: false # profile icons are shown in the navbar instead (enable_navbar_social)

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  /* Blue accent instead of the theme's default purple (light) / cyan (dark) */
  :root { --global-theme-color: #1f6fd1; --global-hover-color: #1f6fd1; }
  html[data-theme="dark"] { --global-theme-color: #6ea8fe; --global-hover-color: #6ea8fe; }
  .post article .profile { margin-left: 1.5rem; margin-bottom: 1rem; }
  .post article h2 { clear: both; margin-top: 2rem; }
  .post article .publications { margin-top: 0; }
  /* Quiet links in running text: same color as the text, thin underline */
  .post article .clearfix > p a,
  .post article .clearfix > ul a {
    color: inherit;
    text-decoration: underline;
    text-decoration-color: var(--global-divider-color);
    text-underline-offset: 3px;
  }
  .post article .clearfix > p a:hover,
  .post article .clearfix > ul a:hover { text-decoration-color: currentColor; }
</style>

I am a DPhil student in Engineering Science at the University of Oxford, working on AI for physics with the
[Machine Learning Research Group](https://www.robots.ox.ac.uk/~mosb/bgl/people/) and the [Quantum Device Lab](https://eng.ox.ac.uk/quantumdevicelab/about-us).
My research sits at the intersection of machine learning, mathematics, physics and quantum computing, from learning the dynamics of quantum systems to
physics-inspired optimizers for deep learning. I spent six months as a visiting guest researcher at the
[Max Planck Institute for the Science of Light](https://mpl.mpg.de/divisions/marquardt-division/research), working on an AI scientist for quantum systems.

If you would like to chat, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/lucas-schorling/).

## Publications

<div class="publications">
{% bibliography --group_by none %}
</div>

## Talks and posters

- **ICLR 2026**, Rio de Janeiro, Brazil, April 2026. Poster: _A Physics-Inspired Optimizer: Velocity Regularized Adam_.
- **APS Global Physics Summit 2025**, Los Angeles, USA, March 2025. Talk: _Meta-learning characteristics and dynamics of quantum systems_.
- **SpinQubit6**, Sydney, Australia, November 2024. Poster: _Meta-learning of dynamics and characteristics of quantum systems_.

## Teaching

- **Retained Lecturer in Engineering Science** (teaching mathematics), Exeter College, University of Oxford, 2024–2025

## Education

- **DPhil in Machine Learning for Quantum Technologies** (Engineering Science), University of Oxford, 2023–present
- **MSc in Mathematical Modelling and Scientific Computing**, University of Oxford, 2022–2023
- **BSc in Engineering Science**, Technical University of Munich, 2018–2022

## Experience

- **Visiting Guest Researcher**, Max Planck Institute for the Science of Light, 2026
- **AI researcher** at start-ups in Munich and San Francisco
- **Internships** at Daimler and Siemens

## Hackathons and others

- Prize winner, ETH Oxford Hackathon
- Builders Retreat organized by Entrepreneur First, Lakestar, OpenAI and Palantir
