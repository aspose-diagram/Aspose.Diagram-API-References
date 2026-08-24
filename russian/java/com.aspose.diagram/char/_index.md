---
title: Char
second_title: Справочник API Aspose.Diagram for Java
description: Содержит атрибуты форматирования текста фигур, такие как цвет шрифта, стиль текста, регистр, позиция относительно базовой линии и размер в пунктах.
type: docs
weight: 45
url: /ru/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

Содержит атрибуты форматирования текста фигуры, такие как шрифт, цвет, стиль текста, регистр, положение относительно базовой линии и размер в пунктах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Char()](#Char--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | Указывает идентификационный номер шрифта, используемого для форматирования текста, содержащего азиатские символы. |
| [getAsianFontName()](#getAsianFontName--) | Указывает название азиатского шрифта, используемого для форматирования текста. Используется в Visio 2013. |
| [getCase()](#getCase--) | Определяет регистр текста фигуры. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Когда содержится в элементе Char, элемент Color. |
| [getColorTrans()](#getColorTrans--) | Определяет степень прозрачности цвета текста слоя или фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный). |
| [getComplexScriptFont()](#getComplexScriptFont--) | Содержит номер шрифта, используемого для форматирования текста, состоящего из символов сложных скриптов. |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | Указывает название шрифта ComplexScript, используемого для форматирования текста. Используется в Visio 2013. |
| [getComplexScriptSize()](#getComplexScriptSize--) | Размер шрифта, используемого для форматирования текста, состоящего из символов сложных скриптов. |
| [getDblUnderline()](#getDblUnderline--) | Указывает, имеет ли диапазон текста двойное подчеркивание снизу. |
| [getDel()](#getDel--) | Флаг, указывающий, был ли элемент удалён локально. |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | Определяет, отформатирован ли текст как двойное зачеркивание. |
| [getFont()](#getFont--) | Указывает идентификационный номер шрифта, используемого для форматирования текста. |
| [getFontName()](#getFontName--) | Указывает имя шрифта, используемого для форматирования текста. Он используется для Visio 2013 |
| [getFontScale()](#getFontScale--) | Указывает ширину шрифта. |
| [getHighlight()](#getHighlight--) | Указывает выделение. |
| [getIX()](#getIX--) | Нулевой индекс элемента внутри его родительского элемента. |
| [getLangID()](#getLangID--) | Указывает идентификатор локали (LCID) языка, на котором была введена формула ячейки, текст, пользовательское свойство или комментарий. |
| [getLetterspace()](#getLetterspace--) | Указывает количество пространства между двумя или более символами. |
| [getLocale()](#getLocale--) | Указывает локаль текстового фрагмента для целей проверки орфографии. |
| [getLocalizeFont()](#getLocalizeFont--) | Указывает, следует ли локализовать (перевести на другой язык) текст фигуры. |
| [getOverline()](#getOverline--) | Указывает, есть ли у текста линия сверху. |
| [getPerpendicular()](#getPerpendicular--) | Указывает, отображается ли текстовое поле перпендикулярно другому тексту в текстовом блоке. |
| [getPos()](#getPos--) | Указывает положение текста фигуры относительно базовой линии. |
| [getRTLText()](#getRTLText--) | Определяет, направлено ли направление текста текущего фрагмента символов слева направо или справа налево. |
| [getSize()](#getSize--) | Указывает размер текста в текстовом блоке фигуры. |
| [getStrikethru()](#getStrikethru--) | Указывает, отформатирован ли текст как зачеркивание. |
| [getStyle()](#getStyle--) | Указывает форматирование символов, применяемое к диапазону текста в текстовом блоке фигуры. |
| [getUseVertical()](#getUseVertical--) | Определяет, вертикален ли фрагмент символов или горизонтален. |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | Указывает, является ли шрифт полужирным. |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | Указывает, является ли шрифт двойным зачеркиванием. |
| [isDoubleUnderline()](#isDoubleUnderline--) | Указывает, является ли шрифт двойным подчеркиванием. |
| [isItalic()](#isItalic--) | Указывает, является ли шрифт курсивом. |
| [isStrikethrough()](#isStrikethrough--) | Указывает, является ли шрифт зачеркиванием. |
| [isSubscript()](#isSubscript--) | Указывает, является ли шрифт нижним индексом. |
| [isSuperscript()](#isSuperscript--) | Указывает, является ли шрифт верхним индексом. |
| [isUnderline()](#isUnderline--) | Указывает, является ли шрифт подчеркиванием. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | Для описания этого свойства см. [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | Для описания этого свойства см. [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | Для описания этого свойства см. [getCase()](../../com.aspose.diagram/char\#getCase--) |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | Для описания этого свойства см. [getColor()](../../com.aspose.diagram/char\#getColor--) |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--) |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | Для описания этого свойства, пожалуйста, смотрите [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--) |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | Для описания этого свойства, пожалуйста, смотрите [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--) |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--) |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--) |
| [setDel(int value)](#setDel-int-) | Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/char\#getDel--) |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--) |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | Для описания этого свойства, пожалуйста, смотрите [getFont()](../../com.aspose.diagram/char\#getFont--) |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | Для описания этого свойства, пожалуйста, смотрите [getFontName()](../../com.aspose.diagram/char\#getFontName--) |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getFontScale()](../../com.aspose.diagram/char\#getFontScale--) |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getHighlight()](../../com.aspose.diagram/char\#getHighlight--) |
| [setIX(int value)](#setIX-int-) | Для описания этого свойства, пожалуйста, смотрите [getIX()](../../com.aspose.diagram/char\#getIX--) |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | Для описания этого свойства, пожалуйста, смотрите [getLangID()](../../com.aspose.diagram/char\#getLangID--) |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--) |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | Для описания этого свойства, пожалуйста, смотрите [getLocale()](../../com.aspose.diagram/char\#getLocale--) |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | Для описания этого свойства, пожалуйста, смотрите [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--) |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getOverline()](../../com.aspose.diagram/char\#getOverline--) |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | Для описания этого свойства, пожалуйста, смотрите [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--) |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | Для описания этого свойства, пожалуйста, смотрите [getPos()](../../com.aspose.diagram/char\#getPos--) |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getRTLText()](../../com.aspose.diagram/char\#getRTLText--) |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | Для описания этого свойства, пожалуйста, смотрите [getSize()](../../com.aspose.diagram/char\#getSize--) |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--) |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | Для описания этого свойства, пожалуйста, смотрите [getStyle()](../../com.aspose.diagram/char\#getStyle--) |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | Для описания этого свойства, пожалуйста, смотрите [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
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
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


Указывает идентификационный номер шрифта, используемого для форматирования текста, содержащего азиатские символы.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


Указывает название азиатского шрифта, используемого для форматирования текста. Используется в Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


Определяет регистр текста фигуры.

**Returns:**
[Case](../../com.aspose.diagram/case)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Когда содержится в элементе Char, элемент Color.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Определяет степень прозрачности цвета текста слоя или фигуры, от 0 (полностью непрозрачный) до 1 (полностью прозрачный).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


Содержит номер шрифта, используемого для форматирования текста, состоящего из символов сложных сценариев. Сложные сценарии — это языки, символы которых требуют лигатур или формирования, такие как языки с письмом справа налево (арабский, фарси, иврит и урду) и несколько южноазиатских языков.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


Указывает название шрифта ComplexScript, используемого для форматирования текста. Используется в Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


Размер шрифта, используемого для форматирования текста, состоящего из символов сложных сценариев. Сложные сценарии — это языки, чьи символы требуют лигатур или формирования, такие как языки, пишущиеся справа налево (арабский, фарси, иврит и урду) и несколько южно-азиатских языков.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


Указывает, имеет ли диапазон текста двойное подчеркивание снизу.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Флаг, указывающий, был ли элемент удалён локально. Значение 1 указывает, что элемент был удалён локально.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


Определяет, отформатирован ли текст как двойное зачеркивание.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


Указывает идентификационный номер шрифта, используемого для форматирования текста.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


Указывает имя шрифта, используемого для форматирования текста. Он используется для Visio 2013

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


Указывает ширину шрифта.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


Указывает выделение.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Нулевой индекс элемента внутри его родительского элемента.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Указывает идентификатор локали (LCID) языка, на котором была введена формула ячейки, текст, пользовательское свойство или комментарий. Список языков, поддерживаемых приложениями Microsoft Office, и их соответствующие идентификаторы языков см. в элементе DocLangID.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


Указывает количество пространства между двумя или более символами. Пробел может добавляться или уменьшаться с шагом в 1/20 пункта.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


Указывает локаль текстового фрагмента для целей проверки орфографии.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


Указывает, следует ли локализовать (перевести на другой язык) текст фигуры.

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


Указывает, есть ли у текста линия сверху.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


Указывает, отображается ли текстовое поле перпендикулярно другому тексту в текстовом блоке.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


Указывает положение текста фигуры относительно базовой линии.

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


Определяет, направлено ли направление текста текущего фрагмента символов слева направо или справа налево.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


Указывает размер текста в текстовом блоке фигуры.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


Указывает, отформатирован ли текст как зачеркивание.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


Указывает форматирование символов, применяемое к диапазону текста в текстовом блоке фигуры.

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


Определяет, вертикален ли фрагмент символов или горизонтален.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBold() {#isBold--}
```
public boolean isBold()
```


Указывает, является ли шрифт полужирным.

**Returns:**
boolean
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


Указывает, является ли шрифт двойным зачеркиванием.

**Returns:**
boolean
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


Указывает, является ли шрифт двойным подчеркиванием.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Указывает, является ли шрифт курсивом.

**Returns:**
boolean
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


Указывает, является ли шрифт зачеркиванием.

**Returns:**
boolean
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Указывает, является ли шрифт нижним индексом.

**Returns:**
boolean
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Указывает, является ли шрифт верхним индексом.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Указывает, является ли шрифт подчеркиванием.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAsianFont(IntValue value) {#setAsianFont-com.aspose.diagram.IntValue-}
```
public void setAsianFont(IntValue value)
```


Для описания этого свойства см. [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


Для описания этого свойства см. [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


Для описания этого свойства см. [getCase()](../../com.aspose.diagram/char\#getCase--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


Для описания этого свойства см. [getColor()](../../com.aspose.diagram/char\#getColor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDel()](../../com.aspose.diagram/char\#getDel--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFont()](../../com.aspose.diagram/char\#getFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFontName()](../../com.aspose.diagram/char\#getFontName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getIX()](../../com.aspose.diagram/char\#getIX--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getLangID()](../../com.aspose.diagram/char\#getLangID--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getLocale()](../../com.aspose.diagram/char\#getLocale--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


Для описания этого свойства, пожалуйста, смотрите [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getOverline()](../../com.aspose.diagram/char\#getOverline--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


Для описания этого свойства, пожалуйста, смотрите [getPos()](../../com.aspose.diagram/char\#getPos--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getSize()](../../com.aspose.diagram/char\#getSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


Для описания этого свойства, пожалуйста, смотрите [getStyle()](../../com.aspose.diagram/char\#getStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


Для описания этого свойства, пожалуйста, смотрите [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

