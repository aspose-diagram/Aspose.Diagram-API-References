---
title: GluedShapes
second_title: Aspose.Diagram för .NET API-referens
description: Returnerar en array som innehåller identifierarna för de former som är limmade på en form.
type: docs
weight: 820
url: /sv/net/aspose.diagram/shape/gluedshapes/
---
## Shape.GluedShapes method

Returnerar en array som innehåller identifierarna för de former som är limmade på en form.

```csharp
public long[] GluedShapes(GluedShapesFlags flag, string categoryFilter, Shape otherShape)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flag | GluedShapesFlags | Dimensionaliteten och riktningen för anslutningspunkterna för de former som ska återvändas. Se Anmärkningar för möjliga värden[`GluedShapesFlags`](../../gluedshapesflags/). |
| categoryFilter | String | Filtrerar matrisen av returnerade form-ID:n genom att begränsa den till ID:n för former som matchar den angivna kategorinString. |
| otherShape | Shape | Valfritt: ytterligare form som returnerade former också måste limmas till, kan vara[`Shape`](../) eller null. |

### Returvärde

ID-arrayInt64.

### Se även

* enum [GluedShapesFlags](../../gluedshapesflags/)
* class [Shape](../)
* namnutrymme [Aspose.Diagram](../../shape/)
* hopsättning [Aspose.Diagram](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
