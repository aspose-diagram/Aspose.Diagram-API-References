---
title: Para
second_title: Справочник API Aspose.Diagram for Java
description: Содержит элементы форматирования абзаца для текста фигур, такие как отступы, межстрочный интервал, маркеры и горизонтальное выравнивание абзацев.
type: docs
weight: 274
url: /ru/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

Содержит элементы форматирования абзацев для текста фигуры, такие как отступы, межстрочный интервал, маркеры и горизонтальное выравнивание абзацев.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Para()](#Para--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | Определяет стиль маркера. |
| [getBulletFont()](#getBulletFont--) | Представляет номер шрифта, используемого для форматирования текста, когда указана пользовательская строка маркера, и значение в элементе Bullet не равно нулю. |
| [getBulletFontSize()](#getBulletFontSize--) | Указывает размер маркера. |
| [getBulletStr()](#getBulletStr--) | "Используется для создания пользовательского стиля маркера. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getFlags()](#getFlags--) | Указывает, направлено ли направление текста слева направо или справа налево. |
| [getHorzAlign()](#getHorzAlign--) | Указывает горизонтальное выравнивание текста в текстовом блоке фигуры. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getIndFirst()](#getIndFirst--) | Указывает расстояние, на которое первая строка каждого абзаца в текстовом блоке фигуры отступает от левого отступа абзаца. |
| [getIndLeft()](#getIndLeft--) | Указывает расстояние, на которое все строки текста в абзаце отступают от левого поля текстового блока. |
| [getIndRight()](#getIndRight--) | Указывает расстояние, на которое все строки текста в абзаце отступают от правого поля текстового блока. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | Указывает, следует ли локализовать шрифт маркера (перевести его на другой язык). |
| [getSpAfter()](#getSpAfter--) | Указывает количество пространства, вставляемого после каждого абзаца в текстовом блоке фигуры. |
| [getSpBefore()](#getSpBefore--) | Указывает количество пространства, вставляемого перед каждым абзацем в текстовом блоке фигуры. |
| [getSpLine()](#getSpLine--) | Указывает расстояние между одной строкой текста и следующей, где 100 % соответствует высоте строки текста. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | Представляет расстояние между первой строкой абзаца и маркером. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | Для описания этого свойства см. [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | Для описания этого свойства см. [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | Для описания этого свойства см. [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства см. [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | Для описания этого свойства см. [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | Для описания этого свойства см. [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства см. [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | Для описания этого свойства см. [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | Для описания этого свойства см. [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


Определяет стиль маркера.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


Представляет номер шрифта, используемого для форматирования текста, когда указана пользовательская строка маркера, и значение в элементе Bullet не равно нулю.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


Указывает размер маркера.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"Используется для создания пользовательского стиля маркера. Введите стиль как строку (в кавычках). Например, вы можете ввести строку, ""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


Указывает, направлено ли направление текста слева направо или справа налево.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


Указывает горизонтальное выравнивание текста в текстовом блоке фигуры.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


Нулевой индекс элемента внутри его родительского элемента.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


Указывает расстояние, на которое первая строка каждого абзаца в текстовом блоке фигуры отступает от левого отступа абзаца. Это значение независимо от масштаба чертежа. Если чертеж масштабируется, отступ первой строки остаётся прежним.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


Указывает расстояние, на которое все строки текста в абзаце отступают от левого поля текстового блока. Это значение независимо от масштаба чертежа. Если чертеж масштабируется, левый отступ остаётся прежним.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


Указывает расстояние, на которое все строки текста в абзаце отступают от правого поля текстового блока. Это значение независимо от масштаба чертежа. Если чертеж масштабируется, правый отступ остаётся прежним.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


Указывает, следует ли локализовать шрифт маркера (перевести его на другой язык).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


Указывает количество пространства, вставляемого после каждого абзаца в текстовом блоке фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


Указывает количество пространства, вставляемого перед каждым абзацем в текстовом блоке фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


Указывает расстояние между одной строкой текста и следующей, где 100 % соответствует высоте строки текста.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


Представляет расстояние между первой строкой абзаца и маркером.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


Для описания этого свойства см. [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


Для описания этого свойства см. [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


Для описания этого свойства см. [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


Для описания этого свойства см. [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства см. [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


Для описания этого свойства см. [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


Для описания этого свойства см. [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства см. [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


Для описания этого свойства см. [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


Для описания этого свойства см. [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


Для описания этого свойства см. [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


Для описания этого свойства см. [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


Для описания этого свойства см. [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


Для описания этого свойства см. [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


Для описания этого свойства см. [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


Для описания этого свойства см. [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

