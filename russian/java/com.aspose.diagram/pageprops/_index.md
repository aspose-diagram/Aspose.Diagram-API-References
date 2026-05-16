---
title: PageProps
second_title: Справочник API Aspose.Diagram for Java
description: Содержит ячейки, которые управляют атрибутами страницы, такими как ширина, высота и масштаб страницы.
type: docs
weight: 268
url: /ru/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Содержит ячейки, управляющие атрибутами страницы, такими как ширина, высота и масштаб страницы.
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Определяет, будет ли страница чертежа автоматически изменять размер, чтобы соответствовать диаграмме. |
| [getDrawingScale()](#getDrawingScale--) | Представляет значение единицы черчения в текущем масштабе черчения. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Указывает тип масштаба чертежа, используемого для страницы. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Указывает размер чертежа страницы. |
| [getInhibitSnap()](#getInhibitSnap--) | Указывает, привязываются ли фигуры на переднем плане к другим объектам на странице и к фигурам на заднем плане. |
| [getPageHeight()](#getPageHeight--) | Указывает высоту страницы в единицах черчения. |
| [getPageScale()](#getPageScale--) | Указывает значение единицы страницы по умолчанию в текущем масштабе черчения. |
| [getPageWidth()](#getPageWidth--) | Указывает ширину страницы в единицах черчения. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Содержит число, которое указывает угол наклона, когда применяется тип тени страницы по умолчанию. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Указывает расстояние в единицах страницы, на которое падающая тень фигуры смещена горизонтально от фигуры. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Указывает расстояние в единицах страницы, на которое падающая тень фигуры смещена вертикально от фигуры. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Указывает процент увеличения или уменьшения тени фигуры. |
| [getShdwType()](#getShdwType--) | Указывает тип тени по умолчанию для страницы. |
| [getUIVisibility()](#getUIVisibility--) | Определяет, отображается ли имя страницы в пользовательском интерфейсе (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Создаёт глубокую копию этого экземпляра.

**Returns:**
java.lang.Object -
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Определяет, будет ли страница чертежа автоматически изменять размер, чтобы соответствовать диаграмме.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Представляет значение единицы черчения в текущем масштабе черчения. Масштаб черчения для страницы — это отношение единицы страницы, содержащейся в элементе PageScale, к единице черчения. Единицы этого элемента определяют единицы длины по умолчанию (DL) для страницы.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Указывает тип масштаба чертежа, используемого для страницы.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Указывает размер чертежа страницы.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Указывает, привязываются ли фигуры на переднем плане к другим объектам на странице и к фигурам на заднем плане.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Указывает высоту страницы в единицах черчения.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Указывает значение единицы страницы по умолчанию в текущем масштабе черчения. Масштаб черчения для страницы — это отношение единицы страницы в элементе PageScale к единице черчения, указанной в элементе DrawingScale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Указывает ширину страницы в единицах черчения.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Содержит число, которое указывает угол наклона, когда применяется тип тени страницы по умолчанию.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Указывает расстояние в единицах страницы, на которое падающая тень фигуры смещена горизонтально от фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Указывает расстояние в единицах страницы, на которое падающая тень фигуры смещена вертикально от фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Указывает процент увеличения или уменьшения тени фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Указывает тип тени по умолчанию для страницы.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Определяет, отображается ли имя страницы в пользовательском интерфейсе (UI). Значение 1 указывает, что страница не видна; значение 0 указывает, что страница видна.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

