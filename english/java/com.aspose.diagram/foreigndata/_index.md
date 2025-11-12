---
title: ForeignData
second_title: Aspose.Diagram for Java API Reference
description: Contains a MIME Multipurpose Internet Mail Extensions encoded BLOB of picture data such as Windows metafile bitmap or OLE data.
type: docs
weight: 168
url: /java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. |
| [getCompressionType()](#getCompressionType--) | This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. |
| [getExtentX()](#getExtentX--) | This attribute is only meaningful if the foreign data is a metafile. |
| [getExtentY()](#getExtentY--) | This attribute is only meaningful if the foreign data is a metafile. |
| [getForeignType()](#getForeignType--) | Data type. |
| [getImageData()](#getImageData--) | Represents image of ole object as byte array. |
| [getMappingMode()](#getMappingMode--) | This attribute is only meaningful if the foreign data is a metafile. |
| [getObjectData()](#getObjectData--) | Represents embedded ole object data as byte array. |
| [getObjectHeight()](#getObjectHeight--) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Returns the source full name of the source file for the linked OLE object. |
| [getObjectType()](#getObjectType--) | If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute. |
| [getObjectWidth()](#getObjectWidth--) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. |
| [getShowAsIcon()](#getShowAsIcon--) | This attribute is only meaningful if the foreign data is an OLE2 embedded object. |
| [getValue()](#getValue--) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | For the description of this property, please see [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | For the description of this property, please see [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | For the description of this property, please see [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | For the description of this property, please see [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | For the description of this property, please see [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | For the description of this property, please see [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | For the description of this property, please see [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | For the description of this property, please see [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | For the description of this property, please see [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | For the description of this property, please see [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | For the description of this property, please see [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | For the description of this property, please see [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | For the description of this property, please see [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | For the description of this property, please see [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates deep copy of this instance.

**Returns:**
java.lang.Object - 
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the level of compression applied to the file. Compression level is measured in hundreds of a percent.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


This attribute is only meaningful if the foreign data is a raster-based foreign object, such as a DIB, JPG, PNG, TIFF, or GIF file. The value indicates the type of compression applied to the file.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


This attribute is only meaningful if the foreign data is a metafile. The value indicates the horizontal extent of the metafile.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


This attribute is only meaningful if the foreign data is a metafile. The value indicates the vertical extent of the metafile.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Data type.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Represents image of ole object as byte array.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


This attribute is only meaningful if the foreign data is a metafile. The value indicates the metafile mapping mode.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Represents embedded ole object data as byte array.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the height of the object in page units.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Returns the source full name of the source file for the linked OLE object. Only supports setting the source full name when the file type is OleFileType.Unknown. Such as wav file ,avi file..etc..

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


If the ForeignType attribute is "Object", the ForeignData element must also have an ObjectType attribute.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


This attribute is only meaningful if the foreign data is an OLE2 embedded object. The value expresses the width of the object in page units.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


This attribute is only meaningful if the foreign data is an OLE2 embedded object.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Returns:**
byte[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


For the description of this property, please see [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


For the description of this property, please see [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


For the description of this property, please see [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


For the description of this property, please see [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


For the description of this property, please see [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


For the description of this property, please see [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


For the description of this property, please see [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


For the description of this property, please see [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


For the description of this property, please see [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


For the description of this property, please see [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


For the description of this property, please see [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


For the description of this property, please see [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


For the description of this property, please see [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


For the description of this property, please see [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

