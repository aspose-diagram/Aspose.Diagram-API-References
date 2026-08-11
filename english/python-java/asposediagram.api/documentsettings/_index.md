---
title: "DocumentSettings"
linktitle: "DocumentSettings"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that specify document settings."
type: docs
weight: 970
url: /python-java/asposediagram.api/documentsettings/
---

## DocumentSettings class

Contains elements that specify document settings.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [TopPage](#toppage) | int | Specifies the ID of the page that should be displayed when the document is opened by Microsoft Visio. |
| [DefaultTextStyle](#defaulttextstyle) | int | Specifies the ID of a StyleSheet element. The next time the user creates a shape using a drawing tool, the shape inherit |
| [DefaultLineStyle](#defaultlinestyle) | int | Specifies the ID of a StyleSheet element. The next time the user creates a shape using a drawing tool, the shape inherit |
| [DefaultFillStyle](#defaultfillstyle) | int | Specifies the ID of a StyleSheet element. The next time the user creates a shape using a drawing tool, the shape inherit |
| [DefaultGuideStyle](#defaultguidestyle) | int | Specifies the ID of a StyleSheet element. The next time the user creates a guide, the guide inherits its guide style fro |
| [GlueSettings](#gluesettings) | int | Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSetting |
| [SnapSettings](#snapsettings) | int | Specifies the objects that shapes snap to when snap is active in the window. The value of the property is SnapSettings i |
| [SnapExtensions](#snapextensions) | int | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value of the prope |
| [SnapAngles](#snapangles) | FloatPointNumCollection | Contains a collection of SnapAngle elements. |
| [DynamicGridEnabled](#dynamicgridenabled) | int | Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL intege |
| [ProtectStyles](#protectstyles) | int | Specifies whether the user is prevented from creating or editing styles. However, regardless of this setting, the user c |
| [ProtectShapes](#protectshapes) | int | Specifies whether the user is prevented from selecting shapes that have their LockSelect element set to 1. The value of  |
| [ProtectMasters](#protectmasters) | int | Specifies whether the user is prevented from creating, editing, or deleting masters. Regardless of this setting, the use |
| [ProtectBkgnds](#protectbkgnds) | int | Specifies whether the user is prevented from deleting or editing background pages. The value of the property is BOOL int |
| [CustomMenusFile](#custommenusfile) | String | Contains the name of the Microsoft Visio user interface (.vsu) file that defines custom menus and accelerators for a doc |
| [CustomToolbarsFile](#customtoolbarsfile) | String | Contains the name of the Microsoft Visio user interface (.vsu) file that defines custom toolbars and status bars for a d |
| [AttachedToolbars](#attachedtoolbars) | byte[] | A MIME (Multipurpose Internet Mail Extensions) encoded Microsoft Visio user interface (VSU) file representing custom too |

### DocumentSettings.TopPage property {#toppage}

Specifies the ID of the page that should be displayed when the document is opened by Microsoft Visio.

**Type:** int

### DocumentSettings.DefaultTextStyle property {#defaulttextstyle}

Specifies the ID of a StyleSheet element. The next time the user creates a shape using a drawing tool, the shape inherits its text style from the specified StyleSheet element.

**Type:** int

### DocumentSettings.DefaultLineStyle property {#defaultlinestyle}

Specifies the ID of a StyleSheet element. The next time the user creates a shape using a drawing tool, the shape inherits its line style from the specified StyleSheet element.

**Type:** int

### DocumentSettings.DefaultFillStyle property {#defaultfillstyle}

Specifies the ID of a StyleSheet element. The next time the user creates a shape using a drawing tool, the shape inherits its fill style from the specified StyleSheet element.

**Type:** int

### DocumentSettings.DefaultGuideStyle property {#defaultguidestyle}

Specifies the ID of a StyleSheet element. The next time the user creates a guide, the guide inherits its guide style from the specified StyleSheet element.

**Type:** int

### DocumentSettings.GlueSettings property {#gluesettings}

Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSettings integer constant.

**Type:** int

### DocumentSettings.SnapSettings property {#snapsettings}

Specifies the objects that shapes snap to when snap is active in the window. The value of the property is SnapSettings integer constant.

**Type:** int

### DocumentSettings.SnapExtensions property {#snapextensions}

Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value of the property is SnapExtensions integer constant.

**Type:** int

### DocumentSettings.SnapAngles property {#snapangles}

Contains a collection of SnapAngle elements.

**Type:** FloatPointNumCollection

### DocumentSettings.DynamicGridEnabled property {#dynamicgridenabled}

Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL integer constant.

**Type:** int

### DocumentSettings.ProtectStyles property {#protectstyles}

Specifies whether the user is prevented from creating or editing styles. However, regardless of this setting, the user can still apply styles. The value of the property is BOOL integer constant.

**Type:** int

### DocumentSettings.ProtectShapes property {#protectshapes}

Specifies whether the user is prevented from selecting shapes that have their LockSelect element set to 1. The value of the property is BOOL integer constant.

**Type:** int

### DocumentSettings.ProtectMasters property {#protectmasters}

Specifies whether the user is prevented from creating, editing, or deleting masters. Regardless of this setting, the user can still create instances of masters. The value of the property is BOOL integer constant.

**Type:** int

### DocumentSettings.ProtectBkgnds property {#protectbkgnds}

Specifies whether the user is prevented from deleting or editing background pages. The value of the property is BOOL integer constant.

**Type:** int

### DocumentSettings.CustomMenusFile property {#custommenusfile}

Contains the name of the Microsoft Visio user interface (.vsu) file that defines custom menus and accelerators for a document.

**Type:** String

### DocumentSettings.CustomToolbarsFile property {#customtoolbarsfile}

Contains the name of the Microsoft Visio user interface (.vsu) file that defines custom toolbars and status bars for a document.

**Type:** String

### DocumentSettings.AttachedToolbars property {#attachedtoolbars}

A MIME (Multipurpose Internet Mail Extensions) encoded Microsoft Visio user interface (VSU) file representing custom toolbars.

**Type:** byte[]
