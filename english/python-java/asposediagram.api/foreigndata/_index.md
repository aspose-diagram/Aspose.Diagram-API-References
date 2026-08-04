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
| [ImageData](/python-java/asposediagram.api/foreigndata/imagedata/) | byte[] | Represents image of ole object as byte array. |
| [ObjectData](/python-java/asposediagram.api/foreigndata/objectdata/) | byte[] | Represents embedded ole object data as byte array. |
| [ForeignType](/python-java/asposediagram.api/foreigndata/foreigntype/) | int | Data type. The value of the property is ForeignType integer constant. |
| [ObjectType](/python-java/asposediagram.api/foreigndata/objecttype/) | int | If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of t |
| [ShowAsIcon](/python-java/asposediagram.api/foreigndata/showasicon/) | int | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL inte |
| [ObjectWidth](/python-java/asposediagram.api/foreigndata/objectwidth/) | float | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the o |
| [ObjectHeight](/python-java/asposediagram.api/foreigndata/objectheight/) | float | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the  |
| [MappingMode](/python-java/asposediagram.api/foreigndata/mappingmode/) | int | This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode. |
| [ExtentX](/python-java/asposediagram.api/foreigndata/extentx/) | float | This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the me |
| [ExtentY](/python-java/asposediagram.api/foreigndata/extenty/) | float | This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the meta |
| [CompressionType](/python-java/asposediagram.api/foreigndata/compressiontype/) | int | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [CompressionLevel](/python-java/asposediagram.api/foreigndata/compressionlevel/) | float | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [Value](/python-java/asposediagram.api/foreigndata/value/) | byte[] | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [ObjectSourceFullName](/python-java/asposediagram.api/foreigndata/objectsourcefullname/) | String | Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name wh |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](/python-java/asposediagram.api/foreigndata/deepclone/) | Creates deep copy of this instance. |
