---
layout: post
title: "Application de Communication Intra-Entreprise"
date: 2010-03-19 00:00:00
enddate: 2011-03-01 00:00:00
categories: projects university
role: "Software/Architect"
excerpt: Pour une entreprise, créer une cohésion entre les collaborateurs, les services, les équipes n'est pas toujours chose aisée, spécialement à moyen et long terme.
         Nous nous sommes donc intéressés à cette problématique et avons essayé de résoudre celle-ci par l'intermédiaire d'une application de type « réseau communautaire » destinée au monde professionnel (TPE/PME).
tags: php javascript jquery
---


Projet Officiel IUT R&T2

N° de projet : 44
Nom du projet : Application de Communication Intra-Entreprise
Nom du tuteur : Frédéric POURRAZ
Réalisé par : Vincent CARTIER & Vincent HERLEMONT


<div class="row">
    <div class="s12 center-align">
        <img src="{{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise-projet.png">
    </div>
</div>

<ul id="slide-out" class="side-nav fixed">
   <li><a href="#ergonomie_et_arborescences">Ergonomie & Arborescences</a></li>
   <li><a href="#page_daccueil_et_connection">Page d'accueil & Connection</a></li>
   <li><a href="#gestion_des_utilisateurs">Gestion des utilisateurs</a></li>
   <li><a href="#administration_de_la_plate-forme">Administration de la plate-forme</a></li>
   <li><a href="#gestion_des_droits">Gestion des droits</a></li>
   <li><a href="#gestion_plugin">Gestion Plugin</a></li>
   <li><a href="#editeur_wysiwyg">Editeur wysiwyg</a></li>
</ul>

PRESENTATION DU PROJET

Pour une entreprise, créer une cohésion entre les collaborateurs, les services, les équipes n'est pas toujours chose aisée, spécialement à moyen et long terme.
Nous nous sommes donc intéressés à cette problématique et avons essayé de résoudre celle-ci par l'intermédiaire d'une application de type « réseau communautaire » destinée au monde professionnel (TPE/PME).

<div id="ergonomie_et_arborescences"></div>

### Ergonomie & Arborescences

L'interface :

Je l'ai entièrement pensée et programmée.
Conçue de façon à accueillir et pourvoir parcourir des arborescences illimitées de manière très simple et ludique.
![gestion_collaboration_entreprise_interface_all]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_interface_all.png)

Gestion arborescences :
![gestion_collaboration_entreprise_arbre]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_arbre.png)

Popu (html/javascript) qui permet l’authentification de connections.

<div id="page_daccueil_et_connection"></div>

### Page d'accueil & Connection

Message page d'accueil où l'utilisateur, dans notre cas anonyme, n'est pas connecté, n'est pas autorisé à visualiser la page.
![gestion_collaboration_entreprise_PA-1]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_PA-1.jpg)

Popu (html/javascript) qui permet l’authentification de connections.
![gestion_collaboration_entreprise_PA-2]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_PA-2.png)

Message d'erreur en cas d’échec de connections.
![gestion_collaboration_entreprise_PA-3]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_PA-3.png)

Voici l'interface de l'utilisateur une fois connecté.
![gestion_collaboration_entreprise_PA-4]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_PA-4.jpg)

<div id="gestion_des_utilisateurs"></div>

### Gestion des utilisateurs

( on utilise ici la gestion des plugins )
Ces plugins on été développés par Vincent Cartier mon binôme de projet.


Plugin : Formulaire d'ajout de collaborateurs.

![gestion_collaboration_entreprise_FGGU-1]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_FGGU-1.jpg)


Plugin : Listage des utilisateurs

![gestion_collaboration_entreprise_FGGU-2]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_FGGU-2.jpg)

Plugin : Gestion des services

![gestion_collaboration_entreprise_FGGU-3]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_FGGU-3.jpg)

Plugin : gestion des groupes

![gestion_collaboration_entreprise_FGGU-4]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_FGGU-4.jpg)

<div id="administration_de_la_plate-forme"></div>

### Administration de la plate-forme

Cette partie permet de gérer l'arborescence du site en fonction des droits de l'utilisateur.

Voici l'ajout d'une page à celle courante :
![gestion_collaboration_entreprise_AP-1]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_AP-1.jpg)


<div id="gestion_des_droits"></div>

### Gestion des droits

La gestion des droits par groupe d'utilisateurs de n'importe quels plugin ou page à été très difficile à réaliser.

Voici la gestion des droits sur une page :
![gestion_collaboration_entreprise_GD-1]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_GD-1.png)

Explication des gestions d’exception des droits :
![gestion_collaboration_entreprise_GD-2]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_GD-2.png)

<div id="gestion_plugin"></div>

### Gestion Plugin

J'ai mis en place un "protocole" qui permet de créer des plugins très simplement.
Mon binôme les a utilisés à plusieurs reprises pour réaliser les gestions utilisateur, service, groupes de l'entreprise.

Un dossier dans l'arborescence du logiciel est prévue pour faire glisser les dossiers contenant le plugin en question.
Le  plugin n'a pas besoin d'installation ; il est immédiatement disponible dans l'interface d'ajout de plugin.


Voici l'interface en 3 parties :
Un formulaire d'ajout du module en haut.
Une représentation succincte des modules ; on peut modifier l’ordre avec un simple glissement de la  souris.
Représentation réelle des plugins.
![gestion_collaboration_entreprise_ERP-1]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_ERP-1.jpg)


Listing des différents modules classés en thèmes :
![gestion_collaboration_entreprise_ERP-2]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_ERP-2.jpg)

<div id="editeur_wysiwyg"></div>

### Editeur wysiwyg

(http://fr.wikipedia.org/wiki/What_you_see_is_what_you_get)

Voici un éditeur wysiwyg totalement de ma conception en javascript avec possibilité de reporting instantané ( exemple google doc ).

Voici un texte simple :
![gestion_collaboration_entreprise_E-1]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_E-1.jpg)
![gestion_collaboration_entreprise_E-2]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_E-2.jpg)
![gestion_collaboration_entreprise_E-3]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_E-3.jpg)

Incorporation d'images + soulignement en caractère gras.

![gestion_collaboration_entreprise_E-4]({{ site.baseurl }}/img/pages/projects/gestion_collaboration_entreprise_E-4.jpg)
