# A propos du xLM

2 éléments de contexte relatifs au marché du PLM m'ont conduit récemment à reprendre la réflexion que j'avais initié sur "les invariants métiers du PLM" (https://www.linkedin.com/pulse/les-invariants-m%C3%A9tiers-du-plm-bernard-chabot/) ...   
... reflexion qui s'intéressait à ce qui est commun - en matière de PLM - entre les différentes industries. 

Ces éléments de contexte sont :
* La diversification des solutions de "Lifecycle Management" : PLM, SLM, AML, ...   
* La fréquente complexité des modèles applicatifs qui "motorisent" ces solutions

J'ai donc repris cette réflexion avec 2 objectifs :
* Expliquer d'où vient la généricité et comment émergent les invariant métiers (Ce qui est commun à TOUTES les industries)
* Traiter le sujet de la spécificité (Ce qui propre à CHAQUE industrie, voire à CHAQUE entreprise)

## Contexte : La diversification du marché
Le marché historique du PDM (Product Data Management) a évoluer à la fin des années 1990 vers le PLM (Product Lifecycle Management), puis il s'est progressivement "segmenté/diversifié",  ...   
... le "P" pouvant signifier non plus "Product" (c-à-d "Ce qui est fabriqué"), mais "Plant" (c-à-d "Ce qui sert à fabriquer"), mais aussi "Prestation" avec l'arrivé du SLM (Service Lifecycle Management) ou encore "Progiciel" avec l'AML (Application Lifecycle Mangement).   

On peut alors raisonnablement se demander pourquoi autant de solutions différentes pour finalement gérer le cycle de vie d'une chose, dont certe la "nature" est différente (produit manufacturé, usine, service, logiciel, ...) mais pour laquelle la problématique générale reste la même !
> D'autant plus que dans de nombreux cas ce qui doit être conçu, dévelopé et fabriqué est un fait un système consitué à la fois de produit, de logiciel et de service, il n'est donc pas forcement très commode d'avoir 3 applications différentes pour disposer d'une vue unifié d'un produit complexe !!!

En tout logique on devrait plutôt voir apparaitre des solutions de xLM, c'est à dire des solutions permettant de définir, designer, developer et produire une chose __quelque soit la nature de cette chose__ (Mais ce n'est pourtant pas ce qu'il se passe !)
  
  
## Contexte : La compléxité des modèles
J'ai souvent eu l'occasion de prendre connaissance des modèles applicatifs qui sous-tendent ce type de solution, et chaque fois j'ai été effaré de la complexité de ces modèles, ressemblant souvent à des "usine à gaz", mélangeant des concepts qui aurait du être proprement séparés, ou au contraire ne proposant pas de concept plus abstrait succeptible de traiter telle ou telle communalité ! 

## La problématique xLM
J'ai repris la réflexion en me demandant quels étaient tout les "critères élémentaires" qui permettaient de "positionner" une chose :   
* soit par rapport à la nature de cette <Chose> (i.e . son "Extension" / Facette "BE" : ce qu'elle EST),    
* soit par rapport à son cycle de vie (i.e. son "Intention" / Facette "DO" : ce qu'elle FAIT).   

J'ai identifié 12 de ces "critères élémentaires" (Mais il y en a peut-être d'autre ;-)
* 7 critères "intentionnels"
* 5 critères "extensionnels"

Remarque : chaque critère n'est potentiellement valorisé que parmi 2 ou 3 valeurs

![xLM_Axis](https://github.com/iPlumb3r/SEAMLESS/blob/master/Images/xLM_Axis_2020-07-24.png)

La taille de la matrice théorique résultante est de  2x2x2x2x2 X 2x2x2x2x3x3x3 = 32 X 432 = 13824 cellules !    
(Rq : Toutes les "cellules" n'étant pas forcement pertinantes)

> Cela permet déjà de comprendre pourquoi les modèles applicatifs des solutions PLM sont potentiellement si compliqués

## Construction de la facette "DO" (Intention)
En combinant les différents critères élémentaires de la facette "DO" (Intention), ...   
... on parvient à reconstituer les différentes étapes de son cycle de vie.

> Cette facette apporte la généricité

![DO_Facet](https://github.com/iPlumb3r/SEAMLESS/blob/master/Images/xLM_Axis_INT_DeepExplanation_2020-07-23.png)

## Construction de la facette "BE" (Extension)
En combinant les différents critères élémentaires de la facette "BE" (Extension), ...   
... on parvient à positionner la nature de la chose à concevoir.

> Cette facette apporte la spécificité

![BE_Facet](https://github.com/iPlumb3r/SEAMLESS/blob/master/Images/xLM_Axis_EXT_DeepExplanation_2020-07-24.png)

