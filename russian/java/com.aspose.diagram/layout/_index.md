---
title: Разметка
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы, управляющие размещением фигур и настройками маршрутизации соединителей.
type: docs
weight: 215
url: /ru/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Содержит элементы, управляющие размещением фигур и настройками маршрутизации соединителей.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Определяет, когда соединитель перенаправляется. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Определяет, будет ли соединитель прыгать, когда два соединителя пересекаются, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Определяет направление прыжка линии для прыжков линии, происходящих на горизонтальном сегменте динамического соединителя. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Определяет направление прыжка линии для прыжков линии, происходящих на вертикальном сегменте динамического соединителя. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Определяет стиль прыжка линии для прыжков линии на динамическом соединителе. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Определяет внешний вид соединителя. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDisplayLevel()](#getDisplayLevel--) | Определяет диапазон уровня отображения (относительный диапазон группировки по Z-порядку) для фигуры. |
| [getRelationships()](#getRelationships--) | Сохраняет взаимосвязи между контейнерами, списками, выносками и фигурами. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Указывает поведение размещения для размещаемой фигуры. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Указывает, могут ли размещаемые фигуры быть помещены поверх другой фигуры, когда пользователь выбирает Lay Out Shapes (Shapes menu). |
| [getShapePermeableX()](#getShapePermeableX--) | Указывает, может ли соединитель прокладываться горизонтально через фигуру. |
| [getShapePermeableY()](#getShapePermeableY--) | Указывает, может ли соединитель прокладываться вертикально через фигуру. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Указывает, как размещаемая фигура отражается и/или вращается на странице, когда пользователь выбирает Lay Out Shapes (меню Shapes). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Определяет стиль размещения для дочерних элементов. |
| [getShapePlowCode()](#getShapePlowCode--) | Указывает, будет ли размещаемая фигура отодвигаться, когда вы перетаскиваете другую размещаемую фигуру рядом с ней на чертёжной странице. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Указывает стиль маршрутизации и направление соединителя на чертёжной странице. |
| [getShapeSplit()](#getShapeSplit--) | Определяет, может ли эта фигура разделять фигуры, которые можно разделять. |
| [getShapeSplittable()](#getShapeSplittable--) | Определяет, может ли эта 1‑мерная фигура быть разделена. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Для описания этого свойства, пожалуйста, смотрите [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Определяет, когда соединитель перенаправляется.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Определяет, будет ли соединитель прыгать, когда два соединителя пересекаются,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Определяет направление прыжка линии для прыжков линии, происходящих на горизонтальном сегменте динамического соединителя.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Определяет направление прыжка линии для прыжков линии, происходящих на вертикальном сегменте динамического соединителя.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Определяет стиль прыжка линии для прыжков линии на динамическом соединителе.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Определяет внешний вид соединителя.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Определяет диапазон уровня отображения (относительный диапазон группировки по Z-порядку) для фигуры.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Сохраняет взаимосвязи между контейнерами, списками, выносками и фигурами.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Указывает поведение размещения для размещаемой фигуры.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Указывает, могут ли размещаемые фигуры быть помещены поверх другой фигуры, когда пользователь выбирает Lay Out Shapes (Shapes menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Указывает, может ли соединитель прокладываться горизонтально через фигуру.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Указывает, может ли соединитель прокладываться вертикально через фигуру.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Указывает, как размещаемая фигура отражается и/или вращается на странице, когда пользователь выбирает Lay Out Shapes (меню Shapes).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Определяет стиль размещения для дочерних элементов.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Указывает, будет ли размещаемая фигура отодвигаться, когда вы перетаскиваете другую размещаемую фигуру рядом с ней на чертёжной странице.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Указывает стиль маршрутизации и направление соединителя на чертёжной странице.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Определяет, может ли эта фигура разделять фигуры, которые можно разделять.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Определяет, может ли эта 1‑мерная фигура быть разделена.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Для описания этого свойства, пожалуйста, смотрите [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

