---
title: ForeignData
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat een MIME Multipurpose Internet Mail Extensions gecodeerde BLOB van afbeeldingsgegevens, zoals Windows-metabestand bitmap of OLE-gegevens.
type: docs
weight: 164
url: /nl/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Dit attribuut is alleen betekenisvol als de externe gegevens een rastergebaseerd extern object zijn, zoals een DIB-, JPG-, PNG-, TIFF- of GIF-bestand. |
| [getCompressionType()](#getCompressionType--) | Dit attribuut is alleen betekenisvol als de externe gegevens een rastergebaseerd extern object zijn, zoals een DIB-, JPG-, PNG-, TIFF- of GIF-bestand. |
| [getExtentX()](#getExtentX--) | Dit attribuut is alleen betekenisvol als de foreign data een metabestand is. |
| [getExtentY()](#getExtentY--) | Dit attribuut is alleen betekenisvol als de foreign data een metabestand is. |
| [getForeignType()](#getForeignType--) | Gegevenstype. |
| [getImageData()](#getImageData--) | Stelt de afbeelding van een ole-object voor als byte-array. |
| [getMappingMode()](#getMappingMode--) | Dit attribuut is alleen betekenisvol als de foreign data een metabestand is. |
| [getObjectData()](#getObjectData--) | Stelt de ingebedde ole-objectgegevens voor als byte-array. |
| [getObjectHeight()](#getObjectHeight--) | Dit attribuut is alleen betekenisvol als de vreemde gegevens een OLE2 embedded object zijn. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Retourneert de volledige naam van de bron van het bronbestand voor het gekoppelde OLE-object. |
| [getObjectType()](#getObjectType--) | Als het attribuut ForeignType "Object" is, moet het ForeignData‑element ook een ObjectType‑attribuut hebben. |
| [getObjectWidth()](#getObjectWidth--) | Dit attribuut is alleen betekenisvol als de vreemde gegevens een OLE2 embedded object zijn. |
| [getShowAsIcon()](#getShowAsIcon--) | Dit attribuut is alleen betekenisvol als de vreemde gegevens een OLE2 embedded object zijn. |
| [getValue()](#getValue--) | Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Voor de beschrijving van deze eigenschap, zie [getCompressionLevel()](../../com.aspose.diagram/foreigndata\\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Voor de beschrijving van deze eigenschap, zie [getCompressionType()](../../com.aspose.diagram/foreigndata\\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Voor de beschrijving van deze eigenschap, zie [getExtentX()](../../com.aspose.diagram/foreigndata\\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Voor de beschrijving van deze eigenschap, zie [getExtentY()](../../com.aspose.diagram/foreigndata\\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Voor de beschrijving van deze eigenschap, zie [getForeignType()](../../com.aspose.diagram/foreigndata\\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Voor de beschrijving van deze eigenschap, zie [getImageData()](../../com.aspose.diagram/foreigndata\\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Voor de beschrijving van deze eigenschap, zie [getMappingMode()](../../com.aspose.diagram/foreigndata\\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Voor de beschrijving van deze eigenschap, zie [getObjectData()](../../com.aspose.diagram/foreigndata\\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Voor de beschrijving van deze eigenschap, zie [getObjectHeight()](../../com.aspose.diagram/foreigndata\\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Voor de beschrijving van deze eigenschap, zie [getObjectType()](../../com.aspose.diagram/foreigndata\\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Voor de beschrijving van deze eigenschap, zie [getObjectWidth()](../../com.aspose.diagram/foreigndata\\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Voor de beschrijving van deze eigenschap, zie [getShowAsIcon()](../../com.aspose.diagram/foreigndata\\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Voor de beschrijving van deze eigenschap, zie [getValue()](../../com.aspose.diagram/foreigndata\\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Dit attribuut is alleen betekenisvol als de vreemde gegevens een rastergebaseerd object zijn, zoals een DIB-, JPG-, PNG-, TIFF- of GIF-bestand. De waarde geeft het compressieniveau aan dat op het bestand wordt toegepast. Het compressieniveau wordt gemeten in honderdsten van een procent.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een rastergebaseerd object zijn, zoals een DIB-, JPG-, PNG-, TIFF- of GIF-bestand. De waarde geeft het type compressie aan dat op het bestand wordt toegepast.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een metafile zijn. De waarde geeft de horizontale omvang van de metafile aan.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een metafile zijn. De waarde geeft de verticale omvang van de metafile aan.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Gegevenstype.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Stelt de afbeelding van een ole-object voor als byte-array.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een metafile zijn. De waarde geeft de mappingmodus van de metafile aan.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Stelt de ingebedde ole-objectgegevens voor als byte-array.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een OLE2 embedded object zijn. De waarde geeft de hoogte van het object weer in pagina-eenheden.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Retourneert de volledige naam van de bron van het bronbestand voor het gekoppelde OLE-object. Ondersteunt alleen het instellen van de volledige bronnaam wanneer het bestandstype OleFileType.Unknown is. Bijvoorbeeld wav‑bestand, avi‑bestand, enz.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Als het attribuut ForeignType "Object" is, moet het ForeignData‑element ook een ObjectType‑attribuut hebben.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een OLE2 embedded object zijn. De waarde geeft de breedte van het object weer in pagina-eenheden.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Dit attribuut is alleen betekenisvol als de vreemde gegevens een OLE2 embedded object zijn.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens.

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


Voor de beschrijving van deze eigenschap, zie [getCompressionLevel()](../../com.aspose.diagram/foreigndata\\#getCompressionLevel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Voor de beschrijving van deze eigenschap, zie [getCompressionType()](../../com.aspose.diagram/foreigndata\\#getCompressionType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Voor de beschrijving van deze eigenschap, zie [getExtentX()](../../com.aspose.diagram/foreigndata\\#getExtentX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Voor de beschrijving van deze eigenschap, zie [getExtentY()](../../com.aspose.diagram/foreigndata\\#getExtentY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Voor de beschrijving van deze eigenschap, zie [getForeignType()](../../com.aspose.diagram/foreigndata\\#getForeignType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getImageData()](../../com.aspose.diagram/foreigndata\\#getImageData--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMappingMode()](../../com.aspose.diagram/foreigndata\\#getMappingMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getObjectData()](../../com.aspose.diagram/foreigndata\\#getObjectData--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Voor de beschrijving van deze eigenschap, zie [getObjectHeight()](../../com.aspose.diagram/foreigndata\\#getObjectHeight--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\\#getObjectSourceFullName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Voor de beschrijving van deze eigenschap, zie [getObjectType()](../../com.aspose.diagram/foreigndata\\#getObjectType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Voor de beschrijving van deze eigenschap, zie [getObjectWidth()](../../com.aspose.diagram/foreigndata\\#getObjectWidth--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowAsIcon()](../../com.aspose.diagram/foreigndata\\#getShowAsIcon--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getValue()](../../com.aspose.diagram/foreigndata\\#getValue--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

