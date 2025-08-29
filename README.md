# TEI-SETAF

Ce dépôt est en cours de construction. 

Ce dépôt comprend les données TEI produites dans le cadre du projet SETAF. 

Description :
- La liste des textes avec plus de détails se trouve dans le [tableau CSV](https://github.com/SETAFDH/TEI-SETAF/blob/main/TEI_table.csv) du dépôt.
- Le dossier "schema" contient l'ODD du projet sous différents formats (.odd, .html, .rng).
- Le dossier "data" contient les textes au format XML-TEI et HTML.

Description des fichiers XML-TEI :
  - Chaque fichier .xml se compose de trois grandes parties : <b>teiHeader</b>, <b>sourceDoc</b> et <b>body</b>. Le <b>teiHeader</b>, l'en-tête du fichier, contient les métadonnées de l'ouvrage et les informations indispensables à l'identification du fichier. La section <b>sourceDoc</b> comprend toutes les informations qui étaient contenues dans les fichiers ALTO d'origine. Dans le <b>body</b>, le corps du texte, nous proposons une balise <b>choice</b> qui comprend trois couches : les lignes océrisées et extraites à partir du <b>sourceDoc</b>, dans la balise <b>orig</b>, et les mêmes lignes normalisées dans les balises <b>reg type="intermediary"</b> et <b>reg type="advanced"</b>.

Description des fichiers HTML :
à venir

Pour comprendre l'état d'avancement des textes (qualité *gold*, *en cours* ou *à venir*), il suffit de consulter le [tableau CSV](https://github.com/SETAFDH/TEI-SETAF/blob/main/TEI_table.csv) du dépôt et/ou le teiHeader des fichiers XML-TEI.


## Projet SETAF

GitHub du projet : https://github.com/SETAFDH 

Site du projet : https://www.unige.ch/setaf


## Financeur

Ce projet est financé par le Fonds national suisse (FNS). Numéro de projet : [205056](https://data.snf.ch/grants/grant/205056).


## Licence

Les transcriptions sont [CC-BY](https://creativecommons.org/licenses/by/4.0), et les images suivent les règles de différentes bibliothèques numériques : [e-rara](https://www.e-rara.ch/wiki/termsOfUse?lang=en), [ONB](https://www.onb.ac.at/en/use), [Gallica](https://gallica.bnf.fr/edit/und/conditions-dutilisation-des-contenus-de-gallica), [BSB](https://oai.bsb-muenchen.de/doc/en/imprint), [MDZ](https://digitale-sammlungen.de/en), [Manchester Library Digital Collections](https://www.manchester.ac.uk/), [Réro Doc](https://doc.rero.ch/?ln=en).


## Citer le dépôt

- Version `1.0`: Sonia Solfrini, Geneviève Gross, Pierre-Olivier Beaulnes, Aurélia Marques Oliveira, Mylène Dejouy, Simon Gabay et Daniela Solfaroli Camillocci, _Données TEI du projet SETAF_, version `1.0`, Genève, université de Genève, 2023-2026, https://github.com/SETAFDH/TEI-SETAF.

```bibtex
@misc{solfrini_tei_setaf,
  author={Solfrini, Sonia and Gross, Geneviève and Beaulnes, Pierre-Olivier and Marques Oliveira, Aurélia and Dejouy, Mylène and Gabay, Simon and Solfaroli Camillocci, Daniela},
  title={Données TEI du projet SETAF},
  version={1.0},
  address={Genève},
  publisher={université de Genève},
  year={2023-2026},
  url={https://github.com/SETAFDH/TEI-SETAF},
}
```

## Citer le projet

à venir
