---
title: ForeignData
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält einen MIME Multipurpose Internet Mail Extensions codierten BLOB von Bilddaten wie Windows metafile bitmap oder OLE-Daten.
type: docs
weight: 164
url: /de/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein rasterbasiertes Fremdobjekt sind, wie z. B. eine DIB-, JPG-, PNG-, TIFF- oder GIF-Datei. |
| [getCompressionType()](#getCompressionType--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein rasterbasiertes Fremdobjekt sind, wie z. B. eine DIB-, JPG-, PNG-, TIFF- oder GIF-Datei. |
| [getExtentX()](#getExtentX--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten eine Metadatei sind. |
| [getExtentY()](#getExtentY--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten eine Metadatei sind. |
| [getForeignType()](#getForeignType--) | Datentyp. |
| [getImageData()](#getImageData--) | Stellt das Bild eines OLE-Objekts als Byte-Array dar. |
| [getMappingMode()](#getMappingMode--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten eine Metadatei sind. |
| [getObjectData()](#getObjectData--) | Stellt eingebettete OLE-Objektdaten als Byte-Array dar. |
| [getObjectHeight()](#getObjectHeight--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein OLE2 eingebettetes Objekt sind. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Gibt den vollständigen Namen der Quelldatei für das verknüpfte OLE-Objekt zurück. |
| [getObjectType()](#getObjectType--) | Wenn das Attribut ForeignType "Object" ist, muss das Element ForeignData ebenfalls ein Attribut ObjectType besitzen. |
| [getObjectWidth()](#getObjectWidth--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein OLE2 eingebettetes Objekt sind. |
| [getShowAsIcon()](#getShowAsIcon--) | Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein OLE2 eingebettetes Objekt sind. |
| [getValue()](#getValue--) | Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein rasterbasiertes Fremdobjekt sind, wie z. B. eine DIB-, JPG-, PNG-, TIFF- oder GIF-Datei. Der Wert gibt das Kompressionsniveau an, das auf die Datei angewendet wird. Das Kompressionsniveau wird in Hundertstel Prozent gemessen.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein rasterbasiertes Fremdobjekt sind, wie z. B. eine DIB-, JPG-, PNG-, TIFF- oder GIF-Datei. Der Wert gibt den Typ der auf die Datei angewendeten Kompression an.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten eine Metadatei sind. Der Wert gibt die horizontale Ausdehnung der Metadatei an.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten eine Metadatei sind. Der Wert gibt die vertikale Ausdehnung der Metadatei an.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Datentyp.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Stellt das Bild eines OLE-Objekts als Byte-Array dar.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten eine Metadatei sind. Der Wert gibt den Mapping‑Modus der Metadatei an.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Stellt eingebettete OLE-Objektdaten als Byte-Array dar.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein OLE2 eingebettetes Objekt sind. Der Wert gibt die Höhe des Objekts in Seiteneinheiten an.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Gibt den vollständigen Namen der Quelldatei für das verknüpfte OLE-Objekt zurück. Das Festlegen des vollständigen Namens wird nur unterstützt, wenn der Dateityp OleFileType.Unknown ist, z. B. wav‑Datei, avi‑Datei usw.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Wenn das Attribut ForeignType "Object" ist, muss das Element ForeignData ebenfalls ein Attribut ObjectType besitzen.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein OLE2 eingebettetes Objekt sind. Der Wert gibt die Breite des Objekts in Seiteneinheiten an.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Dieses Attribut ist nur sinnvoll, wenn die Fremddaten ein OLE2 eingebettetes Objekt sind.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

