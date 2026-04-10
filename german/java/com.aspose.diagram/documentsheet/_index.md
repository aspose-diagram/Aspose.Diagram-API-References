---
title: DocumentSheet
second_title: Aspose.Diagram for Java API-Referenz
description: Gibt die ShapeSheet-Struktur eines Dokuments an.
type: docs
weight: 127
url: /de/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

Gibt die ShapeSheet-Struktur eines Dokuments an.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | Enthält Elemente, die Informationen über in einer Dokumentseite eingefügte Kommentare enthalten. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Enthält eine Sammlung von ConnectionABCD-Elementen. |
| [getConnections()](#getConnections--) | Enthält eine Sammlung von Connection-Elementen. |
| [getDocProps()](#getDocProps--) | Enthält Elemente, die die Vorschauqualität, den Umfang und das Ausgabeformat des Dokuments steuern. |
| [getFillStyle()](#getFillStyle--) | StyleSheet-Element, von dem dieser Stil die Füllformatierung erbt. |
| [getForeign()](#getForeign--) | Enthält Elemente, die die Breite und Höhe eines Objekts aus einem anderen Programm angeben, das in einem Microsoft Visio-Dokument verwendet wird. |
| [getForeignData()](#getForeignData--) | Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten. |
| [getHyperlinks()](#getHyperlinks--) | Enthält eine Sammlung von Hyperlink-Elementen. |
| [getLineStyle()](#getLineStyle--) | StyleSheet-Element, von dem dieser Stil die Linienformatierung erbt. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getProps()](#getProps--) | Enthält eine Sammlung von Prop-Elementen. |
| [getReviewers()](#getReviewers--) | Enthält Elemente, die Identifizierungsinformationen über einen Dokumentprüfer enthalten. |
| [getScratchs()](#getScratchs--) | Enthält eine Sammlung von Scratch-Elementen. |
| [getTextStyle()](#getTextStyle--) | StyleSheet-Element, von dem dieser Stil die Textformatierung erbt. |
| [getUniqueID()](#getUniqueID--) | Eine GUID (global eindeutiger Bezeichner), die die Form identifiziert. |
| [getUsers()](#getUsers--) | Enthält eine Sammlung von User-Elementen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Enthält Elemente, die Informationen über in einer Dokumentseite eingefügte Kommentare enthalten.

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


Enthält eine Sammlung von ConnectionABCD-Elementen.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Enthält eine Sammlung von Connection-Elementen.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


Enthält Elemente, die die Vorschauqualität, den Umfang und das Ausgabeformat des Dokuments steuern.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet-Element, von dem dieser Stil die Füllformatierung erbt.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Enthält Elemente, die die Breite und Höhe eines aus einem anderen Programm stammenden Objekts in einem Microsoft Visio-Dokument angeben. Außerdem enthält es Elemente, die den Abstand angeben, um den das Bild des Objekts innerhalb seiner Ränder versetzt ist.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Enthält eine Sammlung von Hyperlink-Elementen.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet-Element, von dem dieser Stil die Linienformatierung erbt.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getName() {#getName--}
```
public String getName()
```


Der Name des Elements.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Der universelle Name des Elements.

**Returns:**
java.lang.String
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Enthält eine Sammlung von Prop-Elementen.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


Enthält Elemente, die Identifizierungsinformationen über einen Dokumentprüfer enthalten.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Enthält eine Sammlung von Scratch-Elementen.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet-Element, von dem dieser Stil die Textformatierung erbt.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Eine GUID (global eindeutiger Bezeichner), die die Form identifiziert.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Enthält eine Sammlung von User-Elementen.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

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

