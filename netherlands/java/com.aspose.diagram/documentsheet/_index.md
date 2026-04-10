---
title: DocumentSheet
second_title: Aspose.Diagram voor Java API-referentie
description: Specificeert de ShapeSheet‑structuur van een document.
type: docs
weight: 127
url: /nl/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

Specificeert de ShapeSheet-structuur van een document.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | Bevat elementen die informatie bevatten over opmerkingen die in een documentpagina zijn ingevoegd. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Bevat een verzameling van ConnectionABCD-elementen. |
| [getConnections()](#getConnections--) | Bevat een verzameling van Connection-elementen. |
| [getDocProps()](#getDocProps--) | Bevat elementen die de previewkwaliteit, reikwijdte en uitvoerformaat van het document regelen. |
| [getFillStyle()](#getFillStyle--) | StyleSheet-element waarvan deze stijl de opvulopmaak erft. |
| [getForeign()](#getForeign--) | Bevat elementen die de breedte en hoogte specificeren van een object uit een ander programma dat in een Microsoft Visio‑document wordt gebruikt. |
| [getForeignData()](#getForeignData--) | Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens. |
| [getHyperlinks()](#getHyperlinks--) | Bevat een verzameling Hyperlink‑elementen. |
| [getLineStyle()](#getLineStyle--) | StyleSheet-element waarvan deze stijl de lijnopmaak erft. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getProps()](#getProps--) | Bevat een verzameling Prop‑elementen. |
| [getReviewers()](#getReviewers--) | Bevat elementen die identificerende informatie over een documentbeoordeler bevatten. |
| [getScratchs()](#getScratchs--) | Bevat een verzameling Scratch-elementen. |
| [getTextStyle()](#getTextStyle--) | StyleSheet-element waarvan deze stijl de tekstopmaak erft. |
| [getUniqueID()](#getUniqueID--) | Een GUID (globaal unieke identifier) die de vorm identificeert. |
| [getUsers()](#getUsers--) | Bevat een verzameling User-elementen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Voor de beschrijving van deze eigenschap, zie [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Bevat elementen die informatie bevatten over opmerkingen die in een documentpagina zijn ingevoegd.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Bevat een verzameling van ConnectionABCD-elementen.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Bevat een verzameling van Connection-elementen.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


Bevat elementen die de previewkwaliteit, reikwijdte en uitvoerformaat van het document regelen.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet-element waarvan deze stijl de opvulopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Bevat elementen die de breedte en hoogte van een object uit een ander programma specificeren dat in een Microsoft Visio‑document wordt gebruikt. Bevat ook elementen die de afstand specificeren waarmee de afbeelding van het object binnen zijn randen is verschoven.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Bevat een verzameling Hyperlink‑elementen.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet-element waarvan deze stijl de lijnopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getName() {#getName--}
```
public String getName()
```


De naam van het element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


De universele naam van het element.

**Returns:**
java.lang.String
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Bevat een verzameling Prop‑elementen.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


Bevat elementen die identificerende informatie over een documentbeoordeler bevatten.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Bevat een verzameling Scratch-elementen.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet-element waarvan deze stijl de tekstopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Een GUID (globaal unieke identifier) die de vorm identificeert.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Bevat een verzameling User-elementen.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Voor de beschrijving van deze eigenschap, zie [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

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

