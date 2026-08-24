---
title: PageLayout
second_title: Справочник API Aspose.Diagram for Java
description: Содержит ячейки, которые управляют настройками разметки страницы для фигур и соединителей, такими как расстояние между всеми фигурами на странице, расстояние между всеми соединителями на странице и стиль маршрутизации для всех соединителей на странице.
type: docs
weight: 263
url: /ru/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Содержит ячейки, управляющие настройками макета страницы для фигур и соединителей, такие как расстояние между всеми фигурами на странице, расстояние между всеми соединителями на странице и стиль маршрутизации для всех соединителей на странице.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Определяет количество вертикального пространства между фигурами на чертёжной странице при использовании Microsoft Visio для размещения фигур на странице. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Определяет количество вертикального пространства между фигурами на чертёжной странице при использовании Microsoft Visio для размещения фигур на странице. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Указывает, как фигуры размещаются на странице, когда пользователь выбирает "Lay Out Shapes" (меню Shape). |
| [getBlockSizeX()](#getBlockSizeX--) | Определяет вертикальный размер блока, область, в которой каждая из ваших фигур должна помещаться на чертёжной странице при использовании Microsoft Visio для размещения фигур. |
| [getBlockSizeY()](#getBlockSizeY--) | Определяет количество горизонтального пространства между фигурами на чертёжной странице при использовании Microsoft Visio для размещения фигур. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Определяет, какая фигура является родительской при использовании фигур с помощью управляющих маркеров. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDynamicsOff()](#getDynamicsOff--) | Указывает, перемещаются ли размещаемые фигуры и перенаправляются ли соединители вокруг других фигур и соединителей на чертёжной странице. |
| [getEnableGrid()](#getEnableGrid--) | Указывает, будет ли Microsoft Visio размещать фигуры на основе внутренней сетки страницы, когда пользователь выбирает «Разместить фигуры» (меню «Фигура»). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Указывает, какие динамические соединители раздвигать, если они маршрутизируются друг над другом. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Указывает, какие динамические соединители выравнивать друг над другом, если они маршрутизируются друг над другом. |
| [getLineJumpCode()](#getLineJumpCode--) | Указывает стиль перехода линии для всех соединителей на чертёжной странице, у которых нет локального стиля перехода линии. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Указывает размер перескоков линий на горизонтальных сегментах динамических соединителей на странице в процентах от значения элемента LineToLineX (который задаёт горизонтальный зазор между всеми соединителями на чертёжной странице). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Указывает размер перескоков линий на вертикальных сегментах динамических соединителей на странице в процентах от значения элемента LineToLineY (который задаёт вертикальный зазор между всеми соединителями на чертёжной странице). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Указывает направление прыжков линии на горизонтальных сегментах динамических соединителей на листе чертежа, для которых не задано локальное направление прыжка. |
| [getLineRouteExt()](#getLineRouteExt--) | Указывает внешний вид по умолчанию для всех соединителей на странице. |
| [getLineToLineX()](#getLineToLineX--) | Указывает минимальный горизонтальный зазор между динамическими соединителями на чертёжной странице. |
| [getLineToLineY()](#getLineToLineY--) | Указывает минимальный вертикальный зазор между динамическими соединителями на чертёжной странице. |
| [getLineToNodeX()](#getLineToNodeX--) | Указывает минимальный вертикальный зазор между динамическими соединителями и фигурами на чертёжной странице. |
| [getLineToNodeY()](#getLineToNodeY--) | Определяет горизонтальный размер блока, область, в которой каждая из ваших фигур должна помещаться на чертёжной странице при использовании Microsoft Visio для размещения фигур. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Указывает направление прыжков линии на вертикальных динамических соединителях на листе чертежа, для которых не задано локальное направление прыжка. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Указывает минимальный горизонтальный зазор между динамическими соединителями и фигурами на чертёжной странице. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Указывает, могут ли фигуры на странице автоматически разделяться. |
| [getPlaceDepth()](#getPlaceDepth--) | Указывает, отдаляются ли размещаемые фигуры, когда пользователь перетаскивает одну размещаемую фигуру рядом с другой размещаемой фигурой на чертёжной странице. |
| [getPlaceFlip()](#getPlaceFlip--) | Указывает, как размещаемые фигуры отражаются и/или вращаются на странице, когда фигуры размещаются с помощью команды "Lay Out Shapes" в Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Указывает стиль маршрутизации и направление для всех динамических соединителей на странице чертежа, у которых нет локального стиля маршрутизации. |
| [getPlowCode()](#getPlowCode--) | Определяет динамические соединители, к которым вы хотите добавить переходы. |
| [getResizePage()](#getResizePage--) | Указывает, следует ли увеличивать страницу, чтобы охватить чертёж, после того как пользователь выбирает «Разместить фигуры» (меню «Фигуры»). |
| [getRouteStyle()](#getRouteStyle--) | Для автоматически размещаемого чертежа указывает метод, с помощью которого чертеж анализируется перед созданием макета, и определяет тип макета. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Определяет количество вертикального пространства между фигурами на чертёжной странице при использовании Microsoft Visio для размещения фигур на странице.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Определяет количество вертикального пространства между фигурами на чертёжной странице при использовании Microsoft Visio для размещения фигур на странице.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Указывает, как фигуры размещаются на странице, когда пользователь выбирает "Lay Out Shapes" (меню Shape).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Определяет вертикальный размер блока, область, в которой каждая из ваших фигур должна помещаться на чертёжной странице при использовании Microsoft Visio для размещения фигур.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Определяет количество горизонтального пространства между фигурами на чертёжной странице при использовании Microsoft Visio для размещения фигур.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Определяет, какая фигура является родительской при использовании фигур с помощью управляющих маркеров. Этот элемент задаёт поведение всех фигур на чертёжной странице.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Указывает, перемещаются ли размещаемые фигуры и перенаправляются ли соединители вокруг других фигур и соединителей на чертёжной странице.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Указывает, будет ли Microsoft Visio размещать фигуры на основе внутренней сетки страницы, когда пользователь выбирает «Разместить фигуры» (меню «Фигура»).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Указывает, какие динамические соединители раздвигать, если они маршрутизируются друг над другом.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Указывает, какие динамические соединители выравнивать друг над другом, если они маршрутизируются друг над другом.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Указывает стиль перехода линии для всех соединителей на чертёжной странице, у которых нет локального стиля перехода линии.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Указывает размер перескоков линий на горизонтальных сегментах динамических соединителей на странице в процентах от значения элемента LineToLineX (который задаёт горизонтальный зазор между всеми соединителями на чертёжной странице). Значение этого элемента находится в диапазоне от 0 до 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Указывает размер перескоков линий на вертикальных сегментах динамических соединителей на странице в процентах от значения элемента LineToLineY (который задаёт вертикальный зазор между всеми соединителями на чертёжной странице). Этот элемент может принимать значение от 0 до 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Указывает направление прыжков линии на горизонтальных сегментах динамических соединителей на листе чертежа, для которых не задано локальное направление прыжка.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Указывает внешний вид по умолчанию для всех соединителей на странице.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Указывает минимальный горизонтальный зазор между динамическими соединителями на чертёжной странице.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Указывает минимальный вертикальный зазор между динамическими соединителями на чертёжной странице.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Указывает минимальный вертикальный зазор между динамическими соединителями и фигурами на чертёжной странице.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Определяет горизонтальный размер блока, область, в которой каждая из ваших фигур должна помещаться на чертёжной странице при использовании Microsoft Visio для размещения фигур.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Указывает направление прыжков линии на вертикальных динамических соединителях на листе чертежа, для которых не задано локальное направление прыжка.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Указывает минимальный горизонтальный зазор между динамическими соединителями и фигурами на чертёжной странице.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Указывает, могут ли фигуры на странице автоматически разделяться.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Указывает, отдаляются ли размещаемые фигуры, когда пользователь перетаскивает одну размещаемую фигуру рядом с другой размещаемой фигурой на чертёжной странице.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Указывает, как размещаемые фигуры переворачиваются и/или вращаются на странице, когда фигуры размещаются с помощью команды «Lay Out Shapes» в Microsoft Visio. Допустимы следующие шестнадцатеричные значения.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Указывает стиль маршрутизации и направление для всех динамических соединителей на странице чертежа, у которых нет локального стиля маршрутизации.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Определяет динамические соединители, к которым вы хотите добавить переходы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Указывает, следует ли увеличивать страницу, чтобы охватить чертёж, после того как пользователь выбирает «Разместить фигуры» (меню «Фигуры»).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Для автоматически размещаемого чертежа указывает метод, с помощью которого чертеж анализируется перед созданием макета, и определяет тип макета.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


Для описания этого свойства, пожалуйста, см. [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

