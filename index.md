---
layout: default
---

<div style="max-width: 700px; margin: 4rem auto; text-align: center;">

  <h1>B’s Bathroom Blog</h1>

  <p style="font-size: 1.2rem; margin-top: 1.5rem;">
    A public journal reviewing bathrooms across  
    <strong>Florida Atlantic University’s campus</strong>.
  </p>

  <p style="color: #555; margin-top: 1rem;">
    Entries focus on what a good bathroom experience should be. Plus some of my day's rambelings
  </p>

</div>

<hr style="max-width: 700px; margin: 3rem auto;">

<div style="max-width: 700px; margin: 0 auto;">

  <h2>Recent Reviews</h2>

  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span style="color:#777;"> — {{ post.date | date: "%B %d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>

</div>


