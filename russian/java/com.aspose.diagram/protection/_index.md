---
title: Защита
second_title: Справочник API Aspose.Diagram for Java
description: Блокировка помогает предотвратить непреднамеренные изменения фигуры, но не препятствует Microsoft Visio сбрасывать значения в других обстоятельствах.
type: docs
weight: 312
url: /ru/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Блокировка помогает предотвратить случайные изменения фигуры, но не препятствует Microsoft Visio сбрасывать значения в других случаях. Она также не защищает от изменений, внесённых в окне ShapeSheet.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getLockAspect()](#getLockAspect--) | Указывает, зафиксировано ли соотношение сторон фигуры. |
| [getLockBegin()](#getLockBegin--) | Указывает, зафиксирована ли начальная точка 1‑D фигуры в определённом месте. |
| [getLockCalcWH()](#getLockCalcWH--) | Указывает, зафиксирован ли прямоугольник выделения фигуры, чтобы его нельзя было пересчитать при редактировании вершины или изменении типа элемента в элементе Geom. |
| [getLockCrop()](#getLockCrop--) | Указывает, зафиксирован ли внешний объект от обрезки с помощью инструмента Crop в Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Определяет, может ли пользователь добавлять, удалять или изменять пользовательские свойства в пользовательском интерфейсе (UI), используя диалоговое окно Define Custom Properties. |
| [getLockDelete()](#getLockDelete--) | Указывает, зафиксирована ли фигура от удаления. |
| [getLockEnd()](#getLockEnd--) | Указывает, зафиксирована ли конечная точка 1‑D фигуры в определённом месте. |
| [getLockFormat()](#getLockFormat--) | Указывает, зафиксировано ли форматирование фигуры, чтобы его нельзя было изменить. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Позволяет подфигуре блокировать изменения форматирования, применяемые к родительской групповой фигуре в пользовательском интерфейсе Visio, которые иначе распространялись бы на отдельные групповые фигуры. |
| [getLockGroup()](#getLockGroup--) | Указывает, зафиксирована ли группа, чтобы её нельзя было разгруппировать. |
| [getLockHeight()](#getLockHeight--) | Указывает, зафиксирована ли высота фигуры. |
| [getLockMoveX()](#getLockMoveX--) | Указывает, зафиксировано ли горизонтальное положение фигуры, чтобы её нельзя было переместить по горизонтали. |
| [getLockMoveY()](#getLockMoveY--) | Указывает, зафиксировано ли вертикальное положение фигуры, чтобы её нельзя было переместить по вертикали. |
| [getLockRotate()](#getLockRotate--) | Указывает, зафиксирована ли фигура от вращения с помощью инструмента Rotation или команд Rotate Left и Rotate Right в Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Указывает, зафиксирован ли прямоугольник выделения фигуры, чтобы его нельзя было пересчитать при редактировании вершины или изменении типа элемента в элементе Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | Указывает, зафиксирован ли текст фигуры, чтобы его нельзя было редактировать. |
| [getLockThemeColors()](#getLockThemeColors--) | Не позволяет пользователям применять к фигуре цвета темы. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Не позволяет пользователям применять эффекты темы к форме. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Указывает, заблокированы ли вершины формы, чтобы их нельзя было редактировать с помощью любых инструментов на панели инструментов. |
| [getLockWidth()](#getLockWidth--) | Указывает, заблокирована ли ширина формы, чтобы она оставалась неизменной при изменении размеров формы. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Указывает, заблокировано ли соотношение сторон формы. Если заблокировано, форму можно изменять только пропорционально; её нельзя изменять в одном измерении.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Указывает, зафиксирована ли начальная точка 1‑D фигуры в определённом месте.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Указывает, зафиксирован ли прямоугольник выделения фигуры, чтобы его нельзя было пересчитать при редактировании вершины или изменении типа элемента в элементе Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Указывает, зафиксирован ли внешний объект от обрезки с помощью инструмента Crop в Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Определяет, может ли пользователь добавлять, удалять или изменять пользовательские свойства в пользовательском интерфейсе (UI), используя диалоговое окно Define Custom Properties.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Указывает, зафиксирована ли фигура от удаления.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Указывает, зафиксирована ли конечная точка 1‑D фигуры в определённом месте.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Указывает, заблокировано ли форматирование формы, чтобы его нельзя было изменить. В частности, этот элемент защищает от изменения форматирования текста, линии и заливки, а также от изменения того, от какого элемента Style наследуется форма.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Позволяет подфигуре блокировать изменения форматирования, применяемые к родительской групповой фигуре в пользовательском интерфейсе Visio, которые иначе распространялись бы на отдельные групповые фигуры.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Указывает, зафиксирована ли группа, чтобы её нельзя было разгруппировать.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Указывает, заблокирована ли высота формы. Если заблокировано, её высота остаётся неизменной при изменении размеров формы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Указывает, зафиксировано ли горизонтальное положение фигуры, чтобы её нельзя было переместить по горизонтали.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Указывает, зафиксировано ли вертикальное положение фигуры, чтобы её нельзя было переместить по вертикали.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Указывает, зафиксирована ли фигура от вращения с помощью инструмента Rotation или команд Rotate Left и Rotate Right в Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Указывает, зафиксирован ли прямоугольник выделения фигуры, чтобы его нельзя было пересчитать при редактировании вершины или изменении типа элемента в элементе Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Указывает, заблокирован ли текст формы, чтобы его нельзя было редактировать. Однако текст всё ещё может быть отформатирован применением стиля, используя параметры Style на вкладке Шрифт в диалоговом окне Текст.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Не позволяет пользователям применять к фигуре цвета темы.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Не позволяет пользователям применять эффекты темы к форме.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Указывает, заблокированы ли вершины формы, чтобы их нельзя было редактировать с помощью любых инструментов на панели инструментов.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Указывает, заблокирована ли ширина формы, чтобы она оставалась неизменной при изменении размеров формы.

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


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

