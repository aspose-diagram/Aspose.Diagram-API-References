---
title: Diagram
second_title: Aspose.Diagram voor .NET API-referentie
description: Hoofdelement van Visioobjecthiërarchie.
type: docs
weight: 1170
url: /nl/net/aspose.diagram/diagram/
---
## Diagram class

Hoofdelement van Visio-objecthiërarchie.

```csharp
public class Diagram : IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Diagram](diagram/#constructor)() | De standaard constructeur. |
| [Diagram](diagram/#constructor_1)(Stream) | Constructor van de openbare klasse, laadt het diagram uit de stream. |
| [Diagram](diagram/#constructor_4)(string) | Public class constructor, laadt het diagram uit het bestand. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Constructor van openbare klasse, laadt het diagram uit de stream met behulp van een vooraf gedefinieerd formaat. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Constructor van de openbare klasse, laadt het diagram uit de stream met behulp van vooraf gedefinieerde laadbestandsopties. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Constructor van openbare klasse, laadt het diagram uit het bestand met behulp van een vooraf gedefinieerd formaat. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Constructor van openbare klasse, laadt het diagram uit het bestand met behulp van vooraf gedefinieerde laadbestandsopties. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Specificeert de actieve pagina |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Het buildnummer van de Visio-instantie die is gebruikt om het document te maken. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Bevat de kleurentabel van het document. Elk document bevat een enkele kleurentabel, , die de 24 standaardkleuren vermeldt die beschikbaar zijn voor toepassing op objecten zoals vormen, tekst en lagen in het document. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Bevat de DataConnection-elementen voor het document. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | De verzameling DataRecordset-objecten die zijn gekoppeld aan een Document-object. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | De unieke ID van de gebruikersinterfacetaal die de gebruiker heeft opgegeven in Microsoft Office 2010 Taalvoorkeuren. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Bevat documenteigenschapselementen zoals de titel van het document, auteur, enzovoort. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Bevat elementen die documentinstellingen specificeren. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Specificeert de ShapeSheet-structuur van een document. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde MAPI e-mailrouteringsbon voor het document. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Bevat een EventItem-element voor elke gebeurtenis waarop een object moet reageren. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Geeft het pad naar de map Fonts aan |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Bevat een verzameling lettertype-elementen |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Bevat elementen voor de kop- en voettekst van een document. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Haalt de interruptmonitor op en stelt deze in. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Geeft aan of het document buiten Visio is gewijzigd. Indien aanwezig, zal Visio de inhoud van het bestand volledig testen. Weglaten voor bestanden die u buiten Visio maakt. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Collectie Master-objecten. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Of metrische eenheden in de tekening moeten worden gebruikt. Stel dit attribuut in op True (1) om metrische eenheden te gebruiken; stel deze in op False (0) om Engelse eenheden te gebruiken. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Verzamelpagina-objecten. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | De lint-XML-tekenreeks die wordt doorgegeven aan het document om de lintgebruikersinterface aan te passen. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | XML-waarde. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Geeft aan of het document buiten Visio is gewijzigd. Indien aanwezig, zal Visio de inhoud van het bestand volledig testen. Weglaten voor bestanden die u buiten Visio maakt. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Collectie StyleSheet-objecten. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | De lint-XML-tekenreeks die wordt doorgegeven aan het document om de werkbalk Snelle toegang of het lint aan te passen. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Slaat informatie op over diagramvalidatie voor het document. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Haalt het VbaProject op[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Bevat de projectgegevens van Microsoft Visual Basic for Applications in MIME-gecodeerde indeling (Multipurpose Internet Mail Extensions). |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Het versienummer van de Visio-instantie. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Bevat de vensterelementen voor een document. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Voegt master toe aan diagram vanuit brondiagram op master's Name of NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Voegt master toe aan diagram van sjabloonstroom door master's ID. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Voegt master toe aan diagram vanuit sjabloonstroom door Master's Name of NameU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Voegt master toe aan diagram vanuit sjabloonbestand door master's ID. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Voegt master toe aan diagram vanuit sjabloonbestand op master's Name of NameU. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Voegt door master gemaakte vorm toe aan specifieke pagina. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Voegt vorm toe gemaakt door master op pagina met gedefinieerde PinX en PinY. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Voegt een door de master gemaakte vorm toe aan de pagina met gedefinieerde PinX,PinY,Width en Height. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Combineert een ander Diagram-object. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Kopieert thema van een brondiagram. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Haal het pad naar de standaardlettertypenmap op |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Ontvang ongebruikte stijlen |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Geeft aan of dit diagram verborgen informatie bevat. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Legt de vormen uit en/of herleidt de connectoren voor alle pagina's van het diagram. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Drukt het hele document af op de standaardprinter. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Drukt het document af volgens de gespecificeerde printerinstellingen, met behulp van de standaard (geen gebruikersinterface) printcontroller. |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Drukt het hele document af op de standaardprinter. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Print het hele document naar de gespecificeerde printer, met behulp van de standaard (geen gebruikersinterface) printcontroller. |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Drukt het document af volgens de gespecificeerde printerinstellingen, met behulp van de standaard (geen gebruikersinterface) printcontroller. |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Drukt het document af volgens de opgegeven printerinstellingen, met behulp van de standaard (geen gebruikersinterface) printcontroller en een documentnaam. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Print het hele document naar de gespecificeerde printer, met behulp van de standaard (geen gebruikersinterface) printcontroller. |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Drukt het document af met behulp van de standaard (geen gebruikersinterface) printcontroller en een documentnaam. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Drukt het document af volgens de opgegeven printerinstellingen, met behulp van de standaard (geen gebruikersinterface) printcontroller en een documentnaam. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Drukt het document af met behulp van de standaard (geen gebruikersinterface) printcontroller en een documentnaam. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Roept Refresh-methode op voor alle DataRecordSet in het diagram. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Ongebruikte informatie verwijderen |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Verwijdert VBA/macro uit dit diagram. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Slaat de diagramgegevens op in de stream. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Slaat het diagram op in een stream met behulp van de opgegeven opslagopties. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Slaat de diagramgegevens op in het bestand. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Slaat het document op in een bestand met de opgegeven opslagopties. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Exporteert het diagram van vsd stream naar vdw stream formaat. Nog niet geïmplementeerd. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Exporteert het diagram van vsd stream naar *.vdw bestandsformaat. Nog niet geïmplementeerd. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Exporteert het diagram van vsd-bestand naar vdw-streamformaat. Nog niet geïmplementeerd. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Exporteert het diagram van vsd naar vdw formaat. Nog niet geïmplementeerd. |

### Zie ook

* naamruimte [Aspose.Diagram](../../aspose.diagram/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
