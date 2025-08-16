---
layout: default
title: Home
description: Portfolio site
---

<div class="page-container">
  <div class="content">
    <section>
      <h1>Welcome</h1>
      <p>This is my portfolio site.</p>
    </section>

    <section>
      <h2>Mixtapes</h2>
      <p>Stuff here...</p>
    </section>

    <section>
      <h2>Videos</h2>
      <p>Stuff here...</p>
    </section>
  </div>

  <!-- Bottom banner -->
  <div class="bottom-banner">
    <img src="/assets/images/banner.png" alt="Banner">
  </div>
</div>

<style>
  /* full page black background */
  body {
    margin: 0;
    background: black;
    font-family: Arial, sans-serif;
    color: #fff;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }

  /* center grey strip */
  .page-container {
    background: #333; /* grey center */
    width: 960px;     /* adjust width as needed */
    margin: 0 auto;   /* centers it, leaving black on the sides */
    display: flex;
    flex-direction: column;
    flex-grow: 1;
  }

  /* main content */
  .content {
    padding: 20px;
    flex: 1;
  }

  /* bottom banner hugs bottom */
  .bottom-banner {
    margin-top: auto;
  }
  .bottom-banner img {
    width: 100%;
    display: block;
  }
</style>
