---
title: "ForeignData"
linktitle: "ForeignData"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data."
type: docs
weight: 990
url: /nodejs/aspose.diagram/foreigndata/
---

## ForeignData class

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

## Methods

| Name | Description |
| --- | --- |
| [deepClone()](#deepclone) | Creates deep copy of this instance. |
| [getCompressionLevel()](#getcompressionlevel) | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [getCompressionType()](#getcompressiontype) | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [getExtentX()](#getextentx) | This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the me |
| [getExtentY()](#getextenty) | This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the meta |
| [getForeignType()](#getforeigntype) | Data type. The value of the property is ForeignType integer constant. |
| [getImageData()](#getimagedata) | Represents image of ole object as byte array. |
| [getMappingMode()](#getmappingmode) | This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode. |
| [getObjectData()](#getobjectdata) | Represents embedded ole object data as byte array. |
| [getObjectHeight()](#getobjectheight) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the  |
| [getObjectSourceFullName()](#getobjectsourcefullname) | Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name wh |
| [getObjectType()](#getobjecttype) | If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of t |
| [getObjectWidth()](#getobjectwidth) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the o |
| [getShowAsIcon()](#getshowasicon) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL inte |
| [getValue()](#getvalue) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [setCompressionLevel()](#setcompressionlevel) | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [setCompressionType()](#setcompressiontype) | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, o |
| [setExtentX()](#setextentx) | This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the me |
| [setExtentY()](#setextenty) | This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the meta |
| [setForeignType()](#setforeigntype) | Data type. The value of the property is ForeignType integer constant. |
| [setImageData()](#setimagedata) | Represents image of ole object as byte array. |
| [setMappingMode()](#setmappingmode) | This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode. |
| [setObjectData()](#setobjectdata) | Represents embedded ole object data as byte array. |
| [setObjectHeight()](#setobjectheight) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the  |
| [setObjectSourceFullName()](#setobjectsourcefullname) | Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name wh |
| [setObjectType()](#setobjecttype) | If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of t |
| [setObjectWidth()](#setobjectwidth) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the o |
| [setShowAsIcon()](#setshowasicon) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL inte |
| [setValue()](#setvalue) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |

### deepClone() {#deepclone}

Creates deep copy of this instance.

**Returns:** Object — `Object`

### getCompressionLevel() {#getcompressionlevel}

This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the level of compression applied to the file. Compression level is measured in hundreds of a percent.

### getCompressionType() {#getcompressiontype}

This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the type of compression applied to the file. The value of the property is CompressionType integer constant.

### getExtentX() {#getextentx}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the metafile.

### getExtentY() {#getextenty}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the metafile.

### getForeignType() {#getforeigntype}

Data type. The value of the property is ForeignType integer constant.

### getImageData() {#getimagedata}

Represents image of ole object as byte array.

### getMappingMode() {#getmappingmode}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode.

### getObjectData() {#getobjectdata}

Represents embedded ole object data as byte array.

### getObjectHeight() {#getobjectheight}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the object in page units.

### getObjectSourceFullName() {#getobjectsourcefullname}

Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name when the file type is OleFileType.Unknown. Such as wav file ,avi file..etc..

### getObjectType() {#getobjecttype}

If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of the property is ObjectType integer constant.

### getObjectWidth() {#getobjectwidth}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the object in page units.

### getShowAsIcon() {#getshowasicon}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL integer constant.

### getValue() {#getvalue}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

### setCompressionLevel() {#setcompressionlevel}

This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the level of compression applied to the file. Compression level is measured in hundreds of a percent.

### setCompressionType() {#setcompressiontype}

This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the type of compression applied to the file. The value of the property is CompressionType integer constant.

### setExtentX() {#setextentx}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the metafile.

### setExtentY() {#setextenty}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the metafile.

### setForeignType() {#setforeigntype}

Data type. The value of the property is ForeignType integer constant.

### setImageData() {#setimagedata}

Represents image of ole object as byte array.

### setMappingMode() {#setmappingmode}

This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode.

### setObjectData() {#setobjectdata}

Represents embedded ole object data as byte array.

### setObjectHeight() {#setobjectheight}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the object in page units.

### setObjectSourceFullName() {#setobjectsourcefullname}

Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name when the file type is OleFileType.Unknown. Such as wav file ,avi file..etc..

### setObjectType() {#setobjecttype}

If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. The value of the property is ObjectType integer constant.

### setObjectWidth() {#setobjectwidth}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the object in page units.

### setShowAsIcon() {#setshowasicon}

This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value of the property is BOOL integer constant.

### setValue() {#setvalue}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.
