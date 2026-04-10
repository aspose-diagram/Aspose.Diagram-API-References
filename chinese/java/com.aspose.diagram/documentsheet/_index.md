---
title: DocumentSheet
second_title: Aspose.Diagram for Java API 参考
description: 指定文档的 ShapeSheet 结构。
type: docs
weight: 127
url: /zh/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

指定文档的 ShapeSheet 结构。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | 包含提供关于插入文档页面的批注信息的元素。 |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | 包含 ConnectionABCD 元素的集合。 |
| [getConnections()](#getConnections--) | 包含 Connection 元素的集合。 |
| [getDocProps()](#getDocProps--) | 包含控制文档预览质量、范围和输出格式的元素。 |
| [getFillStyle()](#getFillStyle--) | 此样式从中继承填充格式的 StyleSheet 元素。 |
| [getForeign()](#getForeign--) | 包含指定在 Microsoft Visio 文档中使用的来自其他程序的对象宽度和高度的元素。 |
| [getForeignData()](#getForeignData--) | 包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。 |
| [getHyperlinks()](#getHyperlinks--) | 包含 Hyperlink 元素的集合。 |
| [getLineStyle()](#getLineStyle--) | 此样式从中继承线条格式的 StyleSheet 元素。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getProps()](#getProps--) | 包含 Prop 元素的集合。 |
| [getReviewers()](#getReviewers--) | 包含提供文档审阅者身份信息的元素。 |
| [getScratchs()](#getScratchs--) | 包含一组 Scratch 元素。 |
| [getTextStyle()](#getTextStyle--) | 此样式从中继承文本格式的 StyleSheet 元素。 |
| [getUniqueID()](#getUniqueID--) | 标识形状的 GUID（全局唯一标识符）。 |
| [getUsers()](#getUsers--) | 包含一组 User 元素。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


包含提供关于插入文档页面的批注信息的元素。

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


包含 ConnectionABCD 元素的集合。

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


包含 Connection 元素的集合。

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


包含控制文档预览质量、范围和输出格式的元素。

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


此样式从中继承填充格式的 StyleSheet 元素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


包含指定来自其他程序的对象在 Microsoft Visio 文档中使用的宽度和高度的元素。同时包括指定对象图像在其边界内偏移距离的元素。

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


包含 Hyperlink 元素的集合。

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


此样式从中继承线条格式的 StyleSheet 元素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getName() {#getName--}
```
public String getName()
```


元素的名称。

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


元素的通用名称。

**Returns:**
java.lang.String
### getProps() {#getProps--}
```
public PropCollection getProps()
```


包含 Prop 元素的集合。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


包含提供文档审阅者身份信息的元素。

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


包含一组 Scratch 元素。

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


此样式从中继承文本格式的 StyleSheet 元素。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


标识形状的 GUID（全局唯一标识符）。

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


包含一组 User 元素。

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


有关此属性的描述，请参阅 [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

