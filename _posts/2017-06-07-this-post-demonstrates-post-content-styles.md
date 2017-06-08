---
layout: post
title: "Mise en forme Markdown - Kramdown"
categories: jekyll
author: "Pierre K."
meta: "e-TAC"
---
**Table des matières** (créée automatiquement)
* TOC
{:toc}

Voyez le [fichier source](https://gist.github.com/marathon67/fbd4f10ad866aff837d36d88c85fcf5c){: target='_blank'} de ce billet pour découvrir les notations **Markdown** permettant d'obtenir le *résultat affiché*. Consultez aussi le document [Kramdown Quick reference](https://kramdown.gettalong.org/quickref.html){: target='_blank'}.  
Et vous pourrez également vous référer à la notice du [thème par défaut de Jekyll](https://github.com/jekyll/minima){: target='_blank'}, employé ici : **Minima**.
**N. B.** il est également possible d'intégrer directement du code HTML dans les pages. 

## Mise en forme élémentaire

**Attention** : Markdown est un langage où des conventions de positionnement et indentation sont prises en compte. Vérifiez toujours que vos textes et commandes sont correctement alignés.

Pour créer un paragraphe, appuyez sur `Entrée` deux fois.  
Pour créer un saut de ligne, vous devez laisser deux espaces à la fin de la ligne précédente.

En entourant un mot ou expression d'une étoile vous *le mettez en italique*  
En entourant un mot ou expression de deux étoiles vous **le mettez en italique**
  
----
Quatre petits traits, seuls sur leur ligne, produiront une ligne de séparation (hr).

## Des titres pour structurer le texte : niveau 2

Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu.
Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

### Un autre de niveau 3

Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum.

#### Et enfin de niveau 4

Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

## Des mises en forme pour des paragraphes

**Voici une citation :**
> In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum.

**Un bloc de code :**
```
<html>
  <head>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
```

**Des notes de bas de page :**

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris[^morice] lobortis nulla et felis ullamcorper bibendum[^bib]. Phasellus et hendrerit mauris.

[^bib]: Non, ce n'est pas du placement de produit pour les pneus Michelin !

[^morice]: Rien à voir avec mon cousin Maurice !

**Et des abréviations :**

Ce texte n'est pas écrit en HTML mais dans un autre language !

*[autre language]: C'est du Markdown

*[HTML]: HyperText Markup Language

## Trois types de listes

### Une liste non ordonnée (liste à puces)

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

- First item, yo
- Second item, dawg
- Third item, what what?!
- Fourth item, fo sheezy my neezy

### Une liste ordonnée (liste numérotée)

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

1. First item, yo
2. Second item, dawg
3. Third item, what what?!
4. Fourth item, fo sheezy my neezy

### Et une liste de définitions

Prune
:   Fruit à noyau, à chair comestible sucrée et juteuse. Elle est produite par certaines espèces d'arbres du genre *Prunus*.
:   Amende, contravention (argotique).

Orange
:   L’orange est un agrume, fruit des orangers, des arbres de différentes espèces de la famille des Rutacées ou d'hybrides de ceux-ci.

## Inclure des médias

### Images

Les images sont déposées ici dans le dossier `\assets\images`. Pensez à laisser **deux espaces** après la photo pour que la légende passe bien à la ligne !

![Un caloptéryx mâle]({{site.url}}/assets/images/demoiselle.jpg){:height="600px" width="600px"}  
<i class="fa fa-camera-retro" aria-hidden="true"></i> Calopteryx mâle - Photo P. Kessler - juin 2017
{: .legende}

Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.
Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc.

### Vidéos Youtube

**Rien de plus simple** : copiez directement dans la page le code d'inclusion donné sur Youtube ! 

<iframe width="560" height="315" src="https://www.youtube.com/embed/t3yEhIAOeg8?ecver=1" frameborder="0" allowfullscreen></iframe>


### Et fichiers .pdf

<i class="fa fa-file-pdf-o" aria-hidden="true"></i> Téléchargez le [Guide du média lycéen]({{site.url}}/assets/guide_lyceen.pdf).

**P.S.** Pour voir la liste des icônes disponibles, consultez la page [FontAwesome](http://fontawesome.io/cheatsheet/){: target="_blank"}.

## Pour finir, un tableau


|-----------------+------------+-----------------+----------------|
| Default aligned |Left aligned| Center aligned  | Right aligned  |
|-----------------|:-----------|:---------------:|---------------:|
| First body part |Second cell | Third cell      | fourth cell    |
| Second line     |foo         | **strong**      | baz            |
| Third line      |quux        | baz             | bar            |
|-----------------+------------+-----------------+----------------|
| Second body     |            |                 |                |
| 2 line          |            |                 |                |
|=================+============+=================+================|
| Footer row      |            |                 |                |
|-----------------+------------+-----------------+----------------|
