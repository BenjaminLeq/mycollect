<div align="center">

# MyCollect

### Vos collections, à votre façon.

Gestionnaire de collections local, moderne et entièrement personnalisable pour Windows.

[![Version](https://img.shields.io/badge/version-0.19.4-6c5ce7?style=flat-square)](../../releases/latest)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=flat-square&logo=windows)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![Licence](https://img.shields.io/badge/licence-propri%C3%A9taire-lightgrey?style=flat-square)

[Télécharger la dernière version](../../releases/latest) · [Signaler un problème](../../issues)

</div>

---

MyCollect permet de gérer aussi bien des appareils photo que des livres, des jeux vidéo, des timbres ou toute autre collection. Créez vos propres champs, ajoutez des photos et des documents, puis retrouvez vos objets grâce aux vues, aux filtres et aux tableaux de bord.

Toutes les données restent sur votre ordinateur : aucun compte ni connexion Internet ne sont nécessaires pour utiliser l’application.

## Aperçu

<p align="center">
  <img alt="Tableau de bord de MyCollect" src="https://github.com/user-attachments/assets/d8675149-267c-471a-85e6-d267c2af1206" width="32%">
  <img alt="Vue tableau de MyCollect" src="https://github.com/user-attachments/assets/5ca048b7-8ddc-4071-915a-345f31646ce5" width="32%">
  <img alt="Vue cartes de MyCollect" src="https://github.com/user-attachments/assets/567857d6-12b3-4625-9f95-e1b6bc57d5f6" width="32%">
</p>
<p align="center">
  <img alt="Tableau de bord de MyCollect en thème sombre" src="https://github.com/user-attachments/assets/483d6189-d61d-4e91-b5cf-31d58059a5fb" width="32%">
  <img alt="Vue tableau de MyCollect en thème sombre" src="https://github.com/user-attachments/assets/235433c9-cd76-4f31-b5af-ff84c34d6a64" width="32%">
  <img alt="Vue cartes de MyCollect en thème sombre" src="https://github.com/user-attachments/assets/db70e260-bd95-4888-b1f6-1423227b63ba" width="32%">
</p>

## Points forts

- **Collections sur mesure** - créez autant de collections que nécessaire et définissez leurs champs par glisser-déposer.
- **10 types de champs** - texte, zone de texte, nombre, date, prix, note sur 5, lien web, image, galerie et pièce jointe PDF.
- **Trois modes d’affichage** - tableau de bord, tableau triable et cartes illustrées.
- **Recherche efficace** - recherche instantanée, filtres cumulables, favoris et détection des doublons.
- **Tableaux de bord personnalisables** - statistiques, répartitions, listes, taux de complétion et notes libres.
- **Gestion en série** - sélection multiple, duplication, favoris et mise à la corbeille en quelques clics.
- **Import et export** - CSV, JSON et archives portables `.mycollect` avec leurs médias.
- **Fiches PDF** - exportez un objet avec ses informations, ses liens et ses photographies.
- **Protection des données** - sauvegarde automatique, fichier de secours et corbeille avec conservation pendant 30 jours.
- **Confort d’utilisation** - thèmes clair et sombre, aide intégrée et fonctionnement hors ligne.

## Installation

### Version recommandée : installateur Windows

1. Ouvrez la page des [Releases](../../releases/latest).
2. Téléchargez `MyCollect_Setup_x.x.x.exe`.
3. Lancez l’installeur, puis suivez les instructions affichées.

MyCollect est compatible avec **Windows 10 et Windows 11**.

> [!TIP]
> Après l’installation, un double-clic sur un fichier `.mycollect` l’importe directement dans l’application déjà ouverte.

## Premiers pas

1. Cliquez sur **+ Nouvelle collection** et donnez-lui un nom.
2. Ouvrez **Champs** pour définir les informations propres à vos objets.
3. Cliquez sur **+ Ajouter un objet** et complétez sa fiche.
4. Choisissez la vue **Tableau de bord**, **Tableau** ou **Cartes**.

Chaque modification est enregistrée automatiquement.

## Imports, exports et sauvegardes

| Format | Utilisation |
| --- | --- |
| **CSV** | Exploiter dans un tableur les objets actuellement visibles et leur ordre de tri. |
| **JSON** | Exporter ou importer une collection structurée, médias inclus. |
| **`.mycollect`** | Transférer facilement une collection complète avec ses images et ses pièces jointes. |
| **PDF** | Créer une fiche A4 d’un objet avec ses données et ses photographies. |

Pour conserver une sauvegarde externe complète, utilisez régulièrement l’export `.mycollect` ou la commande **Créer une copie du fichier JSON**.

## Données et confidentialité

MyCollect fonctionne localement et ne nécessite aucun compte en ligne. Avec la version installée, les données sont enregistrées dans :

```text
%LOCALAPPDATA%\MyCollect\
```

Ce dossier contient notamment la base `collection_manager.json`, sa sauvegarde `.bak`, les images et les pièces jointes. Lors d’un lancement depuis les sources, les données sont conservées dans le dossier `data` du projet.

> [!IMPORTANT]
> Une sauvegarde automatique ne remplace pas une copie externe. Exportez régulièrement vos collections vers un autre emplacement.

## Raccourcis utiles

| Raccourci ou geste | Action |
| --- | --- |
| `F1` | Ouvrir l’aide intégrée. |
| `Ctrl` + clic | Sélectionner plusieurs objets. |
| `Ctrl` + `D` | Dupliquer la sélection. |
| `Suppr` | Placer la sélection dans la corbeille. |
| Double-clic | Ouvrir la fiche détaillée d’un objet. |
| Clic droit | Afficher les actions disponibles. |
| Clic sur un en-tête | Trier le tableau et inverser le tri. |

## Développement

### Technologies

- Python 3.11+
- PySide6 / Qt 6
- ReportLab pour les exports PDF
- PyInstaller pour la distribution Windows

## Aide et retours

L’aide complète est accessible à tout moment avec `F1`. Pour signaler un problème ou proposer une amélioration, [ouvrez une issue](../../issues).

## Licence

Copyright © 2026 Benjamin Lequeux. Tous droits réservés.

MyCollect peut être utilisé à titre personnel ou professionnel dans les conditions décrites par la licence. La redistribution commerciale, la vente et la publication d’une version modifiée nécessitent une autorisation écrite préalable.

---

<div align="center">

Développé par **Benjamin Lequeux**

</div>
