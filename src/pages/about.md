---
layout: layouts/page.njk
title: About Me
description: Learn more about me and this website
permalink: /about/
---

## 👋 Hey There!

Welcome to my little corner of the internet! I'm **{{ site.author.name }}**, and this is my personal website where I share my thoughts, projects, and whatever else strikes my fancy.

### 📫 Other webpages

Check out my other cool stuff. 

{% if site.social.Printables %}- **Printables:** [{{ site.social.Printables }}]({{ site.social.Printables }})
{% endif %}

### 🔗 Link to Me!

Want to add my site to your links page? Use this badge:

<div style="text-align: center; margin: 2rem 0;">
  <img src="{{ badges.myBadge.image }}" alt="{{ site.title }}" width="88" height="31" onerror="this.alt='Badge coming soon!'">
</div>

```html
{{ badges.myBadge.code }}
```

### 🤝 Credits & Inspiration

WIP

---

**"Make the web weird again!" 🌈✨💫**
