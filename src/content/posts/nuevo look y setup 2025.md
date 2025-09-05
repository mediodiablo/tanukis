---
title: 'nuevo look y setup de cojudeces.com: static site (agosto 2025)'
description: 'hoy, con un poquito de dedicación, podemos relanzar cojudeces.com sin necesidad de apoyarnos en un content management system'
published: 2025-08-14
updateDate:
tags: ['web', 'blogging', 'updates', 'gear-and-tech']
url:
type: post
site: cojudeces.com
status: published
---

qué tal internet! Después de nuestro fallido intento del año pasado, nos ha vuelto a picar el bichito de las páginas web estáticas.

## nuevo espíritu: web estática

Está vez sí lo hemos logrado. El setup es el mismo que utilizamos en el primer intento:

1. escribir artículos en markdown en nuestra laptop
2. subir los artículos a un repositorio en Github
3. conectar Github con Netlify y publicar desde ahí

Lo que siempre hemos querido es controlar nuestro contenido y nuestro diseño. Desde siempre. Pero nunca nos dimos el tiempo de aprender a desarrollar páginas web. Dudamos de nuestra capacidad a pesar de (o por motivo de) ser egresados de la facultad de ingeniería de sistemas de la U de Lima.

Hoy, con un poquito de dedicación, podemos relanzar cojudeces.com sin necesidad de apoyarnos en un content management system (e.g., Wordpress, Ghost, Squarespace).

A partir de este momento, entonces, somos libres, seámoslo siempre, y the world is ours.

Qué podría salir mal?

![the world is yours](../../assets/2025-08-scarface-final-scene.jpeg 'pobre tony montana')

## cojudeces irrelevantes para nerds

### tema

Feliz y finalmente encontramos un tema que nos gustó por su simpleza (además es gratis): [MultiTerm](https://astro.build/themes/details/multiterm/), creado por [Stel Clementine](https://github.com/stelcodes) y modificado a punta de martillazos por [Johnny Pacheco](https://github.com/mediodiablo).

MultiTerm nos da lo básico: un landing page, un about page, una sección de posts por tags, una página de archivo, y un link para RSS readers.

Nosotros añadimos una sección del blog en sí, y simplificamos el archivo (renombrado arch.chivo). Con estas pequeñas modificaciones, ya podemos publicar cojudeces.com así como la vemos en agosto del 2025.

![2025-08 cojudeces.com snapshot](../../assets/2025-08-cojudeces-snapshot.png 'así relanzamos en agosto del 2025')

El plan es ir, de a pocos, añadiendo nuevas secciones, agrupando otras, manteniendo siempre una estética simple y (ojalá) de buen gusto.

### herramienta y workflow

#### visual studio code

Nuestros martillazos salieron de Visual Studio Code. Durante una semana, en esos 60 minutos de calma que a veces encontramos cuando todos en casa se quedan dormidos, logramos descifrar marginalmente el código de Multiterm. Un poco de HTML y CSS, y otro poco de JS.

#### markdown y obsidian

El contenido de las páginas y de los posts están escritos en markdown utilizando Obsidian como nuestro cuaderno de notas.

Una vez que terminamos de escribir un post, copiamos el archivo (e.g., post.mkd) al folder que contiene el código y contenido de cojudeces en nuestra laptop (e.g., ~/developer/websites/cojudeces/)

#### git

Dejamos que Git se encargue de mantener el orden con los cambios a la página y los nuevos posts. Hacemos el push desde VS Code hacia Github.
