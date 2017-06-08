---
title: Utiliser Jekyll-admin
layout: post
categories: jekyll
author: "Pierre K."
meta: "e-TAC"
---
**Jekyll-admin** est un fichier *.gem* qui vous permettra de publier sous Jekyll à la façon d'un CMS, si vous êtes allergique au codage sous **Atom**. Personnellement, je préfère en rester à une méthode plus directe.

Commentez (ou décommentez) la ligne `gem "jekyll-admin"` dans le fichier `Gemfile` pour inhiber / utiliser cette extension. Quand elle est en service, il faut explorer `localhost:4000/admin` pour voir l'interface auteur.

![Jekyll-admin - capture d'écran]({{site.url}}/assets/images/jekyll_admin.jpg){: height="470px" width="600px"}  
<i class="fa fa-camera-retro" aria-hidden="true"></i> Jekyll Admin - Édition d'un article
{: .legende}
*[CMS]: Content Management System : logiciel permettant de gérer les contenus d'un site
