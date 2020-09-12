---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

: Importante

Utiliza la siguiente informacion de contacto para cualquier comunicacion sobre el curso. 
# Contacto

Utiliza la siguiente informacion de contacto para cualquier comunicacion sobre el curso. Para agendar una reunion es necesario tener acceso institucional a Teams de Microsoft.Para agendar una reunion es necesario tener acceso institucional a Teams de Microsoft.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

