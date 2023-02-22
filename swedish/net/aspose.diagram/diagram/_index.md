---
title: Diagram
second_title: Aspose.Diagram för .NET API-referens
description: Rotelement i Visioobjekthierarkin.
type: docs
weight: 1170
url: /sv/net/aspose.diagram/diagram/
---
## Diagram class

Rotelement i Visio-objekthierarkin.

```csharp
public class Diagram : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Diagram](diagram/#constructor)() | Default_Constructor |
| [Diagram](diagram/#constructor_1)(Stream) | Public class constructor, laddar diagrammet från strömmen. |
| [Diagram](diagram/#constructor_4)(string) | Public class constructor, laddar diagrammet från filen. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Public class constructor, laddar diagrammet från strömmen med fördefinierat format. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Public class constructor, laddar diagrammet från strömmen med fördefinierade laddningsfilalternativ. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Public class constructor, laddar diagrammet från filen med fördefinierat format. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Public class constructor, laddar diagrammet från filen med fördefinierade laddningsfilalternativ. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Anger den aktiva sidan |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Byggnumret för Visio-instansen som användes för att skapa dokumentet. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Innehåller dokumentets färgtabell. Varje dokument innehåller en enfärgstabell, som listar de 24 standardfärgerna som är tillgängliga för applicering på objekt såsom former, text och lager i dokumentet. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Innehåller DataConnection-elementen för dokumentet. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | Samlingen av DataRecordset-objekt associerade med ett Document-objekt. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | Det unika ID:t för användargränssnittsspråket som användaren har angett i Microsoft Office 2010 Språkinställningar. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Innehåller dokumentegenskapselement som dokumentets titel, författare och så vidare. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Innehåller element som anger dokumentinställningar. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Anger ett dokuments ShapeSheet-struktur. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Innehåller en MIME (Multipurpose Internet Mail Extensions)-kodad MAPI-e-postdirigering för dokumentet. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Innehåller ett EventItem-element för varje händelse som ett objekt ska svara på. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Indikerar sökvägen till mappen Fonts |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Innehåller en samling teckensnittselement |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Innehåller element för ett dokuments sidhuvud och sidfot. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Hämtar och ställer in avbrottsmonitorn. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Indikerar om dokumentet har ändrats utanför Visio. Om det finns kommer Visio att testa innehållet i filen fullständigt. Uteslut för filer du skapar utanför Visio. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Samling Huvudobjekt. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Om metriska enheter ska användas i ritningen. Ställ in detta attribut till True (1) för att använda metriska enheter; ställ in den på False (0) för att använda engelska enheter. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Samlingssidans objekt. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | Ribbon XML-strängen som skickas till dokumentet för att anpassa menyfliksområdets användargränssnitt. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | XML-värde. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Indikerar om dokumentet har ändrats utanför Visio. Om det finns kommer Visio att testa innehållet i filen fullständigt. Uteslut för filer du skapar utanför Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Collection StyleSheet-objekt. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | Bandets XML-sträng som skickas till dokumentet för att anpassa verktygsfältet Snabbåtkomst eller menyfliksområdet. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Lagrar information om diagramvalidering för dokumentet. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Hämtar VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Innehåller Microsoft Visual Basic for Applications-projektdata i MIME (Multipurpose Internet Mail Extensions)-kodat format. |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Visio-instansens versionsnummer. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Innehåller Window-elementen för ett dokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Lägger till master till diagram från källdiagram efter masters namn eller NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Lägger till master till diagram från mallström efter masters ID. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Lägger till master till diagram från mallström efter masters namn eller NamnU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Lägger till master till diagram från mallfil efter masters ID. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Lägger till master till diagram från mallfil efter masters namn eller NamnU. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Lägger till form skapad av master till specifik sida. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Lägger till form skapad av master på sidan med definierade PinX och PinY. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Lägger till form skapad av master på sidan med definierade PinX, PinY, Width och Height. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Kombinerar ett annat Diagram-objekt. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Kopierar tema från ett källdiagram. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Hämta sökvägen för standardteckensnittsmappen |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Skaffa oanvända Styles |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Indikerar om detta diagram har dold information. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Lägger ut formerna och/eller dirigerar om kontakterna för alla sidor i diagrammet. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Skriver ut hela dokumentet till standardskrivaren. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Skriver ut dokumentet enligt de angivna skrivarinställningarna, med hjälp av standardutskriftskontrollern (utan användargränssnitt). |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Skriver ut hela dokumentet till standardskrivaren. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Skriv ut hela dokumentet till den angivna skrivaren, med standardutskriftskontrollern (inget användargränssnitt). |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Skriver ut dokumentet enligt de angivna skrivarinställningarna, med hjälp av standardutskriftskontrollern (utan användargränssnitt). |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Skriver ut dokumentet enligt de angivna skrivarinställningarna, med hjälp av standardutskriftskontrollern (inget användargränssnitt) och ett dokumentnamn. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Skriv ut hela dokumentet till den angivna skrivaren, med standardutskriftskontrollern (inget användargränssnitt). |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Skriver ut dokumentet med standardutskriftskontrollern (utan användargränssnitt) och ett dokumentnamn. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Skriver ut dokumentet enligt de angivna skrivarinställningarna, med hjälp av standardutskriftskontrollern (inget användargränssnitt) och ett dokumentnamn. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Skriver ut dokumentet med standardutskriftskontrollern (utan användargränssnitt) och ett dokumentnamn. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Anropar uppdateringsmetoden för alla DataRecordSet i diagrammet. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Ta bort oanvänd information |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Tar bort VBA/makro från detta diagram. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Sparar diagramdata i strömmen. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Sparar diagrammet i en ström med de angivna sparalternativen. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Sparar diagramdata i filen. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Sparar dokumentet till en fil med de angivna sparalternativen. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Exporterar diagrammet från vsd-ström till vdw-strömformat. Inte implementerat ännu. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Exporterar diagrammet från vsd-ström till *.vdw-filformat. Inte implementerat ännu. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Exporterar diagrammet från vsd-fil till vdw-strömformat. Inte implementerat ännu. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Exporterar diagrammet från vsd till vdw-format. Inte implementerat ännu. |

### Se även

* namnutrymme [Aspose.Diagram](../../aspose.diagram/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
