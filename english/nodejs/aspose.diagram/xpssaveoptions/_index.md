---
title: "XPSSaveOptions"
linktitle: "XPSSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when rendering diagram pages to XPS."
type: docs
weight: 2960
url: /nodejs/aspose.diagram/xpssaveoptions/
---

## XPSSaveOptions class

Allows to specify additional options when rendering diagram pages to XPS.

```js
new XPSSaveOptions()
```

Initializes a new instance of this class that can be used to save a document in the SaveFileFormat format.

## Methods

| Name | Description |
| --- | --- |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getExportHiddenPage()](#getexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [getPageCount()](#getpagecount) | Gets or sets the number of pages to render in XPS. Default is MaxValue which means all pages of the diagram will be rend |
| [getPageIndex()](#getpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [getSaveForegroundPagesOnly()](#getsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setExportHiddenPage()](#setexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [setPageCount()](#setpagecount) | Gets or sets the number of pages to render in XPS. Default is MaxValue which means all pages of the diagram will be rend |
| [setPageIndex()](#setpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [setSaveForegroundPagesOnly()](#setsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getExportHiddenPage() {#getexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

### getPageCount() {#getpagecount}

Gets or sets the number of pages to render in XPS. Default is MaxValue which means all pages of the diagram will be rendered.

### getPageIndex() {#getpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### getSaveForegroundPagesOnly() {#getsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

### getWarningCallback() {#getwarningcallback}

Gets or sets warning callback.

### setDefaultFont() {#setdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### setExportHiddenPage() {#setexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

### setPageCount() {#setpagecount}

Gets or sets the number of pages to render in XPS. Default is MaxValue which means all pages of the diagram will be rendered.

### setPageIndex() {#setpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### setSaveForegroundPagesOnly() {#setsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
