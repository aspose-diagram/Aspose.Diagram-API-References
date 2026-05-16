---
title: StyleSheet
second_title: Справочник API Aspose.Diagram for Java
description: Представляет стиль, определённый в документе.
type: docs
weight: 393
url: /ru/java/com.aspose.diagram/stylesheet/
---

**Inheritance:**
java.lang.Object
```
public class StyleSheet
```

Представляет стиль, определённый в документе.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StyleSheet()](#StyleSheet--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChars()](#getChars--) | Содержит коллекцию элементов Char. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Содержит коллекцию элементов ConnectionABCD. |
| [getConnections()](#getConnections--) | Содержит коллекцию элементов Connection. |
| [getEvent()](#getEvent--) | Содержит элементы, задающие формулы, управляющие событиями фигур. |
| [getFill()](#getFill--) | Содержит текущие значения форматирования заливки для фигуры и её тени, включая шаблон, цвет переднего плана и цвет фона. |
| [getFillStyle()](#getFillStyle--) | Элемент StyleSheet, из которого этот стиль наследует форматирование заливки. |
| [getForeign()](#getForeign--) | Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE. |
| [getGroup()](#getGroup--) | Содержит элементы, управляющие тем, как добавлять фигуры в группу, перемещать её участников и выбирать группы. |
| [getHelp()](#getHelp--) | Содержит элементы, указывающие тему справочного файла элемента Shape и информацию об авторских правах. |
| [getID()](#getID--) | Уникальный идентификатор элемента в пределах его родительского элемента. |
| [getImage()](#getImage--) | Содержит значения гаммы, яркости, контраста, размытия, резкости, шумоподавления и прозрачности для растрового изображения. |
| [getLayout()](#getLayout--) | Содержит элементы, управляющие размещением фигур и настройками маршрутизации соединителей. |
| [getLine()](#getLine--) | Содержит элементы, управляющие атрибутами линии для фигуры, такими как шаблон, толщина и цвет. |
| [getLineStyle()](#getLineStyle--) | Элемент StyleSheet, из которого этот стиль наследует форматирование линий. |
| [getMisc()](#getMisc--) | Содержит элементы, указывающие тему справочного файла элемента Shape и информацию об авторских правах. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getPageLayout()](#getPageLayout--) | Содержит Diagram, который управляет настройками разметки страницы для фигур и соединителей, такими как расстояние между всеми фигурами на странице, расстояние между всеми соединителями на странице и стиль маршрутизации для всех соединителей на странице. |
| [getParas()](#getParas--) | Содержит коллекцию элементов Para. |
| [getProtection()](#getProtection--) | Блокировка помогает предотвратить непреднамеренные изменения фигуры, но не препятствует Microsoft Visio сбрасывать значения в других обстоятельствах. |
| [getRulerGrid()](#getRulerGrid--) | Содержит элементы, задающие настройки линейки и сетки страницы. |
| [getStyleProp()](#getStyleProp--) | Содержит элементы, управляющие поведением стиля, например, включает ли стиль атрибуты текста, линии и заливки. |
| [getTabsCollection()](#getTabsCollection--) | Содержит коллекцию элементов Tab. |
| [getTextBlock()](#getTextBlock--) | Содержит элементы, указывающие выравнивание, отступы и позиции табуляции по умолчанию текста в текстовом блоке фигуры. |
| [getTextStyle()](#getTextStyle--) | Элемент StyleSheet, из которого этот стиль наследует форматирование текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, см. [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--) |
| [setID(int value)](#setID-int-) | Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/stylesheet\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, см. [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/stylesheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, см. [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StyleSheet() {#StyleSheet--}
```
public StyleSheet()
```


Конструктор.

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
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Содержит элементы, задающие формулы, управляющие событиями фигур.

**Returns:**
[Event](../../com.aspose.diagram/event)
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


Элемент StyleSheet, из которого этот стиль наследует форматирование заливки.

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
### getID() {#getID--}
```
public int getID()
```


Уникальный идентификатор элемента в пределах его родительского элемента.

**Returns:**
int
### getImage() {#getImage--}
```
public Image getImage()
```


Содержит значения гаммы, яркости, контраста, размытия, резкости, шумоподавления и прозрачности для растрового изображения.

**Returns:**
[Image](../../com.aspose.diagram/image)
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


Элемент StyleSheet, из которого этот стиль наследует форматирование линий.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Содержит Diagram, который управляет настройками разметки страницы для фигур и соединителей, такими как расстояние между всеми фигурами на странице, расстояние между всеми соединителями на странице и стиль маршрутизации для всех соединителей на странице.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Содержит коллекцию элементов Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Блокировка помогает предотвратить случайные изменения фигуры, но не препятствует Microsoft Visio сбрасывать значения в других случаях. Она также не защищает от изменений, внесённых в окне ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Содержит элементы, задающие настройки линейки и сетки страницы.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getStyleProp() {#getStyleProp--}
```
public StyleProp getStyleProp()
```


Содержит элементы, управляющие поведением стиля, например, включает ли стиль атрибуты текста, линии и заливки.

**Returns:**
[StyleProp](../../com.aspose.diagram/styleprop)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Содержит коллекцию элементов Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
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


Элемент StyleSheet, из которого этот стиль наследует форматирование текста.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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


Для описания этого свойства, пожалуйста, см. [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Для описания этого свойства, пожалуйста, см. [getID()](../../com.aspose.diagram/stylesheet\#getID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Для описания этого свойства, пожалуйста, см. [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/stylesheet\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, см. [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Для описания этого свойства, пожалуйста, см. [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

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

