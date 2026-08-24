---
title: DocumentSheet
second_title: Справочник API Aspose.Diagram for Java
description: Указывает структуру ShapeSheet документа.
type: docs
weight: 127
url: /ru/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

Указывает структуру ShapeSheet документа.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | Содержит элементы, содержащие информацию о комментариях, вставленных на страницу документа. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Содержит коллекцию элементов ConnectionABCD. |
| [getConnections()](#getConnections--) | Содержит коллекцию элементов Connection. |
| [getDocProps()](#getDocProps--) | Содержит элементы, управляющие качеством предварительного просмотра документа, областью и форматом вывода. |
| [getFillStyle()](#getFillStyle--) | Элемент StyleSheet, из которого этот стиль наследует форматирование заливки. |
| [getForeign()](#getForeign--) | Содержит элементы, указывающие ширину и высоту объекта из другой программы, используемого в документе Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Содержит BLOB данных изображения, закодированный в MIME (Multipurpose Internet Mail Extensions), например, Windows метафайл, растровое изображение или данные OLE. |
| [getHyperlinks()](#getHyperlinks--) | Содержит коллекцию элементов Hyperlink. |
| [getLineStyle()](#getLineStyle--) | Элемент StyleSheet, из которого этот стиль наследует форматирование линий. |
| [getName()](#getName--) | Имя элемента. |
| [getNameU()](#getNameU--) | Универсальное имя элемента. |
| [getProps()](#getProps--) | Содержит коллекцию элементов Prop. |
| [getReviewers()](#getReviewers--) | Содержит элементы, содержащие идентифицирующую информацию о рецензенте документа. |
| [getScratchs()](#getScratchs--) | Содержит коллекцию элементов Scratch. |
| [getTextStyle()](#getTextStyle--) | Элемент StyleSheet, из которого этот стиль наследует форматирование текста. |
| [getUniqueID()](#getUniqueID--) | GUID (глобальный уникальный идентификатор), идентифицирующий форму. |
| [getUsers()](#getUsers--) | Содержит коллекцию элементов User. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, смотрите [getFillStyle()](../../com.aspose.diagram/documentsheet\\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, смотрите [getLineStyle()](../../com.aspose.diagram/documentsheet\\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getName()](../../com.aspose.diagram/documentsheet\\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getNameU()](../../com.aspose.diagram/documentsheet\\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Для описания этого свойства, пожалуйста, смотрите [getTextStyle()](../../com.aspose.diagram/documentsheet\\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Для описания этого свойства, пожалуйста, смотрите [getUniqueID()](../../com.aspose.diagram/documentsheet\\#getUniqueID--) |
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
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


Содержит элементы, управляющие качеством предварительного просмотра документа, областью и форматом вывода.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Содержит коллекцию элементов Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Элемент StyleSheet, из которого этот стиль наследует форматирование линий.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Содержит коллекцию элементов Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


Содержит элементы, содержащие идентифицирующую информацию о рецензенте документа.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Содержит коллекцию элементов Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Элемент StyleSheet, из которого этот стиль наследует форматирование текста.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


GUID (глобальный уникальный идентификатор), идентифицирующий форму.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Содержит коллекцию элементов User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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


Для описания этого свойства, пожалуйста, смотрите [getFillStyle()](../../com.aspose.diagram/documentsheet\\#getFillStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Для описания этого свойства, пожалуйста, смотрите [getLineStyle()](../../com.aspose.diagram/documentsheet\\#getLineStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getName()](../../com.aspose.diagram/documentsheet\\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getNameU()](../../com.aspose.diagram/documentsheet\\#getNameU--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Для описания этого свойства, пожалуйста, смотрите [getTextStyle()](../../com.aspose.diagram/documentsheet\\#getTextStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Для описания этого свойства, пожалуйста, смотрите [getUniqueID()](../../com.aspose.diagram/documentsheet\\#getUniqueID--)

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

