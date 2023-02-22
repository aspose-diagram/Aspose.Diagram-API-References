---
title: DataRecordSet
second_title: Aspose.Diagram för .NET API-referens
description: Lagrar formaterar uppdaterar och exponerar data som efterfrågas från en databas i Microsoft Visio.
type: docs
weight: 1140
url: /sv/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Lagrar, formaterar, uppdaterar och exponerar data som efterfrågas från en databas i Microsoft Visio.

```csharp
public class DataRecordSet
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Konstruktör. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Innehåller XML som överensstämmer med ADOs klassiska XML-schema för en ADO-postuppsättning och som beskriver data i datapostuppsättningen. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Definierar en regel som jämför en kolumn i det överordnade DataRecordset-elementet med ett formdataobjekt från den senaste framgångsrika automatiska länkningsåtgärden som utfördes i användargränssnittet. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Ett kontrollsummavärde, genererat av Visio och baserat på data-postuppsättningsegenskaper. Sätt detta attribut till 0; Visio beräknar om detta värde vid körning. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | Kommandosträngen som används för att fråga data från datakällan. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | Anslutnings-ID för det associerade DataConnection-objektet. Finns inte för XML-datakällor. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Innehåller alla DataColumn-element i en datapostuppsättning. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | Datapostuppsättningens ID, unikt i dokumentet. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | Visningsnamnet (eller "vänligt") namn på datapostuppsättningen. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | Nästa tillgängliga Visio-rad-ID. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Alternativ att tillämpa på datapostuppsättningen. Möjliga värden kan vara valfri kombination av en eller flera av de som visas i följande tabell. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Identifierar en eller flera primärnyckelkolumner i datapostuppsättningen. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Indikerar en rad i datapostuppsättningen kopplad till en form som är i konflikt efter att datapostuppsättningen har uppdaterats. RowID - Indikerar en rad i datapostuppsättningen länkad till en form som är i konflikt efter att datapostuppsättningen har uppdaterats. ShapeID - Form-ID för formen som är involverad i konflikten. Sid-ID - Sid-ID för formen som är involverad i konflikten. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Hur ofta (i minuter) Visio uppdaterar datapostuppsättningen automatiskt. Detta värde måste vara 1 eller större. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Om användargränssnittet för dataavstämning ska inaktiveras. True (1) för att inaktivera användargränssnittet (UI). False (0) för att aktivera UI. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Om användarändringar i formdataobjekt ska skrivas över i former kopplade till data när datapostuppsättningen uppdateras. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Definierar hur form-datalänkar behandlas när former kopieras eller klipps ut. 1 för att ersätta befintliga länkar i målformen. 0 för att behålla befintliga länkar i målformen. Om detta attribut saknas frågar Visio användaren om länkar ska ersättas vid kopiering eller klippning. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Mappar en datauppsättningsrad till en form. RadID - Rad-ID för raden, unikt inom datapostuppsättningen. ShapeID - Form-ID för formen kopplad till data i datapostuppsättningsraden identifierad av RowID. PageID - Sid-ID för formen som är länkad till data i dataregistreringsraden identifierad av RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Om ordningen på raderna i datapostmängden ska användas som primärnyckel. Sant (1) om rad-ID:n bestäms av radordning. False (0) om rad-ID:n bestäms av värden i primärnyckelkolumnen/-kolumnerna i datapostuppsättningen. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | Datum och tid då datapostuppsättningen senast uppdaterades. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Kör frågesträngen som är associerad med den anslutna (icke-XML-baserade) DataRecordset och uppdaterar länkade former med ny data från datakällan som returneras av frågan. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Kör frågesträngen som är associerad med den anslutna (icke-XML-baserade) DataRecordset och uppdaterar länkade former med ny data från datakällan som returneras av frågan. |

### Se även

* namnutrymme [Aspose.Diagram](../../aspose.diagram/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
