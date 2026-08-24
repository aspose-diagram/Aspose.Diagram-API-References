---
title: ForeignData
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene un BLOB codificato MIME Multipurpose Internet Mail Extensions di dati immagine, come bitmap di metafile Windows o dati OLE.
type: docs
weight: 164
url: /it/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Questo attributo ha senso solo se i dati esterni sono un oggetto esterno basato su raster, come un file DIB, JPG, PNG, TIFF o GIF. |
| [getCompressionType()](#getCompressionType--) | Questo attributo ha senso solo se i dati esterni sono un oggetto esterno basato su raster, come un file DIB, JPG, PNG, TIFF o GIF. |
| [getExtentX()](#getExtentX--) | Questo attributo ha senso solo se i dati esterni sono un metafile. |
| [getExtentY()](#getExtentY--) | Questo attributo ha senso solo se i dati esterni sono un metafile. |
| [getForeignType()](#getForeignType--) | Tipo di dati. |
| [getImageData()](#getImageData--) | Rappresenta l'immagine dell'oggetto OLE come array di byte. |
| [getMappingMode()](#getMappingMode--) | Questo attributo ha senso solo se i dati esterni sono un metafile. |
| [getObjectData()](#getObjectData--) | Rappresenta i dati dell'oggetto OLE incorporato come array di byte. |
| [getObjectHeight()](#getObjectHeight--) | Questo attributo ha senso solo se i dati esterni sono un oggetto OLE2 incorporato. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Restituisce il nome completo della sorgente del file di origine per l'oggetto OLE collegato. |
| [getObjectType()](#getObjectType--) | Se l'attributo ForeignType è "Object", l'elemento ForeignData deve inoltre avere un attributo ObjectType. |
| [getObjectWidth()](#getObjectWidth--) | Questo attributo ha senso solo se i dati esterni sono un oggetto OLE2 incorporato. |
| [getShowAsIcon()](#getShowAsIcon--) | Questo attributo ha senso solo se i dati esterni sono un oggetto OLE2 incorporato. |
| [getValue()](#getValue--) | Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Per la descrizione di questa proprietà, consultare [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Per la descrizione di questa proprietà, consultare [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Per la descrizione di questa proprietà, consultare [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Per la descrizione di questa proprietà, consultare [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Per la descrizione di questa proprietà, consultare [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Per la descrizione di questa proprietà, consultare [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Per la descrizione di questa proprietà, consultare [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Per la descrizione di questa proprietà, consultare [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Per la descrizione di questa proprietà, consultare [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Per la descrizione di questa proprietà, consultare [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Per la descrizione di questa proprietà, consultare [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Per la descrizione di questa proprietà, consultare [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Per la descrizione di questa proprietà, consultare [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profonda di questa istanza.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Questo attributo ha senso solo se i dati esterni sono un oggetto esterno basato su raster, come un file DIB, JPG, PNG, TIFF o GIF. Il valore indica il livello di compressione applicato al file. Il livello di compressione è misurato in centinaia di percento.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Questo attributo ha senso solo se i dati esterni sono un oggetto esterno basato su raster, come un file DIB, JPG, PNG, TIFF o GIF. Il valore indica il tipo di compressione applicato al file.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Questo attributo ha senso solo se i dati esterni sono un metafile. Il valore indica l'estensione orizzontale del metafile.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Questo attributo ha senso solo se i dati esterni sono un metafile. Il valore indica l'estensione verticale del metafile.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Tipo di dati.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Rappresenta l'immagine dell'oggetto OLE come array di byte.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Questo attributo ha senso solo se i dati esterni sono un metafile. Il valore indica la modalità di mappatura del metafile.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Rappresenta i dati dell'oggetto OLE incorporato come array di byte.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Questo attributo ha senso solo se i dati esterni sono un oggetto OLE2 incorporato. Il valore esprime l'altezza dell'oggetto in unità di pagina.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Restituisce il nome completo della sorgente del file di origine per l'oggetto OLE collegato. Supporta l'impostazione del nome completo della sorgente solo quando il tipo di file è OleFileType.Unknown. Ad esempio file wav, file avi, ecc.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Se l'attributo ForeignType è "Object", l'elemento ForeignData deve inoltre avere un attributo ObjectType.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Questo attributo ha senso solo se i dati esterni sono un oggetto OLE2 incorporato. Il valore esprime la larghezza dell'oggetto in unità di pagina.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Questo attributo ha senso solo se i dati esterni sono un oggetto OLE2 incorporato.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE.

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


Per la descrizione di questa proprietà, consultare [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Per la descrizione di questa proprietà, consultare [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Per la descrizione di questa proprietà, consultare [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Per la descrizione di questa proprietà, consultare [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Per la descrizione di questa proprietà, consultare [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Per la descrizione di questa proprietà, consultare [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Per la descrizione di questa proprietà, consultare [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Per la descrizione di questa proprietà, consultare [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Per la descrizione di questa proprietà, consultare [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Per la descrizione di questa proprietà, consultare [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Per la descrizione di questa proprietà, consultare [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Per la descrizione di questa proprietà, consultare [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Per la descrizione di questa proprietà, consultare [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Per la descrizione di questa proprietà, consultare [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

