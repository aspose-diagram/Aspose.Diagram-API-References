---
title: DataRecordSet
second_title: Aspose.Diagram voor .NET API-referentie
description: Bewaart formatteert vernieuwt en stelt gegevens beschikbaar die worden opgevraagd uit een database in Microsoft Visio.
type: docs
weight: 1140
url: /nl/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Bewaart, formatteert, vernieuwt en stelt gegevens beschikbaar die worden opgevraagd uit een database in Microsoft Visio.

```csharp
public class DataRecordSet
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Aannemer. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Bevat XML die voldoet aan het klassieke ADO XML-schema voor een ADO-recordset en dat de gegevens in de datarecordset beschrijft. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Definieert een regel die een kolom in het bovenliggende DataRecordset-element vergelijkt met een vormgegevensitem van de laatste succesvolle automatische koppelingsactie die is uitgevoerd in de gebruikersinterface. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Een controlesomwaarde, gegenereerd door Visio en gebaseerd op eigenschappen van gegevensrecordsets. Zet dit attribuut op 0; Visio berekent deze waarde tijdens runtime opnieuw. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | De opdrachtreeks die wordt gebruikt om gegevens uit de gegevensbron op te vragen. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | De verbindings-ID voor het bijbehorende DataConnection-object. Bestaat niet voor XML-gegevensbronnen. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Bevat alle DataColumn-elementen in een gegevensrecordset. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | De gegevensrecordset-ID, uniek binnen het document. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | De weergegeven (of "vriendelijke") naam van de gegevensrecordset. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | De volgende beschikbare Visio-rij-ID. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Opties om toe te passen op de gegevensrecordset. Mogelijke waarden kunnen elke combinatie zijn van een of meer van de waarden die in de volgende tabel worden weergegeven. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Identificeert een of meer primaire-sleutelkolommen in de gegevensrecordset. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Geeft een rij in de datarecordset aan die is gekoppeld aan een vorm die in conflict is nadat de datarecordset is vernieuwd. RowID - Geeft een rij aan in de datarecordset die is gekoppeld aan een vorm die in conflict is nadat de datarecordset is vernieuwd. ShapeID - Vorm-ID van de vorm die betrokken is bij het conflict. PageID - Pagina-ID van de vorm die betrokken is bij het conflict. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Hoe vaak (in minuten) Visio de gegevensrecordset automatisch vernieuwt. Deze waarde moet 1 of groter zijn. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Of de gebruikersinterface voor gegevensafstemming moet worden uitgeschakeld. Waar (1) om de gebruikersinterface (UI) uit te schakelen. Onwaar (0) om de gebruikersinterface in te schakelen. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Of gebruikerswijzigingen aan vormgegevensitems in vormen die aan gegevens zijn gekoppeld, moeten worden overschreven wanneer de gegevensrecordset wordt vernieuwd. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Definieert hoe vormgegevenskoppelingen worden behandeld wanneer vormen worden gekopieerd of geknipt. 1 om bestaande links in de doelvorm te vervangen. 0 om bestaande links in de doelvorm te behouden. Als dit kenmerk ontbreekt, vraagt Visio de gebruiker of koppelingen bij kopiëren of knippen moeten worden vervangen. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Wijst een datarecordset-rij toe aan een vorm. RowID - Rij-ID van de rij, uniek binnen de datarecordset. ShapeID - Vorm-ID van de vorm gekoppeld aan gegevens in de datarecordsetrij geïdentificeerd door RowID. PageID - Pagina-ID van de shape die is gekoppeld aan gegevens in de datarecordsetrij geïdentificeerd door RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Of de volgorde van de rijen in de gegevensrecordset als primaire sleutel moet worden gebruikt. Waar (1) als rij-ID's worden bepaald door rijvolgorde. Onwaar (0) als rij-ID's worden bepaald door waarden in de primaire sleutelkolom(men) van de gegevensrecordset. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | De datum en tijd waarop de gegevensrecordset voor het laatst is vernieuwd. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Voert de querytekenreeks uit die is gekoppeld aan de verbonden (niet op XML gebaseerde) DataRecordset en werkt gekoppelde shapes bij met nieuwe gegevens uit de gegevensbron die door de query wordt geretourneerd. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Voert de querytekenreeks uit die is gekoppeld aan de verbonden (niet op XML gebaseerde) DataRecordset en werkt gekoppelde shapes bij met nieuwe gegevens uit de gegevensbron die door de query wordt geretourneerd. |

### Zie ook

* naamruimte [Aspose.Diagram](../../aspose.diagram/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
