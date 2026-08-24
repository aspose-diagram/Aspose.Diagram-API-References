---
title: Форма
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, определяющие фигуру на главной странице или в элементе группы фигур.
type: docs
weight: 355
url: /ru/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Содержит элементы, определяющие фигуру в Master, Page или элементе группы фигур.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Shape()](#Shape--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [bringForward()](#bringForward--) | Перемещает фигуру вперёд на одну позицию в порядке Z. |
| [bringToFront()](#bringToFront--) | Перемещает фигуру в переднюю часть порядка Z. |
| [centerDrawing()](#centerDrawing--) | Центрировать фигуру относительно размеров страницы. |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Возвращает массив, содержащий идентификаторы (ID) фигур, соединённых с данной фигурой. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Возвращает массив, содержащий идентификаторы фигур, зависящих от фигуры. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Получает элемент управления ActiveX. |
| [getActs()](#getActs--) | Содержит коллекцию элементов Act. |
| [getAlign()](#getAlign--) | Указывает выравнивание фигуры относительно направляющей или точки направляющей, к которой фигура приклеена. |
| [getChars()](#getChars--) | Содержит коллекцию элементов Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Содержит коллекцию элементов ConnectionABCD. |
| [getConnections()](#getConnections--) | Содержит коллекцию элементов Connection. |
| [getConnectorRule()](#getConnectorRule--) | Возвращает connectorRule, содержащий идентификатор фигуры и соединение, которое связано с фигурой. |
| [getConnectorsType()](#getConnectorsType--) | Получить тип соединителей |
| [getControlData()](#getControlData--) | Получает данные элемента управления. |
| [getControls()](#getControls--) | Содержит коллекцию элементов Control. |
| [getData1()](#getData1--) | Содержит произвольное строковое значение, используемое для предоставления дополнительной информации о фигуре. |
| [getData2()](#getData2--) | Содержит произвольное строковое значение, используемое для предоставления дополнительной информации о фигуре. |
| [getData3()](#getData3--) | Содержит произвольное строковое значение, используемое для предоставления дополнительной информации о фигуре. |
| [getDel()](#getDel--) | Флаг, указывающий, удалён ли элемент локально. |
| [getDiagram()](#getDiagram--) | Корневой элемент иерархии объектов Visio. |
| [getDisplayText()](#getDisplayText--) | Получить текст, отображаемый в интерфейсе. |
| [getEvent()](#getEvent--) | Содержит элементы, задающие формулы, управляющие событиями фигур. |
| [getFields()](#getFields--) | Содержит коллекцию элементов Field. |
| [getFill()](#getFill--) | Содержит текущие значения форматирования заливки для фигуры и её тени, включая шаблон, цвет переднего плана и цвет фона. |
| [getFillStyle()](#getFillStyle--) | Таблица стилей, из которой эта фигура наследует параметры заливки. |
| [getForeign()](#getForeign--) | Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE. |
| [getGeoms()](#getGeoms--) | Содержит коллекцию элементов Geom. |
| [getGroup()](#getGroup--) | Содержит элементы, управляющие тем, как добавлять фигуры в группу, перемещать её участников и выбирать группы. |
| [getHelp()](#getHelp--) | Содержит элементы, указывающие тему справочного файла элемента Shape и информацию об авторских правах. |
| [getHyperlinks()](#getHyperlinks--) | Содержит коллекцию элементов Hyperlink. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getImage()](#getImage--) | Содержит значения гаммы, яркости, контраста, размытия, резкости, шумоподавления и прозрачности для растрового изображения. |
| [getInheritChars()](#getInheritChars--) | Содержит символьные значения для фигуры, наследуемые от главной фигуры. |
| [getInheritFill()](#getInheritFill--) | Содержит значения параметров заливки для фигуры, наследуемые от родительского стиля и главной фигуры. |
| [getInheritGeoms()](#getInheritGeoms--) | Содержит значения Geoms для фигуры, наследуемой от главной фигуры. |
| [getInheritLine()](#getInheritLine--) | Содержит значения форматирования линий для фигуры, наследуемой от родительского стиля и главной фигуры. |
| [getInheritParas()](#getInheritParas--) | Содержит paras для фигуры, наследуемой от родительского стиля и главной фигуры. |
| [getInheritProps()](#getInheritProps--) | Содержит props для фигуры, наследуемой от главной фигуры. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Содержит значения textblock для фигуры, наследуемой от родительского стиля и главной фигуры. |
| [getInheritUsers()](#getInheritUsers--) | Содержит пользователей для фигуры, наследуемой от главной фигуры. |
| [getLayerMem()](#getLayerMem--) | Содержит элемент LayerMember, который указывает каждый слой, к которому назначена фигура. |
| [getLayout()](#getLayout--) | Содержит элементы, управляющие размещением фигур и настройками маршрутизации соединителей. |
| [getLine()](#getLine--) | Содержит элементы, управляющие атрибутами линии для фигуры, такими как шаблон, толщина и цвет. |
| [getLineStyle()](#getLineStyle--) | StyleSheet, из которой эта фигура наследует форматирование линий |
| [getMaster()](#getMaster--) | Master, из которого фигура наследует свои данные. |
| [getMasterShape()](#getMasterShape--) | Этот атрибут может присутствовать только в фигурах, которые являются членами групповой фигуры, и группа является экземпляром мастера. |
| [getMisc()](#getMisc--) | Содержит элементы, указывающие тему справочного файла элемента Shape и информацию об авторских правах. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getOneD()](#getOneD--) | Определяет, ведёт ли фигура себя как одно-мерный (1-D) объект. |
| [getPage()](#getPage--) | Корневой элемент иерархии объектов Visio. |
| [getParas()](#getParas--) | Содержит коллекцию элементов Para. |
| [getParentShape()](#getParentShape--) | Родитель фигуры. |
| [getProps()](#getProps--) | Содержит коллекцию элементов Prop. |
| [getProtection()](#getProtection--) | Блокировка помогает предотвратить непреднамеренные изменения фигуры, но не препятствует Microsoft Visio сбрасывать значения в других обстоятельствах. |
| [getPureText()](#getPureText--) | Получить строку текста |
| [getRootShape()](#getRootShape--) | Возвращает фигуру верхнего уровня экземпляра, если эта фигура является частью экземпляра мастера. |
| [getScratchs()](#getScratchs--) | Содержит коллекцию элементов Scratch. |
| [getShapes()](#getShapes--) | Содержит коллекцию элементов Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Содержит коллекцию элементов SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | Содержит коллекцию элементов Tab. |
| [getText()](#getText--) | Содержит текст фигуры. |
| [getTextBlock()](#getTextBlock--) | Содержит элементы, указывающие выравнивание, отступы и позиции табуляции по умолчанию текста в текстовом блоке фигуры. |
| [getTextStyle()](#getTextStyle--) | StyleSheet, из которой эта фигура наследует форматирование текста. |
| [getTextXForm()](#getTextXForm--) | Содержит элементы, указывающие информацию о позиционировании текстового блока фигуры. |
| [getThreeDFormat()](#getThreeDFormat--) | Получает ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Определяет, ведёт ли фигура себя как двумерный (2-D) объект. |
| [getType()](#getType--) | Тип фигуры. |
| [getUniqueID()](#getUniqueID--) | GUID (глобальный уникальный идентификатор), назначенный фигуре. |
| [getUsers()](#getUsers--) | Содержит коллекцию элементов User. |
| [getXForm()](#getXForm--) | Содержит элементы, указывающие общую информацию о позиционировании фигуры. |
| [getXForm1D()](#getXForm1D--) | Содержит координаты x и y начальной и конечной точек 1‑мерной фигуры. |
| [getZOrderIndex()](#getZOrderIndex--) | Возвращает индекс фигуры в порядке z, за исключением направляющей фигуры. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Возвращает массив, содержащий идентификаторы фигур, приклеенных к фигуре. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Указывает, соединены ли эти две фигуры. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Указывает, содержит ли эта фигура другую фигуру. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Указывает, приклеены ли эти две фигуры. |
| [isInGroup()](#isInGroup--) | Указывает, находится ли эта фигура в групповой фигуре. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Указывает, пересекается ли эта фигура с другой фигурой. |
| [isTextEmpty()](#isTextEmpty--) | Указывает, содержит ли фигура текст и является ли текст пустым. |
| [move(double dX, double dY)](#move-double-double-) | Перемещает фигуру на dX и dY дюймов от текущего положения. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Перемещает фигуру в новое абсолютное положение на странице. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Обновляет положение фигуры, включая трансформацию, соединения и геометрию, при изменении текста фигуры или других. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Заменяет строку текста фигуры. |
| [sendBackward()](#sendBackward--) | Перемещает фигуру назад на одну позицию в порядке Z. |
| [sendToBack()](#sendToBack--) | Перемещает фигуру в конец порядка Z. |
| [setAngle(double angle)](#setAngle-double-) | Устанавливает новый угол фигуры. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Для описания этого свойства см. [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Установить тип соединителей |
| [setData1(String value)](#setData1-java.lang.String-) | Для описания этого свойства см. [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Для описания этого свойства см. [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Для описания этого свойства см. [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Для описания этого свойства см. [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Для описания этого свойства см. [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства см. [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Устанавливает новую высоту фигуры. |
| [setID(long value)](#setID-long-) | Для описания этого свойства см. [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства см. [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Для описания этого свойства см. [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Для описания этого свойства см. [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства см. [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства см. [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Для описания этого свойства, пожалуйста, смотрите [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Для описания этого свойства, пожалуйста, смотрите [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Применить предустановленную тему к этой фигуре |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Применить предустановленный вариант темы quickstyle к этой фигуре |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Применить предустановленный вариант темы quickstyle к этой фигуре, как варианты стилей темы в выпадающем списке стилей фигур |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Применить предустановленный вариант темы к этой фигуре |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Для описания этого свойства, пожалуйста, смотрите [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Для описания этого свойства, пожалуйста, смотрите [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, смотрите [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Для описания этого свойства, пожалуйста, смотрите [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Для описания этого свойства, пожалуйста, смотрите [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Устанавливает новую ширину фигуры. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Для описания этого свойства, пожалуйста, смотрите [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Для описания этого свойства, пожалуйста, смотрите [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Создаёт HTML фигуры и сохраняет его в поток в указанном формате. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Создаёт HTML фигуры и сохраняет его в поток в указанном формате. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Создаёт HTML и сохраняет его в файл. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Создаёт изображение фигуры и сохраняет его в поток в указанном формате. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Создаёт изображение фигуры и сохраняет его в поток в указанном формате. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Создаёт изображение фигуры и сохраняет его в файл. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Создаёт PDF фигуры и сохраняет его в поток. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Создаёт PDF фигуры и сохраняет его в поток. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Сохраняет фигуру в PDF-файл. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Сохраняет фигуру в SVG-файл. |
| [ungroup()](#ungroup--) | Разгруппировать фигуру |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Конструктор.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Перемещает фигуру вперёд на одну позицию в порядке Z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Перемещает фигуру в переднюю часть порядка Z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Центрировать фигуру относительно размеров страницы.

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Возвращает массив, содержащий идентификаторы (ID) фигур, соединённых с данной фигурой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаг | int | Фильтрует массив возвращённых идентификаторов фигур по направленности соединителей. Смотрите замечания для возможных значений Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Фильтрует массив возвращаемых идентификаторов фигур, ограничивая его идентификаторами фигур, соответствующих указанному categoryString. |

**Returns:**
long[] — массив идентификаторов long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Возвращает массив, содержащий идентификаторы фигур, зависящих от фигуры.

**Returns:**
long[] — массив идентификаторов long.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Получает элемент управления ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Содержит коллекцию элементов Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Указывает выравнивание фигуры относительно направляющей или точки направляющей, к которой фигура приклеена. Элемент Align отображается только для фигур, приклеенных к направляющим или точкам направляющих.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Содержит коллекцию элементов Char.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
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
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Возвращает connectorRule, содержащий идентификатор фигуры и соединение, которое связано с фигурой.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Получить тип соединителей

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Получает данные элемента управления.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Содержит коллекцию элементов Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Содержит произвольное строковое значение, используемое для предоставления дополнительной информации о фигуре.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Содержит произвольное строковое значение, используемое для предоставления дополнительной информации о фигуре.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Содержит произвольное строковое значение, используемое для предоставления дополнительной информации о фигуре.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, удалён ли элемент локально. Значение 1 означает, что элемент удалён локально.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Корневой элемент иерархии объектов Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Получить текст, отображаемый в интерфейсе.

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Содержит элементы, задающие формулы, управляющие событиями фигур.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Содержит коллекцию элементов Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Содержит текущие значения форматирования заливки для фигуры и её тени, включая шаблон, цвет переднего плана и цвет фона.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Таблица стилей, из которой эта фигура наследует параметры заливки.

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
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Содержит коллекцию элементов Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Содержит элементы, управляющие тем, как добавлять фигуры в группу, перемещать её участников и выбирать группы.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Содержит элементы, указывающие тему справочного файла элемента Shape и информацию об авторских правах.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Содержит коллекцию элементов Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Содержит значения гаммы, яркости, контраста, размытия, резкости, шумоподавления и прозрачности для растрового изображения.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Содержит символьные значения для фигуры, наследуемые от главной фигуры.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Содержит значения параметров заливки для фигуры, наследуемые от родительского стиля и главной фигуры.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Содержит значения Geoms для фигуры, наследуемой от главной фигуры.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Содержит значения форматирования линий для фигуры, наследуемой от родительского стиля и главной фигуры.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Содержит paras для фигуры, наследуемой от родительского стиля и главной фигуры.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Содержит props для фигуры, наследуемой от главной фигуры.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Содержит значения textblock для фигуры, наследуемой от родительского стиля и главной фигуры.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Содержит пользователей для фигуры, наследуемой от главной фигуры.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Содержит элемент LayerMember, который указывает каждый слой, к которому назначена фигура.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Содержит элементы, управляющие размещением фигур и настройками маршрутизации соединителей.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Содержит элементы, которые управляют атрибутами линии для фигуры, такими как узор, толщина и цвет. Эти элементы определяют, форматированы ли концы линии (например, со стрелкой), размер форматов концов линии, радиус скругляющего круга, применяемого к линии, и стиль окончания линии (круглое или квадратное).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet, из которой эта фигура наследует форматирование линий

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Master, из которого фигура наследует свои данные.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Этот атрибут может присутствовать только в фигурах, которые являются членами групповой фигуры, и группа является экземпляром мастера. Атрибут содержит идентификатор, ссылающийся на соответствующую подфигуру в мастере.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Содержит элементы, указывающие тему справочного файла элемента Shape и информацию об авторских правах.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Имя элемента.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Универсальное имя элемента.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Определяет, ведёт ли фигура себя как одноразмерный (1‑D) объект. Только для чтения.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Корневой элемент иерархии объектов Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Содержит коллекцию элементов Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Родитель фигуры.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Содержит коллекцию элементов Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Блокировка помогает предотвратить случайные изменения фигуры, но не препятствует Microsoft Visio сбрасывать значения в других случаях. Она также не защищает от изменений, внесённых в окне ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Получить строку текста

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Возвращает фигуру верхнего уровня экземпляра, если эта фигура является частью экземпляра мастера. Только для чтения.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Содержит коллекцию элементов Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Содержит коллекцию элементов Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Содержит коллекцию элементов SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Содержит коллекцию элементов Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Содержит текст фигуры.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Содержит элементы, указывающие выравнивание, отступы и позиции табуляции по умолчанию текста в текстовом блоке фигуры.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet, из которой эта фигура наследует форматирование текста.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Содержит элементы, указывающие информацию о позиционировании текстового блока фигуры.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Получает ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Определяет, ведёт ли фигура себя как двумерный (2-D) объект.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Тип фигуры. Может принимать одно из следующих значений: Group, Shape, Guide или Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID (глобальный уникальный идентификатор), назначенный фигуре.

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
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Содержит координаты x и y начальной и конечной точек 1‑D формы. Этот элемент появляется только для 1‑D форм.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Возвращает индекс фигуры в порядке z, за исключением направляющей фигуры.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Возвращает массив, содержащий идентификаторы фигур, приклеенных к фигуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаг | int | Размерность и направленность точек соединения фигур, которые нужно вернуть. См. замечания для возможных значений Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Фильтрует массив возвращаемых идентификаторов фигур, ограничивая его идентификаторами фигур, соответствующих указанному categoryString. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Опционально: дополнительная фигура, к которой также должны быть приклеены возвращаемые фигуры, может быть [Shape](../../com.aspose.diagram/shape) или null. |

**Returns:**
long[] — массив идентификаторов long.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


Указывает, соединены ли эти две фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | фигура |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Указывает, содержит ли эта фигура другую фигуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Указывает, приклеены ли эти две фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | фигура |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Указывает, находится ли эта фигура в групповой фигуре.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Указывает, пересекается ли эта фигура с другой фигурой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Указывает, содержит ли фигура текст и является ли текст пустым.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Перемещает фигуру на dX и dY дюймов от текущего положения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dX | double | Смещение X double. |
| dY | double | Смещение Y double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Перемещает фигуру в новое абсолютное положение на странице.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newPinX | double | Новая координата x пина фигуры (центр вращения) относительно начала координат её родителя. double. |
| newPinY | double | Новая координата y пина фигуры (центр вращения) относительно начала координат её родителя. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Обновляет позицию фигуры, включая трансформацию (xform), соединения и геометрию, при изменении текста фигуры или других её свойств. Мы собираем данные фигуры, такие как её текст, затем вычисляем позицию фигуры. Этот метод используется только для обновления данных фигуры.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Заменяет строку текста фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Перемещает фигуру назад на одну позицию в порядке Z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Перемещает фигуру в конец порядка Z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Устанавливает новый угол фигуры. Единица измерения угла — радиан.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | double | Новый угол, единица измерения которого — радиан, а не degree double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Для описания этого свойства см. [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Установить тип соединителей

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Для описания этого свойства см. [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Для описания этого свойства см. [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Для описания этого свойства см. [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Для описания этого свойства см. [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Для описания этого свойства см. [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Для описания этого свойства см. [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Устанавливает новую высоту фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Для описания этого свойства см. [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Для описания этого свойства см. [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Для описания этого свойства см. [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Для описания этого свойства см. [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства см. [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства см. [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Для описания этого свойства, пожалуйста, смотрите [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Для описания этого свойства, пожалуйста, смотрите [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Применить предустановленную тему к этой фигуре

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Применить предустановленный вариант темы quickstyle к этой фигуре

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Применить предустановленный вариант темы quickstyle к этой фигуре, как варианты стилей темы в выпадающем списке стилей фигур

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Применить предустановленный вариант темы к этой фигуре

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Для описания этого свойства, пожалуйста, смотрите [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Для описания этого свойства, пожалуйста, смотрите [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Для описания этого свойства, пожалуйста, смотрите [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Для описания этого свойства, пожалуйста, смотрите [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Устанавливает новую ширину фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Для описания этого свойства, пожалуйста, смотрите [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Для описания этого свойства, пожалуйста, смотрите [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Создаёт HTML фигуры и сохраняет его в поток в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Создаёт HTML фигуры и сохраняет его в поток в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Создаёт HTML и сохраняет его в файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Создаёт изображение фигуры и сохраняет его в поток в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Создаёт изображение фигуры и сохраняет его в поток в указанном формате.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Создаёт PDF фигуры и сохраняет его в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Создаёт PDF фигуры и сохраняет его в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Сохраняет фигуру в PDF-файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


Сохраняет фигуру в SVG-файл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Разгруппировать фигуру

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

