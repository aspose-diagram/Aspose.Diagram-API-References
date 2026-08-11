---
title: "ForeignData"
linktitle: "ForeignData"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data."
type: docs
weight: 1340
url: /python-java/asposediagram.api/foreigndata/
---

## ForeignData class

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ImageData](#imagedata) | byte[] | Represents image of ole object as byte array. |
| [ObjectData](#objectdata) | byte[] | Represents embedded ole object data as byte array. |
| [ForeignType](#foreigntype) | int | Data type. The value of the property is ForeignType integer constant. |
| [ObjectType](#objecttype) | int | If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of t |
| [ShowAsIcon](#showasicon) | int | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL inte |
| [ObjectWidth](#objectwidth) | float | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the o |
| [ObjectHeight](#objectheight) | float | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the  |
| [MappingMode](#mappingmode) | int | This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode. |
| [ExtentX](#extentx) | float | This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the me |
| [ExtentY](#extenty) | float | This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the meta |
| [CompressionType](#compressiontype) | int | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [CompressionLevel](#compressionlevel) | float | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [Value](#value) | byte[] | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [ObjectSourceFullName](#objectsourcefullname) | String | Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name wh |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### ForeignData.ImageData property {#imagedata}

Represents image of ole object as byte array.

**Type:** byte[]

### ForeignData.ObjectData property {#objectdata}

Represents embedded ole object data as byte array.

**Type:** byte[]

### ForeignData.ForeignType property {#foreigntype}

Data type. The value of the property is ForeignType integer constant.

**Type:** int

### ForeignData.ObjectType property {#objecttype}

If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of the property is ObjectType integer constant.

**Type:** int

### ForeignData.ShowAsIcon property {#showasicon}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL integer constant.

**Type:** int

### ForeignData.ObjectWidth property {#objectwidth}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the object in page units.

**Type:** float

### ForeignData.ObjectHeight property {#objectheight}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the object in page units.

**Type:** float

### ForeignData.MappingMode property {#mappingmode}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode.

**Type:** int

### ForeignData.ExtentX property {#extentx}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the metafile.

**Type:** float

### ForeignData.ExtentY property {#extenty}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the metafile.

**Type:** float

### ForeignData.CompressionType property {#compressiontype}

This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the type of compression applied to the file. The value of the property is CompressionType integer constant.

**Type:** int

### ForeignData.CompressionLevel property {#compressionlevel}

This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the level of compression applied to the file. Compression level is measured in hundreds of a percent.

**Type:** float

### ForeignData.Value property {#value}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Type:** byte[]

### ForeignData.ObjectSourceFullName property {#objectsourcefullname}

Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name when the file type is OleFileType.Unknown. Such as wav file ,avi file..etc..

**Type:** String

### deepClone() {#deepclone}

Creates deep copy of this instance.
