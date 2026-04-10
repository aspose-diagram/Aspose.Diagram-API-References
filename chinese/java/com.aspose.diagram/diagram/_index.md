---
title: 图表
second_title: Aspose.Diagram for Java API 参考
description: Visio 对象层次结构的根元素。
type: docs
weight: 117
url: /zh/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Visio 对象层次结构的根元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | 公共类构造函数，从文件加载图表。 |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | 公共类构造函数，从流加载图表。 |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | 公共类构造函数，使用预定义格式从流加载图表。 |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | 公共类构造函数，使用预定义的加载文件选项从流加载图表。 |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | 公共类构造函数，使用预定义格式从文件加载图表。 |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | 公共类构造函数，使用预定义的加载文件选项从文件加载图表。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | 通过主对象的 Name 或 NameU，将母版从源图表添加到图表中。 |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | 通过主对象的 ID，将母版从模板流添加到图表中。 |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | 通过主对象的 Name 或 NameU，将母版从模板流添加到图表中。 |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | 通过主对象的 ID，将母版从模板文件添加到图表中。 |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | 通过主对象的 Name 或 NameU，将母版从模板文件添加到图表中。 |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | 将由母版创建的形状添加到指定页面。 |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | 在页面上将由母版创建的形状添加，使用定义的 PinX、PinY、宽度和高度。 |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | 在页面上将由母版创建的形状添加，使用定义的 PinX 和 PinY。 |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | 合并另一个图表对象。 |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | 从源图表复制主题。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，涉及释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | 将图表从 VSD 流导出为 VDW 流格式。 |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | 将图表从 VSD 流导出为 *.vdw 文件格式。 |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | 将图表从 VSD 文件导出为 VDW 流格式。 |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | 将图表从 VSD 导出为 VDW 格式。 |
| [getActivePage()](#getActivePage--) | 指定活动页面 |
| [getBuildnum()](#getBuildnum--) | 用于创建文档的 Visio 实例的生成号。 |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | 包含文档的颜色表。 |
| [getDataConnections()](#getDataConnections--) | 包含文档的 DataConnection 元素。 |
| [getDataRecordSets()](#getDataRecordSets--) | 与 Document 对象关联的 DataRecordset 对象集合。 |
| [getDefaultFontDir()](#getDefaultFontDir--) | 获取默认字体文件夹路径 |
| [getDocLangID()](#getDocLangID--) | 用户在 Microsoft Office 2010 语言首选项中指定的用户界面语言的唯一 ID。 |
| [getDocumentProps()](#getDocumentProps--) | 包含文档属性元素，例如文档的标题、作者等。 |
| [getDocumentSettings()](#getDocumentSettings--) | 包含指定文档设置的元素。 |
| [getDocumentSheet()](#getDocumentSheet--) | 指定文档的 ShapeSheet 结构。 |
| [getEmailRoutingData()](#getEmailRoutingData--) | 包含文档的 MIME（Multipurpose Internet Mail Extensions） 编码的 MAPI 电子邮件路由单。 |
| [getEventItems()](#getEventItems--) | 为对象应响应的每个事件包含一个 EventItem 元素。 |
| [getFonts()](#getFonts--) | 包含 Font 元素的集合。 |
| [getHeaderFooter()](#getHeaderFooter--) | 包含文档页眉和页脚的元素。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 中断监视器。 |
| [getKey()](#getKey--) | 指示文档是否在 Visio 之外被修改。 |
| [getMasters()](#getMasters--) | Master 对象的集合。 |
| [getMetric()](#getMetric--) | 是否在绘图中使用公制单位。 |
| [getPages()](#getPages--) | Page 对象的集合。 |
| [getRibbonX()](#getRibbonX--) | 传递给文档以自定义功能区用户界面的 Ribbon XML 字符串。 |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML 值。 |
| [getStart()](#getStart--) | 指示文档是否在 Visio 之外被修改。 |
| [getStyleSheets()](#getStyleSheets--) | StyleSheet 对象的集合。 |
| [getUnusedStyles()](#getUnusedStyles--) | 获取未使用的样式。 |
| [getUserCustomUI()](#getUserCustomUI--) | 传递给文档以自定义快速访问工具栏或功能区的 Ribbon XML 字符串。 |
| [getValidation()](#getValidation--) | 存储有关文档图表验证的信息。 |
| [getVbProjectData()](#getVbProjectData--) | 包含 Microsoft Visual Basic for Applications 项目数据，采用 MIME（Multipurpose Internet Mail Extensions） 编码格式。 |
| [getVbaProject()](#getVbaProject--) | 获取 VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--)。 |
| [getVersion()](#getVersion--) | Visio 实例的版本号。 |
| [getWindows()](#getWindows--) | 包含文档的 Window 元素。 |
| [hasHiddenInfo()](#hasHiddenInfo--) | 指示此图表是否包含隐藏信息。 |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | 为图表的所有页面布局形状和/或重新路由连接器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | 将整个文档打印到指定的打印机，使用标准（无用户界面）打印控制器。 |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | 将整个文档打印到指定的打印机，使用标准（无用户界面）打印控制器。 |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | 打印文档，使用标准（无用户界面）打印控制器和文档名称。 |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | 打印文档，使用标准（无用户界面）打印控制器和文档名称。 |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | 删除未使用的信息。 |
| [removeMacro()](#removeMacro--) | 从此图表中移除 VBA/macro。 |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | 将图表保存到流中。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将图表保存到流中。 |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | 使用指定的保存选项将文档保存到文件。 |
| [save(String filename, int format)](#save-java.lang.String-int-) | 将图表数据保存到文件。 |
| [setBuildnum(long value)](#setBuildnum-long-) | 有关此属性的描述，请参阅 [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | 有关此属性的描述，请参阅 [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | 有关此属性的描述，请参阅 [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | 指示 Fonts 文件夹路径 |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | 有关此属性的描述，请参阅 [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | 有关此属性的描述，请参阅 [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | 有关此属性的描述，请参阅 [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | 有关此属性的描述，请参阅 [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | 有关此属性的描述，请参阅 [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | 有关此属性的描述，请参阅 [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | 有关此属性的描述，请参阅 [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | 有关此属性的描述，请参阅 [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


公共类构造函数，从文件加载图表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


公共类构造函数，从流加载图表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 数据流。 |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


公共类构造函数，使用预定义格式从流加载图表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 数据流。 |
| 格式 | int | 数据 Aspose.Diagram.LoadFileFormat。 |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


公共类构造函数，使用预定义的加载文件选项从流加载图表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 数据流。 |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | 数据 [LoadOptions](../../com.aspose.diagram/loadoptions)。 |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


公共类构造函数，使用预定义格式从文件加载图表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| 格式 | int | 文件格式。 |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


公共类构造函数，使用预定义的加载文件选项从文件加载图表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | 数据 [LoadOptions](../../com.aspose.diagram/loadoptions)。 |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


通过主对象的 Name 或 NameU，将母版从源图表添加到图表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | 源图表。 |
| masterName | java.lang.String | Master 的 Name 或 NameU。 |

**Returns:**
int - 此图表中 masters 集合内 master 的唯一 ID。
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


通过主对象的 ID，将母版从模板流添加到图表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templateStream | java.io.InputStream | 模板流。 |
| masterID | int | 模板中 masters 集合内 master 的唯一 ID。 |

**Returns:**
int - 此图表中 masters 集合内 master 的唯一 ID。
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


通过主对象的 Name 或 NameU，将母版从模板流添加到图表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templateStream | java.io.InputStream | 模板流。 |
| masterName | java.lang.String | Master 的 Name 或 NameU。 |

**Returns:**
int - 此图表中 masters 集合内 master 的唯一 ID。
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


通过主对象的 ID，将母版从模板文件添加到图表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templateFilePath | java.lang.String | 模板文件的路径（可为 vdx、vst 或 vsd 格式）。 |
| masterID | int | 模板中 masters 集合内 master 的唯一 ID。 |

**Returns:**
int - 此图表中 masters 集合内 master 的唯一 ID。
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


通过主对象的 Name 或 NameU，将母版从模板文件添加到图表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| templateFilePath | java.lang.String | 模板文件的路径（可为 vdx、vst 或 vsd 格式）。 |
| masterName | java.lang.String | Master 的 Name 或 NameU。 |

**Returns:**
int - 此图表中 masters 集合内 master 的唯一 ID。
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


将由母版创建的形状添加到指定页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | 新的形状对象[Shape](../../com.aspose.diagram/shape)。 |
| masterName | java.lang.String | 母版的名称。 |
| pageNumber | int | 页面的索引。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


在页面上将由母版创建的形状添加，使用定义的 PinX、PinY、宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度（英寸）。 |
| height | double | 指定形状的高度（英寸）。 |
| masterName | java.lang.String | 母版的名称。 |
| pageNumber | int | 页面的索引。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


在页面上将由母版创建的形状添加，使用定义的 PinX 和 PinY。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| masterName | java.lang.String | 母版的名称。 |
| pageNumber | int | 页面的索引。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


合并另一个图表对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | 另一个 Diagram 对象。 |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


从源图表复制主题。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | 源图表。 |

### dispose() {#dispose--}
```
public void dispose()
```


执行应用程序定义的任务，涉及释放、释放或重置非托管资源。

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


将图表从 vsd 流导出为 vdw 流格式。尚未实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd 流。 |
| outputVdw | java.io.InputStream | vdw 流。 |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


将图表从 vsd 流导出为 \\*.vdw 文件格式。尚未实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \\*.vsd 文件名。 |
| outputVdw | java.lang.String | vdw 流。 |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


将图表从 vsd 文件导出为 vdw 流格式。尚未实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputVsd | java.lang.String | \\*.vsd 文件名。 |
| outputVdw | java.io.InputStream | vdw 流。 |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


将图表从 vsd 导出为 vdw 格式。尚未实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputVsd | java.lang.String | \\*.vsd 文件名。 |
| outputVdw | java.lang.String | \\*.vdw 文件名。 |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


指定活动页面

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


用于创建文档的 Visio 实例的生成号。

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


包含文档的颜色表。每个文档包含一个颜色表，列出 24 种标准颜色，可用于文档中形状、文本和图层等对象。

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


包含文档的 DataConnection 元素。

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


与 Document 对象关联的 DataRecordset 对象集合。

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


获取默认字体文件夹路径

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


用户在 Microsoft Office 2010 语言首选项中指定的用户界面语言的唯一 ID。

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


包含文档属性元素，例如文档的标题、作者等。

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


包含指定文档设置的元素。

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


指定文档的 ShapeSheet 结构。

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


包含文档的 MIME（Multipurpose Internet Mail Extensions） 编码的 MAPI 电子邮件路由单。

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


为对象应响应的每个事件包含一个 EventItem 元素。

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


包含 Font 元素的集合。

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


包含文档页眉和页脚的元素。

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


中断监视器。

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


指示文档是否在 Visio 之外被修改。如果存在，Visio 将完整测试文件内容。对于在 Visio 之外创建的文件请省略此项。

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Master 对象的集合。

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


是否在绘图中使用公制单位。将此属性设为 True（1）以使用公制单位；设为 False（0）以使用英制单位。

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Page 对象的集合。

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


传递给文档以自定义功能区用户界面的 Ribbon XML 字符串。

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML 值。

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


指示文档是否在 Visio 之外被修改。如果存在，Visio 将完整测试文件内容。对于在 Visio 之外创建的文件请省略此项。

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


StyleSheet 对象的集合。

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


获取未使用的样式。

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


传递给文档以自定义快速访问工具栏或功能区的 Ribbon XML 字符串。

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


存储有关文档图表验证的信息。

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


包含 Microsoft Visual Basic for Applications 项目数据，采用 MIME（Multipurpose Internet Mail Extensions） 编码格式。

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


获取 VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--)。

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Visio 实例的版本号。Microsoft Visio 2010 = 14。

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


包含文档的 Window 元素。

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


指示此图表是否包含隐藏信息。

**Returns:**
布尔
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


为图表的所有页面布局形状和/或重新路由连接器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | 使用 [LayoutOptions](../../com.aspose.diagram/layoutoptions) 配置布局选项。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


将整个文档打印到指定的打印机，使用标准（无用户界面）打印控制器。如果 printerName 为 Null 或为空，将使用默认打印机。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerName | java.lang.String | 打印机的名称。可以为 Null。 |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


将整个文档打印到指定的打印机，使用标准（无用户界面）打印控制器。如果 printerName 为 Null 或为空，将使用默认打印机。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerName | java.lang.String | 打印机的名称。可以为 Null。 |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | 打印选项。 |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


打印文档，使用标准（无用户界面）打印控制器和文档名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerName | java.lang.String | 打印机的名称。可以为 Null。 |
| documentName | java.lang.String | 打印文档时显示的文档名称（例如，在打印状态对话框或打印队列中）。 |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


打印文档，使用标准（无用户界面）打印控制器和文档名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| printerName | java.lang.String | 打印机的名称。可以为 Null。 |
| documentName | java.lang.String | 打印文档时显示的文档名称（例如，在打印状态对话框或打印队列中）。 |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | 打印选项。 |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


删除未使用的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | int | 删除隐藏信息项。 |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


从此图表中移除 VBA/macro。

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


将图表保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 文件流。 |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | 保存选项。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


将图表保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 文件流。 |
| 格式 | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


使用指定的保存选项将文档保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) 保存图表选项。 |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


将图表数据保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 文件名。 |
| 格式 | int | Aspose.Diagram.SaveFileFormat 保存文件格式。 |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


有关此属性的描述，请参阅 [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


有关此属性的描述，请参阅 [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


有关此属性的描述，请参阅 [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


指示 Fonts 文件夹路径

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


有关此属性的描述，请参阅 [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


有关此属性的描述，请参阅 [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


有关此属性的描述，请参阅 [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


有关此属性的描述，请参阅 [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


有关此属性的描述，请参阅 [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


有关此属性的描述，请参阅 [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


有关此属性的描述，请参阅 [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


有关此属性的描述，请参阅 [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

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

