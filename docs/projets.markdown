---
layout: page
title: Projets
permalink: /projets/
usemathjax: true
---

<style type="text/css" media="screen">
.container {
margin: 10px auto;
max-width: 750px;
text-align: center;
}
h1 {
margin: 30px 0;
font-size: 4em;
line-height: 1;
letter-spacing: -1px;
}
</style>


#### Projet CITiES
{: .header_color}
<hr style="height:2px;border-width:0;color:gray;background-color:#367588"><br>
<span class="time">2013 - 2016</span><br>

Le projet <a href="https://anr.fr/Projet-ANR-12-MONU-0020">ANR CITiES</a> a eu pour mission principale de développer un outil d’aide à la décision, appelé modèle transport-urbanisme, pour la conception et l’évaluation des politiques de transport et d’aménagement urbain. Ces modèles permettent de représenter les interactions complexes entre l'usage des sols et le transport de biens et de personnes sur un territoire. La taille du territoire étudié peut aller de l'échelle d'un village jusqu'à une région. Dans le cadre du projet CITiES, le territoire étudié a été l'agglomération Grenobloise.<br>

<div class="container">
<h1> <img src="../assets/images/tranus.png" alt="tranus"> </h1>
</div>

La majorité de ces modèles résulte d'un couplage entre différents modules simulant chacun divers phénomènes économiques (réseau de transport, utilisation des sols, ...). L'utilisation d'un modèle transport-urbanisme peut se décomposer en trois phases :

1. une phase dite d'instanciation durant laquelle les données nécessaires à la conception du modèle sont collectées auprès d'agences d'urbanisme ou directement dans des bases de données nationales,
2. une phase dite de calage, où les paramètres propres au modèle sont ajustés afin que le modèle reproduise le plus fidèlement possible une ou plusieurs données,
3. une phase dite de prospective, où différents scénarios de développement transport-urbain sont testés pour planifier l'aménagement des sols et/ou du réseau de transport.

Ces modèles mettent en jeu un nombre considérable de paramètres (coefficients scalaires) n'ayant pas de représentation économique particulière. Certains de ces paramètres, dits influents, peuvent avoir un impact considérable sur la qualité de prédiction du modèle. Mes travaux de thèse se sont inscrits dans la seconde phase.

J'ai notamment développé une procédure de calage du modèle transport-urbanisme <a href="http://www.tranus.com/tranus-english">Tranus</a>. Cette procédure combine une phase d'analyse de sensibilité et une phase d'optimisation. La phase d'analyse de sensibilité a pour but d'identifier les paramètres influents du modèle et ainsi réduire la dimension du problème d'optimisation. La version calée de Tranus avait ensuite pour objectif d'être utilisée dans une phase de prospective, afin de tester des scénarios de développement transport-urbain conjointement avec l'agence d'urbanisme de Grenoble.


<br>
#### Projet LUG2
{: .header_color}
<hr style="height:2px;border-width:0;color:gray;background-color:#367588"><br>
<span class="time">2017 - 2020</span><br>

Le projet <a href="https://www.minalogic.com/8-projets-finances-au-22eme-aap-du-fui-regions/">FUI LUG2</a> a eu pour objectif de développer un nouveau prototype d'antennes acoustiques capables d'identifier, localiser et quantifier précisément les sources de bruit dans un environnement complexe. Le projet était piloté par la société MicrodB et a associé partenaires académiques (Laboratoire Vibrations Acoustique, Institut Camille Jordan, MaiMoSiNE) et industriels (Rtone, Terabee).

<div class="container">
<h1> <img style="width:60%" src="../assets/images/lug2.png" alt="lug2"> </h1>
</div>

La localisation et quantification de sources de bruit peuvent se résumer par le schéma ci-dessus. L'objet d'étude est par exemple un moteur de voiture dont on veut déterminer à une fréquence donnée quelles sont les parties/composantes à l'origine du bruit. Pour cela, des jeux de mesures (pressions acoustiques) sont acquis à l'aide d'une antenne de microphones. Puis, à partir de ces mesures on cherche à reconstruire le champ sonore sur une grille modélisant la surface de l'objet d'étude. D'un point de vue numérique, cette reconstruction consiste en la résolution d'un problème inverse.

Mes contributions au projet LUG2 consistent en deux méthodes visant à :
1. quantifier l'impact de sources d'incertitude propres à l'antenne et au modèle de propagation à la fois sur les jeux de mesures acquis et sur la reconstruction du champ sonore,
2. identifier le placement optimal d'antennes de microphones pour permettre à des techniciens de microdB de pouvoir rapidement effectuer des mesures successives *in situ*.

<br>
#### Projets internes IFP Energies Nouvelles (IFPEN)
{: .header_color}
<hr style="height:2px;border-width:0;color:gray;background-color:#367588"><br>
<span class="time">2018 - 2019</span><br>


Les principaux axes de recherche de l'IFPEN Solaize portent sur le développement de catalyseurs pour la production de carburants plus respectueux de l'environnement. Les projets de l'IFPEN sont menés au sein d'équipes pluridisciplinaires constituées de collaborateurs issus des départements de recherche et des départements fonctionnels ou métiers.

<div class="container">
<h1> <img style="width:100%" src="../assets/images/ifpen.png" alt="lug2"> </h1>
</div>

J'ai contribué à trois projets dont deux portant sur l'utilisation de méthodes <<Machine Learning>> pour la modélisation de procédés pétrochimiques en particulier l'hydrocraquage. J'ai développé deux modèles :
1. le premier pour prédire des propriétés de produits obtenus par hydrocraquage à partir de données réelles issues de raffineries,
2. le second pour déterminer des catégories de catalyseurs performants à partir de données moléculaires.
