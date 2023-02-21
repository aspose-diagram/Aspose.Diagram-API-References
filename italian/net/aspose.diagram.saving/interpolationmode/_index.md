---
title: InterpolationMode
second_title: Aspose.Diagram per riferimento API .NET
description: Lenumerazione InterpolationMode specifica lalgoritmo utilizzato quando le immagini vengono ridimensionate o ruotate.
type: docs
weight: 3290
url: /it/net/aspose.diagram.saving/interpolationmode/
---
## InterpolationMode enumeration

L'enumerazione InterpolationMode specifica l'algoritmo utilizzato quando le immagini vengono ridimensionate o ruotate.

```csharp
public enum InterpolationMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Invalid | `-1` | Equivalente all'elemento Invalid dell'enumerazione QualityMode. |
| Default | `0` | Specifica la modalità predefinita. |
| Low | `1` | Specifica l'interpolazione di bassa qualità. |
| High | `2` | Specifica l'interpolazione di alta qualità. |
| Bilinear | `3` | Specifica l'interpolazione bilineare. Non viene eseguito alcun prefiltro. Questa modalità non è adatta per ridurre un'immagine al di sotto del 50 percento della sua dimensione originale. |
| Bicubic | `4` | Specifica l'interpolazione bicubica. Non viene eseguito alcun prefiltro. Questa modalità non è adatta per ridurre un'immagine al di sotto del 25 percento rispetto alle dimensioni originali. |
| NearestNeighbor | `5` | Specifica l'interpolazione del vicino più prossimo. |
| HighQualityBilinear | `6` | Specifica l'interpolazione bilineare di alta qualità. Il prefiltraggio viene eseguito per garantire una termoretrazione di alta qualità. |
| HighQualityBicubic | `7` | Specifica l'interpolazione bicubica di alta qualità. Il prefiltraggio viene eseguito per garantire una termoretrazione di alta qualità. Questa modalità produce immagini trasformate della massima qualità. |

### Guarda anche

* spazio dei nomi [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->