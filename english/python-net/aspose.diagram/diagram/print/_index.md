---
title: print method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.diagram/diagram/print/
is_root: false
---

## print() {#}

Prints the whole document to the default printer.



```python
def print(self):
    ...
```




## print(options) {#aspose.diagram.saving.PrintSaveOptions}

Prints the whole document to the default printer.



```python
def print(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | aspose.diagram.saving.PrintSaveOptions | The print options. |


## print(printer_name) {#str}

Print the whole document to the specified printer,using the standard (no User Interface) print controller.



```python
def print(self, printer_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_name | str | The name of the printer.Can be Null |
### Remarks

If printerName is Null or empty will be used default printer.

## print(printer_settings) {#aspose.pydrawing.printing.PrinterSettings}

Prints the document according to the specified printer settings,using the standard (no User Interface) print controller.



```python
def print(self, printer_settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | The printer settings to use. |
### Remarks

The System.Drawing.Printing.PrinterSettingsobject allows you to specify the printer to print on, the range of pages of to print and other options.

## print(printer_name, options) {#str-aspose.diagram.saving.PrintSaveOptions}

Print the whole document to the specified printer,using the standard (no User Interface) print controller.



```python
def print(self, printer_name, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_name | str | The name of the printer.Can be Null |
| options | aspose.diagram.saving.PrintSaveOptions | The print options. |
### Remarks

If printerName is Null or empty will be used default printer.

## print(printer_settings, options) {#aspose.pydrawing.printing.PrinterSettings-aspose.diagram.saving.PrintSaveOptions}

Prints the document according to the specified printer settings,using the standard (no User Interface) print controller.



```python
def print(self, printer_settings, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | The printer settings to use. |
| options | aspose.diagram.saving.PrintSaveOptions | The print options. |
### Remarks

The System.Drawing.Printing.PrinterSettingsobject allows you to specify the printer to print on, the range of pages of to print and other options.

## print(printer_settings, document_name) {#aspose.pydrawing.printing.PrinterSettings-str}

Prints the document according to the specified printer settings,using the standard (no User Interface) print controller and a document name.



```python
def print(self, printer_settings, document_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | The printer settings to use. |
| document_name | str | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |


## print(printer_name, document_name) {#str-str}

Prints the document,using the standard (no User Interface) print controller and a document name.



```python
def print(self, printer_name, document_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_name | str | The name of the printer.Can be Null |
| document_name | str | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |


## print(printer_settings, document_name, options) {#aspose.pydrawing.printing.PrinterSettings-str-aspose.diagram.saving.PrintSaveOptions}

Prints the document according to the specified printer settings,using the standard (no User Interface) print controller and a document name.



```python
def print(self, printer_settings, document_name, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | The printer settings to use. |
| document_name | str | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |
| options | aspose.diagram.saving.PrintSaveOptions | The print options. |


## print(printer_name, document_name, options) {#str-str-aspose.diagram.saving.PrintSaveOptions}

Prints the document,using the standard (no User Interface) print controller and a document name.



```python
def print(self, printer_name, document_name, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_name | str | The name of the printer.Can be Null |
| document_name | str | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |
| options | aspose.diagram.saving.PrintSaveOptions | The print options. |



### See Also
* module [aspose.diagram](../../)
* class [Diagram](/diagram/python-net/aspose.diagram/diagram)
