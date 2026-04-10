---
title: ForeignData
second_title: Справочник API Aspose.Diagram for Java
description: Содержит BLOB данных изображения, закодированный в формате MIME Multipurpose Internet Mail Extensions, например, bitmap метафайла Windows или данные OLE.
type: docs
weight: 164
url: /ru/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Этот атрибут имеет смысл только если внешние данные представляют собой растровый внешний объект, такой как файл DIB, JPG, PNG, TIFF или GIF. |
| [getCompressionType()](#getCompressionType--) | Этот атрибут имеет смысл только если внешние данные представляют собой растровый внешний объект, такой как файл DIB, JPG, PNG, TIFF или GIF. |
| [getExtentX()](#getExtentX--) | Этот атрибут имеет смысл только если внешние данные являются метафайлом. |
| [getExtentY()](#getExtentY--) | Этот атрибут имеет смысл только если внешние данные являются метафайлом. |
| [getForeignType()](#getForeignType--) | Тип данных. |
| [getImageData()](#getImageData--) | Представляет изображение объекта OLE в виде массива байтов. |
| [getMappingMode()](#getMappingMode--) | Этот атрибут имеет смысл только если внешние данные являются метафайлом. |
| [getObjectData()](#getObjectData--) | Представляет встроенные данные объекта OLE в виде массива байтов. |
| [getObjectHeight()](#getObjectHeight--) | Этот атрибут имеет смысл только если внешние данные являются встроенным объектом OLE2. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Возвращает полное имя исходного файла для связанного объекта OLE. |
| [getObjectType()](#getObjectType--) | If the ForeignType attribute is \"Object\", the ForeignData element must also have an ObjectType attribute. |
| [getObjectWidth()](#getObjectWidth--) | Этот атрибут имеет смысл только если внешние данные являются встроенным объектом OLE2. |
| [getShowAsIcon()](#getShowAsIcon--) | Этот атрибут имеет смысл только если внешние данные являются встроенным объектом OLE2. |
| [getValue()](#getValue--) | Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Для описания этого свойства, пожалуйста, см. [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Для описания этого свойства, пожалуйста, см. [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Для описания этого свойства, пожалуйста, см. [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Для описания этого свойства, пожалуйста, см. [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Для описания этого свойства, пожалуйста, см. [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Для описания этого свойства, пожалуйста, см. [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Для описания этого свойства, пожалуйста, см. [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Для описания этого свойства, пожалуйста, см. [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Для описания этого свойства, пожалуйста, см. [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Для описания этого свойства, пожалуйста, см. [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Для описания этого свойства, пожалуйста, см. [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Для описания этого свойства, пожалуйста, см. [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Для описания этого свойства, пожалуйста, см. [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт глубокую копию этого экземпляра.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Этот атрибут имеет смысл только если внешние данные являются растровым объектом, например файлом DIB, JPG, PNG, TIFF или GIF. Значение указывает уровень сжатия, применённого к файлу. Уровень сжатия измеряется в сотых процента.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Этот атрибут имеет смысл только если внешние данные являются растровым объектом, например файлом DIB, JPG, PNG, TIFF или GIF. Значение указывает тип сжатия, применённого к файлу.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Этот атрибут имеет смысл только если внешние данные являются метафайлом. Значение указывает горизонтальный размер метафайла.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Этот атрибут имеет смысл только если внешние данные являются метафайлом. Значение указывает вертикальный размер метафайла.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Тип данных.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Представляет изображение объекта OLE в виде массива байтов.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Этот атрибут имеет смысл только если внешние данные являются метафайлом. Значение указывает режим отображения метафайла.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Представляет встроенные данные объекта OLE в виде массива байтов.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Этот атрибут имеет смысл только если внешние данные являются встроенным объектом OLE2. Значение задаёт высоту объекта в единицах страницы.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Возвращает полное имя исходного файла для связанного объекта OLE. Установка полного имени поддерживается только когда тип файла OleFileType.Unknown. Например, файлы wav, avi и т.д.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


If the ForeignType attribute is \"Object\", the ForeignData element must also have an ObjectType attribute.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Этот атрибут имеет смысл только если внешние данные являются встроенным объектом OLE2. Значение задаёт ширину объекта в единицах страницы.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Этот атрибут имеет смысл только если внешние данные являются встроенным объектом OLE2.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE.

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


Для описания этого свойства, пожалуйста, см. [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Для описания этого свойства, пожалуйста, см. [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Для описания этого свойства, пожалуйста, см. [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Для описания этого свойства, пожалуйста, см. [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Для описания этого свойства, пожалуйста, см. [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Для описания этого свойства, пожалуйста, см. [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Для описания этого свойства, пожалуйста, см. [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Для описания этого свойства, пожалуйста, см. [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Для описания этого свойства, пожалуйста, см. [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Для описания этого свойства, пожалуйста, см. [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Для описания этого свойства, пожалуйста, см. [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Для описания этого свойства, пожалуйста, см. [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Для описания этого свойства, пожалуйста, см. [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Для описания этого свойства, пожалуйста, см. [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

