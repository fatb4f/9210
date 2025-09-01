# Introduction

Ce cours traite de la programmation orientée objet avec le langage C++.

L’industrie du logiciel a vécu, depuis son émergence, des progrès significatifs grâce auxquels elle a pu s’immiscer dans les domaines les plus variés de l’activité humaine. Dans ce contexte, différentes approches ou méthodes de conception, les unes plus efficaces que les autres, ont vu le jour. Ainsi, l’_approche structurée_, guidée par les traitements, est réputée efficace quand il s’agit de se concentrer sur les traitements. L’_approche systémique_, fondée sur la définition des parties en interdépendance et en relation avec leur environnement, fonctionne bien lorsqu’elle s’applique à l’univers de la gestion. Quant à l’_approche par les connaissances_, elle est réservée au développement de systèmes à base de connaissances et à tous les domaines se caractérisant par une forte expertise. Toutes ces approches comportent toutefois un certain nombre de contraintes ou de limitations :

*   taille et complexité croissantes des logiciels;
*   éparpillement dans les programmes des différents aspects touchant une même entité;
*   faible réutilisabilité;
*   difficulté d’évolution;
*   difficulté dans le traitement du parallélisme;
*   logique étrangère à la réalisation des interfaces utilisateurs.

L’_approche orientée objet_ semble être la solution idéale; elle s’inscrit dans la continuité des progrès réalisés en informatique. L’objet constitue une représentation d’une portion cohérente de la réalité, c’est-à-dire un modèle exact et complet d’un élément du monde réel. La modélisation objet possède trois caractéristiques fondamentales :

*   l’autonomie dans l’environnement;
*   la cohérence assurée par l’interdépendance des éléments en interaction;
*   la stabilité des structures de données par rapport aux modifications qu’elles peuvent subir.

Deux circonstances ont favorisé l’avènement de ces caractéristiques :

1.  Sous l’égide des sciences cognitives, un brassage d’idées et une série de travaux ont conduit à une vision synthétique du fonctionnement mental et des processus de cognition.
2.  Quelques principes issus de ces travaux ont inspiré les concepteurs de langages de programmation qui les ont divulgués, vulgarisés et surtout traduits dans les syntaxes des nouveaux langages.

On ne saurait prétendre que ces langages soutiennent toute la subtilité et toute la complexité de l’esprit humain, même si certains mécanismes fondamentaux du traitement des connaissances y sont pris en compte. Néanmoins, ils représentent bien plus qu’une simple collection de nouveaux langages : la programmation orientée objet, en tant que paradigme, constitue une nouvelle manière de réfléchir sur le sens du traitement informatique et sur la façon de structurer les informations à l’intérieur d’un ordinateur.

Il est clair que l’intérêt suscité par la programmation orientée objet dépasse largement le cercle restreint des spécialistes et prend de plus en plus d’importance dans tous les domaines de l’informatique. Ainsi, le cours INF 2005 _Programmation orientée objet avec C++_ présente cette approche comme un outil efficace permettant de construire des logiciels de qualité. En utilisant le langage de programmation C++, ce cours constitue une référence qui exploite, dans la mesure du possible, les principaux avantages de ce langage.

Les utilisateurs du langage de programmation C++ doivent se poser plusieurs questions : Qu’est-ce qu’un objet? Comment peut-on décrire un objet? Comment manipuler les objets? Quelles sont les relations possibles entre les objets? Les réponses à toutes ces questions se trouvent dans un grand nombre de techniques qui permettent de réaliser efficacement des logiciels réutilisables, fiables et extensibles : l’héritage, le polymorphisme, la généricité, le masquage, etc. Ce sont là autant de concepts que nous nous proposons d’étudier dans ce cours.

## Objectifs d’apprentissage

À la fin du cours, vous devriez être capable de :

*   définir en détail ce qu’est la programmation orientée objet;
*   utiliser le langage C++ pour développer des programmes simples ou participer à l’élaboration de programmes complexes;
*   distinguer la programmation orientée objet des autres types de programmation (si vous avez de l’expérience avec ces autres types de programmation).

## Durée du cours

135 heures, réparties sur 15 semaines.

