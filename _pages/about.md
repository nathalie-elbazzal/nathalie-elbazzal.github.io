---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-wrapper {
  max-width: 900px;
}

.home-title {
  font-size: 1.15rem;
  font-weight: 600;
  color: #111;
  margin: 0 0 1.2rem 0;
  line-height: 1.35;
}

.home-layout {
  display: grid;
  grid-template-columns: minmax(0, 2.4fr) minmax(150px, 0.8fr);
  gap: 2rem;
  align-items: start;
}

.home-text {
  font-size: 0.86rem;
  line-height: 1.65;
  color: #111;
  margin: 0;
  text-align: left;
}

.interests-box {
  border-left: 2px solid #7A263A;
  padding-left: 0.9rem;
}

.interests-title {
  color: #7A263A;
  font-size: 0.74rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  margin-bottom: 0.6rem;
}

.interest-item {
  font-size: 0.78rem;
  color: #111;
  margin-bottom: 0.3rem;
}

.home-logos {
  display: flex;
  align-items: center;
  gap: 1.8rem;
  margin-top: 2rem;
  flex-wrap: wrap;
}

.home-logos img {
  width: auto !important;
  max-width: 125px !important;
  max-height: 42px !important;
  object-fit: contain !important;
}

@media (max-width: 768px) {
  .home-layout {
    display: block;
  }

  .interests-box {
    margin-top: 1.4rem;
  }

  .home-logos {
    gap: 1.2rem;
    justify-content: flex-start;
  }

  .home-logos img {
    max-width: 100px !important;
    max-height: 34px !important;
  }
}
</style>

<div class="home-wrapper">

  <h2 class="home-title">
    Hello and welcome to my website!
  </h2>

  <div class="home-layout">
<div style="text-align: justify; text-justify: inter-word;">
      <p class="home-text">Growing up in an environment shaped by recurrent geopolitical tensions, and later working across the Middle East, gave me first-hand insight into how political instability translates into economic outcomes. Witnessing how conflict, sanctions, and geopolitical uncertainty reshaped trade, markets, and firms’ behavior led me to pursue research in international economics. What started with my Master’s theses has since developed into a broader research agenda. Today, as a PhD Candidate in Economics at the University of Paris 8 and a Research Affiliate at the Paris School of Economics, I explore these questions through maritime trade, market integration, and global value chains, with the support of the CEPR ReCIPE Big Research Grant.</p>
    </div>

    <div class="interests-box">
      <div class="interests-title">Research Interests</div>

      <div class="interest-item">International Trade</div>
      <div class="interest-item">Geoeconomics</div>
      <div class="interest-item">Global Value Chains</div>
      <div class="interest-item">Political Economy</div>
    </div>

  </div>

  <div class="home-logos">
    <img src="/images/paris8-logo.jpg" alt="Université Paris 8">
    <img src="/images/pse-logo.png" alt="Paris School of Economics">
    <img src="/images/cepr-logo.png" alt="CEPR ReCIPE">
  </div>

</div>
