---
layout: single
title: "Cybersecurity"
permalink: /cybersecurity/
author_profile: true
---

{% include base_path %}

# Cybersecurity Projects & Research

This section showcases my work in cybersecurity, including security research, implementations, and analysis.

## Featured Projects

### [Security Project 1]
**Focus Areas**: Vulnerability Assessment, Penetration Testing, Security Automation

Brief description of the project, security challenges addressed, and your contributions.

- Key security findings or improvements
- Tools and methodologies used
- Impact on security posture
- [Link to repository if applicable (sanitized)]

---

### [Security Project 2]
**Focus Areas**: Incident Response, Threat Intelligence, Security Monitoring

Brief description of the project, security challenges addressed, and your contributions.

- Key security findings or improvements
- Tools and methodologies used
- Impact on security posture
- [Link to repository if applicable (sanitized)]

---

## Security Research & Blog Posts

{% assign posts = site.posts | where: "categories", "Cybersecurity" %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

---

*Also explore my [IT Infrastructure & SRE projects](/portfolio/it-infrastructure/).*