Vous pouvez toutefois, si nécessaire, profitez d’un _report de la fin du cours_. Pour des précisions sur cette possibilité, consultez le [Guide des études à distance](https://www.teluq.ca/site/documents/etudes/guide_etudes_distance.pdf "Guide des études à distance") (p. 36).

## Démarche d’apprentissage

La spécificité de la formation à distance que vous offre la TÉLUQ exige une bonne discipline personnelle, tout en faisant appel à votre autonomie. Afin de vous soutenir dans votre apprentissage, nous vous proposons une démarche qui alterne entre la lecture active des textes de référence des modules, la vérification et la mise en application des connaissances par la réalisation d’exercices autocorrectifs et la réalisation de trois travaux pratiques servant à votre évaluation.

Sur le site de la TÉLUQ, une section intitulée [Stratégies d’étude](https://www.teluq.uquebec.ca/pls/modlect/diegmk01.pr_init_gm_v1?p_guide_code=STRAT_ETUDE) regroupe, sous différentes rubriques, divers conseils d’ordre pédagogique. Il y a aussi la section [L’art de vivre ses études](https://www.teluq.ca/siteweb/sante/) qui contient des conseils fort judicieux. Si vous connaissez peu la formation à distance, nous vous recommandons fortement la consultation de ces deux sections.

Pour ce qui est du cours, il comprend :

*   une activité de [démarrage](https://inf2005.teluq.ca/apprentissage/demarrage/ "Démarrage");
*   cinq modules thématiques ([M1](https://inf2005.teluq.ca/apprentissage/module-1/introduction/ "Introduction") | [M2](https://inf2005.teluq.ca/apprentissage/module-2/introduction/ "Introduction") | [M3](https://inf2005.teluq.ca/apprentissage/module-3/introduction/ "Introduction") | [M4](https://inf2005.teluq.ca/apprentissage/module-4/introduction/ "Introduction") | [M5](https://inf2005.teluq.ca/apprentissage/module-5/introduction/ "Introduction"));
*   une activité de [clôture](https://inf2005.teluq.ca/apprentissage/cloture/ "Clôture");
*   trois travaux pratiques ([TP1](https://inf2005.teluq.ca/evaluation/travail-pratique-1/ "Travail pratique 1") | [TP2](https://inf2005.teluq.ca/evaluation/travail-pratique-2/ "Travail pratique 2") | [TP3](https://inf2005.teluq.ca/evaluation/travail-pratique-3/ "Travail pratique 3"));
*   une activité finale pendant laquelle vous vous préparez au [projet final](https://inf2005.teluq.ca/evaluation/projetfinal/ "Examen").

Les cinq modules partagent une même structure :

*   **Théorie** : l’étude d’un texte de référence présentant les concepts et les techniques en lien avec la thématique du module. De nombreux exemples accompagnent la présentation théorique de la thématique. Des ressources complémentaires sur certains aspects théoriques sont parfois suggérées.
*   **Pratique** : la réalisation d’exercices pratiques en lien avec la thématique du module. Des questions à choix multiples sont parfois présentes pour vérifier votre compréhension de certains concepts du domaine.

## Évaluation des apprentissages

L’évaluation des apprentissages ou, en d’autres termes, l’évaluation de l’atteinte des objectifs d’apprentissage du cours, comprend la réalisation de trois travaux pratiques (chacun compte pour 20 % de la note finale) et un projet final (40 %).

## Encadrement

Une personne tutrice vous accompagne tout au long du cours.

La personne tutrice utilise principalement le courriel pour interagir avec vous. Les activités principales qu’elle est amenée à réaliser sont les suivantes :

*   Accueillir, encourager, motiver, faire un suivi proactif.
*   Répondre à vos questions sur le contenu des textes de référence, sur les consignes des activités et les consignes de réalisation des activités d’évaluation (travaux pratiques et examen).
*   Conseiller sur votre cheminement à privilégier dans le cours.
*   Évaluer les travaux pratiques et l’examen en vous fournissant une rétroaction formative détaillée.

© [Hamadou Saliah-Hassane](https://www.teluq.ca/siteweb/univ/saliah.html), 2015. Tous droits réservés.
