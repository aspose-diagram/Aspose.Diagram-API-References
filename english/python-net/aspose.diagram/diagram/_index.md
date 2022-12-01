---
title: Diagram class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 580
url: /python-net/aspose.diagram/diagram/
is_root: false
---

## Diagram class

Root element of Visio objects hierarchy.



The Diagram type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Diagram()](/diagram/python-net/aspose.diagram/diagram/__init__/#) |  |
| [Diagram(filename)](/diagram/python-net/aspose.diagram/diagram/__init__/#str) | Public class constructor,<br/>loads the diagram from the file. |
| [Diagram(stream)](/diagram/python-net/aspose.diagram/diagram/__init__/#io.RawIOBase) | Public class constructor,<br/>loads the diagram from the stream. |
| [Diagram(filename, format)](/diagram/python-net/aspose.diagram/diagram/__init__/#str-LoadFileFormat) | Public class constructor,<br/>loads the diagram from the file using predefined format. |
| [Diagram(stream, format)](/diagram/python-net/aspose.diagram/diagram/__init__/#io.RawIOBase-LoadFileFormat) | Public class constructor,<br/>loads the diagram from the stream using predefined format. |
| [Diagram(filename, options)](/diagram/python-net/aspose.diagram/diagram/__init__/#str-LoadOptions) | Public class constructor,<br/>loads the diagram from the file using predefined load file options. |
| [Diagram(stream, options)](/diagram/python-net/aspose.diagram/diagram/__init__/#io.RawIOBase-LoadOptions) | Public class constructor,<br/>loads the diagram from the stream using predefined load file options. |


### Properties
| Property | Description |
| :- | :- |
| [start](/diagram/python-net/aspose.diagram/diagram/start) | Indicates whether the document has been modified outside of Visio. <br/>If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio. |
| [key](/diagram/python-net/aspose.diagram/diagram/key) | Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio. |
| [metric](/diagram/python-net/aspose.diagram/diagram/metric) | Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units. |
| [buildnum](/diagram/python-net/aspose.diagram/diagram/buildnum) | The build number of the Visio instance used to create the document. |
| [version](/diagram/python-net/aspose.diagram/diagram/version) | The version number of the Visio instance. Microsoft Visio 2010 = 14. |
| [doc_lang_id](/diagram/python-net/aspose.diagram/diagram/doc_lang_id) | The unique ID of the user-interface language the user has specified in Microsoft Office 2010 Language Preferences. |
| [style_sheets](/diagram/python-net/aspose.diagram/diagram/style_sheets) | Collection StyleSheet objects. |
| [masters](/diagram/python-net/aspose.diagram/diagram/masters) | Collection Master objects. |
| [pages](/diagram/python-net/aspose.diagram/diagram/pages) | Collection Page objects. |
| [document_props](/diagram/python-net/aspose.diagram/diagram/document_props) | Contains document property elements such as the document's title, author, and so on. |
| [document_settings](/diagram/python-net/aspose.diagram/diagram/document_settings) | Contains elements that specify document settings. |
| [colors](/diagram/python-net/aspose.diagram/diagram/colors) | Contains the document's color table. Each document contains a single color table, <br/>which lists the 24 standard colors that are available for application to objects <br/>such as shapes, text, and layers in the document. |
| [fonts](/diagram/python-net/aspose.diagram/diagram/fonts) | Contains a collection of Font elements |
| [document_sheet](/diagram/python-net/aspose.diagram/diagram/document_sheet) | Specifies a document's ShapeSheet structure. |
| [active_page](/diagram/python-net/aspose.diagram/diagram/active_page) | Specifies the active page |
| [windows](/diagram/python-net/aspose.diagram/diagram/windows) | Contains the Window elements for a document. |
| [event_items](/diagram/python-net/aspose.diagram/diagram/event_items) | Contains an EventItem element for each event to which an object should respond. |
| [header_footer](/diagram/python-net/aspose.diagram/diagram/header_footer) | Contains elements for a document's header and footer. |
| [vb_project_data](/diagram/python-net/aspose.diagram/diagram/vb_project_data) | Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format. |
| [email_routing_data](/diagram/python-net/aspose.diagram/diagram/email_routing_data) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded MAPI e-mail routing slip for the document. |
| [data_connections](/diagram/python-net/aspose.diagram/diagram/data_connections) | Contains the DataConnection elements for the document. |
| [data_record_sets](/diagram/python-net/aspose.diagram/diagram/data_record_sets) | The collection of DataRecordset objects associated with a Document object. |
| [ribbon_x](/diagram/python-net/aspose.diagram/diagram/ribbon_x) | The Ribbon XML string that is passed to the document to customize the ribbon user interface. |
| [user_custom_ui](/diagram/python-net/aspose.diagram/diagram/user_custom_ui) | The Ribbon XML string that is passed to the document to customize the Quick Access toolbar or the ribbon. |
| [validation](/diagram/python-net/aspose.diagram/diagram/validation) | Stores information about diagram validation for the document. |
| [solution_xm_ls](/diagram/python-net/aspose.diagram/diagram/solution_xm_ls) | XML value. |
| [vba_project](/diagram/python-net/aspose.diagram/diagram/vba_project) | Gets the VbaProject[Diagram.vba_project](/diagram/python-net/aspose.diagram/diagram#vba_project). |
| [interrupt_monitor](/diagram/python-net/aspose.diagram/diagram/interrupt_monitor) | Gets and sets the interrupt monitor. |


### Methods
| Method | Description |
| :- | :- |
| [save(filename, format)](/diagram/python-net/aspose.diagram/diagram/save/#str-SaveFileFormat) | Saves the diagram data to the file. |
| [save(stream, format)](/diagram/python-net/aspose.diagram/diagram/save/#io.RawIOBase-SaveFileFormat) | Saves the diagram data to the stream. |
| [save(filename, options)](/diagram/python-net/aspose.diagram/diagram/save/#str-aspose.diagram.saving.SaveOptions) |  |
| [save(stream, options)](/diagram/python-net/aspose.diagram/diagram/save/#io.RawIOBase-aspose.diagram.saving.SaveOptions) |  |
| [export(input_vsd, output_vdw)](/diagram/python-net/aspose.diagram/diagram/export/#str-str) | Exports the diagram from vsd to vdw format. Not implemented yet. |
| [export(input_vsd, output_vdw)](/diagram/python-net/aspose.diagram/diagram/export/#str-io.RawIOBase) | Exports the diagram from vsd file to vdw stream format. Not implemented yet. |
| [export(input_vsd, output_vdw)](/diagram/python-net/aspose.diagram/diagram/export/#io.RawIOBase-str) | Exports the diagram from vsd stream to *.vdw file format. Not implemented yet. |
| [export(input_vsd, output_vdw)](/diagram/python-net/aspose.diagram/diagram/export/#io.RawIOBase-io.RawIOBase) | Exports the diagram from vsd stream to vdw stream format. Not implemented yet. |
| [add_master(src_diagram, master_name)](/diagram/python-net/aspose.diagram/diagram/add_master/#Diagram-str) |  |
| [add_master(template_stream, master_name)](/diagram/python-net/aspose.diagram/diagram/add_master/#io.RawIOBase-str) | Adds master to diagram from template stream by master's Name or NameU. |
| [add_master(template_stream, master_id)](/diagram/python-net/aspose.diagram/diagram/add_master/#io.RawIOBase-int) | Adds master to diagram from template stream by master's ID. |
| [add_master(template_file_path, master_name)](/diagram/python-net/aspose.diagram/diagram/add_master/#str-str) | Adds master to diagram from template file by master's Name or NameU. |
| [add_master(template_file_path, master_id)](/diagram/python-net/aspose.diagram/diagram/add_master/#str-int) | Adds master to diagram from template file by master's ID. |
| [add_shape(new_shape, master_name, page_number)](/diagram/python-net/aspose.diagram/diagram/add_shape/#Shape-str-int) | Adds shape created by master to specific page. |
| [add_shape(pin_x, pin_y, master_name, page_number)](/diagram/python-net/aspose.diagram/diagram/add_shape/#float-float-str-int) | Adds shape created by master on page with defined PinX and PinY. |
| [add_shape(pin_x, pin_y, width, height, master_name, page_number)](/diagram/python-net/aspose.diagram/diagram/add_shape/#float-float-float-float-str-int) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [print(options)](/diagram/python-net/aspose.diagram/diagram/print/#aspose.diagram.saving.PrintSaveOptions) |  |
| [print()](/diagram/python-net/aspose.diagram/diagram/print/#) | Prints the whole document to the default printer. |
| [print(printer_name)](/diagram/python-net/aspose.diagram/diagram/print/#str) | Print the whole document to the specified printer,using the standard (no User Interface) print controller. |
| [print(printer_name, options)](/diagram/python-net/aspose.diagram/diagram/print/#str-aspose.diagram.saving.PrintSaveOptions) |  |
| [print(printer_settings, options)](/diagram/python-net/aspose.diagram/diagram/print/#aspose.pydrawing.printing.PrinterSettings-aspose.diagram.saving.PrintSaveOptions) |  |
| [print(printer_settings)](/diagram/python-net/aspose.diagram/diagram/print/#aspose.pydrawing.printing.PrinterSettings) | Prints the document according to the specified printer settings,using the standard (no User Interface) print controller. |
| [print(printer_settings, document_name, options)](/diagram/python-net/aspose.diagram/diagram/print/#aspose.pydrawing.printing.PrinterSettings-str-aspose.diagram.saving.PrintSaveOptions) |  |
| [print(printer_settings, document_name)](/diagram/python-net/aspose.diagram/diagram/print/#aspose.pydrawing.printing.PrinterSettings-str) | Prints the document according to the specified printer settings,using the standard (no User Interface) print controller and a document name. |
| [print(printer_name, document_name, options)](/diagram/python-net/aspose.diagram/diagram/print/#str-str-aspose.diagram.saving.PrintSaveOptions) |  |
| [print(printer_name, document_name)](/diagram/python-net/aspose.diagram/diagram/print/#str-str) | Prints the document,using the standard (no User Interface) print controller and a document name. |
| [copy_theme(source)](/diagram/python-net/aspose.diagram/diagram/copy_theme/#Diagram) |  |
| [combine(second_diagram)](/diagram/python-net/aspose.diagram/diagram/combine/#Diagram) |  |
| [refresh()](/diagram/python-net/aspose.diagram/diagram/refresh/#) | Invokes Refresh method for all DataRecordSet in the Diagram. |
| [layout(options)](/diagram/python-net/aspose.diagram/diagram/layout/#aspose.diagram.autolayout.LayoutOptions) |  |
| [has_hidden_info()](/diagram/python-net/aspose.diagram/diagram/has_hidden_info/#) | Indicates whether this diagram has hidden information. |
| [remove_hidden_information(item)](/diagram/python-net/aspose.diagram/diagram/remove_hidden_information/#int) | Remove unused information |
| [get_unused_styles()](/diagram/python-net/aspose.diagram/diagram/get_unused_styles/#) | Get unused Styles |
| [get_default_font_dir()](/diagram/python-net/aspose.diagram/diagram/get_default_font_dir/#) | Get the Default Fonts folder path |
| [remove_macro()](/diagram/python-net/aspose.diagram/diagram/remove_macro/#) | Removes VBA/macro from this diagram. |


### See Also

* module [aspose.diagram](../)
