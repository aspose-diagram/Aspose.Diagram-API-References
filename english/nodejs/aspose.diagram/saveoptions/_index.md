---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "This is an abstract base class for classes that allow the user to specify additional options when saving a diagram into a particular format."
type: docs
weight: 2250
url: /nodejs/aspose.diagram/saveoptions/
---

## SaveOptions class

This is an abstract base class for classes that allow the user to specify additional options when saving a diagram into a particular format. An instance of the SaveOptions class or any derived class is passed to the stream Save or string Save overloads for the user to define custom options when saving a document.

## Methods

| Name | Description |
| --- | --- |
| [createSaveOptions(saveFormat)](#createsaveoptions) *(static)* | Creates a save options object of a class suitable for the specified save format. |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the document will be saved if this save options object is used. The value of the property  |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the document will be saved if this save options object is used. The value of the property  |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### createSaveOptions(saveFormat) (static) {#createsaveoptions}

Creates a save options object of a class suitable for the specified save format.

| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | Number | SaveFileFormat |

**Returns:** SaveOptions — `SaveOptions` An object of a class that derives from SaveOptions.

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the document will be saved if this save options object is used. The value of the property is SaveFileFormat integer constant.

### getWarningCallback() {#getwarningcallback}

Gets or sets warning callback.

### setDefaultFont() {#setdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the document will be saved if this save options object is used. The value of the property is SaveFileFormat integer constant.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
