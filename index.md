---
layout: default
title: Home
---
<div class="site-header">
  <a href="/">
<img src="{{ '/SavageLogo.png' | relative_url }}" alt="Logo" class="site-logo">



  </a>
</div>

<style>
  .home-wrap { max-width: 860px; margin: 0 auto; padding: 1.25rem 0; }
  .home-title { margin: 0 0 1rem 0; line-height: 1.15; letter-spacing: -0.02em; }
  .topic-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 12px;
}

  @media (max-width: 640px) { .topic-grid { grid-template-columns: 1fr; } }

  .topic-card {
    display: block;
    padding: 14px 14px 12px 14px;
    border: 1px solid rgba(0,0,0,0.14);
    border-radius: 12px;
    text-decoration: none;
    background: #fff;
    transition: transform .08s ease, border-color .08s ease, box-shadow .08s ease;
  }
  .topic-card:hover {
    transform: translateY(-1px);
    border-color: rgba(0,0,0,0.24);
    box-shadow: 0 6px 18px rgba(0,0,0,0.08);
  }
  .topic-name { margin: 0; font-size: 1.05rem; }
  .topic-sub { margin: 6px 0 0 0; opacity: 0.82; font-size: 0.95rem; }
  .topic-meta { margin-top: 10px; font-size: 0.85rem; opacity: 0.65; }
  .site-header {
  max-width: 860px;
  margin: 0 auto 1rem auto;
}

.site-logo {
  height: 28px;
  width: auto;
  display: block;
}

</style>

<div class="home-wrap">
  <h1 class="home-title">Clear answers and tools to navigate the realities of modern life</h1>

  <div class="topic-grid">
    <a class="topic-card" href="/finance/">
      <h2 class="topic-name">Finance</h2>
      <p class="topic-sub">Money decisions, triage, basics that actually matter.</p>
    
    </a>

    <a class="topic-card" href="/time/">
      <h2 class="topic-name">Time</h2>
      <p class="topic-sub">Capacity, priorities, how to get everything done.</p>
    
    </a>


 
  </div>
</div>
