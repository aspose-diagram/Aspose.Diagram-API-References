---
title: "Diagram"
linktitle: "Diagram"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Root element of Visio objects hierarchy."
type: docs
weight: 630
url: /nodejs/aspose.diagram/diagram/
---

## Diagram class

Root element of Visio objects hierarchy.

```js
new Diagram()
```

## Methods

| Name | Description |
| --- | --- |
| [createDiagramFromStream(stream, callback)](#creatediagramfromstream) *(static)* | Public class constructor, loads the diagram from the stream. |
| [createDiagramFromStream(stream, format, callback)](#creatediagramfromstream-1) *(static)* | Public class constructor, loads the diagram from the stream using predefined format. |
| [createDiagramFromStream(stream, options, callback)](#creatediagramfromstream-2) *(static)* | Public class constructor, loads the diagram from the file using predefined load file options. |
| [save(diagram, stream, saveFormat)](#save) *(static)* | Saves the diagram data to the stream. |
| [save(diagram, stream, options)](#save-1) *(static)* | Saves the diagram to a file using the specified save options. |
| [addMaster(srcDiagram, masterName)](#addmaster) | Adds master to diagram from source diagram by master's Name or NameU. |
| [addMaster(templateFilePath, masterName)](#addmaster-1) | Adds master to diagram from template file by master's Name or NameU. |
| [addMaster(templateFilePath, masterID)](#addmaster-2) | Adds master to diagram from template file by master's ID. |
| [addShape(newShape, masterName, pageNumber)](#addshape) | Adds shape created by master to specific page. |
| [addShape(pinX, pinY, masterName, pageNumber)](#addshape-1) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, width, height, masterName, pageNumber)](#addshape-2) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [combine(secondDiagram)](#combine) | Combines another Diagram object. |
| [constructor_overload$1(filename)](#constructor-overload1) | Public class constructor, loads the diagram from the file. |
| [constructor_overload$2(filename, format)](#constructor-overload2) | Public class constructor, loads the diagram from the file using predefined format. |
| [constructor_overload$3(filename, options)](#constructor-overload3) | Public class constructor, loads the diagram from the file using predefined load file options. |
| [copyTheme(source)](#copytheme) | Copies Theme from a source Diagram. |
| [dispose()](#dispose) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getActivePage()](#getactivepage) | Specifies the active page |
| [getBuildnum()](#getbuildnum) | The build number of the Visio instance used to create the document. |
| [getColors()](#getcolors) | Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors tha |
| [getDataConnections()](#getdataconnections) | Contains the DataConnection elements for the document. |
| [getDataRecordSets()](#getdatarecordsets) | The collection of DataRecordset objects associated with a Document object. |
| [getDefaultFontDir()](#getdefaultfontdir) | Get the Default Fonts folder path |
| [getDocLangID()](#getdoclangid) | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [getDocumentProps()](#getdocumentprops) | Contains document property elements such as the document's title, author, and so on. |
| [getDocumentSettings()](#getdocumentsettings) | Contains elements that specify document settings. |
| [getDocumentSheet()](#getdocumentsheet) | Specifies a document's ShapeSheet structure. |
| [getEmailRoutingData()](#getemailroutingdata) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [getEventItems()](#geteventitems) | Contains an EventItem element for each event to which an object should respond. |
| [getFonts()](#getfonts) | Contains a collection of Font elements |
| [getHeaderFooter()](#getheaderfooter) | Contains elements for a document's header and footer. |
| [getInterruptMonitor()](#getinterruptmonitor) | Gets and sets the interrupt monitor. |
| [getKey()](#getkey) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [getMasters()](#getmasters) | Collection Master objects. |
| [getMetric()](#getmetric) | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [getPages()](#getpages) | Collection Page objects. |
| [getRibbonX()](#getribbonx) | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [getSolutionXMLs()](#getsolutionxmls) | XML value. |
| [getStart()](#getstart) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [getStyleSheets()](#getstylesheets) | Collection StyleSheet objects. |
| [getUnusedStyles()](#getunusedstyles) | Get unused Styles |
| [getUserCustomUI()](#getusercustomui) | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [getValidation()](#getvalidation) | Stores information about diagram validation for the document. |
| [getVbaProject()](#getvbaproject) | Gets the VbaProjectVbaProject. |
| [getVbProjectData()](#getvbprojectdata) | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [getVersion()](#getversion) | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [getWindows()](#getwindows) | Contains the Window elements for a document. |
| [hasHiddenInfo()](#hashiddeninfo) | Indicates whether this diagram has hidden information. |
| [layout(options)](#layout) | Lays out the shapes and/or reroutes the connectors for all pages of diagram. |
| [print(printerName)](#print) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerNam |
| [print(printerName, options)](#print-1) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerNam |
| [print(printerName, documentName, options)](#print-2) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [print(printerName, documentName)](#print-3) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [removeHiddenInformation(item)](#removehiddeninformation) | Remove unused information |
| [removeMacro()](#removemacro) | Removes VBA/macro from this diagram. |
| [save(filename, format)](#save-2) | Saves the diagram data to the file. |
| [save(stream, saveOptions)](#save-3) | Save the diagram to the stream. |
| [save(filename, options)](#save-4) | Saves the document to a file using the specified save options. |
| [setBuildnum()](#setbuildnum) | The build number of the Visio instance used to create the document. |
| [setDocLangID()](#setdoclangid) | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [setEmailRoutingData()](#setemailroutingdata) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [setFontDirs()](#setfontdirs) | Indicates the Fonts folder path |
| [setInterruptMonitor()](#setinterruptmonitor) | Gets and sets the interrupt monitor. |
| [setKey()](#setkey) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [setMetric()](#setmetric) | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [setRibbonX()](#setribbonx) | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [setStart()](#setstart) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [setUserCustomUI()](#setusercustomui) | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [setVbProjectData()](#setvbprojectdata) | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [setVersion()](#setversion) | The version number of the Visio instance. Microsoft Visio 2010 = 14. |

### createDiagramFromStream(stream, callback) (static) {#creatediagramfromstream}

Public class constructor, loads the diagram from the stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The data stream |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
aspose.diagram.Diagram.createDiagramFromStream(readStream, function(diagram, err) {
if (err) {
console.log("open error");
return;
}
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```

### createDiagramFromStream(stream, format, callback) (static) {#creatediagramfromstream-1}

Public class constructor, loads the diagram from the stream using predefined format.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The data stream |
| format | Number | A |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
aspose.diagram.Diagram.createDiagramFromStream(readStream, aspose.diagram.LoadFileFormat.VSDX, function(diagram, err) {
if (err) {
console.log("open error");
return;
}
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```

### createDiagramFromStream(stream, options, callback) (static) {#creatediagramfromstream-2}

Public class constructor, loads the diagram from the file using predefined load file options.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The data stream |
| options | LoadOptions | The data |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
options = new aspose.diagram.LoadOptions(aspose.diagram.LoadFileFormat.VSDX);
aspose.diagram.Diagram.createDiagramFromStream(readStream, options, function(diagram, err) {
if (err) {
console.log("open error: " + err);
return;
}
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```

### save(diagram, stream, saveFormat) (static) {#save}

Saves the diagram data to the stream.

| Parameter | Type | Description |
| --- | --- | --- |
| diagram | Diagram | The diagram object to save |
| stream | WritableStream | The stream |
| saveFormat | Number | A |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var writeStream = fs.createWriteStream("output-stream.vsdx");
aspose.diagram.Diagram.saveToStream(diagram, writeStream, aspose.diagram.SaveFileFormat.VSDX);
```

### save(diagram, stream, options) (static) {#save-1}

Saves the diagram to a file using the specified save options.

| Parameter | Type | Description |
| --- | --- | --- |
| diagram | Diagram | The diagram object to save |
| stream | WritableStream | The stream |
| options | SaveOptions | SaveOptions |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var writeStream = fs.createWriteStream("output-stream.vsdx");
var options = new aspose.diagram.DiagramSaveOptions(aspose.diagram.SaveFileFormat.VSDX);
aspose.diagram.Diagram.saveToStream(diagram, writeStream, options);
```

### addMaster(srcDiagram, masterName) {#addmaster}

Adds master to diagram from source diagram by master's Name or NameU.

| Parameter | Type | Description |
| --- | --- | --- |
| srcDiagram | Diagram | source diagram. |
| masterName | String | Master's Name or NameU. |

**Returns:** Number — `Number` The unique ID of the master within masters collection in this diagram.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";
// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);
// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);
// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);
// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);
// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);
// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### addMaster(templateFilePath, masterName) {#addmaster-1}

Adds master to diagram from template file by master's Name or NameU.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterName | String | Master's Name or NameU. |

**Returns:** Number — `Number` The unique ID of the master within masters collection in this diagram.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";
// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);
// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);
// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);
// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);
// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);
// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### addMaster(templateFilePath, masterID) {#addmaster-2}

Adds master to diagram from template file by master's ID.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterID | Number | The unique ID of the master within masters collection in template. |

**Returns:** Number — `Number` The unique ID of the master within masters collection in this diagram.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";
// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);
// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);
// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);
// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);
// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);
// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### addShape(newShape, masterName, pageNumber) {#addshape}

Adds shape created by master to specific page.

| Parameter | Type | Description |
| --- | --- | --- |
| newShape | Shape | New shape object |
| masterName | String | Master's name. |
| pageNumber | Number | Index of page. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### addShape(pinX, pinY, masterName, pageNumber) {#addshape-1}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |
| pageNumber | Number | Index of page. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";
// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);
// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);
// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);
// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);
// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);
// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### addShape(pinX, pinY, width, height, masterName, pageNumber) {#addshape-2}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape in inches. |
| height | Number | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |
| pageNumber | Number | Index of page. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";
// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);
// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);
// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);
// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);
// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);
// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### combine(secondDiagram) {#combine}

Combines another Diagram object.

| Parameter | Type | Description |
| --- | --- | --- |
| secondDiagram | Diagram | Another Diagram object. |

### constructor_overload$1(filename) {#constructor-overload1}

Public class constructor, loads the diagram from the file.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |

### constructor_overload$2(filename, format) {#constructor-overload2}

Public class constructor, loads the diagram from the file using predefined format.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| format | Number | LoadFileFormat |

### constructor_overload$3(filename, options) {#constructor-overload3}

Public class constructor, loads the diagram from the file using predefined load file options.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| options | LoadOptions | The data |

### copyTheme(source) {#copytheme}

Copies Theme from a source Diagram.

| Parameter | Type | Description |
| --- | --- | --- |
| source | Diagram | source diagram. |

### dispose() {#dispose}

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### getActivePage() {#getactivepage}

Specifies the active page

### getBuildnum() {#getbuildnum}

The build number of the Visio instance used to create the document.

### getColors() {#getcolors}

Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors that are available for application to objects such as shapes, text, and layers in the document.

### getDataConnections() {#getdataconnections}

Contains the DataConnection elements for the document.

### getDataRecordSets() {#getdatarecordsets}

The collection of DataRecordset objects associated with a Document object.

### getDefaultFontDir() {#getdefaultfontdir}

Get the Default Fonts folder path

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveFontInfo.vsd");
console.log(diagram.getDefaultFontDir());
```

### getDocLangID() {#getdoclangid}

The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences.

### getDocumentProps() {#getdocumentprops}

Contains document property elements such as the document's title, author, and so on.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Introduction.vsdx");
// Display Visio version and document modification time at different stages
console.log("Visio Instance Version : " + diagram.getVersion());
console.log("Full Build Number Created : " + diagram.getDocumentProps().getBuildNumberCreated());
console.log("Full Build Number Edited : " + diagram.getDocumentProps().getBuildNumberEdited());
console.log("Date Created : " + diagram.getDocumentProps().getTimeCreated());
console.log("Date Last Edited : " + diagram.getDocumentProps().getTimeEdited());
console.log("Date Last Printed : " + diagram.getDocumentProps().getTimePrinted());
console.log("Date Last Saved : " + diagram.getDocumentProps().getTimeSaved());
```

### getDocumentSettings() {#getdocumentsettings}

Contains elements that specify document settings.

### getDocumentSheet() {#getdocumentsheet}

Specifies a document's ShapeSheet structure.

### getEmailRoutingData() {#getemailroutingdata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document.

### getEventItems() {#geteventitems}

Contains an EventItem element for each event to which an object should respond.

### getFonts() {#getfonts}

Contains a collection of Font elements

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveFontInfo.vsd");
fonts = diagram.getFonts();
for (var it = fonts.iterator(); it.hasNext();) {
font = it.next();
// Display information about the fonts
console.log(font.getName());
}
```

### getHeaderFooter() {#getheaderfooter}

Contains elements for a document's header and footer.

### getInterruptMonitor() {#getinterruptmonitor}

Gets and sets the interrupt monitor.

### getKey() {#getkey}

Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

### getMasters() {#getmasters}

Collection Master objects.

### getMetric() {#getmetric}

Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units. The value of the property is BOOL integer constant.

### getPages() {#getpages}

Collection Page objects.

### getRibbonX() {#getribbonx}

The Ribbon XML string that is passed to the document to customize the ribbon user interface.

### getSolutionXMLs() {#getsolutionxmls}

XML value.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("SolutionXML.vsdx");
// iterate through SolutionXML elements
for (it = diagram.getSolutionXMLs().iterator(); it.hasNext();) {
solutionXML = it.next();
// get name property
console.log(solutionXML.getName());
// get xml value
console.log(solutionXML.getXmlValue());
}
```

### getStart() {#getstart}

Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

### getStyleSheets() {#getstylesheets}

Collection StyleSheet objects.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ApplyCustomStyleSheets.vsd");
sourceShape = null;
// get page by name
page = diagram.getPages().getPage("Flow 1");
// Find the shape that you want to apply style to
for (it = page.getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getName() == "Process") {
sourceShape = shape;
break;
}
}
customStyleSheet = null;
// Find the required style sheet
for (it = diagram.getStyleSheets().iterator(); it.hasNext();) {
styleSheet = it.next();
if (styleSheet.getName() == "Callout") {
customStyleSheet = styleSheet;
break;
}
}
if (sourceShape != null && customStyleSheet != null) {
// Apply text style
sourceShape.setTextStyle(customStyleSheet);
// Apply fill style
sourceShape.setFillStyle(customStyleSheet);
// Apply line style
sourceShape.setLineStyle(customStyleSheet);
}
diagram.save("out-ApplyCustomStyleSheets.vdx", aspose.diagram.SaveFileFormat.VDX);
```

### getUnusedStyles() {#getunusedstyles}

Get unused Styles

### getUserCustomUI() {#getusercustomui}

The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon.

### getValidation() {#getvalidation}

Stores information about diagram validation for the document.

### getVbaProject() {#getvbaproject}

Gets the VbaProjectVbaProject.

### getVbProjectData() {#getvbprojectdata}

Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Macro.vsdm");
// remove all macros
diagram.setVbProjectData(null);
// save the Visio diagram
diagram.save("out-RemoveMacros.vssm", aspose.diagram.SaveFileFormat.VSSM);
```

### getVersion() {#getversion}

The version number of the Visio instance. Microsoft Visio 2010 = 14.

### getWindows() {#getwindows}

Contains the Window elements for a document.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// iterate through the window elements
for (it = diagram.getWindows().iterator(); it.hasNext();) {
window = it.next();
console.log("ID: " + window.getID());
console.log("Type: " + window.getWindowType());
console.log("Window height: " + window.getWindowHeight());
console.log("Window width: " + window.getWindowWidth());
console.log("Window state: " + window.getWindowState());
}
```

### hasHiddenInfo() {#hashiddeninfo}

Indicates whether this diagram has hidden information.

### layout(options) {#layout}

Lays out the shapes and/or reroutes the connectors for all pages of diagram.

| Parameter | Type | Description |
| --- | --- | --- |
| options | LayoutOptions | Using the |

### print(printerName) {#print}

Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerName is Null or empty will be used default printer.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |

### print(printerName, options) {#print-1}

Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerName is Null or empty will be used default printer.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |
| options | PrintSaveOptions | The print options. |

### print(printerName, documentName, options) {#print-2}

Prints the document,using the standard (no User Interface) print controller and a document name.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |
| documentName | String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |
| options | PrintSaveOptions | The print options. |

### print(printerName, documentName) {#print-3}

Prints the document,using the standard (no User Interface) print controller and a document name.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |
| documentName | String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// call the print method to print whole Diagram using the printer name
// and set document name in the print job
diagram.print("Microsoft Print to PDF", "Job name while printing with Aspose.Diagram");
```

### removeHiddenInformation(item) {#removehiddeninformation}

Remove unused information

| Parameter | Type | Description |
| --- | --- | --- |
| item | Number | RemoveHiddenInfoItem. |

### removeMacro() {#removemacro}

Removes VBA/macro from this diagram.

### save(filename, format) {#save-2}

Saves the diagram data to the file.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| format | Number | SaveFileFormat |

### save(stream, saveOptions) {#save-3}

Save the diagram to the stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | OutputStream | The file stream. |
| saveOptions | SaveOptions | The save options. |

### save(filename, options) {#save-4}

Saves the document to a file using the specified save options.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| options | SaveOptions | SaveOptions |

### setBuildnum() {#setbuildnum}

The build number of the Visio instance used to create the document.

### setDocLangID() {#setdoclangid}

The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences.

### setEmailRoutingData() {#setemailroutingdata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document.

### setFontDirs() {#setfontdirs}

Indicates the Fonts folder path

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fontDirs = ["C:\\MyFonts\\", "D:\\Misc\\Fonts\\"];
diagram = new aspose.diagram.Diagram("SpecifyFontLocation.vsdx");
// setting the custom font directories
diagram.setFontDirs(fontDirs);
// saving Visio diagram in PDF format
diagram.save("out-SpecifyFontLocation.pdf", aspose.diagram.SaveFileFormat.PDF);
```

### setInterruptMonitor() {#setinterruptmonitor}

Gets and sets the interrupt monitor.

### setKey() {#setkey}

Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

### setMetric() {#setmetric}

Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units. The value of the property is BOOL integer constant.

### setRibbonX() {#setribbonx}

The Ribbon XML string that is passed to the document to customize the ribbon user interface.

### setStart() {#setstart}

Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

### setUserCustomUI() {#setusercustomui}

The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon.

### setVbProjectData() {#setvbprojectdata}

Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Macro.vsdm");
// remove all macros
diagram.setVbProjectData(null);
// save the Visio diagram
diagram.save("out-RemoveMacros.vssm", aspose.diagram.SaveFileFormat.VSSM);
```

### setVersion() {#setversion}

The version number of the Visio instance. Microsoft Visio 2010 = 14.
