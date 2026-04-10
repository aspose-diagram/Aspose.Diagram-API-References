---
title: DocumentProperties
second_title: Aspose.Diagram for Java API 参考
description: 包含文档属性元素，例如文档标题、作者等。
type: docs
weight: 125
url: /zh/java/com.aspose.diagram/documentproperties/
---

**Inheritance:**
java.lang.Object
```
public class DocumentProperties
```

包含文档属性元素，例如文档的标题、作者等。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlternateNames()](#getAlternateNames--) | 指定文档的别名。 |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | 包含用于创建文档的实例的完整生成号。 |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | 包含上次用于编辑文档的实例的生成号。 |
| [getCategory()](#getCategory--) | 指定绘图类型的描述性文本，例如流程图或办公布局。 |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | 包含用户输入的信息，用于标识创建绘图的公司或绘图所针对的公司。 |
| [getCreator()](#getCreator--) | 标识创建或最后更新文件的人员。 |
| [getCustomProps()](#getCustomProps--) | CustomProp 的集合。 |
| [getDesc()](#getDesc--) | 包含文档的描述性文本字符串。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | 包含用于相对超链接的路径（相对超链接是指链接的文件位置相对于 Microsoft Visio 图表进行描述的超链接）。 |
| [getKeywords()](#getKeywords--) | 包含标识文件主题或其他重要信息的文本字符串，例如项目名称、客户名称或版本号。 |
| [getLanguage()](#getLanguage--) | 指定语言 |
| [getManager()](#getManager--) | 包含用户输入的文本字符串，用于标识项目或部门的负责人。 |
| [getPreviewPicture()](#getPreviewPicture--) | 包含作为文档预览的元文件流。 |
| [getSubject()](#getSubject--) | 包含用户自定义的文本字符串，用于描述文档的内容。 |
| [getTemplate()](#getTemplate--) | 包含指定创建文档的模板文件名的字符串值。 |
| [getTimeCreated()](#getTimeCreated--) | 包含指示文档创建时间的日期和时间值。 |
| [getTimeEdited()](#getTimeEdited--) | 包含指示文档上次编辑时间的日期和时间值。 |
| [getTimePrinted()](#getTimePrinted--) | 包含指示文档上次打印时间的日期和时间值。 |
| [getTimeSaved()](#getTimeSaved--) | 包含指示文档上次保存时间的日期和时间值。 |
| [getTitle()](#getTitle--) | 包含用户自定义的文本字符串，作为文档的描述性标题。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | 有关此属性的描述，请参阅 [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--) |
| [setBuildNumberCreated(String value)](#setBuildNumberCreated-java.lang.String-) | 有关此属性的描述，请参阅 [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--) |
| [setBuildNumberEdited(String value)](#setBuildNumberEdited-java.lang.String-) | 有关此属性的描述，请参阅 [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--) |
| [setCategory(String value)](#setCategory-java.lang.String-) | 有关此属性的描述，请参阅 [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--) |
| [setCompany(String value)](#setCompany-java.lang.String-) | 有关此属性的描述，请参阅 [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--) |
| [setCreator(String value)](#setCreator-java.lang.String-) | 有关此属性的描述，请参阅 [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--) |
| [setDesc(String value)](#setDesc-java.lang.String-) | 有关此属性的描述，请参阅 [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--) |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | 有关此属性的描述，请参阅 [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--) |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 有关此属性的描述，请参阅 [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--) |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | 有关此属性的描述，请参阅 [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--) |
| [setManager(String value)](#setManager-java.lang.String-) | 有关此属性的描述，请参阅 [getManager()](../../com.aspose.diagram/documentproperties\#getManager--) |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | 有关此属性的描述，请参阅 [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--) |
| [setSubject(String value)](#setSubject-java.lang.String-) | 有关此属性的描述，请参阅 [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--) |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | 有关此属性的描述，请参阅 [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--) |
| [setTimeCreated(DateTime value)](#setTimeCreated-com.aspose.diagram.DateTime-) | 有关此属性的描述，请参阅 [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--) |
| [setTimeEdited(DateTime value)](#setTimeEdited-com.aspose.diagram.DateTime-) | 有关此属性的描述，请参阅 [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--) |
| [setTimePrinted(DateTime value)](#setTimePrinted-com.aspose.diagram.DateTime-) | 有关此属性的描述，请参阅 [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--) |
| [setTimeSaved(DateTime value)](#setTimeSaved-com.aspose.diagram.DateTime-) | 有关此属性的描述，请参阅 [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | 有关此属性的描述，请参阅 [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--) |
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
### getAlternateNames() {#getAlternateNames--}
```
public String getAlternateNames()
```


指定文档的别名。

**Returns:**
java.lang.String
### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public String getBuildNumberCreated()
```


包含用于创建文档的实例的完整生成号。

**Returns:**
java.lang.String
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public String getBuildNumberEdited()
```


包含上次用于编辑文档的实例的生成号。

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public String getCategory()
```


指定绘图类型的描述性文本，例如流程图或办公布局。此文本也可以在 Microsoft Visio 用户界面的属性对话框的“类别”框中输入。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public String getCompany()
```


包含用户输入的信息，用于标识创建绘图的公司或绘图所针对的公司。最大长度为 63 个字符。

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


标识创建或最后更新文件的人员。最大长度为 63 个字符。

**Returns:**
java.lang.String
### getCustomProps() {#getCustomProps--}
```
public CustomPropCollection getCustomProps()
```


CustomProp 的集合。

**Returns:**
[CustomPropCollection](../../com.aspose.diagram/custompropcollection)
### getDesc() {#getDesc--}
```
public String getDesc()
```


包含文档的描述性文本字符串。使用此元素存储有关文档的重要信息，例如其用途、最近的更改或待处理的更改。最大长度为 191 个字符。

**Returns:**
java.lang.String
### getHyperlinkBase() {#getHyperlinkBase--}
```
public String getHyperlinkBase()
```


包含用于相对超链接的路径（相对超链接是指其链接文件位置相对于 Microsoft Visio 图表进行描述的超链接）。默认情况下，超链接路径相对于当前文档，除非在此元素中指定了其他路径。最大长度为 256 个字符。

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


包含用于标识文件主题或其他重要信息的文本字符串，例如项目名称、客户名称或版本号。最大字符串长度为 63 个字符。

**Returns:**
java.lang.String
### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


指定语言

```
setLanguage("en-GB");
         setLanguage("en-US");
```

**Returns:**
java.lang.String
### getManager() {#getManager--}
```
public String getManager()
```


包含用户输入的文本字符串，用于标识项目或部门负责人。最大长度为 63 个字符。

**Returns:**
java.lang.String
### getPreviewPicture() {#getPreviewPicture--}
```
public byte[] getPreviewPicture()
```


包含作为文档预览的元文件流。

**Returns:**
byte[]
### getSubject() {#getSubject--}
```
public String getSubject()
```


包含用户自定义的文本字符串，描述文档的内容。最大长度为 63 个字符。

**Returns:**
java.lang.String
### getTemplate() {#getTemplate--}
```
public String getTemplate()
```


包含指定创建文档的模板文件名的字符串值。

**Returns:**
java.lang.String
### getTimeCreated() {#getTimeCreated--}
```
public DateTime getTimeCreated()
```


包含指示文档创建时间的日期和时间值。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeEdited() {#getTimeEdited--}
```
public DateTime getTimeEdited()
```


包含指示文档上次编辑时间的日期和时间值。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePrinted() {#getTimePrinted--}
```
public DateTime getTimePrinted()
```


包含指示文档上次打印时间的日期和时间值。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeSaved() {#getTimeSaved--}
```
public DateTime getTimeSaved()
```


包含指示文档上次保存时间的日期和时间值。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTitle() {#getTitle--}
```
public String getTitle()
```


包含用户自定义的文本字符串，作为文档的描述性标题。最大长度为 63 个字符。

**Returns:**
java.lang.String
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




### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public void setAlternateNames(String value)
```


有关此属性的描述，请参阅 [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setBuildNumberCreated(String value) {#setBuildNumberCreated-java.lang.String-}
```
public void setBuildNumberCreated(String value)
```


有关此属性的描述，请参阅 [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setBuildNumberEdited(String value) {#setBuildNumberEdited-java.lang.String-}
```
public void setBuildNumberEdited(String value)
```


有关此属性的描述，请参阅 [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


有关此属性的描述，请参阅 [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public void setCompany(String value)
```


有关此属性的描述，请参阅 [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


有关此属性的描述，请参阅 [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDesc(String value) {#setDesc-java.lang.String-}
```
public void setDesc(String value)
```


有关此属性的描述，请参阅 [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public void setHyperlinkBase(String value)
```


有关此属性的描述，请参阅 [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


有关此属性的描述，请参阅 [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


有关此属性的描述，请参阅 [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setManager(String value) {#setManager-java.lang.String-}
```
public void setManager(String value)
```


有关此属性的描述，请参阅 [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public void setPreviewPicture(byte[] value)
```


有关此属性的描述，请参阅 [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


有关此属性的描述，请参阅 [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public void setTemplate(String value)
```


有关此属性的描述，请参阅 [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setTimeCreated(DateTime value) {#setTimeCreated-com.aspose.diagram.DateTime-}
```
public void setTimeCreated(DateTime value)
```


有关此属性的描述，请参阅 [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeEdited(DateTime value) {#setTimeEdited-com.aspose.diagram.DateTime-}
```
public void setTimeEdited(DateTime value)
```


有关此属性的描述，请参阅 [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePrinted(DateTime value) {#setTimePrinted-com.aspose.diagram.DateTime-}
```
public void setTimePrinted(DateTime value)
```


有关此属性的描述，请参阅 [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeSaved(DateTime value) {#setTimeSaved-com.aspose.diagram.DateTime-}
```
public void setTimeSaved(DateTime value)
```


有关此属性的描述，请参阅 [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


有关此属性的描述，请参阅 [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

