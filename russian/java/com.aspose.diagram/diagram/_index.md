---
title: Диаграмма
second_title: Справочник API Aspose.Diagram for Java
description: Корневой элемент иерархии объектов Visio.
type: docs
weight: 117
url: /ru/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Корневой элемент иерархии объектов Visio.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Публичный конструктор класса, загружает диаграмму из файла. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Публичный конструктор класса, загружает диаграмму из потока. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Публичный конструктор класса, загружает диаграмму из потока, используя предопределённый формат. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Публичный конструктор класса, загружает диаграмму из потока, используя предопределённые параметры загрузки файла. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Публичный конструктор класса, загружает диаграмму из файла, используя предопределённый формат. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Публичный конструктор класса, загружает диаграмму из файла, используя предопределённые параметры загрузки файла. |
## Методы

| Метод | Описание |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Добавляет мастер в диаграмму из исходной диаграммы по имени мастера или NameU. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Добавляет мастер в диаграмму из потока шаблона по ID мастера. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Добавляет мастер в диаграмму из потока шаблона по имени мастера или NameU. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Добавляет мастер в диаграмму из файла шаблона по ID мастера. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Добавляет мастер в диаграмму из файла шаблона по имени мастера или NameU. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Добавляет фигуру, созданную мастером, на определённую страницу. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Добавляет фигуру, созданную мастером, на страницу с определёнными PinX, PinY, Width и Height. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Добавляет фигуру, созданную мастером, на страницу с определёнными PinX и PinY. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Объединяет другой объект Diagram. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Копирует Theme из исходной Diagram. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Экспортирует диаграмму из потока vsd в формат потока vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Экспортирует диаграмму из потока vsd в файловый формат *.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Экспортирует диаграмму из файла vsd в формат потока vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Экспортирует диаграмму из vsd в формат vdw. |
| [getActivePage()](#getActivePage--) | Указывает активную страницу |
| [getBuildnum()](#getBuildnum--) | Номер сборки экземпляра Visio, используемого для создания документа. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Содержит таблицу цветов документа. |
| [getDataConnections()](#getDataConnections--) | Содержит элементы DataConnection для документа. |
| [getDataRecordSets()](#getDataRecordSets--) | Коллекция объектов DataRecordset, связанных с объектом Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Получить путь к папке шрифтов по умолчанию |
| [getDocLangID()](#getDocLangID--) | Уникальный идентификатор языка пользовательского интерфейса, указанный пользователем в настройках языка Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | Содержит элементы свойств документа, такие как название документа, автор и т.д. |
| [getDocumentSettings()](#getDocumentSettings--) | Содержит элементы, задающие настройки документа. |
| [getDocumentSheet()](#getDocumentSheet--) | Указывает структуру ShapeSheet документа. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Содержит MIME (Multipurpose Internet Mail Extensions), закодированный MAPI e-mail routing slip для документа. |
| [getEventItems()](#getEventItems--) | Содержит элемент EventItem для каждого события, на которое объект должен реагировать. |
| [getFonts()](#getFonts--) | Содержит коллекцию элементов Font |
| [getHeaderFooter()](#getHeaderFooter--) | Содержит элементы заголовка и нижнего колонтитула документа. |
| [getInterruptMonitor()](#getInterruptMonitor--) | монитор прерываний. |
| [getKey()](#getKey--) | Указывает, был ли документ изменён вне Visio. |
| [getMasters()](#getMasters--) | Коллекция объектов Master. |
| [getMetric()](#getMetric--) | Использовать ли метрические единицы в чертеже. |
| [getPages()](#getPages--) | Коллекция объектов Page. |
| [getRibbonX()](#getRibbonX--) | Строка Ribbon XML, передаваемая документу для настройки пользовательского интерфейса ленты. |
| [getSolutionXMLs()](#getSolutionXMLs--) | Значение XML. |
| [getStart()](#getStart--) | Указывает, был ли документ изменён вне Visio. |
| [getStyleSheets()](#getStyleSheets--) | Коллекция объектов StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | Получить неиспользуемые стили |
| [getUserCustomUI()](#getUserCustomUI--) | Строка Ribbon XML, передаваемая документу для настройки панели быстрого доступа или ленты. |
| [getValidation()](#getValidation--) | Сохраняет информацию о проверке диаграммы для документа. |
| [getVbProjectData()](#getVbProjectData--) | Содержит данные проекта Microsoft Visual Basic for Applications в формате, закодированном MIME (Multipurpose Internet Mail Extensions). |
| [getVbaProject()](#getVbaProject--) | Получает VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Номер версии экземпляра Visio. |
| [getWindows()](#getWindows--) | Содержит элементы Window для документа. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Указывает, содержит ли эта диаграмма скрытую информацию. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Размещает фигуры и/или перенаправляет соединители для всех страниц диаграммы. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Печатает весь документ на указанный принтер, используя стандартный (без пользовательского интерфейса) контроллер печати. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Печатает весь документ на указанный принтер, используя стандартный (без пользовательского интерфейса) контроллер печати. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Печатает документ, используя стандартный (без пользовательского интерфейса) контроллер печати и имя документа. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Печатает документ, используя стандартный (без пользовательского интерфейса) контроллер печати и имя документа. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Удалить неиспользуемую информацию |
| [removeMacro()](#removeMacro--) | Удаляет VBA/макрос из этой диаграммы. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Сохранить диаграмму в поток. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Сохранить диаграмму в поток. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Сохраняет документ в файл, используя указанные параметры сохранения. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Сохраняет данные диаграммы в файл. |
| [setBuildnum(long value)](#setBuildnum-long-) | Для описания этого свойства см. [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Для описания этого свойства см. [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Для описания этого свойства см. [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Указывает путь к папке Fonts |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Для описания этого свойства см. [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Для описания этого свойства см. [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Для описания этого свойства см. [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Для описания этого свойства см. [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Для описания этого свойства см. [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Для описания этого свойства см. [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Для описания этого свойства см. [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Для описания этого свойства см. [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
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


Публичный конструктор класса, загружает диаграмму из файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Публичный конструктор класса, загружает диаграмму из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Публичный конструктор класса, загружает диаграмму из потока, используя предопределённый формат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных. |
| формат | int | Данные Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Публичный конструктор класса, загружает диаграмму из потока, используя предопределённые параметры загрузки файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Данные [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Публичный конструктор класса, загружает диаграмму из файла, используя предопределённый формат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |
| формат | int | Формат файла. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Публичный конструктор класса, загружает диаграмму из файла, используя предопределённые параметры загрузки файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Данные [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Добавляет мастер в диаграмму из исходной диаграммы по имени мастера или NameU.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | Исходная диаграмма. |
| masterName | java.lang.String | Имя мастера или NameU. |

**Returns:**
int — Уникальный идентификатор мастера в коллекции мастеров в этой диаграмме.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Добавляет мастер в диаграмму из потока шаблона по ID мастера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templateStream | java.io.InputStream | Поток шаблона. |
| masterID | int | Уникальный идентификатор мастера в коллекции мастеров в шаблоне. |

**Returns:**
int — Уникальный идентификатор мастера в коллекции мастеров в этой диаграмме.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Добавляет мастер в диаграмму из потока шаблона по имени мастера или NameU.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templateStream | java.io.InputStream | Поток шаблона. |
| masterName | java.lang.String | Имя мастера или NameU. |

**Returns:**
int — Уникальный идентификатор мастера в коллекции мастеров в этой диаграмме.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Добавляет мастер в диаграмму из файла шаблона по ID мастера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templateFilePath | java.lang.String | Путь к файлу шаблона (может быть в формате vdx, vst или vsd). |
| masterID | int | Уникальный идентификатор мастера в коллекции мастеров в шаблоне. |

**Returns:**
int — Уникальный идентификатор мастера в коллекции мастеров в этой диаграмме.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Добавляет мастер в диаграмму из файла шаблона по имени мастера или NameU.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templateFilePath | java.lang.String | Путь к файлу шаблона (может быть в формате vdx, vst или vsd). |
| masterName | java.lang.String | Имя мастера или NameU. |

**Returns:**
int — Уникальный идентификатор мастера в коллекции мастеров в этой диаграмме.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Добавляет фигуру, созданную мастером, на определённую страницу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Новый объект фигуры[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Имя мастера. |
| pageNumber | int | Индекс страницы. |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Добавляет фигуру, созданную мастером, на страницу с определёнными PinX, PinY, Width и Height.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| width | double | Указывает ширину фигуры в дюймах. |
| height | double | Указывает высоту фигуры в дюймах. |
| masterName | java.lang.String | Имя мастера. |
| pageNumber | int | Индекс страницы. |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Добавляет фигуру, созданную мастером, на страницу с определёнными PinX и PinY.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| masterName | java.lang.String | Имя мастера. |
| pageNumber | int | Индекс страницы. |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Объединяет другой объект Diagram.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Другой объект Diagram. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Копирует Theme из исходной Diagram.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | Исходная диаграмма. |

### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Экспортирует диаграмму из потока vsd в формат потока vdw. Пока не реализовано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputVsd | java.io.InputStream | поток vsd. |
| outputVdw | java.io.InputStream | поток vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Экспортирует диаграмму из потока vsd в формат файла \*.vdw. Пока не реализовано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputVsd | java.io.InputStream | Имя файла \*.vsd. |
| outputVdw | java.lang.String | поток vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Экспортирует диаграмму из файла vsd в формат потока vdw. Пока не реализовано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputVsd | java.lang.String | Имя файла \*.vsd. |
| outputVdw | java.io.InputStream | поток vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Экспортирует диаграмму из vsd в формат vdw. Пока не реализовано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputVsd | java.lang.String | Имя файла \*.vsd. |
| outputVdw | java.lang.String | Имя файла \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Указывает активную страницу

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Номер сборки экземпляра Visio, используемого для создания документа.

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


Содержит таблицу цветов документа. Каждый документ содержит одну таблицу цветов, в которой перечислены 24 стандартных цвета, доступные для применения к объектам, таким как фигуры, текст и слои в документе.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Содержит элементы DataConnection для документа.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Коллекция объектов DataRecordset, связанных с объектом Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Получить путь к папке шрифтов по умолчанию

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


Уникальный идентификатор языка пользовательского интерфейса, указанный пользователем в настройках языка Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Содержит элементы свойств документа, такие как название документа, автор и т.д.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Содержит элементы, задающие настройки документа.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Указывает структуру ShapeSheet документа.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Содержит MIME (Multipurpose Internet Mail Extensions), закодированный MAPI e-mail routing slip для документа.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Содержит элемент EventItem для каждого события, на которое объект должен реагировать.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Содержит коллекцию элементов Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Содержит элементы заголовка и нижнего колонтитула документа.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


монитор прерываний.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Указывает, был ли документ изменён вне Visio. Если присутствует, Visio полностью проверит содержимое файла. Опускайте для файлов, созданных вне Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Коллекция объектов Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Определяет, использовать ли метрические единицы в чертеже. Установите этот атрибут в True (1), чтобы использовать метрические единицы; установите его в False (0), чтобы использовать английские единицы.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Коллекция объектов Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


Строка Ribbon XML, передаваемая документу для настройки пользовательского интерфейса ленты.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


Значение XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Указывает, был ли документ изменён вне Visio. Если присутствует, Visio полностью проверит содержимое файла. Опускайте для файлов, созданных вне Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Коллекция объектов StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Получить неиспользуемые стили

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


Строка Ribbon XML, передаваемая документу для настройки панели быстрого доступа или ленты.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Сохраняет информацию о проверке диаграммы для документа.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Содержит данные проекта Microsoft Visual Basic for Applications в формате, закодированном MIME (Multipurpose Internet Mail Extensions).

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Получает VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Номер версии экземпляра Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Содержит элементы Window для документа.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Указывает, содержит ли эта диаграмма скрытую информацию.

**Returns:**
boolean
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


Размещает фигуры и/или перенаправляет соединители для всех страниц диаграммы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Использование [LayoutOptions](../../com.aspose.diagram/layoutoptions) для настройки параметров макета. |

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


Печатает весь документ на указанном принтере, используя стандартный (без пользовательского интерфейса) контроллер печати. Если printerName равен Null или пуст, будет использован принтер по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| printerName | java.lang.String | Имя принтера. Может быть Null |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Печатает весь документ на указанном принтере, используя стандартный (без пользовательского интерфейса) контроллер печати. Если printerName равен Null или пуст, будет использован принтер по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| printerName | java.lang.String | Имя принтера. Может быть Null |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Параметры печати. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Печатает документ, используя стандартный (без пользовательского интерфейса) контроллер печати и имя документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| printerName | java.lang.String | Имя принтера. Может быть Null |
| documentName | java.lang.String | Имя документа для отображения (например, в диалоговом окне статуса печати или в очереди принтера) во время печати документа. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Печатает документ, используя стандартный (без пользовательского интерфейса) контроллер печати и имя документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| printerName | java.lang.String | Имя принтера. Может быть Null |
| documentName | java.lang.String | Имя документа для отображения (например, в диалоговом окне статуса печати или в очереди принтера) во время печати документа. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Параметры печати. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Удалить неиспользуемую информацию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Удаляет VBA/макрос из этой диаграммы.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Сохранить диаграмму в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток файла. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | Параметры сохранения. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Сохранить диаграмму в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток файла. |
| формат | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Сохраняет документ в файл, используя указанные параметры сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) параметры сохранения диаграммы. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Сохраняет данные диаграммы в файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | java.lang.String | Имя файла. |
| формат | int | Aspose.Diagram.SaveFileFormat формат сохранения файла. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Для описания этого свойства см. [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Для описания этого свойства см. [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Для описания этого свойства см. [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Указывает путь к папке Fonts

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Для описания этого свойства см. [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Для описания этого свойства см. [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Для описания этого свойства см. [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Для описания этого свойства см. [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Для описания этого свойства см. [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Для описания этого свойства см. [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Для описания этого свойства см. [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Для описания этого свойства см. [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

