# TEI-SETAF

Ce dépôt est en cours de construction. 

Ce dépôt comprend les données TEI produites dans le cadre du projet SETAF. 

Description :
- La liste des textes avec plus de détails se trouve dans le tableau CSV du dépôt. 
- Le dossier "schema" contient l'ODD du projet sous différents formats (odd, html, rng).
- Le dossier "stylesheets" contient les feuilles de style utilisés pour convertir les données (du format ALTO au TEI, etc.).
- Le dossier "data" contient les données 
  - "data_orig" contient les fichiers TEI où les lignes de texte dans la balise <b>orig</b> (*original form*) ont été contrôlé manuellement (qualité *gold*). Il s'agit de la transcription du texte source produite grâce à un modèle d'OCR et au guide de transcription du projet SETAF.
  - "data_reg" contient les fichiers TEI où les lignes de texte dans la balise <b>reg type="intermediary"</b> sont en cours de traitement. Il s'agit de la régularisation (niveau intermédiaire) du texte source produite grâce au guide de normalisation du projet SETAF.
  - "data_cont" contient les fichiers TEI où les lignes de texte dans la balise <b>reg type="contemporary"</b> sont en cours de traitement. Il s'agit de la traduction du texte source en français contemporain, une étape qui ne concerne que certains textes.

Pour comprendre l'état d'avancement des textes, il suffit de consulter le tableau CSV du dépôt et/ou le teiHeader des fichiers.


## Projet SETAF

GitHub du projet : https://github.com/SETAFDH 

Site du projet : https://www.unige.ch/setaf


## Financeur

Ce projet est financé par le Fonds national suisse (FNS). Numéro de projet : 205056 (https://data.snf.ch/grants/grant/205056).


## Licence

Les transcriptions sont [CC-BY](https://creativecommons.org/licenses/by/4.0), et les images suivent les règles de différentes bibliothèques numériques :
- e-rara : https://www.e-rara.ch/wiki/termsOfUse?lang=en
- Österreichische Nationalbibliothek : https://www.onb.ac.at/en/use


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
