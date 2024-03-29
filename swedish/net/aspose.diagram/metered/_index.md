---
title: Metered
second_title: Aspose.Diagram för .NET API-referens
description: Tillhandahåller metoder för att ställa in mätnyckel.
type: docs
weight: 2340
url: /sv/net/aspose.diagram/metered/
---
## Metered class

Tillhandahåller metoder för att ställa in mätnyckel.

```csharp
public class Metered
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Metered](metered/)() | Initierar en ny instans av den här klassen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetMeteredKey](../../aspose.diagram/metered/setmeteredkey/)(string, string) | Ställer in mätt offentlig och privat nyckel. Om du köper mätlicens, när du startar applikationen, bör detta API anropas, normalt räcker detta. Men om alltid misslyckas med att ladda upp förbrukningsdata och överskrider 24 timmar, kommer licensen att ställas in på utvärderingsstatus, för att undvika sådana fall bör du regelbundet kontrollera licensstatusen, om det är utvärderingsstatus, ring detta API igen. |
| static [GetConsumptionCredit](../../aspose.diagram/metered/getconsumptioncredit/)() | Får konsumtionskredit |
| static [GetConsumptionQuantity](../../aspose.diagram/metered/getconsumptionquantity/)() | Får förbrukningsfilstorlek |

### Exempel

I det här exemplet kommer ett försök att göras att ställa in mätt offentlig och privat nyckel

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

komponentjarfilen:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Se även

* namnutrymme [Aspose.Diagram](../../aspose.diagram/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
