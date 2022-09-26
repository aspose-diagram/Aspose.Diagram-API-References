---
title: Diagram
second_title: Aspose.Diagram für .NET-API-Referenz
description: Stammelement der VisioObjekthierarchie.
type: docs
weight: 1150
url: /de/net/aspose.diagram/diagram/
---
## Diagram class

Stammelement der Visio-Objekthierarchie.

```csharp
public class Diagram : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Diagram](diagram#constructor)() | Default_Constructor |
| [Diagram](diagram#constructor_1)(Stream) | ÖffentlichDiagram Klassenkonstruktor, lädt das Diagramm aus dem Stream. |
| [Diagram](diagram#constructor_4)(string) | ÖffentlichDiagram Klassenkonstruktor, lädt das Diagramm aus der Datei. |
| [Diagram](diagram#constructor_2)(Stream, LoadFileFormat) | ÖffentlichDiagram Klassenkonstruktor, lädt das Diagramm aus dem Stream unter Verwendung des vordefinierten Formats. |
| [Diagram](diagram#constructor_3)(Stream, LoadOptions) | ÖffentlichDiagram Klassenkonstruktor, lädt das Diagramm aus dem Stream unter Verwendung vordefinierter Ladedateioptionen. |
| [Diagram](diagram#constructor_5)(string, LoadFileFormat) | ÖffentlichDiagramKlassenkonstruktor, lädt das Diagramm aus der Datei unter Verwendung des vordefinierten Formats. |
| [Diagram](diagram#constructor_6)(string, LoadOptions) | ÖffentlichDiagram Klassenkonstruktor, lädt das Diagramm aus der Datei unter Verwendung vordefinierter Ladedateioptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage) { get; } | Gibt die aktive Seite an |
| [Buildnum](../../aspose.diagram/diagram/buildnum) { get; set; } | Die Build-Nummer der Visio-Instanz, die zum Erstellen des Dokuments verwendet wurde. |
| [Colors](../../aspose.diagram/diagram/colors) { get; } | Enthält die Farbtabelle des Dokuments. Jedes Dokument enthält eine einzige Farbtabelle, , die die 24 Standardfarben auflistet, die für die Anwendung auf Objekte wie Formen, Text und Ebenen im Dokument verfügbar sind. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections) { get; } | Enthält die DataConnection-Elemente für das Dokument. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets) { get; } | Die Sammlung von DataRecordset-Objekten, die einem Document-Objekt zugeordnet sind. |
| [DocLangID](../../aspose.diagram/diagram/doclangid) { get; set; } | Die eindeutige ID der Sprache der Benutzeroberfläche, die der Benutzer in den Spracheinstellungen von Microsoft Office 2010 angegeben hat. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops) { get; } | Enthält Dokumenteigenschaftselemente wie Titel, Autor usw. des Dokuments. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings) { get; } | Enthält Elemente, die Dokumenteinstellungen angeben. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet) { get; } | Gibt die ShapeSheet-Struktur eines Dokuments an. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata) { get; set; } | Enthält einen MIME (Multipurpose Internet Mail Extensions)-codierten MAPI-E-Mail-Routing-Verteiler für das Dokument. |
| [EventItems](../../aspose.diagram/diagram/eventitems) { get; } | Enthält ein EventItem-Element für jedes Ereignis, auf das ein Objekt reagieren soll. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs) { set; } | Gibt den Pfad des Schriftordners an |
| [Fonts](../../aspose.diagram/diagram/fonts) { get; } | Enthält eine Sammlung von Schriftelementen |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter) { get; } | Enthält Elemente für die Kopf- und Fußzeile eines Dokuments. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor) { get; set; } | Holt und setzt den Interrupt-Monitor. |
| [Key](../../aspose.diagram/diagram/key) { get; set; } | Gibt an, ob das Dokument außerhalb von Visio geändert wurde. Falls vorhanden, testet Visio den Inhalt der Datei vollständig. Für Dateien weglassen, die Sie außerhalb von Visio erstellen. |
| [Masters](../../aspose.diagram/diagram/masters) { get; } | Collection Master-Objekte. |
| [Metric](../../aspose.diagram/diagram/metric) { get; set; } | Ob metrische Einheiten in der Zeichnung verwendet werden sollen. Setzen Sie dieses Attribut auf True (1), um metrische Einheiten zu verwenden; Setzen Sie es auf False (0), um englische Einheiten zu verwenden. |
| [Pages](../../aspose.diagram/diagram/pages) { get; } | Sammlungsseitenobjekte. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx) { get; set; } | Die Ribbon-XML-Zeichenfolge, die an das Dokument übergeben wird, um die Ribbon-Benutzeroberfläche anzupassen. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls) { get; } | XML-Wert. |
| [Start](../../aspose.diagram/diagram/start) { get; set; } | Gibt an, ob das Dokument außerhalb von Visio geändert wurde. Falls vorhanden, testet Visio den Inhalt der Datei vollständig. Für Dateien weglassen, die Sie außerhalb von Visio erstellen. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets) { get; } | Collection StyleSheet-Objekte. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui) { get; set; } | Die Multifunktionsleisten-XML-Zeichenfolge, die an das Dokument übergeben wird, um die Symbolleiste für den Schnellzugriff oder die Multifunktionsleiste anzupassen. |
| [Validation](../../aspose.diagram/diagram/validation) { get; } | Speichert Informationen zur Diagrammvalidierung für das Dokument. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject) { get; } | Ruft das VbaProject ab[`VbaProject`](./vbaproject). |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata) { get; set; } | Enthält die Microsoft Visual Basic for Applications-Projektdaten im MIME-codierten Format (Multipurpose Internet Mail Extensions). |
| [Version](../../aspose.diagram/diagram/version) { get; set; } | Die Versionsnummer der Visio-Instanz. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows) { get; } | Enthält die Fensterelemente für ein Dokument. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster)(Diagram, string) | Fügt Master zu Diagramm aus Quelldiagramm nach Name des Masters oder NameU hinzu. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_1)(Stream, int) | Fügt Master zu Diagramm aus Vorlagenstream nach Master-ID hinzu. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_2)(Stream, string) | Fügt den Master dem Diagramm aus dem Vorlagenstream nach Name des Masters oder NameU hinzu. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_3)(string, int) | Fügt Master zu Diagramm aus Vorlagendatei nach Master-ID hinzu. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_4)(string, string) | Fügt Master zu Diagramm aus Vorlagendatei nach Name des Masters oder NameU hinzu. |
| [AddShape](../../aspose.diagram/diagram/addshape#addshape)(Shape, string, int) | Fügt eine vom Master erstellte Form zu einer bestimmten Seite hinzu. |
| [AddShape](../../aspose.diagram/diagram/addshape#addshape_2)(double, double, string, int) | Fügt eine vom Master erstellte Form auf der Seite mit definiertem PinX und PinY hinzu. |
| [AddShape](../../aspose.diagram/diagram/addshape#addshape_1)(double, double, double, double, string, int) | Fügt eine vom Master erstellte Form auf der Seite mit definierten PinX, PinY, Breite und Höhe hinzu. |
| [Combine](../../aspose.diagram/diagram/combine)(Diagram) | Kombiniert ein anderes Diagrammobjekt. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme)(Diagram) | Kopiert Design aus einem Quelldiagramm. |
| [Dispose](../../aspose.diagram/diagram/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir)() | Holen Sie sich den Ordnerpfad für Standardschriften |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles)() | Erhalten Sie ungenutzte Styles |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo)() | Gibt an, ob dieses Diagramm versteckte Informationen enthält. |
| [Layout](../../aspose.diagram/diagram/layout)(LayoutOptions) | Legt die Shapes fest und/oder leitet die Verbinder für alle Diagrammseiten neu. |
| [Print](../../aspose.diagram/diagram/print#print)() | Druckt das gesamte Dokument auf dem Standarddrucker. |
| [Print](../../aspose.diagram/diagram/print#print_2)(PrinterSettings) | Druckt das Dokument gemäß den angegebenen Druckereinstellungen unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.diagram/diagram/print#print_1)(PrintSaveOptions) | Druckt das gesamte Dokument auf dem Standarddrucker. |
| [Print](../../aspose.diagram/diagram/print#print_6)(string) | Drucken Sie das gesamte Dokument auf dem angegebenen Drucker unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.diagram/diagram/print#print_3)(PrinterSettings, PrintSaveOptions) | Druckt das Dokument gemäß den angegebenen Druckereinstellungen unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.diagram/diagram/print#print_4)(PrinterSettings, string) | Druckt das Dokument gemäß den angegebenen Druckereinstellungen unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche) und eines Dokumentnamens. |
| [Print](../../aspose.diagram/diagram/print#print_7)(string, PrintSaveOptions) | Drucken Sie das gesamte Dokument auf dem angegebenen Drucker unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.diagram/diagram/print#print_8)(string, string) | Druckt das Dokument unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche) und eines Dokumentnamens. |
| [Print](../../aspose.diagram/diagram/print#print_5)(PrinterSettings, string, PrintSaveOptions) | Druckt das Dokument gemäß den angegebenen Druckereinstellungen unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche) und eines Dokumentnamens. |
| [Print](../../aspose.diagram/diagram/print#print_9)(string, string, PrintSaveOptions) | Druckt das Dokument unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche) und eines Dokumentnamens. |
| [Refresh](../../aspose.diagram/diagram/refresh)() | Ruft die Refresh-Methode für alle DataRecordSets im Diagramm auf. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation)(int) | Unbenutzte Informationen entfernen |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro)() | Entfernt VBA/Makro aus diesem Diagramm. |
| [Save](../../aspose.diagram/diagram/save#save)(Stream, SaveFileFormat) | Speichert die Diagrammdaten im Stream. |
| [Save](../../aspose.diagram/diagram/save#save_1)(Stream, SaveOptions) | Speichert das Diagramm unter Verwendung der angegebenen Speicheroptionen in einem Stream. |
| [Save](../../aspose.diagram/diagram/save#save_2)(string, SaveFileFormat) | Speichert die Diagrammdaten in der Datei. |
| [Save](../../aspose.diagram/diagram/save#save_3)(string, SaveOptions) | Speichert das Dokument unter Verwendung der angegebenen Speicheroptionen in einer Datei. |
| static [Export](../../aspose.diagram/diagram/export#export)(Stream, Stream) | Exportiert das Diagramm vom vsd-Stream in das vdw-Stream-Format. Noch nicht implementiert. |
| static [Export](../../aspose.diagram/diagram/export#export_1)(Stream, string) | Exportiert das Diagramm aus dem vsd-Stream in das Dateiformat *.vdw. Noch nicht implementiert. |
| static [Export](../../aspose.diagram/diagram/export#export_2)(string, Stream) | Exportiert das Diagramm aus der VSD-Datei in das VDW-Stream-Format. Noch nicht implementiert. |
| static [Export](../../aspose.diagram/diagram/export#export_3)(string, string) | Exportiert das Diagramm vom vsd- ins vdw-Format. Noch nicht implementiert. |

### Siehe auch

* namensraum [Aspose.Diagram](../../aspose.diagram)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
