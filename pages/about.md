---
title: Acerca de
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cgrillo98.github.io/collectionbuilder-gh/objects/gif2.gif" %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## Sobre esta colección
Este es el resultado del ejercicio de digitalizar, coleccionar y reinterpretar artefactos y materiales pre-digitales almacenados en la Biblioteca Alfonso Borrero Cabal. Este proyecto hace parte de los ejercicios realizados por estudiantes del curso Cultura Digital de la Línea de Humanidades Digitales en la Pontificia Universidad Javeriana en Bogotá.


## Contenidos

Timelinejs –> 
{% include feature/timelinejs.html %}

Línea de tiempo 2

## Título

Descripción del proyecto. This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

Example Code –> 
{% include feature/image.html objectid="demo_001" width="75" %}

Example Code –> 
{% include feature/image.html objectid="demo_001" width="75" caption="an image" %}

Example Code –> 
{% include feature/image.html objectid="demo_001;demo_004;demo_005" %}

Example Code –> 
{% include feature/image.html objectid="demo_001;demo_004" width="75" caption="demo1;nother" %}

Example Code –> 
{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg" width="75" alt="Frank B. Robinson at the Organ" %}

Example Code –> 
{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg" width="75" alt="Frank B. Robinson at the Organ" caption="This guy is good!"%}

Example Code –> 
{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg;https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_psychiana_photographs_010.jpg" caption="this guy!;(was nothing without these women!)" link="https://www.lib.uidaho.edu/digital/psychiana/items/psychiana519.html;https://www.lib.uidaho.edu/digital/psychiana/items/psychiana547.html" alt="Frank B. Robinson at the Organ;Women staff members of Psychiana lined up outside the Psychiana headquarters" %}

Cloud –> 
{% include feature/cloud.html fields="subject" min="1" background="dark" button="outline-warning" %}



Card – > 
{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo002" width="25" centered=true %}
{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo002" width="25" centered=true %}
{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo002" width="25" centered=true %}


Alerts – > 
{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}

Modals – > 
{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary" %}

Fin


<!-- LOS EJEMPLOS DE CÓDIGO LOS SAQUÉ DE ACÁ: https://collectionbuilder.github.io/collectionbuilder-gh/feature_options.html  -->

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
