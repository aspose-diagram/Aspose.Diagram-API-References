---
title: DataRecordSet
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Stocke formate actualise et expose les données interrogées à partir dune base de données dans Microsoft Visio.
type: docs
weight: 1120
url: /fr/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Stocke, formate, actualise et expose les données interrogées à partir d'une base de données dans Microsoft Visio.

```csharp
public class DataRecordSet
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DataRecordSet](datarecordset)() | Constructeur. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata) { get; set; } | Contient du XML conforme au schéma XML classique ADO pour un jeu d'enregistrements ADO et qui décrit les données du jeu d'enregistrements de données. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison) { get; } | Définit une règle qui compare une colonne dans l'élément DataRecordset parent avec un élément de données de forme de la dernière action de liaison automatique réussie effectuée dans l'interface utilisateur. |
| [Checksum](../../aspose.diagram/datarecordset/checksum) { get; set; } | Une valeur de somme de contrôle, générée par Visio et basée sur les propriétés du jeu d'enregistrements de données. Définissez cet attribut sur 0 ; Visio recalcule cette valeur lors de l'exécution. |
| [Command](../../aspose.diagram/datarecordset/command) { get; set; } | La chaîne de commande utilisée pour interroger les données de la source de données. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid) { get; set; } | ID de connexion pour l'objet DataConnection associé. N'existe pas pour les sources de données XML. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns) { get; } | Contient tous les éléments DataColumn d'un jeu d'enregistrements de données. |
| [ID](../../aspose.diagram/datarecordset/id) { get; set; } | ID du jeu d'enregistrements de données, unique dans le document. |
| [Name](../../aspose.diagram/datarecordset/name) { get; set; } | Le nom d'affichage (ou "convivial") du jeu d'enregistrements de données. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid) { get; set; } | Le prochain ID de ligne Visio disponible. |
| [Options](../../aspose.diagram/datarecordset/options) { get; set; } | Options à appliquer au jeu d'enregistrements de données. Les valeurs possibles peuvent être n'importe quelle combinaison d'une ou plusieurs de celles indiquées dans le tableau suivant. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys) { get; } | Identifie une ou plusieurs colonnes de clé primaire dans le jeu d'enregistrements de données. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts) { get; } | Indique une ligne dans le jeu d'enregistrements de données lié à une forme qui est en conflit après l'actualisation du jeu d'enregistrements de données. RowID - Indique une ligne dans le jeu d'enregistrements de données lié à une forme qui est en conflit après l'actualisation du jeu d'enregistrements de données. ShapeID - ID de forme de la forme impliquée dans le conflit. PageID - ID de page de la forme impliquée dans le conflit. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval) { get; set; } | Fréquence (en minutes) à laquelle Visio actualise automatiquement le jeu d'enregistrements de données. Cette valeur doit être supérieure ou égale à 1. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui) { get; set; } | Indique si l'interface utilisateur de rapprochement des données doit être désactivée. True (1) pour désactiver l'interface utilisateur (UI). Faux (0) pour activer l'interface utilisateur. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall) { get; set; } | Indique s'il faut remplacer les modifications apportées par l'utilisateur aux éléments de données de forme dans les formes liées aux données lorsque le jeu d'enregistrements de données est actualisé. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks) { get; set; } | Définit la façon dont les liens de données de forme sont traités lorsque les formes sont copiées ou coupées. 1 pour remplacer les liens existants dans la forme cible. 0 pour conserver les liens existants dans la forme cible. Si cet attribut est absent, Visio demande à l'utilisateur s'il faut remplacer les liens lors de la copie ou de la coupe. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps) { get; } | Mappe une ligne du jeu d'enregistrements de données à une forme. RowID - ID de ligne de la ligne, unique dans le jeu d'enregistrements de données. ShapeID - ID de forme de la forme liée aux données dans la ligne du jeu d'enregistrements de données identifiée par RowID. PageID - ID de page de la forme liée aux données dans la ligne du jeu d'enregistrements de données identifiée par RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder) { get; set; } | S'il faut utiliser l'ordre des lignes dans le jeu d'enregistrements de données comme clé primaire. Vrai (1) si les ID de ligne sont déterminés par l'ordre des lignes. False (0) si les ID de ligne sont déterminés par des valeurs dans la ou les colonnes de clé primaire du jeu d'enregistrements de données. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed) { get; set; } | Date et heure de la dernière actualisation du jeu d'enregistrements de données. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh#refresh)() | Exécute la chaîne de requête associée au DataRecordset connecté (non basé sur XML) et met à jour les formes liées avec les nouvelles données de la source de données renvoyées par la requête. |
| [Refresh](../../aspose.diagram/datarecordset/refresh#refresh_1)(DataConnectionType) | Exécute la chaîne de requête associée au DataRecordset connecté (non basé sur XML) et met à jour les formes liées avec les nouvelles données de la source de données renvoyées par la requête. |

### Voir également

* espace de noms [Aspose.Diagram](../../aspose.diagram)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
