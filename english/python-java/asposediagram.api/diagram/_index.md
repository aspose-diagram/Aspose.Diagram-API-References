---
title: "Diagram"
linktitle: "Diagram"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Root element of Visio objects hierarchy."
type: docs
weight: 890
url: /python-java/asposediagram.api/diagram/
---

## Diagram class

Root element of Visio objects hierarchy.

## Constructors

| Name | Description |
| --- | --- |
| [Diagram](#constructor) |  |
| [Diagram](#constructor) | Public class constructor, loads the diagram from the file. |
| [Diagram](#constructor) | Public class constructor, loads the diagram from the file using predefined format. |
| [Diagram](#constructor) | Public class constructor, loads the diagram from the file using predefined load file options. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Start](#start) | long | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [FontDirs](#fontdirs) | String[] | Indicates the Fonts folder path |
| [Key](#key) | String | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [Metric](#metric) | int | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [Buildnum](#buildnum) | long | The build number of the Visio instance used to create the document. |
| [Version](#version) | String | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [DocLangID](#doclangid) | int | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [StyleSheets](#stylesheets) | StyleSheetCollection | Collection StyleSheet objects. |
| [Masters](#masters) | MasterCollection | Collection Master objects. |
| [Pages](#pages) | PageCollection | Collection Page objects. |
| [DocumentProps](#documentprops) | DocumentProperties | Contains document property elements such as the document's title, author, and so on. |
| [DocumentSettings](#documentsettings) | DocumentSettings | Contains elements that specify document settings. |
| [Colors](#colors) | ColorEntryCollection | Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors tha |
| [Fonts](#fonts) | FontCollection | Contains a collection of Font elements |
| [DocumentSheet](#documentsheet) | DocumentSheet | Specifies a document's ShapeSheet structure. |
| [ActivePage](#activepage) | Page | Specifies the active page |
| [Windows](#windows) | WindowCollection | Contains the Window elements for a document. |
| [EventItems](#eventitems) | EventItemCollection | Contains an EventItem element for each event to which an object should respond. |
| [HeaderFooter](#headerfooter) | HeaderFooter | Contains elements for a document's header and footer. |
| [VbProjectData](#vbprojectdata) | byte[] | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [EmailRoutingData](#emailroutingdata) | byte[] | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [DataConnections](#dataconnections) | DataConnectionCollection | Contains the DataConnection elements for the document. |
| [DataRecordSets](#datarecordsets) | DataRecordSetCollection | The collection of DataRecordset objects associated with a Document object. |
| [RibbonX](#ribbonx) | String | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [UserCustomUI](#usercustomui) | String | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [Validation](#validation) | Validation | Stores information about diagram validation for the document. |
| [SolutionXMLs](#solutionxmls) | SolutionXMLCollection | XML value. |
| [VbaProject](#vbaproject) | VbaProject | Gets the VbaProject VbaProject . |
| [InterruptMonitor](#interruptmonitor) | AbstractInterruptMonitor | Gets and sets the interrupt monitor. |

## Methods

| Name | Description |
| --- | --- |
| [save](#save) | Saves the diagram data to the file. |
| [dispose](#dispose) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [copyTheme](#copytheme) | Copies Theme from a source Diagram. |
| [combine](#combine) | Combines another Diagram object. |
| [addMaster](#addmaster) | Adds master to diagram from source diagram by master's Name or NameU. |
| [hasHiddenInfo](#hashiddeninfo) | Indicates whether this diagram has hidden information. |
| [removeHiddenInformation](#removehiddeninformation) | Remove unused information |
| [getUnusedStyles](#getunusedstyles) | Get unused Styles |
| [addShape](#addshape) | Adds shape created by master to specific page. |
| [print](#print) | Print the whole document to the specified printer,using the standard (no User Interface) print controller.

If printerNa |
| [getDefaultFontDir](#getdefaultfontdir) | Get the Default Fonts folder path |
| [removeMacro](#removemacro) | Removes VBA/macro from this diagram. |

### Diagram() (1 of 4) {#constructor}

---

### Diagram(filename) (2 of 4) {#constructor-1}

Public class constructor, loads the diagram from the file.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |

---

### Diagram(filename, format) (3 of 4) {#constructor-2}

Public class constructor, loads the diagram from the file using predefined format.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| format | int | A LoadFileFormat value. The file format. |

---

### Diagram(filename, options) (4 of 4) {#constructor-3}

Public class constructor, loads the diagram from the file using predefined load file options.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| options | LoadOptions | The data LoadOptions . |

### Diagram.Start property {#start}

Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

**Type:** long

### Diagram.FontDirs property {#fontdirs}

Indicates the Fonts folder path

**Type:** String[]

### Diagram.Key property {#key}

Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

**Type:** String

### Diagram.Metric property {#metric}

Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units. The value of the property is BOOL integer constant.

**Type:** int

### Diagram.Buildnum property {#buildnum}

The build number of the Visio instance used to create the document.

**Type:** long

### Diagram.Version property {#version}

The version number of the Visio instance. Microsoft Visio 2010 = 14.

**Type:** String

### Diagram.DocLangID property {#doclangid}

The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences.

**Type:** int

### Diagram.StyleSheets property {#stylesheets}

Collection StyleSheet objects.

**Type:** StyleSheetCollection

### Diagram.Masters property {#masters}

Collection Master objects.

**Type:** MasterCollection

### Diagram.Pages property {#pages}

Collection Page objects.

**Type:** PageCollection

### Diagram.DocumentProps property {#documentprops}

Contains document property elements such as the document's title, author, and so on.

**Type:** DocumentProperties

### Diagram.DocumentSettings property {#documentsettings}

Contains elements that specify document settings.

**Type:** DocumentSettings

### Diagram.Colors property {#colors}

Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors that are available for application to objects such as shapes, text, and layers in the document.

**Type:** ColorEntryCollection

### Diagram.Fonts property {#fonts}

Contains a collection of Font elements

**Type:** FontCollection

### Diagram.DocumentSheet property {#documentsheet}

Specifies a document's ShapeSheet structure.

**Type:** DocumentSheet

### Diagram.ActivePage property {#activepage}

Specifies the active page

**Type:** Page

### Diagram.Windows property {#windows}

Contains the Window elements for a document.

**Type:** WindowCollection

### Diagram.EventItems property {#eventitems}

Contains an EventItem element for each event to which an object should respond.

**Type:** EventItemCollection

### Diagram.HeaderFooter property {#headerfooter}

Contains elements for a document's header and footer.

**Type:** HeaderFooter

### Diagram.VbProjectData property {#vbprojectdata}

Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format.

**Type:** byte[]

### Diagram.EmailRoutingData property {#emailroutingdata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document.

**Type:** byte[]

### Diagram.DataConnections property {#dataconnections}

Contains the DataConnection elements for the document.

**Type:** DataConnectionCollection

### Diagram.DataRecordSets property {#datarecordsets}

The collection of DataRecordset objects associated with a Document object.

**Type:** DataRecordSetCollection

### Diagram.RibbonX property {#ribbonx}

The Ribbon XML string that is passed to the document to customize the ribbon user interface.

**Type:** String

### Diagram.UserCustomUI property {#usercustomui}

The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon.

**Type:** String

### Diagram.Validation property {#validation}

Stores information about diagram validation for the document.

**Type:** Validation

### Diagram.SolutionXMLs property {#solutionxmls}

XML value.

**Type:** SolutionXMLCollection

### Diagram.VbaProject property {#vbaproject}

Gets the VbaProject VbaProject .

**Type:** VbaProject

### Diagram.InterruptMonitor property {#interruptmonitor}

Gets and sets the interrupt monitor.

**Type:** AbstractInterruptMonitor

### save(filename, format) {#save}

Saves the diagram data to the file.

| Parameter | Type | Description |
| --- | --- | --- |
| filename | String | The file name. |
| format | int | A SaveFileFormat value. SaveFileFormat save file format. |

### dispose() {#dispose}

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### copyTheme(source) {#copytheme}

Copies Theme from a source Diagram.

| Parameter | Type | Description |
| --- | --- | --- |
| source | Diagram | source diagram. |

### combine(secondDiagram) {#combine}

Combines another Diagram object.

| Parameter | Type | Description |
| --- | --- | --- |
| secondDiagram | Diagram | Another Diagram object. |

### addMaster(srcDiagram, masterName) (1 of 3) {#addmaster}

Adds master to diagram from source diagram by master's Name or NameU.

| Parameter | Type | Description |
| --- | --- | --- |
| srcDiagram | Diagram | source diagram. |
| masterName | String | Master's Name or NameU. |

**Returns:** The unique ID of the master within masters collection in this diagram.

**Example:**

```python
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

---

### addMaster(templateFilePath, masterName) (2 of 3) {#addmaster-1}

Adds master to diagram from template file by master's Name or NameU.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterName | String | Master's Name or NameU. |

**Returns:** The unique ID of the master within masters collection in this diagram.

**Example:**

```python
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

---

### addMaster(templateFilePath, masterID) (3 of 3) {#addmaster-2}

Adds master to diagram from template file by master's ID.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterID | int | The unique ID of the master within masters collection in template. |

**Returns:** The unique ID of the master within masters collection in this diagram.

**Example:**

```python
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

### hasHiddenInfo() {#hashiddeninfo}

Indicates whether this diagram has hidden information.

### removeHiddenInformation(item) {#removehiddeninformation}

Remove unused information

| Parameter | Type | Description |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### getUnusedStyles() {#getunusedstyles}

Get unused Styles

### addShape(newShape, masterName, pageNumber) (1 of 3) {#addshape}

Adds shape created by master to specific page.

| Parameter | Type | Description |
| --- | --- | --- |
| newShape | Shape | New shape object Shape . |
| masterName | String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### addShape(pinX, pinY, masterName, pageNumber) (2 of 3) {#addshape-1}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

**Example:**

```python
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

---

### addShape(pinX, pinY, width, height, masterName, pageNumber) (3 of 3) {#addshape-2}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape in inches. |
| height | float | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

**Example:**

```python
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

### print(printerName) (1 of 2) {#print}

Print the whole document to the specified printer,using the standard (no User Interface) print controller.

If printerName is Null or empty will be used default printer.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |

---

### print(printerName, documentName) (2 of 2) {#print-1}

Prints the document,using the standard (no User Interface) print controller and a document name.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |
| documentName | String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("Pages.vsdx");

// call the print method to print whole Diagram using the printer name
// and set document name in the print job
diagram.print("Microsoft Print to PDF", "Job name while printing with Aspose.Diagram");
```

### getDefaultFontDir() {#getdefaultfontdir}

Get the Default Fonts folder path

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveFontInfo.vsd");
console.log(diagram.getDefaultFontDir());
```

### removeMacro() {#removemacro}

Removes VBA/macro from this diagram.
