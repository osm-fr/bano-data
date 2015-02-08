###Descriptif du contenu des fichiers "BANO"

**Qu'est-ce que BANO ?**

BANO = Base d'Adresses Nationale Ouverte

C'est un projet initié par OpenStreetMap France destiné à constituer et diffuser sous licence libre une base de données d'adresses géolocalisées sur l'ensemble du territoire français.

Pour plus de renseignements: http://wiki.openstreetmap.org/wiki/WikiProject_France/WikiProject_Base_Adresses_Nationale_Ouverte_(BANO)


**Licence**

Ces données sont sous licence libre "ODbL" (Open Database Licence). Cette licence implique: l'attribution et le partage à l'identique.

- Pour la mention d'attribution veuillez indiquer "source: BANO" ainsi que la date du jeu de données.
- Pour le partage à l'identique, toute amélioration des données de BANO doit être repartagée sous licence identique, ceci dans le but d'une constante amélioration de BANO.

Ceci est le résumé explicatif de la licence ODbL 1.0. Merci de lire l'avertissement ci-dessous

Vous êtes libres :
- De partager : copier, distribuer et utiliser la base de données.
- De créer : produire des créations à partir de cette base de données.
- D'adapter : modifier, transformer et construire à partir de cette base de données.
Aussi longtemps que :
- Vous mentionnez la paternité : vous devez mentionner la source de la base de données pour toute utilisation publique de la base de données, ou pour toute création produite à partir de la base de données, de la manière indiquée dans l'ODbL. Pour toute utilisation ou redistribution de la base de données, ou création produite à partir de cette base de données, vous devez clairement mentionner aux tiers la licence de la base de données et garder intacte toute mention légale sur la base de données originaire.
- Vous partagez aux conditions identiques : si vous utilisez publiquement une version adaptée de cette base de données, ou que vous produisiez une création à partir d'une base de données adaptée, vous devez aussi offrir cette base de données adaptée selon les termes de la licence ODbL.
- Gardez ouvert : si vous redistribuez la base de données, ou une version modifiée de celle-ci, alors vous ne pouvez utiliser de mesure technique restreignant la création que si vous distribuez aussi une version sans ces restrictions.

Avertissement

Ce résumé explicatif n'est pas un contrat, mais simplement une source pratique pour faciliter la compréhension de la version complète de la licence ODbL 1.0 — il exprime en termes courants les principales notions juridiques du contrat. Ce résumé explicatif n'a pas de valeur juridique, son contenu n'apparaît pas sous cette forme dans le contrat. Seul le texte complet du contrat de licence fait loi.

Version complète en français disponible sur: http://www.vvlibri.org/fr/licence/odbl/10/fr/legalcode


**Origine**

BANO est une base de données composite, constituée à partir de différentes sources:
- OpenStreetMap (ODbL)
- données disponibles en opendata
  - Arles Crau Camargue Montagnette (Licence Ouverte) - juin 2014
  - Ville de Montpellier (Licence Ouverte) - janvier 2015
  - Toulouse Métropole (ODbL) - juin 2014
  - Rennes Métropole (ODbL) - juin 2014
  - Mulhouse Alsace Agglomération (Licence Ouverte) - septembre 2013
  - Grand Nancy (ODbL) - août 2014
  - Nantes Métropole (ODbL) - janvier 2015
  - Grand Lyon (Licence Ouverte) - janvier 2015
  - Bordeaux Métropole (ODbL) - février 2015
  - Strasbourg EuroMétropole (Licence Ouverte) - janvier 2014
  - Communauté Urbaine de Lille Métropole (Licence Ouverte - juin 2014
  - Métropole Nice Côte d'Azur (Licence Ouverte - Janvier 2015)
  - Ville de Limoges (ODbL - Décembre 2014)
  - Ville de La Rochelle (ODbL - Février 2015)
- données adresses collectées sur le site du cadastre et fichier FANTOIR (Licence Ouverte) - 2014


**Format**

Ces fichiers sont proposés au format shapefile, ainsi que sous forme de fichiers CSV (coordonnées WGS84/EPSG:4326 et textes en UTF-8).


**Contenu**

Pour chaque adresse:
- id (unique) : code_insee + codefantoir + numero
- numero : numéro dans la voie avec suffixe (ex: 1, 1BIS, 1D)
- voie : nom de voie
- code_post : code postal sur 5 caractères
- nom_comm : nom de la commune
- source : OSM = donnée directement issue d'OpenStreetMap, OD = donnée provenant de source opendata locale, O+O = donnée de source opendata enrichie par OpenStreetMap, CAD = donnée directement issue du cadastre, C+O = donnée du cadastre enrichie par OSM (nom de voie par exemple)
- lat : latitude en degrés décimaux WGS84
- lon : longitude en degrés décimaux WGS84


**Mise à jour, corrections**

Pour mettre à jour et corriger les données de BANO, il suffit de faire des améliorations directement dans OpenStreetMap, elles seront prises en compte au prochain de cycle de mise à jour.

Un guiche unique de signalement et de correction d'erreur est en cours de co-design. Si vous voulez participer à sa mise en place, contactez-nous par mail.

Pour toute question concernant ces exports, vous pouvez contacter bano@openstreetmap.fr
