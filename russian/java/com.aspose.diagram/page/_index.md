---
title: Page
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, определяющие страницу в документе.
type: docs
weight: 260
url: /ru/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Содержит элементы, определяющие страницу в документе.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Page()](#Page--) | Конструктор. |
| [Page(int ID)](#Page-int-) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Создаёт Activex Control. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Добавляет комментарий к фигуре. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Добавляет комментарий с определёнными PinX и PinY. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Добавляет комментарий к фигуре с идентификатором фигуры. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Добавляет фигуру, созданную мастером, на определённую страницу. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Добавляет фигуру, созданную мастером, на страницу с определёнными PinX, PinY, Width и Height. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Добавляет фигуру, созданную мастером, на страницу с определёнными PinX и PinY. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Добавляет текст с определёнными PinX и PinY. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Добавляет текст с определёнными PinX и PinY. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Применяет стиль ко всей странице. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Автоматическое размещение фигур. |
| [bringForward(long shapeId)](#bringForward-long-) | Перемещает фигуру, определённую по ID, на одну позицию вперёд в порядке Z. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Перемещает фигуру, определённую по ID, на передний план в порядке Z. |
| [centerDrawing()](#centerDrawing--) | Центрирует фигуры страницы относительно её границ. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Соединяет фигуры с помощью соединителя. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Соединяет фигуры с помощью соединителя. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Соединяет фигуры с помощью соединителя. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Соединяет фигуры по индексу соединителя. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Соединяет фигуры по индексу соединителя. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Процесс рисования эллипса. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Процесс рисования одной линии. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Процесс рисования линии. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Процесс рисования полилинии. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Процесс рисования прямоугольника. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | Идентификатор оригинальной страницы чертежа, которая была размечена отдельными наложениями разметки рецензентами чертежа. |
| [getBackPage()](#getBackPage--) | Фоновая страница страницы. |
| [getBackground()](#getBackground--) | Флаг, указывающий, является ли страница фоновой. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Содержит элемент Connect для каждого соединения между двумя фигурами в чертеже. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getPageSheet()](#getPageSheet--) | Содержит элементы, определяющие лист страницы для элемента Page или Master. |
| [getPages()](#getPages--) | Коллекция страниц. |
| [getReviewerID()](#getReviewerID--) | Идентификатор рецензента, связанного с наложением разметки. |
| [getShapes()](#getShapes--) | Коллекция фигур. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX и ViewCenterY задают центральную точку на странице, которую новое представление (окно) принимает при первоначальном открытии. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX и ViewCenterY задают центральную точку на странице, которую новое представление (окно) принимает при первоначальном открытии. |
| [getViewScale()](#getViewScale--) | Коэффициент увеличения по умолчанию, используемый при открытии нового представления (окна) страницы. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Привязать форму к BeginX соединителя |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Привязать форму к EndX соединителя |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Привязать формы. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Привязать формы |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Привязать формы в контейнере |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Привязать формы в контейнере, используя имя соединения |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Привязать формы по идентификатору соединения в контейнере |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Размещает формы и/или перенаправляет соединители для страницы. |
| [moveTo(int index)](#moveTo-int-) | Перемещает страницу в другое место среди страниц. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Перемещает форму, определённую по ID, назад на одну позицию в порядке Z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Перемещает форму, определённую по ID, в конец порядка Z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Для описания этого свойства, пожалуйста, см. [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Для описания этого свойства, пожалуйста, см. [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Для описания этого свойства, пожалуйста, см. [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Для описания этого свойства, пожалуйста, см. [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Применить предустановленную тему к этой странице |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Применить предустановленный вариант темы quickstyle к этой странице |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Применить предустановленный вариант темы к этой странице |
| [setReviewerID(int value)](#setReviewerID-int-) | Для описания этого свойства, пожалуйста, смотрите [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Для описания этого свойства, пожалуйста, смотрите [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Для описания этого свойства, пожалуйста, смотрите [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Для описания этого свойства, пожалуйста, смотрите [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Конструктор.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Конструктор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Создаёт Activex Control.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Тип элемента управления. |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| width | double | Указывает ширину фигуры в дюймах. |
| height | double | Указывает высоту фигуры в дюймах. |

**Returns:**
long - 
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Добавляет комментарий к фигуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Указывает фигуру, к которой добавляется комментарий. |
| comment | java.lang.String | Строка комментария. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Добавляет комментарий с определёнными PinX и PinY.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки комментария (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки комментария (центр вращения) относительно страницы. |
| comment | java.lang.String | Строка комментария. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Добавляет комментарий к фигуре с идентификатором фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Строка комментария. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Добавляет фигуру, созданную мастером, на определённую страницу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Новый объект фигуры[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Имя мастера. |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| stream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
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

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Добавляет фигуру, созданную мастером, на страницу с определёнными PinX и PinY.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| masterName | java.lang.String | Имя мастера. |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Добавляет текст с определёнными PinX и PinY.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает x‑координату привязки текста (центр вращения) относительно страницы. |
| pinY | double | Указывает y‑координату привязки текста (центр вращения) относительно страницы. |
| width | double |  |
| height | double |  |
| текст | java.lang.String | текстовая строка. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Добавляет текст с определёнными PinX и PinY.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает x‑координату привязки текста (центр вращения) относительно страницы. |
| pinY | double | Указывает y‑координату привязки текста (центр вращения) относительно страницы. |
| width | double | Указывает ширину текста. |
| height | double | Указывает высоту текста. |
| текст | java.lang.String | текстовая строка. |
| fontName | java.lang.String | название шрифта текста. |
| fontColor | java.lang.String | цвет шрифта текста. |
| size | double | размер шрифта текста. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Применяет стиль для всей страницы. Значение по умолчанию — -1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textStyle | int | идентификатор стиля текста. |
| lineStyle | int | идентификатор стиля линии. |
| fillStyle | int | идентификатор стиля заливки. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Автоматическое размещение фигур.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Указывает, что фигуры должны автоматически распределяться. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Перемещает фигуру, определённую по ID, на одну позицию вперёд в порядке Z.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeId | long | ID фигуры (long). |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Перемещает фигуру, определённую по ID, на передний план в порядке Z.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeId | long | ID фигуры (long). |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Центрирует фигуры страницы относительно её границ. Центрирование фигур не меняет их взаимное расположение.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Соединяет фигуры с помощью соединителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Фигура, где начинается соединитель [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Расположение на первой фигуре, где будет подключен соединитель Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Фигура, где соединитель заканчивается [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Расположение на второй фигуре, где будет подключен соединитель Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | Фигура с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Соединяет фигуры с помощью соединителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, где соединитель начинается [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Расположение на первой фигуре, где будет подключен соединитель Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | Идентификатор фигуры, где соединитель заканчивается [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Расположение на второй фигуре, где будет подключен соединитель Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | Идентификатор фигуры с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Соединяет фигуры с помощью соединителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, где соединитель начинается [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Имя соединения на первой фигуре, где будет подключен соединитель. |
| shapeToId | long | Идентификатор фигуры, где соединитель заканчивается [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Имя соединения на второй фигуре, где будет подключен соединитель. |
| connectorId | long | Идентификатор фигуры с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Соединяет фигуры по индексу соединителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Фигура, где начинается соединитель [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Индекс соединения на первой фигуре |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Фигура, где соединитель заканчивается [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Индекс соединения на второй фигуре |
| connector | [Shape](../../com.aspose.diagram/shape) | Фигура с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Соединяет фигуры по индексу соединителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, где соединитель начинается [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Индекс соединения на первой фигуре |
| shapeToId | long | Идентификатор фигуры, где соединитель заканчивается [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Индекс соединения на второй фигуре |
| connectorId | long | Идентификатор фигуры с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Процесс рисования эллипса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| width | double | Указывает ширину фигуры |
| height | double | Указывает высоту фигуры |

**Returns:**
long - 
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Процесс рисования одной линии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginX | double | Указывает начальную координату x позиции фигуры относительно страницы. |
| beginY | double | Указывает начальную координату y позиции фигуры относительно страницы. |
| endX | double | Указывает конечную координату x позиции фигуры относительно страницы. |
| endY | double | Указывает конечную координату y положения фигуры относительно страницы. |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Процесс рисования линии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| width | double | Указывает ширину фигуры |
| height | double | Указывает высоту фигуры |
| xyArray | double[] | Массив чередующихся значений x и y, определяющий точки новой фигуры |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Процесс рисования полилинии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| width | double | Указывает ширину фигуры |
| height | double | Указывает высоту фигуры |
| xyArray | double[] | Массив чередующихся значений x и y, определяющий точки новой фигуры |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Процесс рисования прямоугольника.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pinX | double | Указывает координату x привязки фигуры (центр вращения) относительно страницы. |
| pinY | double | Указывает координату y привязки фигуры (центр вращения) относительно страницы. |
| width | double | Указывает ширину фигуры |
| height | double | Указывает высоту фигуры |

**Returns:**
long - Уникальный идентификатор фигуры в коллекции фигур на указанной странице.
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
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


Идентификатор оригинальной страницы чертежа, которая была размечена отдельными наложениями разметки рецензентами чертежа.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


Фоновая страница страницы.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Флаг, указывающий, является ли страница фоновой.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Содержит элемент Connect для каждого соединения между двумя фигурами в чертеже.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Содержит элементы, определяющие лист страницы для элемента Page или Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Коллекция страниц.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


Идентификатор рецензента, связанного с наложением разметки.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Коллекция фигур.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX и ViewCenterY задают центральную точку на странице, которую новое представление (окно) принимает при первоначальном открытии.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX и ViewCenterY задают центральную точку на странице, которую новое представление (окно) принимает при первоначальном открытии.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Коэффициент масштабирования по умолчанию, используемый при открытии нового представления (окна) страницы. Например, 1 = 100 %; 1,5 = 150 %, и т.д.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Привязать форму к BeginX соединителя

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, где соединитель начинается [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Имя соединения на фигуре, к которому будет подключён коннектор. |
| connectorId | long | Идентификатор фигуры с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Привязать форму к EndX соединителя

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeToId | long | Идентификатор фигуры, где соединитель заканчивается [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Имя соединения на второй фигуре, где будет подключен соединитель. |
| connectorId | long | Идентификатор фигуры с типом Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Привязать формы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Фигура, к которой приклеивается из [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Местоположение на первой фигуре, где приклеить Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Фигура, к которой нужно приклеить [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Привязать формы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, к которой приклеивается из [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Местоположение на первой фигуре, где приклеить Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | Идентификатор фигуры, к которой нужно приклеить [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Привязать формы в контейнере

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, к которой приклеивается из [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | Местоположение на первом индексе соединения, где приклеить. |
| shapeToEndConnectionIndex | int | Местоположение на конечном индексе соединения, где приклеить. |
| shapeToId | long | Идентификатор фигуры, к которой нужно приклеить [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Привязать формы в контейнере, используя имя соединения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, к которой приклеивается из [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | Местоположение на первом имени соединения, где приклеить. |
| shapeToEndConnectionName | java.lang.String | Местоположение на конечном имени соединения, где приклеить. |
| shapeToId | long | Идентификатор фигуры, к которой нужно приклеить [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Привязать формы по идентификатору соединения в контейнере

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeFromId | long | Идентификатор фигуры, к которой приклеивается из [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | Местоположение на первом идентификаторе соединения, где приклеить. |
| shapeToEndConnectionID | int | Местоположение на конечном идентификаторе соединения, где приклеить. |
| shapeToId | long | Идентификатор фигуры, к которой нужно приклеить [Shape](../../com.aspose.diagram/shape). |

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


Размещает формы и/или перенаправляет соединители для страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Использование [LayoutOptions](../../com.aspose.diagram/layoutoptions) для настройки параметров макета. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Перемещает страницу в другое место среди страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс целевой страницы. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


Перемещает форму, определённую по ID, назад на одну позицию в порядке Z.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeId | long | ID фигуры (long). |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Перемещает форму, определённую по ID, в конец порядка Z.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeId | long | ID фигуры (long). |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Для описания этого свойства, пожалуйста, см. [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Для описания этого свойства, пожалуйста, см. [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Для описания этого свойства, пожалуйста, см. [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Для описания этого свойства, пожалуйста, см. [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Применить предустановленную тему к этой странице

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Применить предустановленный вариант темы quickstyle к этой странице

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Применить предустановленный вариант темы к этой странице

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

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

