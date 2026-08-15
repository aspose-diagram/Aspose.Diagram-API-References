---
title: Diagram
second_title: Aspose.Diagram för Java API-referens
description: Rot-element för Visio-objekthierarkin.
type: docs
weight: 117
url: /sv/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Rot-element för Visio-objekthierarkin.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Publik klasskonstruktor, laddar diagrammet från filen. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Publik klasskonstruktor, laddar diagrammet från strömmen. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Publik klasskonstruktor, laddar diagrammet från strömmen med fördefinierat format. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Publik klasskonstruktor, laddar diagrammet från strömmen med fördefinierade alternativ för filinläsning. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Publik klasskonstruktor, laddar diagrammet från filen med fördefinierat format. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Publik klasskonstruktor, laddar diagrammet från filen med fördefinierade alternativ för filinläsning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Lägger till master i diagrammet från källdiagrammet med masterens namn eller NameU. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Lägger till master i diagrammet från mallströmmen med masterens ID. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Lägger till master i diagrammet från mallströmmen med masterens namn eller NameU. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Lägger till master i diagrammet från mallfilen med masterens ID. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Lägger till master i diagrammet från mallfilen med masterens namn eller NameU. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Lägger till en form skapad av master till en specifik sida. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Lägger till en form skapad av master på sidan med definierade PinX, PinY, bredd och höjd. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Lägger till en form skapad av master på sidan med definierade PinX och PinY. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Kombinerar ett annat Diagram-objekt. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Kopierar tema från ett källdiagram. |
| [dispose()](#dispose--) | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Exporterar diagrammet från VSD-ström till VDW-strömformat. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Exporterar diagrammet från VSD-ström till *.vdw-filformat. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Exporterar diagrammet från VSD-fil till VDW-strömformat. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Exporterar diagrammet från VSD till VDW-format. |
| [getActivePage()](#getActivePage--) | Anger den aktiva sidan |
| [getBuildnum()](#getBuildnum--) | Byggnumret för Visio-instansen som användes för att skapa dokumentet. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Innehåller dokumentets färgtabell. |
| [getDataConnections()](#getDataConnections--) | Innehåller DataConnection-elementen för dokumentet. |
| [getDataRecordSets()](#getDataRecordSets--) | Samlingen av DataRecordset-objekt som är associerade med ett Document-objekt. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Hämta sökvägen till standardteckensnittsmappen |
| [getDocLangID()](#getDocLangID--) | Det unika ID:t för det användargränssnittsspråk som användaren har angett i Microsoft Office 2010 Språkinställningar. |
| [getDocumentProps()](#getDocumentProps--) | Innehåller element för dokumentegenskaper såsom dokumentets titel, författare osv. |
| [getDocumentSettings()](#getDocumentSettings--) | Innehåller element som specificerar dokumentinställningar. |
| [getDocumentSheet()](#getDocumentSheet--) | Anger ett dokuments ShapeSheet-struktur. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Innehåller ett MIME (Multipurpose Internet Mail Extensions) kodad MAPI e‑postrouting‑slipp för dokumentet. |
| [getEventItems()](#getEventItems--) | Innehåller ett EventItem‑element för varje händelse som ett objekt ska svara på. |
| [getFonts()](#getFonts--) | Innehåller en samling av Font‑element |
| [getHeaderFooter()](#getHeaderFooter--) | Innehåller element för ett dokuments sidhuvud och sidfot. |
| [getInterruptMonitor()](#getInterruptMonitor--) | avbrottsmontorn. |
| [getKey()](#getKey--) | Anger om dokumentet har ändrats utanför Visio. |
| [getMasters()](#getMasters--) | Samling av Master‑objekt. |
| [getMetric()](#getMetric--) | Om metriska enheter ska användas i ritningen. |
| [getPages()](#getPages--) | Samling av Page‑objekt. |
| [getRibbonX()](#getRibbonX--) | Ribbon‑XML‑strängen som skickas till dokumentet för att anpassa ribbon‑användargränssnittet. |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML‑värde. |
| [getStart()](#getStart--) | Anger om dokumentet har ändrats utanför Visio. |
| [getStyleSheets()](#getStyleSheets--) | Samling av StyleSheet‑objekt. |
| [getUnusedStyles()](#getUnusedStyles--) | Hämta oanvända stilar |
| [getUserCustomUI()](#getUserCustomUI--) | Ribbon‑XML‑strängen som skickas till dokumentet för att anpassa snabbåtkomstverktygsfältet eller ribbon. |
| [getValidation()](#getValidation--) | Lagrar information om diagramvalidering för dokumentet. |
| [getVbProjectData()](#getVbProjectData--) | Innehåller Microsoft Visual Basic for Applications‑projektdata i MIME (Multipurpose Internet Mail Extensions) kodat format. |
| [getVbaProject()](#getVbaProject--) | Hämtar VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Versionsnumret för Visio‑instansen. |
| [getWindows()](#getWindows--) | Innehåller Window‑elementen för ett dokument. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Anger om detta diagram har dold information. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Lägger ut formerna och/eller omdirigerar anslutningarna för alla diagram‑sidor. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Skriv ut hela dokumentet till den angivna skrivaren, med den standard (utan användargränssnitt) utskriftskontrollen. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Skriv ut hela dokumentet till den angivna skrivaren, med den standard (utan användargränssnitt) utskriftskontrollen. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Skriver ut dokumentet, med den standard (utan användargränssnitt) utskriftskontrollen och ett dokumentnamn. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Skriver ut dokumentet, med den standard (utan användargränssnitt) utskriftskontrollen och ett dokumentnamn. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Ta bort oanvänd information |
| [removeMacro()](#removeMacro--) | Tar bort VBA/makro från detta diagram. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Spara diagrammet till strömmen. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Spara diagrammet till strömmen. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Sparar dokumentet till en fil med de angivna sparalternativen. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Sparar diagramdata till filen. |
| [setBuildnum(long value)](#setBuildnum-long-) | For the description of this property, please see [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | For the description of this property, please see [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | For the description of this property, please see [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Indicates the Fonts folder path |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | For the description of this property, please see [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | For the description of this property, please see [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | For the description of this property, please see [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | For the description of this property, please see [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | For the description of this property, please see [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | For the description of this property, please see [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | For the description of this property, please see [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | For the description of this property, please see [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
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


Publik klasskonstruktor, laddar diagrammet från filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | The file name. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Publik klasskonstruktor, laddar diagrammet från strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | The data stream. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Publik klasskonstruktor, laddar diagrammet från strömmen med fördefinierat format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | The data stream. |
| format | int | The data Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Publik klasskonstruktor, laddar diagrammet från strömmen med fördefinierade alternativ för filinläsning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | The data stream. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | The data [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Publik klasskonstruktor, laddar diagrammet från filen med fördefinierat format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| format | int | The file format. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Publik klasskonstruktor, laddar diagrammet från filen med fördefinierade alternativ för filinläsning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | The data [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Lägger till master i diagrammet från källdiagrammet med masterens namn eller NameU.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | source diagram. |
| masterName | java.lang.String | Master's Name or NameU. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Lägger till master i diagrammet från mallströmmen med masterens ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templateStream | java.io.InputStream | template stream. |
| masterID | int | The unique ID of the master within masters collection in template. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Lägger till master i diagrammet från mallströmmen med masterens namn eller NameU.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templateStream | java.io.InputStream | template stream. |
| masterName | java.lang.String | Master's Name or NameU. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Lägger till master i diagrammet från mallfilen med masterens ID.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templateFilePath | java.lang.String | Sökväg till mallfil(can vara vdx, vst eller vsd-format). |
| masterID | int | The unique ID of the master within masters collection in template. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Lägger till master i diagrammet från mallfilen med masterens namn eller NameU.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templateFilePath | java.lang.String | Sökväg till mallfil(can vara vdx, vst eller vsd-format). |
| masterName | java.lang.String | Master's Name or NameU. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Lägger till en form skapad av master till en specifik sida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nytt figurobjekt[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Mästarens namn. |
| pageNumber | int | Sidans index. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Lägger till en form skapad av master på sidan med definierade PinX, PinY, bredd och höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger figurens bredd i tum. |
| höjd | double | Anger figurens höjd i tum. |
| masterName | java.lang.String | Mästarens namn. |
| pageNumber | int | Sidans index. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Lägger till en form skapad av master på sidan med definierade PinX och PinY.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| masterName | java.lang.String | Mästarens namn. |
| pageNumber | int | Sidans index. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Kombinerar ett annat Diagram-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Ett annat Diagram-objekt. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Kopierar tema från ett källdiagram.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | source diagram. |

### dispose() {#dispose--}
```
public void dispose()
```


Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exporterar diagrammet från vsd-ström till vdw-strömformat. Ej implementerat ännu.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd-ström. |
| outputVdw | java.io.InputStream | vdw-ström. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exporterar diagrammet från vsd-ström till \*.vdw-filformat. Ej implementerat ännu.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd filnamn. |
| outputVdw | java.lang.String | vdw-ström. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exporterar diagrammet från vsd-fil till vdw-strömformat. Ej implementerat ännu.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd filnamn. |
| outputVdw | java.io.InputStream | vdw-ström. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exporterar diagrammet från vsd till vdw-format. Ej implementerat ännu.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd filnamn. |
| outputVdw | java.lang.String | \*.vdw filnamn. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Anger den aktiva sidan

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Byggnumret för Visio-instansen som användes för att skapa dokumentet.

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


Innehåller dokumentets färgtabell. Varje dokument innehåller en enda färgtabell, som listar de 24 standardfärgerna som är tillgängliga för tillämpning på objekt såsom former, text och lager i dokumentet.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Innehåller DataConnection-elementen för dokumentet.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Samlingen av DataRecordset-objekt som är associerade med ett Document-objekt.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Hämta sökvägen till standardteckensnittsmappen

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


Det unika ID:t för det användargränssnittsspråk som användaren har angett i Microsoft Office 2010 Språkinställningar.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Innehåller element för dokumentegenskaper såsom dokumentets titel, författare osv.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Innehåller element som specificerar dokumentinställningar.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Anger ett dokuments ShapeSheet-struktur.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Innehåller ett MIME (Multipurpose Internet Mail Extensions) kodad MAPI e‑postrouting‑slipp för dokumentet.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Innehåller ett EventItem‑element för varje händelse som ett objekt ska svara på.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Innehåller en samling av Font‑element

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Innehåller element för ett dokuments sidhuvud och sidfot.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


avbrottsmontorn.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Anger om dokumentet har ändrats utanför Visio. Om närvarande kommer Visio att fullt ut testa filens innehåll. Utelämna för filer du skapar utanför Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Samling av Master‑objekt.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Om metriska enheter ska användas i ritningen. Ställ in detta attribut till True (1) för att använda metriska enheter; ställ in det till False (0) för att använda engelska enheter.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Samling av Page‑objekt.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


Ribbon‑XML‑strängen som skickas till dokumentet för att anpassa ribbon‑användargränssnittet.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML‑värde.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Anger om dokumentet har ändrats utanför Visio. Om närvarande kommer Visio att fullt ut testa filens innehåll. Utelämna för filer du skapar utanför Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Samling av StyleSheet‑objekt.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Hämta oanvända stilar

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


Ribbon‑XML‑strängen som skickas till dokumentet för att anpassa snabbåtkomstverktygsfältet eller ribbon.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Lagrar information om diagramvalidering för dokumentet.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Innehåller Microsoft Visual Basic for Applications‑projektdata i MIME (Multipurpose Internet Mail Extensions) kodat format.

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Hämtar VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Versionsnumret för Visio-instansen. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Innehåller Window‑elementen för ett dokument.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Anger om detta diagram har dold information.

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


Lägger ut formerna och/eller omdirigerar anslutningarna för alla diagram‑sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Använd [LayoutOptions](../../com.aspose.diagram/layoutoptions) för att konfigurera layoutalternativ. |

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


Skriv ut hela dokumentet till den angivna skrivaren,med den standard (utan användargränssnitt) utskriftskontrollen. Om printerName är Null eller tom kommer standardskrivaren att användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerName | java.lang.String | Skrivarnamnet.Can vara Null |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Skriv ut hela dokumentet till den angivna skrivaren,med den standard (utan användargränssnitt) utskriftskontrollen. Om printerName är Null eller tom kommer standardskrivaren att användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerName | java.lang.String | Skrivarnamnet.Can vara Null |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Utskriftsalternativen. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Skriver ut dokumentet, med den standard (utan användargränssnitt) utskriftskontrollen och ett dokumentnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerName | java.lang.String | Skrivarnamnet.Can vara Null |
| documentName | java.lang.String | Dokumentnamnet som ska visas (till exempel i en utskriftsstatusdialogruta eller skrivarkö) när dokumentet skrivs ut. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Skriver ut dokumentet, med den standard (utan användargränssnitt) utskriftskontrollen och ett dokumentnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| printerName | java.lang.String | Skrivarnamnet.Can vara Null |
| documentName | java.lang.String | Dokumentnamnet som ska visas (till exempel i en utskriftsstatusdialogruta eller skrivarkö) när dokumentet skrivs ut. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Utskriftsalternativen. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Ta bort oanvänd information

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Tar bort VBA/makro från detta diagram.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Spara diagrammet till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Filströmmen. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | Sparaalternativen. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Spara diagrammet till strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Filströmmen. |
| format | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Sparar dokumentet till en fil med de angivna sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) spara diagramalternativ. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Sparar diagramdata till filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| format | int | Aspose.Diagram.SaveFileFormat spara filformat. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


For the description of this property, please see [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


For the description of this property, please see [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


For the description of this property, please see [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Indicates the Fonts folder path

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


For the description of this property, please see [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


For the description of this property, please see [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


For the description of this property, please see [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


For the description of this property, please see [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


For the description of this property, please see [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


For the description of this property, please see [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


For the description of this property, please see [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


For the description of this property, please see [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

