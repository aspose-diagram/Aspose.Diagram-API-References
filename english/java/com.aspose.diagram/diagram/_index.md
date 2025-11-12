---
title: Diagram
second_title: Aspose.Diagram for Java API Reference
description: Root element of Visio objects hierarchy.
type: docs
weight: 119
url: /java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Root element of Visio objects hierarchy.
## Constructors

| Constructor | Description |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Public class constructor, loads the diagram from the file. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Public class constructor, loads the diagram from the stream. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Public class constructor, loads the diagram from the stream using predefined format. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Public class constructor, loads the diagram from the stream using predefined load file options. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Public class constructor, loads the diagram from the file using predefined format. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Public class constructor, loads the diagram from the file using predefined load file options. |
## Methods

| Method | Description |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Adds master to diagram from source diagram by master's Name or NameU. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Adds master to diagram from template stream by master's ID. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Adds master to diagram from template stream by master's Name or NameU. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Adds master to diagram from template file by master's ID. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Adds master to diagram from template file by master's Name or NameU. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Adds shape created by master to specific page. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Adds shape created by master on page with defined PinX and PinY. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Combines another Diagram object. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Copies Theme from a source Diagram. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Exports the diagram from vsd stream to vdw stream format. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Exports the diagram from vsd stream to \*.vdw file format. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Exports the diagram from vsd file to vdw stream format. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Exports the diagram from vsd to vdw format. |
| [getActivePage()](#getActivePage--) | Specifies the active page |
| [getBuildnum()](#getBuildnum--) | The build number of the Visio instance used to create the document. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Contains the document's color table. |
| [getDataConnections()](#getDataConnections--) | Contains the DataConnection elements for the document. |
| [getDataRecordSets()](#getDataRecordSets--) | The collection of DataRecordset objects associated with a Document object. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Get the Default Fonts folder path |
| [getDocLangID()](#getDocLangID--) | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [getDocumentProps()](#getDocumentProps--) | Contains document property elements such as the document's title, author, and so on. |
| [getDocumentSettings()](#getDocumentSettings--) | Contains elements that specify document settings. |
| [getDocumentSheet()](#getDocumentSheet--) | Specifies a document's ShapeSheet structure. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [getEventItems()](#getEventItems--) | Contains an EventItem element for each event to which an object should respond. |
| [getFonts()](#getFonts--) | Contains a collection of Font elements |
| [getHeaderFooter()](#getHeaderFooter--) | Contains elements for a document's header and footer. |
| [getInterruptMonitor()](#getInterruptMonitor--) | the interrupt monitor. |
| [getKey()](#getKey--) | Indicates whether the document has been modified outside of Visio. |
| [getMasters()](#getMasters--) | Collection Master objects. |
| [getMetric()](#getMetric--) | Whether to use metric units in the drawing. |
| [getPages()](#getPages--) | Collection Page objects. |
| [getRibbonX()](#getRibbonX--) | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML value. |
| [getStart()](#getStart--) | Indicates whether the document has been modified outside of Visio. |
| [getStyleSheets()](#getStyleSheets--) | Collection StyleSheet objects. |
| [getUnusedStyles()](#getUnusedStyles--) | Get unused Styles |
| [getUserCustomUI()](#getUserCustomUI--) | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [getValidation()](#getValidation--) | Stores information about diagram validation for the document. |
| [getVbProjectData()](#getVbProjectData--) | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format. |
| [getVbaProject()](#getVbaProject--) | Gets the VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | The version number of the Visio instance. |
| [getWindows()](#getWindows--) | Contains the Window elements for a document. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Indicates whether this diagram has hidden information. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Lays out the shapes and/or reroutes the connectors for all pages of diagram. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Remove unused information |
| [removeMacro()](#removeMacro--) | Removes VBA/macro from this diagram. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Save the diagram to the stream. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Save the diagram to the stream. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Saves the document to a file using the specified save options. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the diagram data to the file. |
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


Public class constructor, loads the diagram from the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The file name. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Public class constructor, loads the diagram from the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The data stream. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Public class constructor, loads the diagram from the stream using predefined format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The data stream. |
| format | int | The data Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Public class constructor, loads the diagram from the stream using predefined load file options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The data stream. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | The data [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Public class constructor, loads the diagram from the file using predefined format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| format | int | The file format. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Public class constructor, loads the diagram from the file using predefined load file options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | The data [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Adds master to diagram from source diagram by master's Name or NameU.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | source diagram. |
| masterName | java.lang.String | Master's Name or NameU. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Adds master to diagram from template stream by master's ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templateStream | java.io.InputStream | template stream. |
| masterID | int | The unique ID of the master within masters collection in template. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Adds master to diagram from template stream by master's Name or NameU.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templateStream | java.io.InputStream | template stream. |
| masterName | java.lang.String | Master's Name or NameU. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Adds master to diagram from template file by master's ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | java.lang.String | Path to template file(can be vdx, vst or vsd format). |
| masterID | int | The unique ID of the master within masters collection in template. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Adds master to diagram from template file by master's Name or NameU.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | java.lang.String | Path to template file(can be vdx, vst or vsd format). |
| masterName | java.lang.String | Master's Name or NameU. |

**Returns:**
int - The unique ID of the master within masters collection in this diagram.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Adds shape created by master to specific page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | New shape object[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Adds shape created by master on page with defined PinX,PinY,Width and Height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape in inches. |
| height | double | Specifies the height of the shape in inches. |
| masterName | java.lang.String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Adds shape created by master on page with defined PinX and PinY.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | java.lang.String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Combines another Diagram object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Another Diagram object. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Copies Theme from a source Diagram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | source diagram. |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exports the diagram from vsd stream to vdw stream format. Not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd stream. |
| outputVdw | java.io.InputStream | vdw stream. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exports the diagram from vsd stream to \*.vdw file format. Not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd file name. |
| outputVdw | java.lang.String | vdw stream. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exports the diagram from vsd file to vdw stream format. Not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd file name. |
| outputVdw | java.io.InputStream | vdw stream. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exports the diagram from vsd to vdw format. Not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd file name. |
| outputVdw | java.lang.String | \*.vdw file name. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Specifies the active page

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


The build number of the Visio instance used to create the document.

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


Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors that are available for application to objects such as shapes, text, and layers in the document.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Contains the DataConnection elements for the document.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


The collection of DataRecordset objects associated with a Document object.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public ArrayList getDefaultFontDir()
```


Get the Default Fonts folder path

**Returns:**
java.util.ArrayList
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Contains document property elements such as the document's title, author, and so on.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Contains elements that specify document settings.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Specifies a document's ShapeSheet structure.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Contains an EventItem element for each event to which an object should respond.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Contains a collection of Font elements

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Contains elements for a document's header and footer.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


the interrupt monitor.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Collection Master objects.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Collection Page objects.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


The Ribbon XML string that is passed to the document to customize the ribbon user interface.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML value.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Collection StyleSheet objects.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Get unused Styles

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Stores information about diagram validation for the document.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format.

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Gets the VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


The version number of the Visio instance. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Contains the Window elements for a document.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Indicates whether this diagram has hidden information.

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


Lays out the shapes and/or reroutes the connectors for all pages of diagram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Using the [LayoutOptions](../../com.aspose.diagram/layoutoptions) to configure options of layout. |

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


Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerName is Null or empty will be used default printer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerName is Null or empty will be used default printer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | The print options. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Prints the document,using the standard (no User Interface) print controller and a document name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |
| documentName | java.lang.String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Prints the document,using the standard (no User Interface) print controller and a document name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |
| documentName | java.lang.String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | The print options. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Remove unused information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Removes VBA/macro from this diagram.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Save the diagram to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The file stream. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | The save options. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Save the diagram to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The file stream. |
| format | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Saves the document to a file using the specified save options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) save diagram options. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Saves the diagram data to the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The file name. |
| format | int | Aspose.Diagram.SaveFileFormat save file format. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


For the description of this property, please see [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


For the description of this property, please see [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


For the description of this property, please see [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Indicates the Fonts folder path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


For the description of this property, please see [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


For the description of this property, please see [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


For the description of this property, please see [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


For the description of this property, please see [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


For the description of this property, please see [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


For the description of this property, please see [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


For the description of this property, please see [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


For the description of this property, please see [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

