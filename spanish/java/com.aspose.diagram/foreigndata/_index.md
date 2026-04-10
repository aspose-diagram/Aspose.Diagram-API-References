---
title: ForeignData
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene un BLOB codificado en MIME Multipurpose Internet Mail Extensions de datos de imagen, como un mapa de bits de metarchivo de Windows o datos OLE.
type: docs
weight: 164
url: /es/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE.
## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profunda de esta instancia. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Este atributo solo tiene sentido si los datos externos son un objeto externo basado en raster, como un archivo DIB, JPG, PNG, TIFF o GIF. |
| [getCompressionType()](#getCompressionType--) | Este atributo solo tiene sentido si los datos externos son un objeto externo basado en raster, como un archivo DIB, JPG, PNG, TIFF o GIF. |
| [getExtentX()](#getExtentX--) | Este atributo solo tiene sentido si los datos externos son un metarchivo. |
| [getExtentY()](#getExtentY--) | Este atributo solo tiene sentido si los datos externos son un metarchivo. |
| [getForeignType()](#getForeignType--) | Tipo de datos. |
| [getImageData()](#getImageData--) | Representa la imagen del objeto OLE como una matriz de bytes. |
| [getMappingMode()](#getMappingMode--) | Este atributo solo tiene sentido si los datos externos son un metarchivo. |
| [getObjectData()](#getObjectData--) | Representa los datos del objeto OLE incrustado como una matriz de bytes. |
| [getObjectHeight()](#getObjectHeight--) | Este atributo solo tiene sentido si los datos externos son un objeto incrustado OLE2. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Devuelve el nombre completo de origen del archivo fuente para el objeto OLE vinculado. |
| [getObjectType()](#getObjectType--) | Si el atributo ForeignType es "Object", el elemento ForeignData también debe tener un atributo ObjectType. |
| [getObjectWidth()](#getObjectWidth--) | Este atributo solo tiene sentido si los datos externos son un objeto incrustado OLE2. |
| [getShowAsIcon()](#getShowAsIcon--) | Este atributo solo tiene sentido si los datos externos son un objeto incrustado OLE2. |
| [getValue()](#getValue--) | Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Para la descripción de esta propiedad, consulte [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Para la descripción de esta propiedad, consulte [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Para la descripción de esta propiedad, consulte [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Para la descripción de esta propiedad, consulte [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Para la descripción de esta propiedad, consulte [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Para la descripción de esta propiedad, consulte [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Para la descripción de esta propiedad, consulte [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Para la descripción de esta propiedad, consulte [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Para la descripción de esta propiedad, consulte [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Para la descripción de esta propiedad, consulte [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Para la descripción de esta propiedad, consulte [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Para la descripción de esta propiedad, consulte [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Para la descripción de esta propiedad, consulte [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profunda de esta instancia.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Este atributo solo tiene sentido si los datos externos son un objeto externo basado en raster, como un archivo DIB, JPG, PNG, TIFF o GIF. El valor indica el nivel de compresión aplicado al archivo. El nivel de compresión se mide en cientos de un por ciento.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Este atributo solo tiene sentido si los datos externos son un objeto externo basado en raster, como un archivo DIB, JPG, PNG, TIFF o GIF. El valor indica el tipo de compresión aplicado al archivo.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Este atributo solo tiene sentido si los datos externos son un metarchivo. El valor indica la extensión horizontal del metarchivo.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Este atributo solo tiene sentido si los datos externos son un metarchivo. El valor indica la extensión vertical del metarchivo.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Tipo de datos.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Representa la imagen del objeto OLE como una matriz de bytes.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Este atributo solo tiene sentido si los datos externos son un metarchivo. El valor indica el modo de mapeo del metarchivo.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Representa los datos del objeto OLE incrustado como una matriz de bytes.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Este atributo solo tiene sentido si los datos externos son un objeto incrustado OLE2. El valor expresa la altura del objeto en unidades de página.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Devuelve el nombre completo de origen del archivo fuente para el objeto OLE vinculado. Solo admite establecer el nombre completo de origen cuando el tipo de archivo es OleFileType.Unknown. Por ejemplo, archivos wav, avi, etc.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Si el atributo ForeignType es "Object", el elemento ForeignData también debe tener un atributo ObjectType.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Este atributo solo tiene sentido si los datos externos son un objeto incrustado OLE2. El valor expresa el ancho del objeto en unidades de página.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Este atributo solo tiene sentido si los datos externos son un objeto incrustado OLE2.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE.

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


Para la descripción de esta propiedad, consulte [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Para la descripción de esta propiedad, consulte [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Para la descripción de esta propiedad, consulte [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Para la descripción de esta propiedad, consulte [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Para la descripción de esta propiedad, consulte [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Para la descripción de esta propiedad, consulte [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Para la descripción de esta propiedad, consulte [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Para la descripción de esta propiedad, consulte [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Para la descripción de esta propiedad, consulte [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Para la descripción de esta propiedad, consulte [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Para la descripción de esta propiedad, consulte [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Para la descripción de esta propiedad, consulte [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Para la descripción de esta propiedad, consulte [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Para la descripción de esta propiedad, consulte [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

