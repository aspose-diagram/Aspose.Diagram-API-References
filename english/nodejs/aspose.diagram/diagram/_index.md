---
title: "Diagram Class"
linktitle: "Diagram"
articleTitle: "Diagram"
second_title: "Aspose.Diagram for Node.js via Java"
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
| [createDiagramFromStream(stream, callback)](./creatediagramfromstream/) *(static)* | Public class constructor, loads the diagram from the stream. |
| [createDiagramFromStream(stream, format, callback)](./creatediagramfromstream-1/) *(static)* | Public class constructor, loads the diagram from the stream using predefined format. |
| [createDiagramFromStream(stream, options, callback)](./creatediagramfromstream-2/) *(static)* | Public class constructor, loads the diagram from the file using predefined load file options. |
| [save(diagram, stream, saveFormat)](./save/) *(static)* | Saves the diagram data to the stream. |
| [save(diagram, stream, options)](./save-1/) *(static)* | Saves the diagram to a file using the specified save options. |
| [addMaster(srcDiagram, masterName)](./addmaster/) | Adds master to diagram from source diagram by master's Name or NameU. |
| [addMaster(templateFilePath, masterName)](./addmaster-1/) | Adds master to diagram from template file by master's Name or NameU. |
| [addMaster(templateFilePath, masterID)](./addmaster-2/) | Adds master to diagram from template file by master's ID. |
| [addShape(newShape, masterName, pageNumber)](./addshape/) | Adds shape created by master to specific page. |
| [addShape(pinX, pinY, masterName, pageNumber)](./addshape-1/) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, width, height, masterName, pageNumber)](./addshape-2/) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [combine(secondDiagram)](./combine/) | Combines another Diagram object. |
| [constructor_overload$1(filename)](./constructor-overload1/) | Public class constructor, loads the diagram from the file. |
| [constructor_overload$2(filename, format)](./constructor-overload2/) | Public class constructor, loads the diagram from the file using predefined format. |
| [constructor_overload$3(filename, options)](./constructor-overload3/) | Public class constructor, loads the diagram from the file using predefined load file options. |
| [copyTheme(source)](./copytheme/) | Copies Theme from a source Diagram. |
| [dispose()](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getActivePage()](./getactivepage/) | Specifies the active page |
| [getBuildnum()](./getbuildnum/) | The build number of the Visio instance used to create the document. |
| [getColors()](./getcolors/) | Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors tha |
| [getDataConnections()](./getdataconnections/) | Contains the DataConnection elements for the document. |
| [getDataRecordSets()](./getdatarecordsets/) | The collection of DataRecordset objects associated with a Document object. |
| [getDefaultFontDir()](./getdefaultfontdir/) | Get the Default Fonts folder path |
| [getDocLangID()](./getdoclangid/) | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [getDocumentProps()](./getdocumentprops/) | Contains document property elements such as the document's title, author, and so on. |
| [getDocumentSettings()](./getdocumentsettings/) | Contains elements that specify document settings. |
| [getDocumentSheet()](./getdocumentsheet/) | Specifies a document's ShapeSheet structure. |
| [getEmailRoutingData()](./getemailroutingdata/) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [getEventItems()](./geteventitems/) | Contains an EventItem element for each event to which an object should respond. |
| [getFonts()](./getfonts/) | Contains a collection of Font elements |
| [getHeaderFooter()](./getheaderfooter/) | Contains elements for a document's header and footer. |
| [getInterruptMonitor()](./getinterruptmonitor/) | Gets and sets the interrupt monitor. |
| [getKey()](./getkey/) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [getMasters()](./getmasters/) | Collection Master objects. |
| [getMetric()](./getmetric/) | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [getPages()](./getpages/) | Collection Page objects. |
| [getRibbonX()](./getribbonx/) | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [getSolutionXMLs()](./getsolutionxmls/) | XML value. |
| [getStart()](./getstart/) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [getStyleSheets()](./getstylesheets/) | Collection StyleSheet objects. |
| [getUnusedStyles()](./getunusedstyles/) | Get unused Styles |
| [getUserCustomUI()](./getusercustomui/) | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [getValidation()](./getvalidation/) | Stores information about diagram validation for the document. |
| [getVbaProject()](./getvbaproject/) | Gets the VbaProjectVbaProject. |
| [getVbProjectData()](./getvbprojectdata/) | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [getVersion()](./getversion/) | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [getWindows()](./getwindows/) | Contains the Window elements for a document. |
| [hasHiddenInfo()](./hashiddeninfo/) | Indicates whether this diagram has hidden information. |
| [layout(options)](./layout/) | Lays out the shapes and/or reroutes the connectors for all pages of diagram. |
| [print(printerName)](./print/) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerNam |
| [print(printerName, options)](./print-1/) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerNam |
| [print(printerName, documentName, options)](./print-2/) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [print(printerName, documentName)](./print-3/) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [removeHiddenInformation(item)](./removehiddeninformation/) | Remove unused information |
| [removeMacro()](./removemacro/) | Removes VBA/macro from this diagram. |
| [save(filename, format)](./save-2/) | Saves the diagram data to the file. |
| [save(stream, saveOptions)](./save-3/) | Save the diagram to the stream. |
| [save(filename, options)](./save-4/) | Saves the document to a file using the specified save options. |
| [setBuildnum()](./setbuildnum/) | The build number of the Visio instance used to create the document. |
| [setDocLangID()](./setdoclangid/) | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [setEmailRoutingData()](./setemailroutingdata/) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [setFontDirs()](./setfontdirs/) | Indicates the Fonts folder path |
| [setInterruptMonitor()](./setinterruptmonitor/) | Gets and sets the interrupt monitor. |
| [setKey()](./setkey/) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [setMetric()](./setmetric/) | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [setRibbonX()](./setribbonx/) | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [setStart()](./setstart/) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [setUserCustomUI()](./setusercustomui/) | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [setVbProjectData()](./setvbprojectdata/) | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [setVersion()](./setversion/) | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
