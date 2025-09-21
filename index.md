---
layout: default
title: Home
---

<style>
  body {
    background-color: white;
  }

  .header-grid {
    display: grid;
    grid-template-columns: 1fr auto; /* flexible */
    align-items: center;
    gap: 20px;
  }

  .header-grid img {
    max-width: 100%;
    height: auto; /* proportional */
  }

  /* single column smartphone */
  @media (max-width: 600px) {
    .header-grid {
      grid-template-columns: 1fr; 
      text-align: center;
    }

    .header-grid img {
      max-width: 200px;
      margin: 0 auto;
    }
  }
</style>

<div class="header-grid">
  <div>
    <img src="./images/YelLogo-GDSClouders.png" alt="Logo">
  </div>
  <div>
    <h1>GDSClouders Resource Center</h1>
  </div>
</div>

## [Meet Camila!](./camila.md)
**Camila, our mascot, is an agile, meticulous, and fundamental creature for her own ecosystem, immersed in the cloud. She's the visual embodiment of GDSClouders' philosophy and its approach to innovation and technology infrastructure management.**

# Welcome onboard! Heres the basic GDSClouders Resources

- [Cryptpad](https://cryptpad.fr) -- **Office Suite and Document sharing**
- [Discord](https://discord.com) -- **Chat, Sharing, Meetings**
- [Taiga](https://tree.taiga.io) -- **Project Management, Tracking activities**

