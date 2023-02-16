---
title: Diagram
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Élément racine de la hiérarchie des objets Visio.
type: docs
weight: 1170
url: /fr/net/aspose.diagram/diagram/
---
## Diagram class

Élément racine de la hiérarchie des objets Visio.

```csharp
public class Diagram : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Diagram](diagram/#constructor)() | Default_Constructor |
| [Diagram](diagram/#constructor_1)(Stream) | Constructeur de classe publique, charge le diagramme à partir du flux. |
| [Diagram](diagram/#constructor_4)(string) | Constructeur de classe publique, charge le diagramme à partir du fichier. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Constructeur de classe publique, charge le diagramme à partir du flux en utilisant un format prédéfini. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Constructeur de classe publique, charge le diagramme à partir du flux à l'aide d'options de fichier de chargement prédéfinies. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Constructeur de classe publique, charge le diagramme à partir du fichier en utilisant le format prédéfini. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Constructeur de classe publique, charge le diagramme à partir du fichier à l'aide d'options de fichier de chargement prédéfinies. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Spécifie la page active |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Le numéro de build de l'instance Visio utilisée pour créer le document. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Contient la table des couleurs du document. Chaque document contient une seule table de couleurs, qui répertorie les 24 couleurs standard disponibles pour l'application aux objets tels que les formes, le texte et les calques dans le document. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Contient les éléments DataConnection pour le document. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | La collection d'objets DataRecordset associés à un objet Document. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | L'ID unique de la langue de l'interface utilisateur que l'utilisateur a spécifiée dans les préférences linguistiques de Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Contient des éléments de propriété de document tels que le titre du document, l'auteur, etc. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Contient des éléments qui spécifient les paramètres du document. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Spécifie la structure ShapeSheet d'un document. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Contient un bordereau de routage de courrier électronique MAPI encodé MIME (Multipurpose Internet Mail Extensions) pour le document. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Contient un élément EventItem pour chaque événement auquel un objet doit répondre. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Indique le chemin du dossier des polices |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Contient une collection d'éléments de police |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Contient des éléments pour l'en-tête et le pied de page d'un document. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Obtient et définit le moniteur d'interruption. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Indique si le document a été modifié en dehors de Visio. S'il est présent, Visio testera entièrement le contenu du fichier. Omettre pour les fichiers que vous créez en dehors de Visio. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Objets maître de collection. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | S'il faut utiliser les unités métriques dans le dessin. Définissez cet attribut sur True (1) pour utiliser les unités métriques ; réglez-le sur False (0) pour utiliser les unités anglaises. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Objets de la page de collection. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | Chaîne XML du ruban transmise au document pour personnaliser l'interface utilisateur du ruban. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | valeur XML. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Indique si le document a été modifié en dehors de Visio. S'il est présent, Visio testera entièrement le contenu du fichier. Omettre pour les fichiers que vous créez en dehors de Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Collection d'objets StyleSheet. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | La chaîne XML du ruban transmise au document pour personnaliser la barre d'outils d'accès rapide ou le ruban. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Stocke des informations sur la validation du diagramme pour le document. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Obtient le VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Contient les données du projet Microsoft Visual Basic pour Applications au format codé MIME (Multipurpose Internet Mail Extensions). |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Le numéro de version de l'instance Visio. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Contient les éléments de fenêtre d'un document. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Ajoute le maître au diagramme à partir du diagramme source par le nom du maître ou le nomU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Ajoute le maître au diagramme à partir du flux de modèle par l'ID du maître. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Ajoute le maître au diagramme à partir du flux de modèle par le nom du maître ou le nomU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Ajoute le maître au diagramme à partir du fichier de modèle par l'ID du maître. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Ajoute le maître au diagramme à partir du fichier de modèle par le nom du maître ou le nomU. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Ajoute la forme créée par le maître à une page spécifique. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Ajoute la forme créée par le maître sur la page avec PinX et PinY définis. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Ajoute la forme créée par le maître sur la page avec PinX, PinY, Largeur et Hauteur définis. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Combine un autre objet Diagramme. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Copie le thème d'un diagramme source. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Obtenir le chemin du dossier des polices par défaut |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Obtenir les styles inutilisés |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Indique si ce diagramme contient des informations masquées. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Présente les formes et/ou redirige les connecteurs pour toutes les pages du diagramme. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Imprime tout le document sur l'imprimante par défaut. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Imprime le document conformément aux paramètres d'imprimante spécifiés, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Imprime tout le document sur l'imprimante par défaut. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Imprimez l'intégralité du document sur l'imprimante spécifiée, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Imprime le document conformément aux paramètres d'imprimante spécifiés, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Imprime le document en fonction des paramètres d'imprimante spécifiés, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur) et d'un nom de document. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Imprimez l'intégralité du document sur l'imprimante spécifiée, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur). |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Imprime le document à l'aide du contrôleur d'impression standard (pas d'interface utilisateur) et d'un nom de document. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Imprime le document en fonction des paramètres d'imprimante spécifiés, à l'aide du contrôleur d'impression standard (pas d'interface utilisateur) et d'un nom de document. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Imprime le document à l'aide du contrôleur d'impression standard (pas d'interface utilisateur) et d'un nom de document. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Invoque la méthode Refresh pour tous les DataRecordSet du diagramme. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Supprimer les informations inutilisées |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Supprime VBA/macro de ce diagramme. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Enregistre les données du diagramme dans le flux. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Enregistre le diagramme dans un flux à l'aide des options d'enregistrement spécifiées. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Enregistre les données du diagramme dans le fichier. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Enregistre le document dans un fichier à l'aide des options d'enregistrement spécifiées. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Exporte le diagramme du flux vsd au format de flux vdw. Pas encore implémenté. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Exporte le diagramme du flux vsd au format de fichier *.vdw. Pas encore implémenté. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Exporte le diagramme du fichier vsd au format de flux vdw. Pas encore implémenté. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Exporte le diagramme du format vsd au format vdw. Pas encore implémenté. |

### Voir également

* espace de noms [Aspose.Diagram](../../aspose.diagram/)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
