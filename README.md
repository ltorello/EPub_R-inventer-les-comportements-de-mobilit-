# Projet_EPub_Corrections
Dépôt du projet de publication numérique

# Création d'un ePub
## Description
![ePub ouvert avec Sigil](https://github.com/ltorello/Projet_EPub_Corrections/assets/92383410/61ae9ced-868b-40e4-b217-542c7046faaf)

Ce projet a consisté à créer un ePub avec le logiciel Sigil. Il ne s'agit pas d'une simple conversion, mais une création de A à Z à partir d'un document PDF océrisé qui a comporté les étapes suivantes :

1) Recherche de documentation décrivant les étapes nécessaires à la création d'un ePub avec le logiciel Sigil
2) Recherches annexes, notamment pour déterminer le format le plus approprié pour les images. 
3) Remise en page du fichier océrisé dans l'optique d'une lecture ergonomique du livre numérique.
4) Balisage des différents chapitres, en partie manuellement et en partie avec des expressions régulières
5) Création des renvois pour les notes de bas de page.

Ce projet est très simple, mais son auteure partait avec des connaissances informatiques proches de zéro. Les différentes étapes nécessaires à la création du livre numériques n'ont pas été forcément compliquées à réaliser, mais ont souvent été très chronophages du fait qu'elles ont été réalisées en grande partie à la main. 

## Outils utilisés
* Adobe Acrobat : océrisation du fichier pdf source
* World : correction de la mise en page après l'océrisation
* Sigil : création du ePub
* Kindle Previewer 3 : conversion du fichier ePub aux formats .mobi et .kpf pour la lecture sur une liseuse Kindle.

## A propos du document source
Le document utilisé pour réaliser ce projet est une publication de la Fondation Jean Monnet éditée dans le cadre du groupe de réflexion 2016-2019 consacré à la mobilité durable. 

## Notice d'utilisation
1) Télécharger le dossier "ePub_Final"
2) Choisir dans le dossier "ePub_Final" la version du projet qui correspond au logiciel utilisé pour la lecture : 
* Le fichier .epub pour n'importe quel lecteur prenant en charge ce type de fichier
* Le fichier .mobi ou le fichier .kpf pour une lecture avec l'application Kindle. Le format kpf est en principe pris en charge sur tous les appareils et applications Kindle. Source : [Amazon](https://kdp.amazon.com/fr_FR/help/topic/G200634390)
3) Les chapitres de la table des matières sont cliquables afin de faciliter la navigation dans le livre. Les numéros dans le texte qui renvoient à une référence en fin de chapitre sont aussi des liens cliquables qui amènent directement à l'emplacement de la note correspondante. 
4) Si l'appareil de lecture possède une connexion internet, il est possible d'ouvrir les liens externes au livres qui sont présents dans les notes et dans les sources. 

## Utilité du dossier "XHTML_Images_CSS"

Les fichiers qui composent ce dossiers ont été fournis pour faciliter l'évaluation. Pour accéder aux images, aux fichiers XHTML et à la feuille de style, ouvrir le dossier XHTML_Images_CSS et ensuite le dossier OEBPS. Ce dossier permet de voir comment le ePub est composé. Il n'est en principe pas nécessaire de le télécharger. On peut aussi ouvrir le fichier .epub qui se trouve dans le dossier "ePub_final" avec Sigil et utiliser la vue "balisage" (<>).

## Mise à jour des données

Les données mises à disposition dans ce dépot ne nécessitent pas de mise à jour.

## Auteure

Ce projet a été réalisé par Laure Torello dans le cadre du cours Publication numérique dispensé par le prof. Isaac Pante à l'Université de Lausanne au semestre d'automne 2021.

## Crédits

Isaac Pante : présentation en classe des spécificités du format ePub et du logiciel Sigil

Le YouTubeur Jesuiscurieux pour son [tutoriel très détaillé](https://www.youtube.com/watch?v=-CpzHoTtZlQ&t=198s) consacré à la création de livres numériques avec Sigil. 

