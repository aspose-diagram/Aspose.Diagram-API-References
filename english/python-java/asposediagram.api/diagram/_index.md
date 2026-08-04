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
| [Start](./start/) | long | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [FontDirs](./fontdirs/) | String[] | Indicates the Fonts folder path |
| [Key](./key/) | String | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the |
| [Metric](./metric/) | int | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to u |
| [Buildnum](./buildnum/) | long | The build number of the Visio instance used to create the document. |
| [Version](./version/) | String | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [DocLangID](./doclangid/) | int | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [StyleSheets](./stylesheets/) | StyleSheetCollection | Collection StyleSheet objects. |
| [Masters](./masters/) | MasterCollection | Collection Master objects. |
| [Pages](./pages/) | PageCollection | Collection Page objects. |
| [DocumentProps](./documentprops/) | DocumentProperties | Contains document property elements such as the document's title, author, and so on. |
| [DocumentSettings](./documentsettings/) | DocumentSettings | Contains elements that specify document settings. |
| [Colors](./colors/) | ColorEntryCollection | Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors tha |
| [Fonts](./fonts/) | FontCollection | Contains a collection of Font elements |
| [DocumentSheet](./documentsheet/) | DocumentSheet | Specifies a document's ShapeSheet structure. |
| [ActivePage](./activepage/) | Page | Specifies the active page |
| [Windows](./windows/) | WindowCollection | Contains the Window elements for a document. |
| [EventItems](./eventitems/) | EventItemCollection | Contains an EventItem element for each event to which an object should respond. |
| [HeaderFooter](./headerfooter/) | HeaderFooter | Contains elements for a document's header and footer. |
| [VbProjectData](./vbprojectdata/) | byte[] | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encode |
| [EmailRoutingData](./emailroutingdata/) | byte[] | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [DataConnections](./dataconnections/) | DataConnectionCollection | Contains the DataConnection elements for the document. |
| [DataRecordSets](./datarecordsets/) | DataRecordSetCollection | The collection of DataRecordset objects associated with a Document object. |
| [RibbonX](./ribbonx/) | String | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [UserCustomUI](./usercustomui/) | String | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [Validation](./validation/) | Validation | Stores information about diagram validation for the document. |
| [SolutionXMLs](./solutionxmls/) | SolutionXMLCollection | XML value. |
| [VbaProject](./vbaproject/) | VbaProject | Gets the VbaProject VbaProject . |
| [InterruptMonitor](./interruptmonitor/) | AbstractInterruptMonitor | Gets and sets the interrupt monitor. |

## Methods

| Name | Description |
| --- | --- |
| [save](./save/) | Saves the diagram data to the file. |
| [dispose](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [copyTheme](./copytheme/) | Copies Theme from a source Diagram. |
| [combine](./combine/) | Combines another Diagram object. |
| [addMaster](./addmaster/) | Adds master to diagram from source diagram by master's Name or NameU. |
| [hasHiddenInfo](./hashiddeninfo/) | Indicates whether this diagram has hidden information. |
| [removeHiddenInformation](./removehiddeninformation/) | Remove unused information |
| [getUnusedStyles](./getunusedstyles/) | Get unused Styles |
| [addShape](./addshape/) | Adds shape created by master to specific page. |
| [print](./print/) | Print the whole document to the specified printer,using the standard (no User Interface) print controller.

If printerNa |
| [getDefaultFontDir](./getdefaultfontdir/) | Get the Default Fonts folder path |
| [removeMacro](./removemacro/) | Removes VBA/macro from this diagram. |
