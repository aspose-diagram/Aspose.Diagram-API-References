---
title: ForeignData
second_title: Aspose.Diagram för Java API-referens
description: Innehåller en MIME Multipurpose Internet Mail Extensions-kodad BLOB av bilddata såsom Windows-metafil bitmap eller OLE-data.
type: docs
weight: 164
url: /sv/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Detta attribut är endast meningsfullt om den främmande datan är ett rasterbaserat främmande objekt, såsom en DIB-, JPG-, PNG-, TIFF- eller GIF-fil. |
| [getCompressionType()](#getCompressionType--) | Detta attribut är endast meningsfullt om den främmande datan är ett rasterbaserat främmande objekt, såsom en DIB-, JPG-, PNG-, TIFF- eller GIF-fil. |
| [getExtentX()](#getExtentX--) | Detta attribut är endast meningsfullt om den främmande datan är en metafil. |
| [getExtentY()](#getExtentY--) | Detta attribut är endast meningsfullt om den främmande datan är en metafil. |
| [getForeignType()](#getForeignType--) | Datatyp. |
| [getImageData()](#getImageData--) | Representerar bild av ole-objekt som byte-array. |
| [getMappingMode()](#getMappingMode--) | Detta attribut är endast meningsfullt om den främmande datan är en metafil. |
| [getObjectData()](#getObjectData--) | Representerar inbäddad ole-objektsdata som byte-array. |
| [getObjectHeight()](#getObjectHeight--) | Detta attribut är endast meningsfullt om den främmande datan är ett OLE2 inbäddat objekt. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Returnerar det fullständiga namnet på källfilen för det länkade OLE-objektet. |
| [getObjectType()](#getObjectType--) | Om attributet ForeignType är "Object" måste ForeignData‑elementet också ha ett ObjectType‑attribut. |
| [getObjectWidth()](#getObjectWidth--) | Detta attribut är endast meningsfullt om den främmande datan är ett OLE2 inbäddat objekt. |
| [getShowAsIcon()](#getShowAsIcon--) | Detta attribut är endast meningsfullt om den främmande datan är ett OLE2 inbäddat objekt. |
| [getValue()](#getValue--) | Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | För beskrivning av denna egenskap, se [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | För beskrivning av denna egenskap, se [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | För beskrivning av denna egenskap, se [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | För beskrivning av denna egenskap, se [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | För beskrivning av denna egenskap, se [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | För beskrivning av denna egenskap, se [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | För beskrivning av denna egenskap, se [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | För beskrivning av denna egenskap, se [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | För beskrivning av denna egenskap, se [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | För beskrivning av denna egenskap, se [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | För beskrivning av denna egenskap, se [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | För beskrivning av denna egenskap, se [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | För beskrivning av denna egenskap, se [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | För beskrivning av denna egenskap, se [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Detta attribut är endast meningsfullt om den främmande datan är ett rasterbaserat främmande objekt, såsom en DIB-, JPG-, PNG-, TIFF- eller GIF-fil. Värdet anger komprimeringsnivån som tillämpas på filen. Komprimeringsnivån mäts i hundradelar av en procent.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Detta attribut är endast meningsfullt om den främmande datan är ett rasterbaserat främmande objekt, såsom en DIB-, JPG-, PNG-, TIFF- eller GIF-fil. Värdet anger typen av kompression som tillämpas på filen.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Detta attribut är endast meningsfullt om den främmande datan är en metafil. Värdet anger den horisontella omfattningen av metafilen.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Detta attribut är endast meningsfullt om den främmande datan är en metafil. Värdet anger den vertikala omfattningen av metafilen.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Datatyp.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Representerar bild av ole-objekt som byte-array.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Detta attribut är endast meningsfullt om den främmande datan är en metafil. Värdet anger metafilens kartläggningsläge.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Representerar inbäddad ole-objektsdata som byte-array.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Detta attribut är endast meningsfullt om den främmande datan är ett OLE2 inbäddat objekt. Värdet uttrycker objektets höjd i sid-enheter.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Returnerar det fullständiga namnet på källfilen för det länkade OLE-objektet. Stöder endast att ange det fullständiga namnet när filtypen är OleFileType.Unknown. Till exempel wav‑fil, avi‑fil osv..

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Om attributet ForeignType är "Object" måste ForeignData‑elementet också ha ett ObjectType‑attribut.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Detta attribut är endast meningsfullt om den främmande datan är ett OLE2 inbäddat objekt. Värdet uttrycker objektets bredd i sid-enheter.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Detta attribut är endast meningsfullt om den främmande datan är ett OLE2 inbäddat objekt.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data.

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


För beskrivning av denna egenskap, se [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


För beskrivning av denna egenskap, se [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


För beskrivning av denna egenskap, se [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


För beskrivning av denna egenskap, se [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


För beskrivning av denna egenskap, se [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


För beskrivning av denna egenskap, se [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


För beskrivning av denna egenskap, se [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


För beskrivning av denna egenskap, se [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


För beskrivning av denna egenskap, se [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


För beskrivning av denna egenskap, se [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


För beskrivning av denna egenskap, se [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


För beskrivning av denna egenskap, se [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


För beskrivning av denna egenskap, se [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


För beskrivning av denna egenskap, se [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

