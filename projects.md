---
layout: default
title: Projects
---

A selection of apps I’ve built:

<div class="projects-grid">

<!-- === Featured Projects === -->

<div class="project-card">
  <a href="{{ '/assets/img/wastenot.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
    <img src="{{ '/assets/img/wastenot.png' | relative_url }}" alt="WasteNot screenshot" width="100%">
  </a>
  <h2>WasteNot</h2>
  <p>Full-stack web app that helps reduce food waste by tracking ingredients and expiration dates, then suggesting recipes with data from the Spoonacular API. Built with React, FastAPI, and PostgreSQL, deployed on Render</p>
  <p><strong>Stack:</strong> React • FastAPI • PostgreSQL</p>
  <ul>
    <li>Designed and implemented a PostgreSQL database schema to store user ingredients and expiration dates</li>
    <li>Connected the database to FastAPI, enabling CRUD operations for ingredient management</li>
    <li>Deployed full-stack app on Render with PostgreSQL database</li>
  </ul>
  <div class="project-buttons">
    <a href="https://www.wastenotkitchen.com/" target="_blank" rel="noopener noreferrer" class="btn">View App</a>
    <a href="https://github.com/kimmiwong/wastenot" target="_blank" rel="noopener noreferrer" class="btn">View Code</a>
  </div>
</div>

<div class="project-card">
  <a href="{{ '/assets/img/expense-tracker.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
    <img src="{{ '/assets/img/expense-tracker.png' | relative_url }}" alt="Expense Tracker Lite screenshot" width="100%">
  </a>
  <h2>Expense Tracker Lite</h2>
  <p>Personal finance app that automatically categorizes expenses using the OpenAI API. Users can log transactions, view spending categories, and track budgets. Built with React, FastAPI, and PostgreSQL</p>
  <p><strong>Stack:</strong> React • FastAPI • PostgreSQL</p>
  <ul>
    <li>Implemented auto-categorization of expenses using the OpenAI API</li>
    <li>Set up PostgreSQL database to store user transactions and categories</li>
    <li>Wrote backend logic for persisting data and supporting expense tracking functionality</li>
  </ul>
  <div class="project-buttons">
    <a href="https://github.com/jkwan14/expense-tracker-lite" target="_blank" rel="noopener noreferrer" class="btn">View Code</a>
  </div>
</div>

<div class="project-card">
  <a href="{{ '/assets/img/pokemon-explorer.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
    <img src="{{ '/assets/img/pokemon-explorer.png' | relative_url }}" alt="Pokémon Explorer screenshot" width="100%">
  </a>
  <h2>Pokémon Explorer</h2>
  <p>React learning project that showcases dynamic routing and data fetching from the PokéAPI. Features multi-page navigation and interactive displays for exploring Pokémon data</p>
  <p><strong>Stack:</strong> React • React Router • PokeAPI</p>
  <ul>
    <li>Implemented multi-page navigation using React Router</li>
    <li>Fetched and displayed data dynamically from the PokeAPI</li>
    <li>Practice project to strengthen React fundamentals</li>
  </ul>
  <div class="project-buttons">
    <a href="https://github.com/jkwan14/pokemon-explorer" target="_blank" rel="noopener noreferrer" class="btn">View Code</a>
  </div>
</div>

</div>

---

## Practice Projects

These smaller apps helped me strengthen core full-stack skills:

<div class="projects-grid">

<div class="project-card">
  <a href="{{ '/assets/img/movie-review.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
    <img src="{{ '/assets/img/movie-review.png' | relative_url }}" alt="Movie Review App screenshot" width="100%">
  </a>
  <h2>Movie Review App</h2>
  <p>A web app where users can browse, add, and review movies</p>
  <p><strong>Stack:</strong> FastAPI • SQLAlchemy • Vanilla JS</p>
  <ul>
    <li>Built custom backend API for movies and reviews</li>
    <li>Implemented relational models (movies ↔ reviews)</li>
    <li>Interactive frontend with vanilla JavaScript</li>
  </ul>
  <div class="project-buttons">
    <a href="https://github.com/jkwan14/movie-reviews" target="_blank" rel="noopener noreferrer" class="btn">View Code</a>
  </div>
</div>

<div class="project-card">
  <a href="{{ '/assets/img/blog-app.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
    <img src="{{ '/assets/img/blog-app.png' | relative_url }}" alt="Blog App screenshot" width="100%">
  </a>
  <h2>Blog App</h2>
<p>A full-stack blogging platform with CRUD posts and comments</p>
<p><strong>Stack:</strong> FastAPI • SQLAlchemy • PostgreSQL</p>
<ul>
  <li>Built FastAPI backend with SQLAlchemy ORM and PostgreSQL database</li>
  <li>Implemented CRUD functionality for posts and comments</li>
  <li>Designed database schema to handle user posts and related comments</li>
</ul>

  <div class="project-buttons">
    <a href="https://github.com/jkwan14/blog-app" target="_blank" rel="noopener noreferrer" class="btn">View Code</a>
  </div>
</div>

</div>
