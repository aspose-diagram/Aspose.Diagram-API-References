---
title: GluedShapes
second_title: Aspose.Diagram für .NET-API-Referenz
description: Gibt ein Array zurück das die Kennungen der Formen enthält die an eine Form geklebt werden.
type: docs
weight: 780
url: /de/net/aspose.diagram/shape/gluedshapes/
---
## Shape.GluedShapes method

Gibt ein Array zurück, das die Kennungen der Formen enthält, die an eine Form geklebt werden.

```csharp
public long[] GluedShapes(GluedShapesFlags flag, string categoryFilter, Shape otherShape)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| flag | GluedShapesFlags | Die Dimensionalität und Richtung der Verbindungspunkte der zurückzugebenden Formen. Siehe Hinweise für mögliche Werte[`GluedShapesFlags`](../../gluedshapesflags). |
| categoryFilter | String | Filtert das Array der zurückgegebenen Shape-IDs, indem es auf die IDs von Shapes beschränkt wird, die der angegebenen Kategorie entsprechenString. |
| otherShape | Shape | Optional: Zusätzliche Form, an die auch zurückgegebene Formen geklebt werden müssen, kann sein[`Shape`](../../shape) oder null. |

### Rückgabewert

IDs-ArrayInt64.

### Siehe auch

* enum [GluedShapesFlags](../../gluedshapesflags)
* class [Shape](../../shape)
* namensraum [Aspose.Diagram](../../shape)
* Montage [Aspose.Diagram](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->