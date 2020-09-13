---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Contacto
**Importante**
Este es el único canal oficial de comunicación para el curso. Utiliza la siguiente informacion de contacto para cualquier comunicacion relacioanda al curso. 
Para agendar una reunión es necesario contar con el acceso institucional a Teams de Microsoft. Utiliza Ctrl- mientras presionas el boton para abrir la página en una nueva ventana.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

