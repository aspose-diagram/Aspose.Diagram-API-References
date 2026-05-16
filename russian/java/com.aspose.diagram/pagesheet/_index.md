---
title: PageSheet
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, определяющие лист страницы для элемента Page или Master.
type: docs
weight: 270
url: /ru/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Содержит элементы, определяющие лист страницы для элемента Page или Master.
## Методы

| Метод | Описание |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Копирует pagesheet из исходного объекта. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Содержит коллекцию элементов Act. |
| [getAnnotations()](#getAnnotations--) | Содержит элементы, содержащие информацию о комментариях, вставленных на страницу документа. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Содержит коллекцию элементов ConnectionABCD. |
| [getConnections()](#getConnections--) | Содержит коллекцию элементов Connection. |
| [getFillStyle()](#getFillStyle--) | Элемент StyleSheet, из которого PageSheet наследует форматирование заливки. |
| [getForeign()](#getForeign--) | Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE. |
| [getHyperlinks()](#getHyperlinks--) | Содержит коллекцию элементов Hyperlink. |
| [getLayers()](#getLayers--) | Содержит коллекцию элементов Layer. |
| [getLineStyle()](#getLineStyle--) | Элемент StyleSheet, из которого PageSheet наследует форматирование линий. |
| [getPageLayout()](#getPageLayout--) | Содержит Diagram, который управляет настройками разметки страницы для фигур и соединителей, такими как расстояние между всеми фигурами на странице, расстояние между всеми соединителями на странице и стиль маршрутизации для всех соединителей на странице. |
| [getPageProps()](#getPageProps--) | Содержит Diagram, который управляет атрибутами страницы, такими как ширина, высота и масштаб. |
| [getPrintProps()](#getPrintProps--) | Содержит элементы, которые управляют тем, как страница чертежа форматируется (отображается) на странице принтера. |
| [getProps()](#getProps--) | Содержит коллекцию элементов Prop. |
| [getRulerGrid()](#getRulerGrid--) | Содержит элементы, задающие настройки линейки и сетки страницы. |
| [getScratchs()](#getScratchs--) | Содержит коллекцию элементов Scratch. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Содержит коллекцию элементов SmartTagDef. |
| [getTextStyle()](#getTextStyle--) | Элемент StyleSheet, из которого PageSheet наследует форматирование текста. |
| [getUniqueID()](#getUniqueID--) | GUID (глобальный уникальный идентификатор) для элемента. |
| [getUsers()](#getUsers--) | Содержит коллекцию элементов User. |
| [getXForm()](#getXForm--) | Содержит элементы, указывающие общую информацию о позиционировании фигуры. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, смотрите [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, смотрите [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Копирует pagesheet из исходного объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Содержит коллекцию элементов Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Содержит элементы, содержащие информацию о комментариях, вставленных на страницу документа.

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


Содержит коллекцию элементов ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Содержит коллекцию элементов Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Элемент StyleSheet, из которого PageSheet наследует форматирование заливки.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio. Также включает элементы, указывающие расстояние смещения изображения объекта внутри его границ.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Содержит коллекцию элементов Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Содержит коллекцию элементов Layer.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Элемент StyleSheet, из которого PageSheet наследует форматирование линий.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Содержит Diagram, который управляет настройками разметки страницы для фигур и соединителей, такими как расстояние между всеми фигурами на странице, расстояние между всеми соединителями на странице и стиль маршрутизации для всех соединителей на странице.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Содержит Diagram, который управляет атрибутами страницы, такими как ширина, высота и масштаб.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Содержит элементы, которые управляют тем, как страница чертежа форматируется (отображается) на странице принтера.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Содержит коллекцию элементов Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Содержит элементы, задающие настройки линейки и сетки страницы.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Содержит коллекцию элементов Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Содержит коллекцию элементов SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Элемент StyleSheet, из которого PageSheet наследует форматирование текста.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID (глобальный уникальный идентификатор) для элемента.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Содержит коллекцию элементов User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Содержит элементы, указывающие общую информацию о позиционировании фигуры.

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


Для описания этого свойства, пожалуйста, смотрите [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Для описания этого свойства, пожалуйста, смотрите [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

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

