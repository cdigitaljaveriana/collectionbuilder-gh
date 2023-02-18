---
title: Acerca de
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## Sobre esta colección
Descripción del proyecto. This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

## Contenidos

INCLUDE AN IMAGE
Image –> {% include feature/image.html objectid="demo_001" width="75" %}

INCLUDE A PDF
PDF – > {% include feature/pdf.html objectid="demo_002" width="50" %}

INCLUDE A VIDEO
Video: {% include feature/video.html objectid="demo_004" %}

INCLUDE AN AUDIO FILE
Audio: {% include feature/audio.html objectid="demo_003" %}

INCLUDE BOOTSTRAP FEATURES
The template also provides includes to make it easier to add Bootstrap components to your Markdown writing. These features allow you to better organize and highlight your content.

INCLUDE A CARD
Card – > {% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo004" width="25" centered=true %}

INCLUDE A BUTTON
Buttons – > {% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}

INCLUDE AN ALERT
Alerts – > {% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}

INCLUDE A MODAL
Modals – > {% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary" %}


Fin

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
