# TEI-SETAF

Ce dépôt est en cours de construction. 

Ce dépôt comprend les données TEI produites dans le cadre du projet SETAF. 

Description :
- La liste des textes avec plus de détails se trouve dans le [tableau CSV](https://github.com/SETAFDH/TEI-SETAF/blob/main/TEI_table.csv) du dépôt.
- Le dossier "schema" contient l'ODD du projet sous différents formats (.odd, .html, .rng).
- Le dossier "stylesheets" contient les feuilles de style utilisés pour convertir les données (du format ALTO au TEI, etc.).
- Le dossier "data" contient les textes au format XML-TEI et HTML.

Description des fichiers XML-TEI :
  - Chaque fichier .xml se compose de trois grandes parties : <b>teiHeader</b>, <b>sourceDoc</b> et <b>body</b>. Le <b>teiHeader</b>, l'en-tête du fichier, contient les métadonnées de l'ouvrage et les informations indispensables à l'identification du fichier. La section <b>sourceDoc</b> comprend toutes les informations qui étaient contenues dans les fichiers ALTO d'origine. Dans le <b>body</b>, le corps du texte, nous proposons une balise <b>choice</b> qui comprend trois couches : les lignes océrisées et extraites à partir du <b>sourceDoc</b>, dans la balise <b>orig</b>, et les mêmes lignes normalisées dans les balises <b>reg type="intermediary"</b> et <b>reg type="contemporary"</b>.

Description des fichiers HTML :
  - Chaque fichier .html <b>orig</b> présente, de façon plus lisible, les lignes de texte tirées des balises <b>orig</b> (*original form*).
  - Chaque fichier .html <b>reg_int</b> présente, de façon plus lisible, les lignes de texte tirées des balises <b>reg type="intermediary"</b>. Il s'agit de la régularisation (niveau intermédiaire) du texte source produite grâce au guide de normalisation du projet SETAF.
  - Chaque fichier .html <b>reg_cont</b> présente, de façon plus lisible, les lignes de texte tirées des balises <b>reg type="contemporary"</b>. Il s'agit de la traduction du texte source en français contemporain, une étape qui ne concerne que certains textes.

Chaque version .html <b>orig</b>, <b>reg_int</b> ou <b>reg_cont</b>, est ajoutée quand le travail sur les lignes de texte tirées des balises correspodantes, dans le fichier XML-TEI, est terminé (qualité *gold*).

Pour comprendre l'état d'avancement des textes (qualité *gold*, *en cours* ou *à venir*), il suffit de consulter le [tableau CSV](https://github.com/SETAFDH/TEI-Varia-Malingre/blob/main/TEI-Varia-Malingre_Table.csv) du dépôt et/ou le teiHeader des fichiers XML-TEI.


## Projet SETAF

GitHub du projet : https://github.com/SETAFDH 

Site du projet : https://www.unige.ch/setaf


## Financeur

Ce projet est financé par le Fonds national suisse (FNS). Numéro de projet : [205056](https://data.snf.ch/grants/grant/205056).


## Licence

Les transcriptions sont [CC-BY](https://creativecommons.org/licenses/by/4.0), et les images suivent les règles de différentes bibliothèques numériques : [e-rara](https://www.e-rara.ch/wiki/termsOfUse?lang=en), [ONB](https://www.onb.ac.at/en/use), [Gallica](https://gallica.bnf.fr/edit/und/conditions-dutilisation-des-contenus-de-gallica), [BSB](https://oai.bsb-muenchen.de/doc/en/imprint).


## Citer le dépôt

- Version `0.9`: Sonia Solfrini, Geneviève Gross, Pierre-Olivier Beaulnes, Aurélia Marques Oliveira, Simon Gabay et Daniela Solfaroli Camillocci, _Données TEI du projet SETAF_, version `0.9`, Genève, université de Genève, 2023, https://github.com/SETAFDH/TEI-SETAF.

```bibtex
@misc{solfrini_tei_setaf_2023,
  author={Solfrini, Sonia and Gross, Geneviève and Beaulnes, Pierre-Olivier and Marques Oliveira, Aurélia, and Gabay, Simon and Solfaroli Camillocci, Daniela},
  title={Données TEI du projet SETAF},
  version={0.9},
  address={Genève},
  publisher={université de Genève},
  year={2023},
  url={https://github.com/SETAFDH/TEI-SETAF},
}
```
