---
title: Window
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Représente une fenêtre ouverte dans une instance de Microsoft Visio. Cet élément contient les informations nécessaires pour recréer exactement une fenêtre dinterface utilisateur dans lespace de travail de lapplication lorsque le fichier DatadiagramML est initialement ouvert par Visio.
type: docs
weight: 4390
url: /fr/net/aspose.diagram/window/
---
## Window class

Représente une fenêtre ouverte dans une instance de Microsoft Visio. Cet élément contient les informations nécessaires pour recréer exactement une fenêtre d'interface utilisateur dans l'espace de travail de l'application lorsque le fichier DatadiagramML est initialement ouvert par Visio.

```csharp
public class Window
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Window](window/)() | Constructeur. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | ID du conteneur : page, feuille ou masque. Uniquement pertinent et nécessaire si ContainerType est spécifié. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Peut être l'une des valeurs suivantes : Document, Page ou Master. Pertinent uniquement lorsque WindowType est spécifié en tant que Drawing ou Sheet. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Chemin du fichier du document affiché dans cette fenêtre. Cet attribut est pertinent pour les fenêtres dont WindowType est spécifié comme Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Spécifie si la fonction de grille dynamique est activée pour un document ou une fenêtre. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Spécifie les objets sur lesquels coller les formes lorsque le collage est activé dans le document. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | L'identifiant unique de l'élément dans son élément parent. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | Master ID si cette fenêtre affiche un master. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | ID de page si cette fenêtre affiche une page. Pertinent uniquement lorsque WindowType est spécifié en tant que Drawing et ContainerType est spécifié en tant que Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | ID de la fenêtre dans laquelle cette fenêtre de gabarit est contenue. Pertinent uniquement lorsque WindowType est spécifié comme Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Indicateur de lecture seule si ce gabarit n'est pas un gabarit de document. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | ID de la feuille dans le conteneur. Pertinent uniquement lorsque Container est spécifié en tant que Sheet. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Spécifie si les points de connexion sont affichés dans une fenêtre. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Spécifie si une grille est affichée dans la fenêtre de dessin. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Spécifie si les repères sont affichés dans la fenêtre de dessin. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Spécifie si les sauts de page sont affichés dans une fenêtre. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Spécifie si les règles sont affichées dans la fenêtre de dessin. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Contient une collection d'éléments SnapAngle. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Spécifie si un paramètre d'extension d'accrochage spécifique est activé ou désactivé pour la fenêtre active. La valeur peut être une somme des valeurs du tableau suivant. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Spécifie les objets auxquels les formes s'accrochent lorsque l'accrochage est actif dans la fenêtre. La valeur peut être une somme des valeurs du tableau suivant. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Spécifie le groupe de fenêtres stencil fusionnées dont la fenêtre est membre. Cet attribut n'est pertinent que pour les éléments Window dont l'attribut WindowType est Stencil, et uniquement si la fenêtre stencil fait partie d'un groupe fusionné de fenêtres stencil. Toutes les fenêtres de gabarit qui font partie du même groupe fusionné ont la même valeur d'élément StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Contient un entier qui spécifie la position relative d'un gabarit dans un groupe dans une fenêtre. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Spécifie la largeur du contrôle d'onglet de page d'une fenêtre de dessin (en tant que fraction de la largeur totale de la fenêtre de dessin). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Double en option. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Double en option. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Double en option. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Hauteur du rectangle de la fenêtre. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Coordonnée gauche du rectangle de la fenêtre. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Cet attribut peut être une somme des valeurs suivantes. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Coordonnée supérieure du rectangle de la fenêtre. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Une valeur énumérée qui peut être l'une des suivantes : Drawing, Sheet, Stencil ou Icon.Un élément Window de WindowType='Stencil' doit apparaître après sa fenêtre de dessin parente (WindowType='Drawing') et avant toute autre fenêtre de dessin éléments. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Largeur du rectangle de la fenêtre. |

### Voir également

* espace de noms [Aspose.Diagram](../../aspose.diagram/)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
