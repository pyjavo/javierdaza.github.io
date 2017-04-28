---
title: "Tips para migrar tu aplicación de Django 1.5 a 1.11"
date:  2017-04-27 17:05:36
image: migrando_django_1.5_a_1.11.jpg
---

En este artículo subiré las diapositivas de mi [última charla en Python Barranquilla](https://www.meetup.com/pythonbaq/events/239118352/) donde hablé sobre como migrar aplicaciones de Django.

Puntos adicionales a tener en cuenta:

- De vez en cuando te saldrán errores extraños....borra tus archivos .pyc

- Mi proyecto no trabajaba con modelos, pues era un proyecto de un blog. Sin embargo, te recomiendo tener TESTS para probar que tus apps funcionen después de la migración.

- La gente de [DSF](https://www.djangoproject.com/foundation/) te avisa con _warnings_, 2 versiones antes para que tengas tiempo de cambiar lo que quedará obsoleto


<iframe src="//slides.com/javidazac/migrando-de-django-1-5-a-1-11/embed" width="100%" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>