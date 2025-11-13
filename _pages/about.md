---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I'm a behavioural scientist focused on turning the "intangible" into something we can name, understand, measure and improve. My PhD examines how cognitive biases in cancer multidisciplinary teams contribute to unwarranted variation in patient outcomes; basically, why similar patients sometimes get different treatment recommendations and have better or worse outcomes that can't be explained by clinical factors.

I'm a methodological pragmatist, i.e., less interested in disciplinary purism, and more invested in assembling the right approach for the problem at hand. I'll use whatever is needed: cognitive ethnography to investigate teamwork in action, social network analysis to map clinician interactions, or AI-voice cloning to design experimental stimuli. I’m always on the lookout for new methods and techniques to get into the nooks and crannies of human behaviour. The through-line in my work is making invisible behavioural patterns visible and actionable.

Humans are the best part of my work, as participants, collaborators or colleagues. And I’m always up for meeting and working with more of them in all their glorious variety.

<hr />

{% include base_path %}

Outside the Lab
===============
My simple pleasures include coming up with article titles heavy on wordplay, walking on crunchy leaves in the autumn and typing with a fresh set of nails. I like thinking about thinking, interdisciplinary knowledge production and creative information visualisation. I have a profound love for cats. But my greatest pleasure lies in reading and collecting well-conceived and beautifully-worded ideas.

<hr />

Research Interests
===============
<ul class="research-interests" style="list-style: none; padding-left: 0;">
  <li>🧠 Expertise, bias, and clinical decision-making</li>
  <li>👥 Team interaction and communication dynamics</li>
  <li>🕸️ Distributed cognition in high-stakes settings</li>
  <li>⚕️ Patient safety and healthcare equity</li>
  <li>📊 Mixed-methods research</li>
</ul>

<hr />

Publications
=======
<ul>
  {% for post in site.publications reversed %}
    {% include publications-layout.html %}
  {% endfor %}
</ul>

<hr />

<h1 id="talks">Talks, Panels and Presentations</h1>
<p align="center" style="max-width: 95%; margin: 0 auto;">
  <img src="images/talks.jpg" alt="Talks, Panels and Presentations">
</p>
<ul class="fa-ul">
  {% for post in site.talks reversed %}
    {% include talks-layout.html %}
  {% endfor %}
</ul>

<hr />

Education
=======
<ul class="fa-ul">
  {% for post in site.education reversed %}
    {% include education-layout.html %}
  {% endfor %}
</ul>

<hr />

Volunteering
=======
<ul>
  {% for post in site.volunteering reversed %}
    {% include volunteering-layout.html %}
  {% endfor %}
</ul>

<hr />
