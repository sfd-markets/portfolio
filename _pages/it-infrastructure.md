---
layout: default
title: "IT Infrastructure & SRE"
permalink: /it-infrastructure/
author_profile: true
---

{% include base_path %}

# IT Infrastructure & SRE Projects

This section showcases my work in Site Reliability Engineering, cloud infrastructure, and DevOps practices.

## Featured Projects

### [Project Name 1]
**Technologies**: Kubernetes, Docker, Terraform, AWS/GCP/Azure

Brief description of the project, what problems it solved, and your role.

- Key achievement or technical highlight
- Impact or results
- [Link to repository or demo if available]

---

### [Project Name 2]
**Technologies**: CI/CD, Monitoring, Infrastructure as Code

Brief description of the project, what problems it solved, and your role.

- Key achievement or technical highlight
- Impact or results
- [Link to repository or demo if available]

---

## Blog Posts & Technical Writing

{% assign posts = site.posts | where: "categories", "Cloud-Native" %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

---

*Interested in my cybersecurity work? Check out my [Cybersecurity projects](/portfolio/cybersecurity/).*
