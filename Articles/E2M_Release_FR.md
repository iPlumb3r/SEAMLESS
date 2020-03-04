Un modèle pour la cartographie sémantique d'écosystème
==

Introduction
-
Chacun d'entre nous, pour des __raisons diverses et variées__ (e.g. veille currentielle, veille produit, étude de marché, veille technologique, démarche entrepreunariale, développement de produit, ...) sommes à conduit à "cartographier", __plus ou moins formellement__ (et en utilisant des outils __plus ou moins adaptés__), l'environnnement dans lequel on évolue actuellement (ou celui dans lequel on souhaite évoluer dans le futur) !

En effet, cartographier son environnement permet d'avoir une vision à la fois globale et précise de celui-ci ...   
... afin de pouvoir mieux agir dessus.

Le modèle E2M (Ecosytem Mapping Model) visent à répondre à ce besoin en proposant :
* Une approche méthodologique
* Un modèle (décliné selon différents formalismes)
* Des propositions d'outils cibles (selon les fonctions requises et l'usage)

Tags
-
#EcosystemMapping #SemanticCartography #MapYourEnvironment #EffectuationMethodology #CompetitiveWatch #ProductWatch #MarketWatch #TechnologyWatch #ProductLifecycleManagement 

Problématique à résoudre
-
Les environnements ont beau être potentiellement __très différents__ d'un cas à l'autre, il s'avère que les questions que l'on se posent à leur propos, mais égalements concepts qui *structurent* ces environnements sont - globalement - toujours les __mêmes__ (ce sont en quelque sorte les *invariants métiers* du domaine de connaissances "ecosystem mapping").

En effet, lorsqu'on cherche à appréhender un écosystème, on essaye essentiellement de répondre au quintuple questionnement suivant : 
* QUOI ?
* Fait QUOI ?
* COMMENT ?
* Pour QUOI ?
* Et POURQUOI ?

![Questions](https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/images/Who-DoesWhat-How-ForWhat-Why.png)

Il est évidement possible de se poser d'autres questions très pertinentes à propos de son environement, toujours est-il que le périmètre de E2M est - pour l'instant - limité à ces 5 questions ;-)

Approche méthodologique
-
L'approche méthodologique permettant de proposer le modèle E2M s'appuie principalement sur le fait de distinguer en chaque chose que l'on doit identifier dans la "carte" (afin de pouvoir le mettre en relation avec d'autres éléments) : 
* d'une part son "intention" (notion qui renvoi à la raison pour laquelle la chose doit être identifiée)
* d'autre part son "extension" (notion qui renvoi à la nature de la chose)

Un article décrivant plus en détail cette approche "Intention VS Extension" est disponible <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/ReasonWhyA2-LevelModel_FR.md">ici</a>.

L'expérience montre que globalement, __l'intention est plus importante que l'extension__, et que souvent les modèles sont "pollués" par l'extension des choses (lorqu'ils sont conçus de manière trop "monolithique"). 

Gérer ces 2 notions de manière "orthogonales" (i.e. "indépendement", mais en possible connexion) permet de disposer d'un modèle plus compact, plus robuste et plus evolutif, car basé sur 2 modules clefs :
* un module "intensionel" qui apporte de la généricité et permet d'adresser une grande diversité d'écosystèmes
* un module "extensionel" qui apporte de la spécificité et qui sert de "racine" à des sous-modules permetant d'adresser des écosystèmes particuliers 

Sémantique Sous-Jacente
-
Un <a href="https://github.com/iPlumb3r/EcosystemMappingModel/tree/master/1_Semantic/Conceptionary">conceptionary</a> permet de descrire les concepts utilisé par E2M (Work in prodress ...)

Le modèle conceptuel simplifié permet de visualer "grosse maille" les relation entres concepts intentioanl et cocnept extentionels :
![TM Ontology](https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/images/ConceptualModel%40E2M_2020-03-04.png)

Fonctionnalités recherchées
-
Réaliser une telle carte nécessite - idéalement - de pouvoir s'appuyer sur 2 modes fonctionels diamétralement opposés, mais totalement complémentaires. Il s'agit des modes suivants :
* Mode "Model-Driven"
* Mode "Model-Discovery" 

Remarque : Le 2nd mode, requiert - là encore idéalement - un mode de réconsiliation en complément

Plus d'information sur ces modes fonctionels <a href="https://github.com/iPlumb3r/EntangledBootstrap/tree/master/4_Functionalities">dans cette page</a>

Ontologies correspondantes
-
Le modèle E2M est décliné pour les 3 formalismes suivants ...   
... et adapté pour certains outils :

<table>
    <thead>
        <tr>
            <th>Ontologie</th>
            <th>Outil</th>
            <th>Mode</th>
            <th>Usage</th>   
            <th>Commentaires</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>OWL</td>
            <td>N'importe que outil "OWL-Compliant"</td>
            <td>En fonction de l'outil</td>
            <td>En fonction de l'outil</td>
            <td>En attente de <a href="http://semapps.org/">SemApps</a></td>
        </tr>
        <tr>
            <td>Topic Maps</td>
            <td>Par exemple pour <a href="https://www.topincs.com/">Topincs</a></td>
            <td>Mode "Model-Driven" uniquement</td>
            <td>Web / Multi-Utilisateur</td>
            <td>Cf <a href="https://www.topincs.com/iPlumb3rSandBox/">"Entangled Bootstrap" Repository (EBR)</a></td>
        </tr>
        <tr>
            <td>KL</td>
            <td>Uniquement pour <a href="http://keeplink.com/">KeepLink</a></td>
            <td>Mode "Model-Driven" et "Model-Discovery" (sans réconsiliation)</td>
            <td>iDevice / Mono-Utilisateur (Mode "Collaboration" à venir)</td>
            <td>En cours de paramétrage du modèle</td>
        </tr>
    </tbody>
</table>

Resources
-
GitHub : <a href="https://github.com/iPlumb3r/EcosystemMappingModel">E2M Repository</a>   
Telegram : <a href="https://t.me/EntangledBootstrap>EBR Group"</a>EBR Group</a> (Projets liés)   
Twitter : <a href="https://twitter.com/iPlumb3r">Semantic Cartography Flux</a>


