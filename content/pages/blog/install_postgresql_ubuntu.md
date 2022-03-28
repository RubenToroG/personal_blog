---
title: Instalación de PostgreSQL en Ubuntu - Linux
excerpt: >-
  Bienvenidos a mi blog, aquí inicia mi vida de desarrollador
date: '2022-03-28'
thumb_image: images/6_thumb.jpg
thumb_image_alt: A handheld game console on a yellow background
image: images/6.jpg
image_alt: A handheld game console on a yellow background
seo:
  title: Mi primer blog
  description: Iniciando mi primer blog en mi nueva vida de desarrollador de software
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: What are some of the best designed video games
      keyName: property
    - name: 'og:description'
      value: Diam sit amet nisl suscipit adipiscing bibendum est ultricies integer
      keyName: property
    - name: 'og:image'
      value: images/6.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: What are some of the best designed video games
    - name: 'twitter:description'
      value: Diam sit amet nisl suscipit adipiscing bibendum est ultricies integer
    - name: 'twitter:image'
      value: images/6.jpg
      relativeUrl: true
layout: post
---

Hola mundo, bienvenidos a mi nuevo blog


Intalación de postgresql en Linux – Ubuntu

sudo apt-get install postgresql postgresql-contrib

sudo -u postgres psql

inicia postgresql en consola, con usuario por defecto postgres

asignar clave a usuario

postgres=# alter user postgres with password ‘nuevopass’;
\q para salir

sudo apt-get install pgadmin3

https://noviello.it/es/como-instalar-pgadmin4-en-ubuntu-20-04-lts/

> The beauty of type lies in its utility, prettiness without readability serves neither author nor reader. - James Felici

![Modern white table](/images/10.jpg)