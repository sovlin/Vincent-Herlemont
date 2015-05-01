---
layout: post
title: "Analysis performances and testing"
date: 2013-05-20 00:00:00
enddate: 2013-08-30 00:00:00
time: "3 mouths"
categories: professional_experience stage
role: "Developer/Analyst"
includeExcerpt: true
company: Imagina-international
excerpt: 
    "<i class=\"mdi-action-alarm-on\"></i> Test platform,
     analysis performances and automatic deployment Compare solutions and documents."
tags: java angularjs nodejs casperjs sahi yourkit
---

Imagina international : Entreprise spécialisée dans l'édition d'un ERP (ATEN).

### Analyse performance

**Problématique :**

Tracer l’utilisation mémoire, tracer l’utilisation CPU. Temps d’exécution des méthodes. Compter le nombre d’invocations par méthode ainsi que leur temps d’exécution. 
Définir des cas d'utilisation pour les développeurs.
Définir les bonnes façons de coder / exemple : optimisation de code, comprendre les allocations mémoire  etc ...

**Outils testés et documentés :**

- Jmeter
- Visual VM+Jconsole
- Jprofiler
- Yourkit.

**Mise en production :**

- Yourkit.

### Plateforme de test

**Problématique Test Fonctionnel**
  
Pouvoir créer des scénarios rapidement ; si assistés, c'est un plus. Les scénarios doivent se diviser en blocs d’actions et ainsi permettre de reconstituer de nouveaux scénarios grâce à ces blocs. 
Exemple de bloc :  Connexion, Créer une fiche client, Rechercher une fiche client etc … 
La solution doit également proposer un rapport détaillé de fin de test.
  
**Problématique Test Performance**
  
La solution de test choisie doit pouvoir déclencher en parallèle le même scénario avec des jeux de données différents (ou non). 
Possibilité de décaler le lancement des scénarios permettant de simuler des cas d’utilisation réelle. Mesure globale des actions.
  
**Outils testés et documentés ( R&D ) :**
 
- SoapUI
- Casperjs 
- Sahi
 
**Outil de mise en production :**

- Sahi
  

### Outil de déploiement

Cet outil a été créé entièrement en nodeJS avec le soutien des librairies expressjs et socket.io.
L'interface utilisateur a été créée en utilisant la librairie angularjs. Le design a bénéficié de l'aide de la librairie pure css.
  
**Fonctionnalités :**

- Affichage de l'état (allumé / éteint) des instances
- Affichage de l'état (allumé / éteint) des serveurs
- Mise à jour de déploiement de l'instance 
- Affichage en temps réel des traces de debug données par les taches ant
- Verrouillage d'une instance
- Possibilité d'indiquer le nom de la personne travaillant sur l'instance
- L'utilisateur peut indiquer le temps durant lequel l'instance est verrouillée.
- Ce temps décrémentera jusqu’à déverrouillage de l'instance.
- Téléchargement de l'instance compilée.
- Accès interne / externe de l'instance.
- Upload fichier HTML5
- Consultation des fichiers
- Téléchargement des fichiers
- Suppression des fichiers

![deploiment]({{ site.baseurl }}/img/pages/professional_experience/imagina-international-stage-outil_deploiment.jpg)
