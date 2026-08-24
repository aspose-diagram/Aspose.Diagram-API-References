---
title: Diagramm
second_title: Aspose.Diagram for Java API-Referenz
description: Stammelement der Visio-Objekthierarchie.
type: docs
weight: 117
url: /de/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Stammelement der Visio-Objekthierarchie.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Öffentlicher Klassenkonstruktor, lädt das Diagramm aus der Datei. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Öffentlicher Klassenkonstruktor, lädt das Diagramm aus dem Stream. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Öffentlicher Klassenkonstruktor, lädt das Diagramm aus dem Stream unter Verwendung eines vordefinierten Formats. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Öffentlicher Klassenkonstruktor, lädt das Diagramm aus dem Stream unter Verwendung vordefinierter Ladeoptionen. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Öffentlicher Klassenkonstruktor, lädt das Diagramm aus der Datei unter Verwendung eines vordefinierten Formats. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Öffentlicher Klassenkonstruktor, lädt das Diagramm aus der Datei unter Verwendung vordefinierter Ladeoptionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Fügt dem Diagramm ein Master aus dem Quelldiagramm anhand des Namens oder NameU des Masters hinzu. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Fügt dem Diagramm ein Master aus dem Vorlagen-Stream anhand der ID des Masters hinzu. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Fügt dem Diagramm ein Master aus dem Vorlagen-Stream anhand des Namens oder NameU des Masters hinzu. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Fügt dem Diagramm ein Master aus der Vorlagendatei anhand der ID des Masters hinzu. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Fügt dem Diagramm ein Master aus der Vorlagendatei anhand des Namens oder NameU des Masters hinzu. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Fügt ein vom Master erstelltes Shape zu einer bestimmten Seite hinzu. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX, PinY, Breite und Höhe hinzu. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX und PinY hinzu. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Kombiniert ein weiteres Diagrammobjekt. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Kopiert das Theme aus einem Quell-Diagramm. |
| [dispose()](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Exportiert das Diagramm vom VSD-Stream in das VDW-Stream-Format. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Exportiert das Diagramm vom VSD-Stream in das *.vdw-Dateiformat. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Exportiert das Diagramm von einer VSD-Datei in das VDW-Stream-Format. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Exportiert das Diagramm von VSD nach VDW. |
| [getActivePage()](#getActivePage--) | Gibt die aktive Seite an |
| [getBuildnum()](#getBuildnum--) | Die Build-Nummer der Visio-Instanz, die zum Erstellen des Dokuments verwendet wurde. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Enthält die Farbpalette des Dokuments. |
| [getDataConnections()](#getDataConnections--) | Enthält die DataConnection-Elemente für das Dokument. |
| [getDataRecordSets()](#getDataRecordSets--) | Die Sammlung von DataRecordset-Objekten, die mit einem Document-Objekt verknüpft sind. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Rufe den Pfad des Standard-Schriftartenordners ab |
| [getDocLangID()](#getDocLangID--) | Die eindeutige ID der Benutzeroberflächensprache, die der Benutzer in den Microsoft Office 2010 Language Preferences angegeben hat. |
| [getDocumentProps()](#getDocumentProps--) | Enthält Dokumenteigenschaftselemente wie den Titel, den Autor usw. des Dokuments. |
| [getDocumentSettings()](#getDocumentSettings--) | Enthält Elemente, die Dokumenteinstellungen festlegen. |
| [getDocumentSheet()](#getDocumentSheet--) | Gibt die ShapeSheet-Struktur eines Dokuments an. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten MAPI-E-Mail-Routing-Slip für das Dokument. |
| [getEventItems()](#getEventItems--) | Enthält ein EventItem-Element für jedes Ereignis, auf das ein Objekt reagieren soll. |
| [getFonts()](#getFonts--) | Enthält eine Sammlung von Font-Elementen |
| [getHeaderFooter()](#getHeaderFooter--) | Enthält Elemente für die Kopf- und Fußzeile eines Dokuments. |
| [getInterruptMonitor()](#getInterruptMonitor--) | der Interrupt-Monitor. |
| [getKey()](#getKey--) | Gibt an, ob das Dokument außerhalb von Visio geändert wurde. |
| [getMasters()](#getMasters--) | Sammlung von Master-Objekten. |
| [getMetric()](#getMetric--) | Ob im Diagramm metrische Einheiten verwendet werden sollen. |
| [getPages()](#getPages--) | Sammlung von Page-Objekten. |
| [getRibbonX()](#getRibbonX--) | Der Ribbon-XML-String, der an das Dokument übergeben wird, um die Ribbon-Benutzeroberfläche anzupassen. |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML-Wert. |
| [getStart()](#getStart--) | Gibt an, ob das Dokument außerhalb von Visio geändert wurde. |
| [getStyleSheets()](#getStyleSheets--) | Sammlung von StyleSheet-Objekten. |
| [getUnusedStyles()](#getUnusedStyles--) | Unbenutzte Stile abrufen |
| [getUserCustomUI()](#getUserCustomUI--) | Der Ribbon-XML-String, der an das Dokument übergeben wird, um die Symbolleiste für den Schnellzugriff oder das Ribbon anzupassen. |
| [getValidation()](#getValidation--) | Speichert Informationen zur Diagrammvalidierung für das Dokument. |
| [getVbProjectData()](#getVbProjectData--) | Enthält die Microsoft Visual Basic for Applications-Projektdaten im MIME (Multipurpose Internet Mail Extensions)-kodierten Format. |
| [getVbaProject()](#getVbaProject--) | Ruft das VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--) ab. |
| [getVersion()](#getVersion--) | Die Versionsnummer der Visio-Instanz. |
| [getWindows()](#getWindows--) | Enthält die Window-Elemente für ein Dokument. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Gibt an, ob dieses Diagramm versteckte Informationen enthält. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Ordnet die Formen an und/oder leitet die Verbinder für alle Seiten des Diagramms neu. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Druckt das gesamte Dokument auf dem angegebenen Drucker, wobei der Standard‑Druckcontroller (keine Benutzeroberfläche) verwendet wird. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Druckt das gesamte Dokument auf dem angegebenen Drucker, wobei der Standard‑Druckcontroller (keine Benutzeroberfläche) verwendet wird. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Druckt das Dokument, wobei der Standard‑Druckcontroller (keine Benutzeroberfläche) und ein Dokumentname verwendet werden. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Druckt das Dokument, wobei der Standard‑Druckcontroller (keine Benutzeroberfläche) und ein Dokumentname verwendet werden. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Unbenutzte Informationen entfernen |
| [removeMacro()](#removeMacro--) | Entfernt VBA/Makro aus diesem Diagramm. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Speichert das Diagramm im Stream. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Speichert das Diagramm im Stream. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Speichert das Dokument in einer Datei unter Verwendung der angegebenen Speicheroptionen. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Speichert die Diagrammdaten in der Datei. |
| [setBuildnum(long value)](#setBuildnum-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Gibt den Pfad des Schriftartenordners an |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Öffentlicher Klassenkonstruktor, lädt das Diagramm aus der Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Dateiname. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Öffentlicher Klassenkonstruktor, lädt das Diagramm aus dem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Datenstrom. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Öffentlicher Klassenkonstruktor, lädt das Diagramm aus dem Stream unter Verwendung eines vordefinierten Formats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Datenstrom. |
| Format | int | Die Daten Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Öffentlicher Klassenkonstruktor, lädt das Diagramm aus dem Stream unter Verwendung vordefinierter Ladeoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Datenstrom. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Die Daten [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Öffentlicher Klassenkonstruktor, lädt das Diagramm aus der Datei unter Verwendung eines vordefinierten Formats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Dateiname. |
| Format | int | Das Dateiformat. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Öffentlicher Klassenkonstruktor, lädt das Diagramm aus der Datei unter Verwendung vordefinierter Ladeoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Dateiname. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Die Daten [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Fügt dem Diagramm ein Master aus dem Quelldiagramm anhand des Namens oder NameU des Masters hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | Quell-Diagramm. |
| masterName | java.lang.String | Name des Masters oder NameU. |

**Returns:**
int – Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in diesem Diagramm.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Fügt dem Diagramm ein Master aus dem Vorlagen-Stream anhand der ID des Masters hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templateStream | java.io.InputStream | Template-Stream. |
| masterID | int | Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in der Vorlage. |

**Returns:**
int – Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in diesem Diagramm.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Fügt dem Diagramm ein Master aus dem Vorlagen-Stream anhand des Namens oder NameU des Masters hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templateStream | java.io.InputStream | Template-Stream. |
| masterName | java.lang.String | Name des Masters oder NameU. |

**Returns:**
int – Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in diesem Diagramm.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Fügt dem Diagramm ein Master aus der Vorlagendatei anhand der ID des Masters hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templateFilePath | java.lang.String | Pfad zur Vorlagendatei(kann das Format vdx, vst oder vsd sein). |
| masterID | int | Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in der Vorlage. |

**Returns:**
int – Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in diesem Diagramm.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Fügt dem Diagramm ein Master aus der Vorlagendatei anhand des Namens oder NameU des Masters hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templateFilePath | java.lang.String | Pfad zur Vorlagendatei(kann das Format vdx, vst oder vsd sein). |
| masterName | java.lang.String | Name des Masters oder NameU. |

**Returns:**
int – Die eindeutige ID des Masters innerhalb der Masters‑Sammlung in diesem Diagramm.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Fügt ein vom Master erstelltes Shape zu einer bestimmten Seite hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Neues Formobjekt[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Name des Masters. |
| pageNumber | int | Index der Seite. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX, PinY, Breite und Höhe hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form in Zoll an. |
| Höhe | double | Gibt die Höhe der Form in Zoll an. |
| masterName | java.lang.String | Name des Masters. |
| pageNumber | int | Index der Seite. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX und PinY hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| masterName | java.lang.String | Name des Masters. |
| pageNumber | int | Index der Seite. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Kombiniert ein weiteres Diagrammobjekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Ein weiteres Diagramm-Objekt. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Kopiert das Theme aus einem Quell-Diagramm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | Quell-Diagramm. |

### dispose() {#dispose--}
```
public void dispose()
```


Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exportiert das Diagramm vom vsd-Stream in das vdw-Stream-Format. Noch nicht implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd-Stream. |
| outputVdw | java.io.InputStream | vdw-Stream. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exportiert das Diagramm vom vsd-Stream in das \*.vdw-Dateiformat. Noch nicht implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd-Dateiname. |
| outputVdw | java.lang.String | vdw-Stream. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exportiert das Diagramm von einer vsd-Datei in das vdw-Stream-Format. Noch nicht implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd-Dateiname. |
| outputVdw | java.io.InputStream | vdw-Stream. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exportiert das Diagramm von vsd nach vdw-Format. Noch nicht implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd-Dateiname. |
| outputVdw | java.lang.String | \*.vdw-Dateiname. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Gibt die aktive Seite an

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Die Build-Nummer der Visio-Instanz, die zum Erstellen des Dokuments verwendet wurde.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


Enthält die Farbtabelle des Dokuments. Jedes Dokument enthält eine einzelne Farbtabelle, die die 24 Standardfarben auflistet, die für Objekte wie Formen, Text und Ebenen im Dokument verwendet werden können.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Enthält die DataConnection-Elemente für das Dokument.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Die Sammlung von DataRecordset-Objekten, die mit einem Document-Objekt verknüpft sind.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Rufe den Pfad des Standard-Schriftartenordners ab

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


Die eindeutige ID der Benutzeroberflächensprache, die der Benutzer in den Microsoft Office 2010 Language Preferences angegeben hat.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Enthält Dokumenteigenschaftselemente wie den Titel, den Autor usw. des Dokuments.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Enthält Elemente, die Dokumenteinstellungen festlegen.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Gibt die ShapeSheet-Struktur eines Dokuments an.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten MAPI-E-Mail-Routing-Slip für das Dokument.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Enthält ein EventItem-Element für jedes Ereignis, auf das ein Objekt reagieren soll.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Enthält eine Sammlung von Font-Elementen

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Enthält Elemente für die Kopf- und Fußzeile eines Dokuments.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


der Interrupt-Monitor.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Gibt an, ob das Dokument außerhalb von Visio geändert wurde. Falls vorhanden, prüft Visio den Inhalt der Datei vollständig. Für Dateien, die Sie außerhalb von Visio erstellen, weglassen.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Sammlung von Master-Objekten.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Gibt an, ob im Diagramm metrische Einheiten verwendet werden sollen. Setzen Sie dieses Attribut auf True (1), um metrische Einheiten zu verwenden; setzen Sie es auf False (0), um englische Einheiten zu verwenden.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Sammlung von Page-Objekten.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


Der Ribbon-XML-String, der an das Dokument übergeben wird, um die Ribbon-Benutzeroberfläche anzupassen.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML-Wert.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Gibt an, ob das Dokument außerhalb von Visio geändert wurde. Falls vorhanden, prüft Visio den Inhalt der Datei vollständig. Für Dateien, die Sie außerhalb von Visio erstellen, weglassen.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Sammlung von StyleSheet-Objekten.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Unbenutzte Stile abrufen

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


Der Ribbon-XML-String, der an das Dokument übergeben wird, um die Symbolleiste für den Schnellzugriff oder das Ribbon anzupassen.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Speichert Informationen zur Diagrammvalidierung für das Dokument.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Enthält die Microsoft Visual Basic for Applications-Projektdaten im MIME (Multipurpose Internet Mail Extensions)-kodierten Format.

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Ruft das VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--) ab.

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Die Versionsnummer der Visio-Instanz. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Enthält die Window-Elemente für ein Dokument.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Gibt an, ob dieses Diagramm versteckte Informationen enthält.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Ordnet die Formen an und/oder leitet die Verbinder für alle Seiten des Diagramms neu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Verwendung von [LayoutOptions](../../com.aspose.diagram/layoutoptions), um Layout‑Optionen zu konfigurieren. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


Druckt das gesamte Dokument an den angegebenen Drucker, wobei der Standard‑Druckcontroller (ohne Benutzeroberfläche) verwendet wird. Wenn printerName Null oder leer ist, wird der Standarddrucker verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerName | java.lang.String | Der Name des Druckers. Kann Null sein. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Druckt das gesamte Dokument an den angegebenen Drucker, wobei der Standard‑Druckcontroller (ohne Benutzeroberfläche) verwendet wird. Wenn printerName Null oder leer ist, wird der Standarddrucker verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerName | java.lang.String | Der Name des Druckers. Kann Null sein. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Die Druckoptionen. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Druckt das Dokument, wobei der Standard‑Druckcontroller (keine Benutzeroberfläche) und ein Dokumentname verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerName | java.lang.String | Der Name des Druckers. Kann Null sein. |
| documentName | java.lang.String | Der Dokumentname, der beim Drucken des Dokuments angezeigt wird (z. B. in einem Druckstatus‑Dialogfeld oder in der Druckwarteschlange). |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Druckt das Dokument, wobei der Standard‑Druckcontroller (keine Benutzeroberfläche) und ein Dokumentname verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerName | java.lang.String | Der Name des Druckers. Kann Null sein. |
| documentName | java.lang.String | Der Dokumentname, der beim Drucken des Dokuments angezeigt wird (z. B. in einem Druckstatus‑Dialogfeld oder in der Druckwarteschlange). |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Die Druckoptionen. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Unbenutzte Informationen entfernen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Entfernt VBA/Makro aus diesem Diagramm.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Speichert das Diagramm im Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Dateistream. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | Die Speicheroptionen. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Speichert das Diagramm im Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Dateistream. |
| Format | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Speichert das Dokument in einer Datei unter Verwendung der angegebenen Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Dateiname. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) Diagrammspeicheroptionen. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Speichert die Diagrammdaten in der Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateiname | java.lang.String | Der Dateiname. |
| Format | int | Aspose.Diagram.SaveFileFormat Speicherdateiformat. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Gibt den Pfad des Schriftartenordners an

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

