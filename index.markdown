---
title: About Me
layout: single
author_profile: true
---

Hi, I’m **Alberto Perches** — a Computer Science student at **Loyola University Maryland**, graduating in **May 2026**.

I’m interested in **full-stack development, systems programming, and security-adjacent work**, and I like building things that are both technically solid and actually usable by people.

## What I do

I’ve worked across a pretty wide stack:

- **Languages:** Python, Java, C/C++, Bash, JavaScript, Ruby, x86 Assembly  
- **Frameworks:** Ruby on Rails, React, Vite  
- **Data & ML:** NumPy, Pandas, scikit-learn, PyTorch  
- **Tools:** Linux, Git, Docker, GitHub Actions, Redis, SQLite, SSH

I’m especially comfortable working in **Linux environments**, collaborating through Git, and writing code that other people on a team can understand and maintain.

## How I work

I care a lot about **process**, not just code.

- I’ve led projects using **Agile workflows**
- I enforce **pull requests, code reviews, and branch protection**
- I automate testing with **GitHub Actions**
- I write documentation because future-me (and teammates) deserve it

I’ve also competed in **collegiate cybersecurity CTFs**, where I’ve worked on challenges involving cryptography, reverse engineering, OSINT, and web exploitation.

## Outside the code

On campus, I’ve been involved in:
- **Drone Club**
- **Cybersecurity Club**
- **Student Life leadership** as a Summer Resident Assistant

I’ve worked in high-responsibility roles like **lifeguarding** and **fitness center operations**, which taught me how to stay calm, communicate clearly, and handle real-world responsibility — skills that transfer surprisingly well to engineering teams.

## Links

- 📄 [Résumé](/assets/resume.pdf)
- 💻 [GitHub](https://github.com/SREEMT)
- 🔗 [LinkedIn](https://linkedin.com/in/alberto-perches)

If you’re interested in my work, check out my projects — especially the **Soccer League Management App**, which I’m particularly proud of.


## Latest Posts

{% assign latest_posts = site.posts | slice: 0, 3 %}
{% for post in latest_posts %}
### [{{ post.title }}]({{ post.url }})
{{ post.excerpt | strip_html | truncate: 140 }}
{% endfor %}
---
