---
title: SWFSaveOptions
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme au format SWF.
type: docs
weight: 3460
url: /fr/net/aspose.diagram.saving/swfsaveoptions/
---
## SWFSaveOptions class

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme au format SWF.

```csharp
public class SWFSaveOptions : SaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SWFSaveOptions](swfsaveoptions)() | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document dans le[`XPS`](../../aspose.diagram/savefileformat)format. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la valeur de police correcte ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de bloc dans pdf, image ou XPS. Définissez la police par défaut telle que MingLiu ou MS Gothic pour les afficher caractères. |
| [PageCount](../../aspose.diagram.saving/swfsaveoptions/pagecount) { get; set; } | Obtient ou définit le nombre de pages à rendre dans XPS. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues. |
| [PageIndex](../../aspose.diagram.saving/swfsaveoptions/pageindex) { get; set; } | Obtient ou définit l'index de base 0 de la première page à afficher. La valeur par défaut est 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/swfsaveoptions/saveforegroundpagesonly) { get; set; } | Spécifie si toutes les pages seront enregistrées en image ou uniquement au premier plan. |
| override [SaveFormat](../../aspose.diagram.saving/swfsaveoptions/saveformat) { get; set; } | Spécifie le format dans lequel les pages de diagramme rendues seront enregistrées si cet objet d'options d'enregistrement est utilisé. Peut être[`XPS`](../../aspose.diagram/savefileformat) seulement. |
| [ViewerIncluded](../../aspose.diagram.saving/swfsaveoptions/viewerincluded) { get; set; } | Spécifie si le document SWF généré doit inclure ou non la visionneuse de documents intégrée. La valeur par défaut est`vrai`. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Obtient ou définit un rappel d'avertissement. |

### Voir également

* class [SaveOptions](../saveoptions)
* espace de noms [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->