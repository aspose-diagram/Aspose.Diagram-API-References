---
title: "Diagram Class"
linktitle: "Diagram"
articleTitle: "Diagram"
second_title: "Aspose.Diagram for Python via Java"
description: "Root element of Visio objects hierarchy."
type: docs
weight: 890
url: /python-java/asposediagram.api/diagram/
---

## Diagram class

Root element of Visio objects hierarchy.

```python
Diagram()
```

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Start](/python-java/asposediagram.api/diagram/start/) | long | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [FontDirs](/python-java/asposediagram.api/diagram/fontdirs/) | String[] | Indicates the Fonts folder path |
| [Key](/python-java/asposediagram.api/diagram/key/) | String | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [Metric](/python-java/asposediagram.api/diagram/metric/) | int | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [Buildnum](/python-java/asposediagram.api/diagram/buildnum/) | long | The build number of the Visio instance used to create the document. |
| [Version](/python-java/asposediagram.api/diagram/version/) | String | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [DocLangID](/python-java/asposediagram.api/diagram/doclangid/) | int | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [StyleSheets](/python-java/asposediagram.api/diagram/stylesheets/) | StyleSheetCollection | Collection StyleSheet objects. |
| [Masters](/python-java/asposediagram.api/diagram/masters/) | MasterCollection | Collection Master objects. |
| [Pages](/python-java/asposediagram.api/diagram/pages/) | PageCollection | Collection Page objects. |
| [DocumentProps](/python-java/asposediagram.api/diagram/documentprops/) | DocumentProperties | Contains document property elements such as the document's title, author, and so on. |
| [DocumentSettings](/python-java/asposediagram.api/diagram/documentsettings/) | DocumentSettings | Contains elements that specify document settings. |
| [Colors](/python-java/asposediagram.api/diagram/colors/) | ColorEntryCollection | Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors tha |
| [Fonts](/python-java/asposediagram.api/diagram/fonts/) | FontCollection | Contains a collection of Font elements |
| [DocumentSheet](/python-java/asposediagram.api/diagram/documentsheet/) | DocumentSheet | Specifies a document's ShapeSheet structure. |
| [ActivePage](/python-java/asposediagram.api/diagram/activepage/) | Page | Specifies the active page |
| [Windows](/python-java/asposediagram.api/diagram/windows/) | WindowCollection | Contains the Window elements for a document. |
| [EventItems](/python-java/asposediagram.api/diagram/eventitems/) | EventItemCollection | Contains an EventItem element for each event to which an object should respond. |
| [HeaderFooter](/python-java/asposediagram.api/diagram/headerfooter/) | HeaderFooter | Contains elements for a document's header and footer. |
| [VbProjectData](/python-java/asposediagram.api/diagram/vbprojectdata/) | byte[] | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [EmailRoutingData](/python-java/asposediagram.api/diagram/emailroutingdata/) | byte[] | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [DataConnections](/python-java/asposediagram.api/diagram/dataconnections/) | DataConnectionCollection | Contains the DataConnection elements for the document. |
| [DataRecordSets](/python-java/asposediagram.api/diagram/datarecordsets/) | DataRecordSetCollection | The collection of DataRecordset objects associated with a Document object. |
| [RibbonX](/python-java/asposediagram.api/diagram/ribbonx/) | String | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [UserCustomUI](/python-java/asposediagram.api/diagram/usercustomui/) | String | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [Validation](/python-java/asposediagram.api/diagram/validation/) | Validation | Stores information about diagram validation for the document. |
| [SolutionXMLs](/python-java/asposediagram.api/diagram/solutionxmls/) | SolutionXMLCollection | XML value. |
| [VbaProject](/python-java/asposediagram.api/diagram/vbaproject/) | VbaProject | Gets the VbaProject VbaProject . |
| [InterruptMonitor](/python-java/asposediagram.api/diagram/interruptmonitor/) | AbstractInterruptMonitor | Gets and sets the interrupt monitor. |

## Methods

| Name | Description |
| --- | --- |
| [save](/python-java/asposediagram.api/diagram/save/) | Saves the diagram data to the file. |
| [dispose](/python-java/asposediagram.api/diagram/dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [copyTheme](/python-java/asposediagram.api/diagram/copytheme/) | Copies Theme from a source Diagram. |
| [combine](/python-java/asposediagram.api/diagram/combine/) | Combines another Diagram object. |
| [addMaster](/python-java/asposediagram.api/diagram/addmaster/) | Adds master to diagram from source diagram by master's Name or NameU. |
| [hasHiddenInfo](/python-java/asposediagram.api/diagram/hashiddeninfo/) | Indicates whether this diagram has hidden information. |
| [removeHiddenInformation](/python-java/asposediagram.api/diagram/removehiddeninformation/) | Remove unused information |
| [getUnusedStyles](/python-java/asposediagram.api/diagram/getunusedstyles/) | Get unused Styles |
| [addShape](/python-java/asposediagram.api/diagram/addshape/) | Adds shape created by master to specific page. |
| [print](/python-java/asposediagram.api/diagram/print/) | Print the whole document to the specified printer,using the standard (no User Interface) print controller.

If printerNa |
| [getDefaultFontDir](/python-java/asposediagram.api/diagram/getdefaultfontdir/) | Get the Default Fonts folder path |
| [removeMacro](/python-java/asposediagram.api/diagram/removemacro/) | Removes VBA/macro from this diagram. |
