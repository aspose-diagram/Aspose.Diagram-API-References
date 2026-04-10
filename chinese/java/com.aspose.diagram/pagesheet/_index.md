---
title: PageSheet
second_title: Aspose.Diagram for Java API 参考
description: 包含定义页面或母版元素的页面工作表的元素。
type: docs
weight: 270
url: /zh/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

包含定义页面或母版元素的页面工作表的元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | 从源对象复制 pagesheet。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | 包含 Act 元素的集合。 |
| [getAnnotations()](#getAnnotations--) | 包含提供关于插入文档页面的批注信息的元素。 |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | 包含 ConnectionABCD 元素的集合。 |
| [getConnections()](#getConnections--) | 包含 Connection 元素的集合。 |
| [getFillStyle()](#getFillStyle--) | StyleSheet 元素，PageSheet 从中继承填充格式。 |
| [getForeign()](#getForeign--) | 包含指定在 Microsoft Visio 文档中使用的来自其他程序的对象宽度和高度的元素。 |
| [getForeignData()](#getForeignData--) | 包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。 |
| [getHyperlinks()](#getHyperlinks--) | 包含 Hyperlink 元素的集合。 |
| [getLayers()](#getLayers--) | 包含 Layer 元素的集合。 |
| [getLineStyle()](#getLineStyle--) | StyleSheet 元素，PageSheet 从中继承线条格式。 |
| [getPageLayout()](#getPageLayout--) | 包含 Diagram，控制页面布局设置，例如形状和连接器的间距，包括页面上所有形状之间的间距、页面上所有连接器之间的间距，以及所有连接器的路由样式。 |
| [getPageProps()](#getPageProps--) | 包含 Diagram，用于控制页面属性，例如页面宽度、高度和比例。 |
| [getPrintProps()](#getPrintProps--) | 包含控制绘图页面在打印机页面上如何格式化（显示）的元素。 |
| [getProps()](#getProps--) | 包含 Prop 元素的集合。 |
| [getRulerGrid()](#getRulerGrid--) | 包含指定页面标尺和网格设置的元素。 |
| [getScratchs()](#getScratchs--) | 包含一组 Scratch 元素。 |
| [getSmartTagDefs()](#getSmartTagDefs--) | 包含 SmartTagDef 元素的集合。 |
| [getTextStyle()](#getTextStyle--) | StyleSheet 元素，PageSheet 从中继承文本格式。 |
| [getUniqueID()](#getUniqueID--) | 元素的 GUID（全局唯一标识符）。 |
| [getUsers()](#getUsers--) | 包含一组 User 元素。 |
| [getXForm()](#getXForm--) | 包含指定形状一般位置信息的元素。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


从源对象复制 pagesheet。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | 源 pagesheet。 |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


包含 Act 元素的集合。

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet 元素，PageSheet 从中继承填充格式。

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
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


包含 Layer 元素的集合。

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet 元素，PageSheet 从中继承线条格式。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


包含 Diagram，控制页面布局设置，例如形状和连接器的间距，包括页面上所有形状之间的间距、页面上所有连接器之间的间距，以及所有连接器的路由样式。

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


包含 Diagram，用于控制页面属性，例如页面宽度、高度和比例。

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


包含控制绘图页面在打印机页面上如何格式化（显示）的元素。

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


包含 Prop 元素的集合。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


包含指定页面标尺和网格设置的元素。

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


包含一组 Scratch 元素。

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


包含 SmartTagDef 元素的集合。

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet 元素，PageSheet 从中继承文本格式。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


元素的 GUID（全局唯一标识符）。

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


包含一组 User 元素。

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


包含指定形状一般位置信息的元素。

**Returns:**
[XForm](../../com.aspose.diagram/xform)
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


有关此属性的描述，请参阅 [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

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

