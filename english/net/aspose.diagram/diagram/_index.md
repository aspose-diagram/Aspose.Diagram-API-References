---
title: Diagram
second_title: Aspose.Diagram for .NET API Reference
description: 
type: docs
weight: 1150
url: /net/aspose.diagram/diagram/
---
## Diagram class

Root element of Visio objects hierarchy.

```csharp
public class Diagram : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Diagram](diagram)() | The default constructor. |
| [Diagram](diagram)(Stream) | Public Diagram class constructor, loads the diagram from the stream. |
| [Diagram](diagram)(string) | Public Diagram class constructor, loads the diagram from the file. |
| [Diagram](diagram)(Stream, LoadFileFormat) | Public Diagram class constructor, loads the diagram from the stream using predefined format. |
| [Diagram](diagram)(Stream, LoadOptions) | Public Diagram class constructor, loads the diagram from the stream using predefined load file options. |
| [Diagram](diagram)(string, LoadFileFormat) | Public Diagram class constructor, loads the diagram from the file using predefined format. |
| [Diagram](diagram)(string, LoadOptions) | Public Diagram class constructor, loads the diagram from the file using predefined load file options. |

## Properties

| Name | Description |
| --- | --- |
| [ActivePage](activepage) { get; } | Specifies the active page |
| [Buildnum](buildnum) { get; set; } | The build number of the Visio instance used to create the document. |
| [Colors](colors) { get; } | Contains the document's color table. Each document contains a single color table, which lists the 24 standard colors that are available for application to objects such as shapes, text, and layers in the document. |
| [DataConnections](dataconnections) { get; } | Contains the DataConnection elements for the document. |
| [DataRecordSets](datarecordsets) { get; } | The collection of DataRecordset objects associated with a Document object. |
| [DocLangID](doclangid) { get; set; } | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [DocumentProps](documentprops) { get; } | Contains document property elements such as the document's title, author, and so on. |
| [DocumentSettings](documentsettings) { get; } | Contains elements that specify document settings. |
| [DocumentSheet](documentsheet) { get; } | Specifies a document's ShapeSheet structure. |
| [EmailRoutingData](emailroutingdata) { get; set; } | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [EventItems](eventitems) { get; } | Contains an EventItem element for each event to which an object should respond. |
| [FontDirs](fontdirs) { set; } | Indicates the Fonts folder path |
| [Fonts](fonts) { get; } | Contains a collection of Font elements |
| [HeaderFooter](headerfooter) { get; } | Contains elements for a document's header and footer. |
| [InterruptMonitor](interruptmonitor) { get; set; } | Gets and sets the interrupt monitor. |
| [Key](key) { get; set; } | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio. |
| [Masters](masters) { get; } | Collection Master objects. |
| [Metric](metric) { get; set; } | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units. |
| [Pages](pages) { get; } | Collection Page objects. |
| [RibbonX](ribbonx) { get; set; } | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [SolutionXMLs](solutionxmls) { get; } | XML value. |
| [Start](start) { get; set; } | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio. |
| [StyleSheets](stylesheets) { get; } | Collection StyleSheet objects. |
| [UserCustomUI](usercustomui) { get; set; } | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [Validation](validation) { get; } | Stores information about diagram validation for the document. |
| [VbaProject](vbaproject) { get; } | Gets the VbaProject[`VbaProject`](./vbaproject). |
| [VbProjectData](vbprojectdata) { get; set; } | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format. |
| [Version](version) { get; set; } | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [Windows](windows) { get; } | Contains the Window elements for a document. |

## Methods

| Name | Description |
| --- | --- |
| [AddMaster](addmaster)(Diagram, string) | Adds master to diagram from source diagram by master's Name or NameU. |
| [AddMaster](addmaster)(Stream, int) | Adds master to diagram from template stream by master's ID. |
| [AddMaster](addmaster)(Stream, string) | Adds master to diagram from template stream by master's Name or NameU. |
| [AddMaster](addmaster)(string, int) | Adds master to diagram from template file by master's ID. |
| [AddMaster](addmaster)(string, string) | Adds master to diagram from template file by master's Name or NameU. |
| [AddShape](addshape)(Shape, string, int) | Adds shape created by master to specific page. |
| [AddShape](addshape)(double, double, string, int) | Adds shape created by master on page with defined PinX and PinY. |
| [AddShape](addshape)(double, double, double, double, string, int) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [Combine](combine)(Diagram) | Combines another Diagram object. |
| [CopyTheme](copytheme)(Diagram) | Copies Theme from a source Diagram. |
| [Dispose](dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetDefaultFontDir](getdefaultfontdir)() | Get the Default Fonts folder path |
| [GetUnusedStyles](getunusedstyles)() | Get unused Styles |
| [HasHiddenInfo](hashiddeninfo)() | Indicates whether this diagram has hidden information. |
| [Layout](layout)(LayoutOptions) | Lays out the shapes and/or reroutes the connectors for all pages of diagram. |
| [Print](print)() | Prints the whole document to the default printer. |
| [Print](print)(PrinterSettings) | Prints the document according to the specified printer settings,using the standard (no User Interface) print controller. |
| [Print](print)(PrintSaveOptions) | Prints the whole document to the default printer. |
| [Print](print)(string) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. |
| [Print](print)(PrinterSettings, PrintSaveOptions) | Prints the document according to the specified printer settings,using the standard (no User Interface) print controller. |
| [Print](print)(PrinterSettings, string) | Prints the document according to the specified printer settings,using the standard (no User Interface) print controller and a document name. |
| [Print](print)(string, PrintSaveOptions) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. |
| [Print](print)(string, string) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [Print](print)(PrinterSettings, string, PrintSaveOptions) | Prints the document according to the specified printer settings,using the standard (no User Interface) print controller and a document name. |
| [Print](print)(string, string, PrintSaveOptions) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [Refresh](refresh)() | Invokes Refresh method for all DataRecordSet in the Diagram. |
| [RemoveHiddenInformation](removehiddeninformation)(int) | Remove unused information |
| [RemoveMacro](removemacro)() | Removes VBA/macro from this diagram. |
| [Save](save)(Stream, SaveFileFormat) | Saves the diagram data to the stream. |
| [Save](save)(Stream, SaveOptions) | Saves the diagram to a stream using the specified save options. |
| [Save](save)(string, SaveFileFormat) | Saves the diagram data to the file. |
| [Save](save)(string, SaveOptions) | Saves the document to a file using the specified save options. |
| static [Export](export)(Stream, Stream) | Exports the diagram from vsd stream to vdw stream format. Not implemented yet. |
| static [Export](export)(Stream, string) | Exports the diagram from vsd stream to *.vdw file format. Not implemented yet. |
| static [Export](export)(string, Stream) | Exports the diagram from vsd file to vdw stream format. Not implemented yet. |
| static [Export](export)(string, string) | Exports the diagram from vsd to vdw format. Not implemented yet. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
