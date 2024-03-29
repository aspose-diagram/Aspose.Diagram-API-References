---
title: Metered
second_title: Aspose.Diagram voor .NET API-referentie
description: Biedt methoden om gemeten sleutel in te stellen.
type: docs
weight: 2340
url: /nl/net/aspose.diagram/metered/
---
## Metered class

Biedt methoden om gemeten sleutel in te stellen.

```csharp
public class Metered
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered/)() | Initialiseert een nieuwe instantie van deze klasse. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [SetMeteredKey](../../aspose.diagram/metered/setmeteredkey/)(string, string) | Stelt gemeten publieke en private sleutel in. Als u een gemeten licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen, normaal gesproken is dit voldoende. Als het echter altijd niet lukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie ingesteld op de evaluatiestatus. Om dit te voorkomen, moet u regelmatig de licentiestatus controleren. Als het de evaluatiestatus is, roept u deze API opnieuw op. |
| static [GetConsumptionCredit](../../aspose.diagram/metered/getconsumptioncredit/)() | Krijgt consumptietegoed |
| static [GetConsumptionQuantity](../../aspose.diagram/metered/getconsumptionquantity/)() | Krijgt verbruiksbestandsgrootte |

### Voorbeelden

In dit voorbeeld wordt geprobeerd een gemeten openbare en privésleutel in te stellen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

het component jar-bestand:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Zie ook

* naamruimte [Aspose.Diagram](../../aspose.diagram/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
