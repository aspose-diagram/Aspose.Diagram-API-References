---
title: DocumentSheet
second_title: Aspose.Diagram for Java API Reference
description: Specifies a documents ShapeSheet structure.
type: docs
weight: 131
url: /java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

Specifies a document's ShapeSheet structure.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | Contains elements that contain information about comments inserted into a document page. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contains a collection of ConnectionABCD elements. |
| [getConnections()](#getConnections--) | Contains a collection of Connection elements. |
| [getDocProps()](#getDocProps--) | Contains elements that control the document's preview quality, scope, and output format. |
| [getFillStyle()](#getFillStyle--) | StyleSheet element from which this style inherits fill formatting. |
| [getForeign()](#getForeign--) | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. |
| [getForeignData()](#getForeignData--) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data. |
| [getHyperlinks()](#getHyperlinks--) | Contains a collection of Hyperlink elements. |
| [getLineStyle()](#getLineStyle--) | StyleSheet element from which this style inherits line formatting. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getProps()](#getProps--) | Contains a collection of Prop elements. |
| [getReviewers()](#getReviewers--) | Contains elements that contain identifying information about a document reviewer. |
| [getScratchs()](#getScratchs--) | Contains a collection of Scratch elements. |
| [getTextStyle()](#getTextStyle--) | StyleSheet element from which this style inherits text formatting. |
| [getUniqueID()](#getUniqueID--) | A GUID (globally unique identifier) identifying the shape. |
| [getUsers()](#getUsers--) | Contains a collection of User elements. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Contains elements that contain information about comments inserted into a document page.

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


Contains a collection of ConnectionABCD elements.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Contains a collection of Connection elements.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


Contains elements that control the document's preview quality, scope, and output format.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet element from which this style inherits fill formatting.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contains a collection of Hyperlink elements.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet element from which this style inherits line formatting.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getName() {#getName--}
```
public String getName()
```


The name of the element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


The universal name of the element.

**Returns:**
java.lang.String
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contains a collection of Prop elements.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


Contains elements that contain identifying information about a document reviewer.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contains a collection of Scratch elements.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet element from which this style inherits text formatting.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


A GUID (globally unique identifier) identifying the shape.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Contains a collection of User elements.

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


For the description of this property, please see [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


For the description of this property, please see [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

