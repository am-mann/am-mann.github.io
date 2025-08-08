---
layout: default
title: "Amy Mann"
permalink: /
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Amy Mann</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <main>
    <img src="assets/img/profile.jpeg" alt="Amy Mann" class="profile" />
    <h1>Amy Mann</h1>
    <p>
I am a [Rhodes Scholar](https://www.utoronto.ca/news/changemakers-u-t-students-awarded-prestigious-rhodes-scholarships) and a University of Toronto undergrad in mathematics and statistcs. I am currently advised by Prof. Monica Alexander in department at Statistical Sciences where I work on US mortality data quality. I previously working in Prof. Jude Kong's AIIM Lab and I was a Laidlaw Scholar advised by Professor Kent Moore, Summer Undegraduate Research Fellow advised by Prof. Debra Wunch. In the summer 2022-2023 I was a Field's Institue Summer Undergraduate Research Fellow where I worked on random walks on threshold graphs for Profs. Ada Chen, Sooyeong Kim, Jane Breen, and students Giovanni Tedesco, Andrei Parfeni, and Alexander. I was the President of the University of Toronto Mathematics Union, representing over 4,000 students enrolled in a math course and I started a community garden at Victoria College in the Annex neighbourhood. I occassionally write for various outlets including the Varsity, Toronto Star, and CBC. I love reading.
    </p>
    <ul>
      <li><a href="/cv.pdf">CV</a></li>
      <li><a href="mailto:amy.mann@mail.utoronto.ca">Email</a></li>
      <li><a href="https://github.com/am-mann">GitHub</a></li>
    </ul>
  </main>
</body>
</html>


## Recent Updates
 - I won a Rhodes Scholarship
 - The paper on co-authored on random walks on threshold graphs got published in Linear Algebra & Its Applications:
- I am trying to learn how to row if you have any advice
   
## Research Projects

<h1>Projects</h1>
<div class="projects-grid">
  {% assign items = site.projects | sort: 'year' | reverse %}
  {% for p in items %}
    <a class="project-card" href="{{ p.url | relative_url }}">
      {% if p.image %}
        <img src="{{ p.image | relative_url }}" alt="{{ p.title }}">
      {% endif %}
      <div class="text">
        <h2>{{ p.title }}</h2>
        {% if p.subtitle %}<p class="subtitle">{{ p.subtitle }}</p>{% endif %}
        <p class="meta">
          {% if p.venue %}{{ p.venue }} · {% endif %}{% if p.year %}{{ p.year }}{% endif %}
        </p>
        {% if p.tags %}
          <p class="tags">
            {% for t in p.tags %}<span class="tag">{{ t }}</span>{% endfor %}
          </p>
        {% endif %}
      </div>
    </a>
  {% endfor %}
</div>

<style>
.projects-grid {
  display:grid; grid-template-columns:repeat(auto-fill, minmax(280px, 1fr));
  gap: 16px; margin-top: 1rem;
}
.project-card {
  display:block; border:1px solid #e5e5e5; border-radius:8px; overflow:hidden;
  text-decoration:none; color:inherit; background:#fff;
  transition: transform .06s ease, box-shadow .06s ease;
}
.project-card:hover { transform: translateY(-2px); box-shadow:0 4px 14px rgba(0,0,0,.08); }
.project-card img { width:100%; height:160px; object-fit:cover; }
.project-card .text { padding:12px; }
.project-card .subtitle { color:#666; margin:.25rem 0 .5rem; }
.project-card .meta { color:#666; font-size:.9rem; }
.tags .tag { background:#f2f2f2; padding:0.15rem 0.4rem; border-radius:0.3rem; margin-right:6px; }
</style>

## Teaching

**MAT223: Linear Algebra I (Fall 2024)**  
Tutorials, grading, and support for upper-year statistics students.

**MAT244: Introduction to Ordinary Differential Equations (Spring 2025)**  
Office hours and assignment help for U of T undergrads.


## Misc

**Books I really love** 
- 2025: Eden's Outcasts, Say Nothing, We Don't Know Ourselves, America, América,
- 2024: Far From the Tree, Mountains beyond Mountains, Amusing Ourselves to Death, The Future is History, The Gnostic Gospels
- 2023: Prairie Fires, Empire of Pain

I enjoy reviewing books and I recently got a Goodreads account. If you ask me for a book recommendation, I will recommend Far From The Tree by Andrew Soloman.

I grew up in Winnipeg, Manitoba. Favourite pictures of the Canadian Prairies.
