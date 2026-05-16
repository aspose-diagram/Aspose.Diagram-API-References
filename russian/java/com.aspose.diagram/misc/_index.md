---
title: Разное
second_title: Справочник API Aspose.Diagram for Java
description: Содержит различные элементы фигур и групп, такие как элементы, управляющие подсветкой выделения и видимостью.
type: docs
weight: 247
url: /ru/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Содержит различные элементы фигур и групп, такие как элементы, управляющие подсветкой выделения и видимостью.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Содержит формулу‑триггер, сгенерированную Microsoft Visio, которая определяет, следует ли переместить начальную точку 1‑D фигуры для поддержания её соединения с другой фигурой. |
| [getCalendar()](#getCalendar--) | Определяет календарь, используемый для пользовательских свойств, текстовых полей и формул элементов. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Содержит текст комментария в строковом формате для фигуры. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Определяет процент, на который масштабируется фигура при её размещении на странице чертежа. |
| [getDynFeedback()](#getDynFeedback--) | Указывает тип визуальной обратной связи, предоставляемой пользователям при перетаскивании соединителя. |
| [getEndTrigger()](#getEndTrigger--) | Содержит формулу‑триггер, сгенерированную Microsoft Visio. |
| [getGlueType()](#getGlueType--) | Указывает, разрешён ли динамический (фигура‑к‑фигуре) клей при соединении с фигурой. |
| [getHideText()](#getHideText--) | Скрывает текст фигуры. |
| [getLangID()](#getLangID--) | Указывает идентификатор локали (LCID) языка, на котором была введена формула ячейки, текст, пользовательское свойство или комментарий. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Определяет, локализуются ли фигуры (сбрасывается ли их элемент LangID) при копировании между документами. |
| [getNoAlignBox()](#getNoAlignBox--) | Указывает, отображается ли прямоугольник выделения, когда фигура выбрана. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Указывает, отображаются ли управляющие маркеры, когда фигура выбрана. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Указывает, изменяет ли фигура свой размер или вращается динамически при манипуляции пользователем. |
| [getNoObjHandles()](#getNoObjHandles--) | Указывает, отображаются ли маркеры выделения, когда фигура выбрана. |
| [getNonPrinting()](#getNonPrinting--) | Указывает, может ли выбранная фигура быть напечатана. |
| [getObjType()](#getObjType--) | Указывает, могут ли объекты быть размещаемыми или маршрутизируемыми в диаграммах при использовании Microsoft Visio для размещения фигур на странице чертежа. |
| [getShapeKeywords()](#getShapeKeywords--) | Содержит поисковые ключевые слова, назначенные пользовательским мастер‑фигурами. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Указывает, следует ли пересчитывать прямоугольник выделения фигуры каждый раз, когда перемещается управляющий маркер. |
| [getWalkPreference()](#getWalkPreference--) | Указывает, перемещается ли конечная точка 1‑мерной фигуры к горизонтальной или вертикальной точке соединения на фигуре, к которой она приклеена, с использованием динамического клея, когда фигура перемещается в неоднозначное положение. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Указывает, может ли фигура быть добавлена в группу путём её размещения в группе. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Указывает, заменяют ли значения указанных ячеек в мастер‑фигуре значения (включая локальные) фигуры, заменяемой в процессе операции замены фигуры. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Содержит формулу‑триггер, сгенерированную Microsoft Visio, которая определяет, следует ли переместить начальную точку 1‑D фигуры для поддержания её соединения с другой фигурой.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Определяет календарь, используемый для пользовательских свойств, текстовых полей и формул элементов.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


Содержит текст комментария в строковом формате для фигуры.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Определяет процент, на который масштабируется фигура при её размещении на странице чертежа.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Указывает тип визуальной обратной связи, предоставляемой пользователям при перетаскивании соединителя.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Содержит формулу‑триггер, сгенерированную Microsoft Visio. Эта формула‑триггер определяет, следует ли переместить конечную точку 1‑D фигуры для поддержания её соединения с другой фигурой.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Указывает, разрешён ли динамический (фигура‑к‑фигуре) клей при соединении с фигурой.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Скрывает текст для фигуры. Вы можете просматривать текст, редактировать свойства и применять стили к тексту в текстовом блоке, хотя изменения не отобразятся, пока вы не укажете элемент HideText со значением 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Указывает идентификатор локали (LCID) языка, на котором была введена формула ячейки, текст, пользовательское свойство или комментарий.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Определяет, локализуются ли фигуры (сбрасывается ли их элемент LangID) при копировании между документами.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Указывает, отображается ли прямоугольник выделения, когда фигура выбрана.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Указывает, отображаются ли управляющие маркеры, когда фигура выбрана.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Указывает, изменяет ли фигура свой размер или вращается динамически при манипуляции пользователем.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Указывает, отображаются ли маркеры выделения, когда фигура выбрана.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Указывает, может ли выбранная фигура быть напечатана.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Указывает, могут ли объекты быть размещаемыми или маршрутизируемыми в диаграммах при использовании Microsoft Visio для размещения фигур на странице чертежа.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Содержит поисковые ключевые слова, назначенные пользовательским мастер‑фигурами.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Указывает, следует ли пересчитывать прямоугольник выделения фигуры каждый раз, когда перемещается управляющий маркер.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Указывает, перемещается ли конечная точка 1‑мерной фигуры к горизонтальной или вертикальной точке соединения на фигуре, к которой она приклеена, с использованием динамического клея, когда фигура перемещается в неоднозначное положение.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


Указывает, может ли фигура быть добавлена в группу путём её размещения в группе.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Указывает, заменяют ли значения указанных ячеек в мастер‑фигуре значения (включая локальные) фигуры, заменяемой в процессе операции замены фигуры.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

