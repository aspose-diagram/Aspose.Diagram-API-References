---
title: GluedShapesFlags
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Spécifie les constantes qui identifient les formes à renvoyer en fonction de la dimensionnalité et de la directionnalité des points de connexion collés à une forme particulière  passé à la méthode Shape.GluedShapes.
type: docs
weight: 1710
url: /fr/net/aspose.diagram/gluedshapesflags/
---
## GluedShapesFlags enumeration

Spécifie les constantes qui identifient les formes à renvoyer, en fonction de la dimensionnalité et de la directionnalité des points de connexion collés à une forme particulière ; passé à la méthode Shape.GluedShapes.

```csharp
public enum GluedShapesFlags
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| GluedShapesAll1D | `0` | Renvoie les ID de toutes les formes 1-D qui sont collées à cette forme. |
| GluedShapesIncoming1D | `1` | Renvoie les ID des formes 1-D dont les extrémités sont collées à cette forme. |
| GluedShapesOutgoing1D | `2` | Renvoie les ID des formes 1D dont les points de départ sont collés à cette forme. |
| GluedShapesAll2D | `3` | Renvoie toutes les formes 2D qui sont collées à cette forme et toutes les formes 2D auxquelles cette forme est collée. |
| GluedShapesIncoming2D | `4` | Si l'objet source est une forme 1D, renvoie les ID de la forme 2D à laquelle le point de départ est collé. Si l'objet source est une forme 2D, renvoie les ID des formes 2D collées à cette forme. |
| GluedShapesOutgoing2D | `5` | Si l'objet source est une forme 1D, renvoie les ID de la forme 2D à laquelle le point final est collé. Si l'objet source est une forme 2D, renvoie les ID des formes 2D auxquelles cette forme est collée. |

### Voir également

* espace de noms [Aspose.Diagram](../../aspose.diagram)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->