# Realisez-une-etude-de-sante-publique
Projet 4 de la formation de data analyst de OpenClassrooms

<img width="614" alt="IMG_Scenario" src="https://github.com/AlexisDlge/Detectez-des-faux-billets/assets/152527939/6c949932-3da9-4faa-a408-3d3da4ec7247">


Félicitations ! Vous avez récemment rejoint une équipe de chercheurs de la [Food and Agriculture Organization of the United Nations (FAO)](https://www.fao.org/home/fr/), en tant que data analyst.

<img width="614" alt="Logo_fao" src="https://github.com/AlexisDlge/Realisez-une-etude-de-sante-publique/assets/152527939/115fc2b8-4783-4892-b87b-9a693d9fca91"> 


Food and Agriculture Organization of the United Nations Food and Agriculture Organization of the United Nations

Son rôle ? C’est l’un des organes qui composent l’ONU et dont l’objectif est « d’aider à construire un monde libéré de la faim ». 

Le responsable de l’équipe, Marc, un chercheur en économie de la santé, est particulièrement enthousiaste à l’idée de votre arrivée au sein de son équipe. En effet, ce recrutement tombe à pic car Julien, l'ancien data analyst, a récemment été muté dans une autre équipe, et la vôtre vient de se voir confier la mission de réaliser une étude de grande ampleur sur le thème de la sous-nutrition dans le monde.

Dès votre arrivée, vous trouvez un mail de Marc dans votre boîte mail :



    Objet : Bienvenue
    De : Marc
    À : Vous

    Hello et bienvenue au sein de la FAO. 
    J’espère que tu te plairas parmi nous. En tous cas, sache que je suis très content de t’accueillir au sein de mon équipe.

    Tu es probablement au courant, mais nous avons une grosse tâche qui nous attend, et nous comptons particulièrement sur toi
    pour nous donner un panorama de l’état de la malnutrition dans le monde, à partir des données que tu trouveras dans le
    dossier en pièce jointe. Je t’invite d’ailleurs fortement à lire le Lexique des données qui s’y trouve, écrit par Julien.
    Dans ce document, tu trouveras le descriptif des différents fichiers ainsi que des notes qui te sont adressées. 
    Nous souhaitons que tu poursuives ses recherches en répondant aux questions qu'il t'a laissé.

    Les données sur lesquelles j’aimerais particulièrement avoir des informations sont, pour l’année 2017 :

        ● la proportion de personnes en état de sous-nutrition ;
        ● le nombre théorique de personnes qui pourraient être nourries. 
          Tu devrais pouvoir calculer ça à partir de la disponibilité alimentaire mondiale ;
        ● idem pour la disponibilité alimentaire des produits végétaux ;
        ● l’utilisation de la disponibilité intérieure, en particulier la part qui est attribuée à l’alimentation animale, 
          celle qui est perdue et celle qui est concrètement utilisée pour l'alimentation humaine. 
          Je crois que Julien avait trouvé un moyen de facilement calculer ces proportions.

     Ce sont les informations principales dont on aimerait que tu puisses nous rendre compte, 
     mais toute idée additionnelle est bonne à prendre ! 

    Il y a aussi Mélanie, une autre chercheuse de l’équipe qui avait quelques demandes. 
    Elle devrait prendre contact avec toi rapidement à ce sujet.

    N’hésite pas à venir me voir si tu as la moindre question !

    Marc.

    PJ : données FAO.zip 


À peine le temps de préparer votre café matinal, que vous recevez un message de Mélanie par messagerie instantanée :

    MELANIE
    Hello, j’espère que tout va bien et que t’intègres bien. 
    En tout cas, je te souhaite à mon tour la bienvenue dans notre équipe.

    VOUS
    Merci ! Je prends mes marques petit à petit. Marc m’a dit que tu avais une demande particulière ?

    MELANIE
    Tout à fait ! Je souhaiterais avoir une étude un peu plus fine pour chacun des pays. 
    Par exemple, j’aimerais que tu puisses nous donner les pays pour lesquels la proportion de personnes sous-alimentées est la
    plus forte en 2017, ceux qui ont le plus bénéficié d’aide depuis 2013, ceux ayant le plus/le moins de 
    disponibilité/habitant, etc., et toutes les infos que tu trouverais utiles pour mettre en relief les pays qui semblent être
    le plus en difficulté, au niveau alimentaire.

    VOUS
    OK pas de soucis, je vais regarder ça.

    MELANIE
    Super, bon courage !

    VOUS
    Merci, à bientôt !

<img width="614" alt="IMG_Livrables" src="https://github.com/AlexisDlge/Detectez-des-faux-billets/assets/152527939/86af4a1f-0feb-4235-b2ba-2f685fcaca46">

* Le notebook R Markdown ou Jupyter (en Python) vous ayant permis de calculer/trouver l’ensemble des résultats demandés.
* Le notebook R Markdown ou Jupyter (en Python) en version PDF.
* Le support de présentation contenant toutes les informations demandées en version PPT ou Gslides.



Pour faciliter votre passage devant le jury, déposez sur la plateforme, dans un dossier zip nommé “Titre_du_projet_nom_prenom”, tous les livrables du projet comme suit : Nom_Prenom_n° du livrable_nom du livrable__date de démarrage du projet. Cela donnera :

* Nom_Prenom_1_notebook_mmaaaa ;
* Nom_Prenom_2_notebook-pdf_mmaaaa ;
* Nom_Prenom_3_presentation_mmaaaa.

Par exemple, le premier livrable peut être nommé comme suit : Dupont_Jean_1_notebook_012023

<img width="614" alt="IMG_Soutenance" src="https://github.com/AlexisDlge/Detectez-des-faux-billets/assets/152527939/a1a8bf0e-898d-4fa4-808b-091d870eb595">
    
Durant la présentation orale, l’évaluateur interprétera le rôle de Marc, le responsable de l’équipe. La soutenance est structurée de la manière suivante :

* Présentation des résultats (15 minutes).
  - Vous présenterez votre notebook et votre support de présentation répondant aux questions. 

* Discussion (10 minutes) :
  - L’évaluateur jouera le rôle de Marc. Il vous challengera sur vos choix, et vérifiera vos connaissances sur certaines fonctions en R ou Python, notamment : 
    - la propreté et l’organisation du code :
    - les opérations d’algèbre relationnelle ( jointure), la restriction (.loc et/ou sélection de colonnes) et l’agrégation 
  - Il vous demandera si le RGPD est respecté dans les data set nettoyés

* Debrief (5 minutes)
    
À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de Marc pour vous permettre de débriefer ensemble.
