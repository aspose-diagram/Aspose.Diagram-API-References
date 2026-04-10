---
title: DocumentSheet
second_title: Aspose.Diagram för Java API-referens
description: Specificerar ett dokuments ShapeSheet-struktur.
type: docs
weight: 127
url: /sv/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

Anger ett dokuments ShapeSheet-struktur.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | Innehåller element som innehåller information om kommentarer som infogats i en dokumentsida. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Innehåller en samling av ConnectionABCD-element. |
| [getConnections()](#getConnections--) | Innehåller en samling av Connection-element. |
| [getDocProps()](#getDocProps--) | Innehåller element som styr dokumentets förhandsgranskningskvalitet, omfattning och utdataformat. |
| [getFillStyle()](#getFillStyle--) | StyleSheet-element från vilket detta stil ärver fyllningsformatering. |
| [getForeign()](#getForeign--) | Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. |
| [getForeignData()](#getForeignData--) | Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data. |
| [getHyperlinks()](#getHyperlinks--) | Innehåller en samling Hyperlink-element. |
| [getLineStyle()](#getLineStyle--) | StyleSheet-element från vilket detta stil ärver linjeformatering. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getProps()](#getProps--) | Innehåller en samling Prop-element. |
| [getReviewers()](#getReviewers--) | Innehåller element som innehåller identifierande information om en dokumentgranskare. |
| [getScratchs()](#getScratchs--) | Innehåller en samling Scratch-element. |
| [getTextStyle()](#getTextStyle--) | StyleSheet-element från vilket detta stil ärver textformatering. |
| [getUniqueID()](#getUniqueID--) | En GUID (globalt unik identifierare) som identifierar formen. |
| [getUsers()](#getUsers--) | Innehåller en samling User-element. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | För beskrivningen av denna egenskap, se [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Innehåller element som innehåller information om kommentarer som infogats i en dokumentsida.

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


Innehåller en samling av ConnectionABCD-element.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Innehåller en samling av Connection-element.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


Innehåller element som styr dokumentets förhandsgranskningskvalitet, omfattning och utdataformat.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet-element från vilket detta stil ärver fyllningsformatering.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. Inkluderar också element som specificerar avståndet som objektets bild förskjuts inom dess kanter.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Innehåller en samling Hyperlink-element.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet-element från vilket detta stil ärver linjeformatering.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getName() {#getName--}
```
public String getName()
```


Elementets namn.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Det universella namnet för elementet.

**Returns:**
java.lang.String
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Innehåller en samling Prop-element.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


Innehåller element som innehåller identifierande information om en dokumentgranskare.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Innehåller en samling Scratch-element.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet-element från vilket detta stil ärver textformatering.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


En GUID (globalt unik identifierare) som identifierar formen.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Innehåller en samling User-element.

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


För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


För beskrivningen av denna egenskap, se [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

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

