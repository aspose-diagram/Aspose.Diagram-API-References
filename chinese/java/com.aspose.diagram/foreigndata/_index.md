---
title: ForeignData
second_title: Aspose.Diagram for Java API 参考
description: 包含使用 MIME 多用途互联网邮件扩展编码的图片数据 BLOB，例如 Windows 元文件位图或 OLE 数据。
type: docs
weight: 164
url: /zh/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | 仅当外部数据是基于光栅的外部对象（例如 DIB、JPG、PNG、TIFF 或 GIF 文件）时，此属性才有意义。 |
| [getCompressionType()](#getCompressionType--) | 仅当外部数据是基于光栅的外部对象（例如 DIB、JPG、PNG、TIFF 或 GIF 文件）时，此属性才有意义。 |
| [getExtentX()](#getExtentX--) | 如果外部数据是元文件，则此属性才有意义。 |
| [getExtentY()](#getExtentY--) | 如果外部数据是元文件，则此属性才有意义。 |
| [getForeignType()](#getForeignType--) | 数据类型。 |
| [getImageData()](#getImageData--) | 表示 OLE 对象的图像，采用字节数组形式。 |
| [getMappingMode()](#getMappingMode--) | 如果外部数据是元文件，则此属性才有意义。 |
| [getObjectData()](#getObjectData--) | 表示嵌入的 OLE 对象数据，采用字节数组形式。 |
| [getObjectHeight()](#getObjectHeight--) | 仅当外部数据是 OLE2 嵌入对象时，此属性才有意义。 |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | 返回链接的 OLE 对象的源文件的完整名称。 |
| [getObjectType()](#getObjectType--) | 如果 ForeignType 属性为 "Object"，则 ForeignData 元素还必须具有 ObjectType 属性。 |
| [getObjectWidth()](#getObjectWidth--) | 仅当外部数据是 OLE2 嵌入对象时，此属性才有意义。 |
| [getShowAsIcon()](#getShowAsIcon--) | 仅当外部数据是 OLE2 嵌入对象时，此属性才有意义。 |
| [getValue()](#getValue--) | 包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | 有关此属性的描述，请参阅 [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | 有关此属性的描述，请参阅 [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | 有关此属性的描述，请参阅 [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | 有关此属性的描述，请参阅 [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | 有关此属性的描述，请参阅 [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | 有关此属性的描述，请参阅 [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | 有关此属性的描述，请参阅 [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | 有关此属性的描述，请参阅 [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | 有关此属性的描述，请参阅 [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | 有关此属性的描述，请参阅 [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | 有关此属性的描述，请参阅 [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | 有关此属性的描述，请参阅 [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | 有关此属性的描述，请参阅 [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | 有关此属性的描述，请参阅 [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此实例的深度副本。

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


仅当外部数据是基于光栅的外部对象（例如 DIB、JPG、PNG、TIFF 或 GIF 文件）时，此属性才有意义。该值表示对文件应用的压缩级别。压缩级别以百分之一为单位计量。

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


仅当外部数据是基于光栅的外部对象（例如 DIB、JPG、PNG、TIFF 或 GIF 文件）时，此属性才有意义。该值表示对文件应用的压缩类型。

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


仅当外部数据是元文件时，此属性才有意义。该值表示元文件的水平范围。

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


仅当外部数据是元文件时，此属性才有意义。该值表示元文件的垂直范围。

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


数据类型。

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


表示 OLE 对象的图像，采用字节数组形式。

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


仅当外部数据是元文件时，此属性才有意义。该值表示元文件的映射模式。

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


表示嵌入的 OLE 对象数据，采用字节数组形式。

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


仅当外部数据是 OLE2 嵌入对象时，此属性才有意义。该值以页面单位表示对象的高度。

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


返回链接的 OLE 对象的源文件的完整名称。仅在文件类型为 OleFileType.Unknown 时支持设置完整名称。例如 wav 文件、avi 文件等。

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


如果 ForeignType 属性为 "Object"，则 ForeignData 元素还必须具有 ObjectType 属性。

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


仅当外部数据是 OLE2 嵌入对象时，此属性才有意义。该值以页面单位表示对象的宽度。

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


仅当外部数据是 OLE2 嵌入对象时，此属性才有意义。

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。

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


有关此属性的描述，请参阅 [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


有关此属性的描述，请参阅 [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


有关此属性的描述，请参阅 [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


有关此属性的描述，请参阅 [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


有关此属性的描述，请参阅 [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


有关此属性的描述，请参阅 [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


有关此属性的描述，请参阅 [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


有关此属性的描述，请参阅 [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


有关此属性的描述，请参阅 [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


有关此属性的描述，请参阅 [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


有关此属性的描述，请参阅 [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


有关此属性的描述，请参阅 [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


有关此属性的描述，请参阅 [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


有关此属性的描述，请参阅 [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

