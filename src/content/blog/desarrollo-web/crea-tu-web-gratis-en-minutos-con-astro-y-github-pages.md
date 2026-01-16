---
title: Tu web gratis en minutos con Astro y Github
link: tu-web-gratis-en-minutos-con-astro-y-github
catalog: true
date: 2026-01-16 07:00:00
tags:
  - Astro
  - Github
categories:
  - Desarrollo web
---

Hoy en día es necesario tener una página web para exponer y mostrar tus ideas al mundo, no obstante, puede que no puedas costearte los gastos que estas generan o directamente no tengas mucho tiempo para desarrollarla o mantenerla.

Por ello, hoy te presento una solución rápida y gratuita de tener tu propia página similar a la mía en cuestión de minutos gracias a Astro y Github Pages.

## Elección de plantilla
No vamos a partir desde cero, si no que vamos a elegir una plantilla base y comenzar nuestra web desde ella.

Para ello, navegamos hasta [la web de plantillas de Astro](https://astro.build/themes/1/?search=&price%5B%5D=free) y en los filtros seleccionamos las características que buscamos para nuestro sitio.

Una vez encontrada nuestra plantilla ideal, navegamos hasta su repositorio git y hacemos click en el botón "Usar esta plantilla", si no lo tiene, simplemente hacemos un fork.

En nombre de nuestro repositorio debe ser [nombre de usuario en github].github.io, esto nos ahorrará muchos pasos para poner en marcha nuestro sitio.

## Puesta en marcha
Ahora que ya tenemos nuestro repositorio listo, debemos poner nuestro sitio en marcha, ya que al ser un sitio estático, necesita ser compilado.

Por tanto, vamos a dejar que Github actions lo haga por nosotros en cada commit y así nosotros simplemente tendremos que encargarnos de trabajar sobre el sitio y su contenido.