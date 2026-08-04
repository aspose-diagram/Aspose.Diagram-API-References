---
title: "ForeignData Class"
linktitle: "ForeignData"
articleTitle: "ForeignData"
second_title: "Aspose.Diagram for Python via Java"
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
| [ImageData](./imagedata/) | byte[] | Represents image of ole object as byte array. |
| [ObjectData](./objectdata/) | byte[] | Represents embedded ole object data as byte array. |
| [ForeignType](./foreigntype/) | int | Data type. The value of the property is ForeignType integer constant. |
| [ObjectType](./objecttype/) | int | If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of t |
| [ShowAsIcon](./showasicon/) | int | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL inte |
| [ObjectWidth](./objectwidth/) | float | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the o |
| [ObjectHeight](./objectheight/) | float | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the  |
| [MappingMode](./mappingmode/) | int | This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode. |
| [ExtentX](./extentx/) | float | This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the me |
| [ExtentY](./extenty/) | float | This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the meta |
| [CompressionType](./compressiontype/) | int | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [CompressionLevel](./compressionlevel/) | float | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [Value](./value/) | byte[] | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [ObjectSourceFullName](./objectsourcefullname/) | String | Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name wh |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
