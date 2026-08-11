---
title: "XAMLSaveOptions"
linktitle: "XAMLSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when rendering diagram pages to XAML."
type: docs
weight: 2920
url: /nodejs/aspose.diagram/xamlsaveoptions/
---

## XAMLSaveOptions class

Allows to specify additional options when rendering diagram pages to XAML.

```js
new XAMLSaveOptions()
```

Initializes a new instance of this class that can be used to save a document in the SaveFileFormat format.

## Methods

| Name | Description |
| --- | --- |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getPageCount()](#getpagecount) | Gets or sets the number of pages to render in XAML. Default is MaxValue which means all pages of the diagram will be ren |
| [getPageIndex()](#getpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [getSaveForegroundPagesOnly()](#getsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [getStreamProvider()](#getstreamprovider) | Gets or sets the IStreamProvider for exporting objects. |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setPageCount()](#setpagecount) | Gets or sets the number of pages to render in XAML. Default is MaxValue which means all pages of the diagram will be ren |
| [setPageIndex()](#setpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [setSaveForegroundPagesOnly()](#setsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [setStreamProvider()](#setstreamprovider) | Gets or sets the IStreamProvider for exporting objects. |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getPageCount() {#getpagecount}

Gets or sets the number of pages to render in XAML. Default is MaxValue which means all pages of the diagram will be rendered.

### getPageIndex() {#getpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### getSaveForegroundPagesOnly() {#getsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

### getStreamProvider() {#getstreamprovider}

Gets or sets the IStreamProvider for exporting objects.

### getWarningCallback() {#getwarningcallback}

Gets or sets warning callback.

### setDefaultFont() {#setdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### setPageCount() {#setpagecount}

Gets or sets the number of pages to render in XAML. Default is MaxValue which means all pages of the diagram will be rendered.

### setPageIndex() {#setpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### setSaveForegroundPagesOnly() {#setsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

### setStreamProvider() {#setstreamprovider}

Gets or sets the IStreamProvider for exporting objects.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
