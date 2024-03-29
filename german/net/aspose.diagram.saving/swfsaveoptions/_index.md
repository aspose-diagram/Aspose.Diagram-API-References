---
title: SWFSaveOptions
second_title: Aspose.Diagram für .NET-API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in SWF.
type: docs
weight: 3470
url: /de/net/aspose.diagram.saving/swfsaveoptions/
---
## SWFSaveOptions class

Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in SWF.

```csharp
public class SWFSaveOptions : SaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SWFSaveOptions](swfsaveoptions/)() | Initialisiert eine neue Instanz dieser Klasse, die zum Speichern eines Dokuments im verwendet werden kann[`XPS`](../../aspose.diagram/savefileformat/) format. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Wenn die Zeichen im Diagramm Unicode sind und nicht mit dem richtigen Schriftartwert festgelegt werden oder die Schriftart nicht lokal installiert ist, können sie als Block in PDF, Bild oder XPS erscheinen. Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese anzuzeigen Zeichen. |
| [PageCount](../../aspose.diagram.saving/swfsaveoptions/pagecount/) { get; set; } | Ruft die Anzahl der in XPS zu rendernden Seiten ab oder legt sie fest. Der Standardwert ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden. |
| [PageIndex](../../aspose.diagram.saving/swfsaveoptions/pageindex/) { get; set; } | Ruft den 0-basierten Index der ersten zu rendernden Seite ab oder legt ihn fest. Standard ist 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/swfsaveoptions/saveforegroundpagesonly/) { get; set; } | Gibt an, ob alle Seiten im Bild oder nur im Vordergrund gespeichert werden. |
| override [SaveFormat](../../aspose.diagram.saving/swfsaveoptions/saveformat/) { get; set; } | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionsobjekt verwendet wird. Kann sein[`XPS`](../../aspose.diagram/savefileformat/) nur. |
| [ViewerIncluded](../../aspose.diagram.saving/swfsaveoptions/viewerincluded/) { get; set; } | Gibt an, ob das generierte SWF-Dokument den integrierten Dokumentbetrachter enthalten soll oder nicht. Der Standardwert ist`WAHR` . |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Ruft Warnrückruf ab oder legt ihn fest. |

### Siehe auch

* class [SaveOptions](../saveoptions/)
* namensraum [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
