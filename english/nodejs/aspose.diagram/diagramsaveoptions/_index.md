---
title: "DiagramSaveOptions"
linktitle: "DiagramSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Can be used to specify additional options when saving a diagram into Visio (VDX\\VSX) format."
type: docs
weight: 650
url: /nodejs/aspose.diagram/diagramsaveoptions/
---

## DiagramSaveOptions class

Can be used to specify additional options when saving a diagram into Visio (VDX\VSX) format. At the moment provides only the SaveFormat property, but in the future will have other options added.

```js
new DiagramSaveOptions()
```

Initializes a new instance of this class that can be used to save a diagram in the VDX format.

## Methods

| Name | Description |
| --- | --- |
| [constructor_overload$1(saveFormat)](#constructor-overload1) | Initializes a new instance of this class that can be used to save a diagram in the VDX or VSX format. |
| [getAutoFitPageToDrawingContent()](#getautofitpagetodrawingcontent) | Defines whether need enlarge page to fit drawing content or not. Default value is false. |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the rendered diagram will be saved if this save options object is used. Can be SaveFileFor |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [setAutoFitPageToDrawingContent()](#setautofitpagetodrawingcontent) | Defines whether need enlarge page to fit drawing content or not. Default value is false. |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the rendered diagram will be saved if this save options object is used. Can be SaveFileFor |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### constructor_overload$1(saveFormat) {#constructor-overload1}

Initializes a new instance of this class that can be used to save a diagram in the VDX or VSX format.

| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | Number | SaveFileFormat |

### getAutoFitPageToDrawingContent() {#getautofitpagetodrawingcontent}

Defines whether need enlarge page to fit drawing content or not. Default value is false.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("BFlowcht.vsdx");
// use saving options
options = new aspose.diagram.DiagramSaveOptions(aspose.diagram.SaveFileFormat.VSDX);
// set Auto fit page property
options.setAutoFitPageToDrawingContent(true);
// save Visio diagram
diagram.save("out-AutoFitShapesInVisio.vsdx", options);
```

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the rendered diagram will be saved if this save options object is used. Can be SaveFileFormat or SaveFileFormat. The value of the property is SaveFileFormat integer constant.

### getWarningCallback() {#getwarningcallback}

Gets or sets warning callback.

### setAutoFitPageToDrawingContent() {#setautofitpagetodrawingcontent}

Defines whether need enlarge page to fit drawing content or not. Default value is false.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("BFlowcht.vsdx");
// use saving options
options = new aspose.diagram.DiagramSaveOptions(aspose.diagram.SaveFileFormat.VSDX);
// set Auto fit page property
options.setAutoFitPageToDrawingContent(true);
// save Visio diagram
diagram.save("out-AutoFitShapesInVisio.vsdx", options);
```

### setDefaultFont() {#setdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the rendered diagram will be saved if this save options object is used. Can be SaveFileFormat or SaveFileFormat. The value of the property is SaveFileFormat integer constant.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
