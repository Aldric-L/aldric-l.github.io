---
title: "Mathematics: Multivariate Analysis and topology (L2)"
date: 2025-01-01
lastmod: 2025-01-01
aliases: 
#    - /courses/microL1S2/graph.png
tags: ["Undergraduate courses (Mathematics)"]
author: "Aldric Labarthe"
description: "Undergraduate course on multivariate real analysis (in $R^n$) with some extensions on optimization theory and topology. The course is given in French at Université Panthéon-Sorbonne." 
summary: "Undergraduate course on multivariate real analysis (in $R^n$) with some extensions on optimization theory and topology. The course is given in French at Université Panthéon-Sorbonne." 
cover:
    image: "2.3.png"
    alt: "Des normes !"
    relative: false
showToc: true
disableAnchoredHeadings: false
---

## Introduction

Ce cours de L2 a pour objectif de proposer une extension des notions d'analyse, enseignées en première année, dans le cas multivarié. Le cours est constitué d'une remise à niveau sur les principaux théorèmes, d'une introduction à la topologie de $R^n$ (et des espaces métriques), d'une partie sur la différentiation et d'une introduction à l'optimisation de problèmes non-contraints. 

Le cours est constitué de 12 séances de TD de 2h30, qui donnent lieu à 4 évaluations de contrôle continu.

## Documents

##### Supports

+ [TD1-2](RappelsAnalyseTD1-2.pdf) – Rappels de cours sur les coordonnées polaires et la topologie dans $R^n$.
+ [TD3-4](RappelsAnalyseTD3-4.pdf) – Rappels de cours sur les limites et la continuité.
+ [TD5-6](RappelsAnalyseTD5-6.pdf) – Rappels de cours sur la dérivabilité et la différentiabilité.
+ [TD7](RappelsAnalyseTD7.pdf) – Rappels de cours sur les dérivées secondes et l'optimisation.

##### Corrigés et approfondissements


+ [Exercices 2024](CorrectionsAnalyseSupp.pdf) – Quelques exercices (souvent plus difficiles) de l'année dernière dont je propose un corrigé.


##### Contrôles continus

<!--+ [Lecture note 1](lecture1.pdf)-->

## Compléments

##### Courbes de niveau d'une fonction à plusieurs variables

La notion de courbe de niveau est souvent considérée comme abstraite par les étudiants alors que, pour la plupart d'entre-eux, ils ont déjà croisé cette notion lors de l'enseignement de microéconomie. On montre donc ici que les courbes d'indifférence sont en réalité les courbes de niveau de la fonction d'utilité (on présente ici une Cobb-Douglas d'équation $U(x, y) = x^{\frac{1}{2}}y^{\frac{1}{2}}$). 


{{< iframe src="indifference_curve_plot.html" width="100%" height="700" >}}


##### Dérivabilité n'est pas différentiabilité


Le TD 5 invite à ne pas confondre différentiabilité et dérivabilité : une fonction peut admettre des dérivées partielles en un point, mais ne pas être différentiable en ce même point. Voici ici un exemple en $(0,0)$ pour $f(x, y) = (x^{11} + y^{11})^{1/11}$.

$\left.\frac{\partial f}{\partial x} \right\vert_{(0,0)} = \lim_{h\to0} \frac{f(h, 0) - f(0, 0)}{h} = 1 = \lim_{h\to0} \frac{f(0, h) - f(0, 0)}{h} = \left.\frac{\partial f}{\partial y} \right\vert_{(0,0)}$

{{< iframe src="non-diff-but-der2.html" width="100%" height="700" >}}

## Références


> Elementary Analysis, Kenneth Roth (2013, Second Edition, Springer)


