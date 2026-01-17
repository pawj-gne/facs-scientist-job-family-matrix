---
layout: default
title: Home
---

<!-- Three-Tier Hero Section -->
<div class="tier-hero">
  <h2>The Three-Tier Model</h2>
  <div class="tier-cards">
    <div class="tier-card operator">
      <div class="tier-card-title">Operator</div>
      <div class="tier-card-level">Sci 2 (SE4/5)</div>
      <div class="tier-card-focus">Focus: The Instrument</div>
    </div>
    <div class="tier-card consultant">
      <div class="tier-card-title">Consultant</div>
      <div class="tier-card-level">Sci 3 (SE6)</div>
      <div class="tier-card-focus">Focus: The Experiment</div>
    </div>
    <div class="tier-card investigator">
      <div class="tier-card-title">Investigator</div>
      <div class="tier-card-level">Sci 4 (SE7)</div>
      <div class="tier-card-focus">Focus: The Core/Field</div>
    </div>
  </div>
</div>

<!-- Navigation Cards -->
<h2 style="text-align: center; color: #6a737d; font-size: 1rem; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 1.5rem; border-bottom: none;">What would you like to do?</h2>

<div class="nav-cards">
  <div class="nav-card" onclick="this.classList.toggle('expanded')">
    <div class="nav-card-icon">📚</div>
    <div class="nav-card-title">Learn the Framework</div>
    <div class="nav-card-description">Understand the philosophy behind the tier system and how it prioritizes contribution over tenure.</div>
    <div class="nav-card-cta">→ Start here if you're new</div>
    <div class="nav-card-links">
      <a href="{{ '/handover-doc' | relative_url }}">Three-Tier Model</a>
      <a href="{{ '/facs-scientist-promotion-criteria-summary' | relative_url }}">Promotion Criteria</a>
      <a href="{{ '/promotion-philosophy' | relative_url }}">Promotion Philosophy</a>
    </div>
  </div>

  <div class="nav-card" onclick="this.classList.toggle('expanded')">
    <div class="nav-card-icon">📋</div>
    <div class="nav-card-title">Frame Your Contributions</div>
    <div class="nav-card-description">Strategies and examples for writing compelling promotion cases that demonstrate real impact.</div>
    <div class="nav-card-cta">→ Ready to apply it</div>
    <div class="nav-card-links">
      <a href="{{ '/project-strategies' | relative_url }}">Reframing Strategies</a>
      <a href="{{ '/promotion-project-examples' | relative_url }}">Worked Examples</a>
      <a href="{{ '/matrix-planning-doc' | relative_url }}">Matrix Planning</a>
    </div>
  </div>

  <div class="nav-card" onclick="this.classList.toggle('expanded')">
    <div class="nav-card-icon">💬</div>
    <div class="nav-card-title">Join the Discussion</div>
    <div class="nav-card-description">Share feedback, ask questions, and help shape the policies that define career progression.</div>
    <div class="nav-card-cta">→ Collaborate with others</div>
    <div class="nav-card-links">
      <a href="{{ '/forum' | relative_url }}">Discussion Forum</a>
      <a href="{{ '/converter' | relative_url }}">Submit a Document</a>
    </div>
  </div>

  <div class="nav-card" onclick="this.classList.toggle('expanded')">
    <div class="nav-card-icon">📁</div>
    <div class="nav-card-title">Browse Reference</div>
    <div class="nav-card-description">Original guidelines, known challenges, and documents contributed by the community.</div>
    <div class="nav-card-cta">→ Deep dive into details</div>
    <div class="nav-card-links">
      <a href="{{ '/orig-matrix-guidelines' | relative_url }}">Original Guidelines</a>
      <a href="{{ '/project-challenges' | relative_url }}">Project Challenges</a>
      {% if site.data.documents.size > 0 %}
      {% for doc in site.data.documents %}
      <a href="{{ '/' | append: doc.path | relative_url }}">{{ doc.title }}</a>
      {% endfor %}
      {% endif %}
    </div>
  </div>
</div>

<!-- Key Principles -->
<div class="principles-bar">
  <div class="principle-item">Individual Contributors Only</div>
  <div class="principle-item">Contribution Over Tenure</div>
  <div class="principle-item">Intellectual Equity</div>
  <div class="principle-item">Active Voice</div>
</div>
