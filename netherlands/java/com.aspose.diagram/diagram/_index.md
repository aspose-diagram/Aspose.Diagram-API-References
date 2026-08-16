---
title: Diagram
second_title: Aspose.Diagram voor Java API-referentie
description: Hoofdelement van de Visio-objecthiërarchie.
type: docs
weight: 117
url: /nl/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Hoofdelement van de Visio-objecthiërarchie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Publieke klasseconstructor, laadt het diagram vanuit het bestand. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Publieke klasseconstructor, laadt het diagram vanuit de stream. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Publieke klasseconstructor, laadt het diagram vanuit de stream met een vooraf gedefinieerd formaat. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Publieke klasseconstructor, laadt het diagram vanuit de stream met vooraf gedefinieerde laadbestandsopties. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Publieke klasseconstructor, laadt het diagram vanuit het bestand met een vooraf gedefinieerd formaat. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Publieke klasseconstructor, laadt het diagram vanuit het bestand met vooraf gedefinieerde laadbestandsopties. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Voegt master toe aan diagram vanuit bron-diagram op basis van de Naam of NameU van de master. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Voegt master toe aan diagram vanuit sjabloonstream op basis van de ID van de master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Voegt master toe aan diagram vanuit sjabloonstream op basis van de Naam of NameU van de master. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Voegt master toe aan diagram vanuit sjabloonbestand op basis van de ID van de master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Voegt master toe aan diagram vanuit sjabloonbestand op basis van de Naam of NameU van de master. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Voegt een vorm toe, gemaakt door master, aan een specifieke pagina. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX, PinY, Breedte en Hoogte. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX en PinY. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Combineert een ander Diagram-object. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Kopieert Thema van een bron-Diagram. |
| [dispose()](#dispose--) | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Exporteert het diagram van een VSD-stream naar VDW-streamformaat. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Exporteert het diagram van een VSD-stream naar *.vdw-bestandsformaat. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Exporteert het diagram van een VSD-bestand naar VDW-streamformaat. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Exporteert het diagram van VSD naar VDW-formaat. |
| [getActivePage()](#getActivePage--) | Specificeert de actieve pagina |
| [getBuildnum()](#getBuildnum--) | Het buildnummer van de Visio-instantie die is gebruikt om het document te maken. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Bevat de kleurtabel van het document. |
| [getDataConnections()](#getDataConnections--) | Bevat de DataConnection-elementen voor het document. |
| [getDataRecordSets()](#getDataRecordSets--) | De collectie van DataRecordset-objecten die geassocieerd zijn met een Document-object. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Haal het pad van de standaardlettertypemap op |
| [getDocLangID()](#getDocLangID--) | De unieke ID van de gebruikersinterface-taal die de gebruiker heeft opgegeven in Microsoft Office 2010 Taalvoorkeuren. |
| [getDocumentProps()](#getDocumentProps--) | Bevat document‑eigenschapselementen zoals de titel, auteur en dergelijke van het document. |
| [getDocumentSettings()](#getDocumentSettings--) | Bevat elementen die documentinstellingen specificeren. |
| [getDocumentSheet()](#getDocumentSheet--) | Specificeert de ShapeSheet-structuur van een document. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde MAPI e-mail routing slip voor het document. |
| [getEventItems()](#getEventItems--) | Bevat een EventItem-element voor elk evenement waarop een object moet reageren. |
| [getFonts()](#getFonts--) | Bevat een collectie van Font-elementen |
| [getHeaderFooter()](#getHeaderFooter--) | Bevat elementen voor de kop- en voettekst van een document. |
| [getInterruptMonitor()](#getInterruptMonitor--) | de onderbrekingsmonitor. |
| [getKey()](#getKey--) | Geeft aan of het document buiten Visio is gewijzigd. |
| [getMasters()](#getMasters--) | Collectie Master-objecten. |
| [getMetric()](#getMetric--) | Of er metrische eenheden in de tekening moeten worden gebruikt. |
| [getPages()](#getPages--) | Collectie Page-objecten. |
| [getRibbonX()](#getRibbonX--) | De Ribbon XML-tekenreeks die aan het document wordt doorgegeven om de ribbon-gebruikersinterface aan te passen. |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML-waarde. |
| [getStart()](#getStart--) | Geeft aan of het document buiten Visio is gewijzigd. |
| [getStyleSheets()](#getStyleSheets--) | Collectie StyleSheet-objecten. |
| [getUnusedStyles()](#getUnusedStyles--) | Ophalen ongebruikte stijlen |
| [getUserCustomUI()](#getUserCustomUI--) | De Ribbon XML-tekenreeks die aan het document wordt doorgegeven om de Quick Access-werkbalk of de ribbon aan te passen. |
| [getValidation()](#getValidation--) | Slaat informatie op over diagramvalidatie voor het document. |
| [getVbProjectData()](#getVbProjectData--) | Bevat de Microsoft Visual Basic for Applications-projectgegevens in MIME (Multipurpose Internet Mail Extensions) gecodeerd formaat. |
| [getVbaProject()](#getVbaProject--) | Haalt de VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--) op. |
| [getVersion()](#getVersion--) | Het versienummer van de Visio-instantie. |
| [getWindows()](#getWindows--) | Bevat de Window-elementen voor een document. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Geeft aan of dit diagram verborgen informatie bevat. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Rangschikt de vormen en/of leidt de connectoren opnieuw voor alle pagina's van het diagram. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Print het hele document naar de opgegeven printer, met de standaard (geen gebruikersinterface) printcontroller. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Print het hele document naar de opgegeven printer, met de standaard (geen gebruikersinterface) printcontroller. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Print het document, met de standaard (geen gebruikersinterface) printcontroller en een documentnaam. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Print het document, met de standaard (geen gebruikersinterface) printcontroller en een documentnaam. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Verwijder ongebruikte informatie |
| [removeMacro()](#removeMacro--) | Verwijdert VBA/macro uit dit diagram. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Sla het diagram op in de stream. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sla het diagram op in de stream. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Slaat het document op in een bestand met de opgegeven opslagopties. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Slaat de diagramgegevens op in het bestand. |
| [setBuildnum(long value)](#setBuildnum-long-) | Voor de beschrijving van deze eigenschap, zie [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Voor de beschrijving van deze eigenschap, zie [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Voor de beschrijving van deze eigenschap, zie [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Geeft het pad van de Fonts-map aan |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Voor de beschrijving van deze eigenschap, zie [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Voor de beschrijving van deze eigenschap, zie [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Voor de beschrijving van deze eigenschap, zie [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Voor de beschrijving van deze eigenschap, zie [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
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


Publieke klasseconstructor, laadt het diagram vanuit het bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De bestandsnaam. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Publieke klasseconstructor, laadt het diagram vanuit de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De gegevensstroom. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Publieke klasseconstructor, laadt het diagram vanuit de stream met een vooraf gedefinieerd formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De gegevensstroom. |
| formaat | int | De gegevens Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Publieke klasseconstructor, laadt het diagram vanuit de stream met vooraf gedefinieerde laadbestandsopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De gegevensstroom. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | De gegevens [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Publieke klasseconstructor, laadt het diagram vanuit het bestand met een vooraf gedefinieerd formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De bestandsnaam. |
| formaat | int | Het bestandsformaat. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Publieke klasseconstructor, laadt het diagram vanuit het bestand met vooraf gedefinieerde laadbestandsopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De bestandsnaam. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | De gegevens [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Voegt master toe aan diagram vanuit bron-diagram op basis van de Naam of NameU van de master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | Bron diagram. |
| masterName | java.lang.String | Naam van Master of NameU. |

**Returns:**
int - De unieke ID van de master binnen de masters-collectie in dit diagram.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Voegt master toe aan diagram vanuit sjabloonstream op basis van de ID van de master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templateStream | java.io.InputStream | template stroom. |
| masterID | int | De unieke ID van de master binnen de masters-collectie in de template. |

**Returns:**
int - De unieke ID van de master binnen de masters-collectie in dit diagram.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Voegt master toe aan diagram vanuit sjabloonstream op basis van de Naam of NameU van de master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templateStream | java.io.InputStream | template stroom. |
| masterName | java.lang.String | Naam van Master of NameU. |

**Returns:**
int - De unieke ID van de master binnen de masters-collectie in dit diagram.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Voegt master toe aan diagram vanuit sjabloonbestand op basis van de ID van de master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templateFilePath | java.lang.String | Pad naar sjabloonbestand (kan vdx-, vst- of vsd-formaat zijn). |
| masterID | int | De unieke ID van de master binnen de masters-collectie in de template. |

**Returns:**
int - De unieke ID van de master binnen de masters-collectie in dit diagram.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Voegt master toe aan diagram vanuit sjabloonbestand op basis van de Naam of NameU van de master.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templateFilePath | java.lang.String | Pad naar sjabloonbestand (kan vdx-, vst- of vsd-formaat zijn). |
| masterName | java.lang.String | Naam van Master of NameU. |

**Returns:**
int - De unieke ID van de master binnen de masters-collectie in dit diagram.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Voegt een vorm toe, gemaakt door master, aan een specifieke pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nieuw vormobject[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Naam van de master. |
| pageNumber | int | Index van pagina. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX, PinY, Breedte en Hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm in inches. |
| height | double | Specificeert de hoogte van de vorm in inches. |
| masterName | java.lang.String | Naam van de master. |
| pageNumber | int | Index van pagina. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX en PinY.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| masterName | java.lang.String | Naam van de master. |
| pageNumber | int | Index van pagina. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Combineert een ander Diagram-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Een ander Diagram-object. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Kopieert Thema van een bron-Diagram.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | Bron diagram. |

### dispose() {#dispose--}
```
public void dispose()
```


Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exporteert het diagram van een vsd-stream naar vdw-streamformaat. Nog niet geïmplementeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd-stream. |
| outputVdw | java.io.InputStream | vdw-stream. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exporteert het diagram van een vsd-stream naar \*.vdw-bestandsformaat. Nog niet geïmplementeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd bestandsnaam. |
| outputVdw | java.lang.String | vdw-stream. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exporteert het diagram van een vsd-bestand naar vdw-streamformaat. Nog niet geïmplementeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd bestandsnaam. |
| outputVdw | java.io.InputStream | vdw-stream. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exporteert het diagram van vsd naar vdw-formaat. Nog niet geïmplementeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd bestandsnaam. |
| outputVdw | java.lang.String | \*.vdw bestandsnaam. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Specificeert de actieve pagina

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Het buildnummer van de Visio-instantie die is gebruikt om het document te maken.

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


Bevat de kleurentabel van het document. Elk document bevat één kleurentabel, die de 24 standaardkleuren opsomt die beschikbaar zijn voor toepassing op objecten zoals vormen, tekst en lagen in het document.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Bevat de DataConnection-elementen voor het document.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


De collectie van DataRecordset-objecten die geassocieerd zijn met een Document-object.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Haal het pad van de standaardlettertypemap op

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


De unieke ID van de gebruikersinterface-taal die de gebruiker heeft opgegeven in Microsoft Office 2010 Taalvoorkeuren.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Bevat document‑eigenschapselementen zoals de titel, auteur en dergelijke van het document.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Bevat elementen die documentinstellingen specificeren.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Specificeert de ShapeSheet-structuur van een document.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde MAPI e-mail routing slip voor het document.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Bevat een EventItem-element voor elk evenement waarop een object moet reageren.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Bevat een collectie van Font-elementen

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Bevat elementen voor de kop- en voettekst van een document.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


de onderbrekingsmonitor.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Geeft aan of het document buiten Visio is gewijzigd. Indien aanwezig zal Visio de inhoud van het bestand volledig testen. Laat weg voor bestanden die u buiten Visio maakt.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Collectie Master-objecten.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Of metrische eenheden in de tekening moeten worden gebruikt. Stel dit attribuut in op True (1) om metrische eenheden te gebruiken; stel het in op False (0) om Engelse eenheden te gebruiken.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Collectie Page-objecten.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


De Ribbon XML-tekenreeks die aan het document wordt doorgegeven om de ribbon-gebruikersinterface aan te passen.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML-waarde.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Geeft aan of het document buiten Visio is gewijzigd. Indien aanwezig zal Visio de inhoud van het bestand volledig testen. Laat weg voor bestanden die u buiten Visio maakt.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Collectie StyleSheet-objecten.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Ophalen ongebruikte stijlen

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


De Ribbon XML-tekenreeks die aan het document wordt doorgegeven om de Quick Access-werkbalk of de ribbon aan te passen.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Slaat informatie op over diagramvalidatie voor het document.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Bevat de Microsoft Visual Basic for Applications-projectgegevens in MIME (Multipurpose Internet Mail Extensions) gecodeerd formaat.

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Haalt de VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--) op.

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Het versienummer van de Visio-instantie. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Bevat de Window-elementen voor een document.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Geeft aan of dit diagram verborgen informatie bevat.

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


Rangschikt de vormen en/of leidt de connectoren opnieuw voor alle pagina's van het diagram.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Gebruik de [LayoutOptions](../../com.aspose.diagram/layoutoptions) om de opties van de lay-out te configureren. |

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


Print het volledige document naar de opgegeven printer, met de standaard (geen gebruikersinterface) printcontroller. Als printerName null of leeg is, wordt de standaardprinter gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| printerName | java.lang.String | De naam van de printer. Kan null zijn. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Print het volledige document naar de opgegeven printer, met de standaard (geen gebruikersinterface) printcontroller. Als printerName null of leeg is, wordt de standaardprinter gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| printerName | java.lang.String | De naam van de printer. Kan null zijn. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | De afdrukopties. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Print het document, met de standaard (geen gebruikersinterface) printcontroller en een documentnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| printerName | java.lang.String | De naam van de printer. Kan null zijn. |
| documentName | java.lang.String | De documentnaam om weer te geven (bijvoorbeeld in een afdrukstatusdialoogvenster of printerwachtrij) tijdens het afdrukken van het document. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Print het document, met de standaard (geen gebruikersinterface) printcontroller en een documentnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| printerName | java.lang.String | De naam van de printer. Kan null zijn. |
| documentName | java.lang.String | De documentnaam om weer te geven (bijvoorbeeld in een afdrukstatusdialoogvenster of printerwachtrij) tijdens het afdrukken van het document. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | De afdrukopties. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Verwijder ongebruikte informatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Verwijdert VBA/macro uit dit diagram.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Sla het diagram op in de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De bestandsstroom. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | De opslagopties. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Sla het diagram op in de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De bestandsstroom. |
| formaat | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Slaat het document op in een bestand met de opgegeven opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De bestandsnaam. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) sla diagramopties op. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Slaat de diagramgegevens op in het bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | java.lang.String | De bestandsnaam. |
| formaat | int | Aspose.Diagram.SaveFileFormat sla bestandsformaat op. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Voor de beschrijving van deze eigenschap, zie [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Geeft het pad van de Fonts-map aan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Voor de beschrijving van deze eigenschap, zie [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Voor de beschrijving van deze eigenschap, zie [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Voor de beschrijving van deze eigenschap, zie [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Voor de beschrijving van deze eigenschap, zie [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Voor de beschrijving van deze eigenschap, zie [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Voor de beschrijving van deze eigenschap, zie [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

