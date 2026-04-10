---
title: Char
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält die Formatierungsattribute für den Text von Formen, wie Schriftfarbe, Textstil, Groß-/Kleinschreibung, Position relativ zur Grundlinie und Punktgröße.
type: docs
weight: 45
url: /de/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

Enthält die Formatierungsattribute für den Text einer Form, wie Schriftart, Farbe, Textstil, Groß-/Kleinschreibung, Position relativ zur Grundlinie und Punktgröße.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Char()](#Char--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | Gibt die ID-Nummer der Schriftart an, die zum Formatieren von Text mit asiatischen Zeichen verwendet wird. |
| [getAsianFontName()](#getAsianFontName--) | Sie gibt den Namen der asiatischen Schriftart an, die zum Formatieren des Textes verwendet wird. Sie wird für Visio 2013 verwendet. |
| [getCase()](#getCase--) | Bestimmt die Groß-/Kleinschreibung des Textes einer Form. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Wenn sie in einem Char-Element enthalten ist, das Color-Element. |
| [getColorTrans()](#getColorTrans--) | Bestimmt den Transparenzgrad für die Textfarbe einer Ebene oder Form, von 0 (vollständig undurchsichtig) bis 1 (vollständig transparent). |
| [getComplexScriptFont()](#getComplexScriptFont--) | Enthält die Nummer der Schriftart, die zum Formatieren von Text mit komplexen Skriptzeichen verwendet wird. |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | Sie gibt den Namen der ComplexScript-Schriftart an, die zum Formatieren des Textes verwendet wird. Sie wird für Visio 2013 verwendet. |
| [getComplexScriptSize()](#getComplexScriptSize--) | Die Größe der Schriftart, die zum Formatieren von Text mit komplexen Skriptzeichen verwendet wird. |
| [getDblUnderline()](#getDblUnderline--) | Gibt an, ob der Textbereich darunter einen doppelten Unterstrich hat. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | Bestimmt, ob der Text als doppelter Durchstrich formatiert ist. |
| [getFont()](#getFont--) | Gibt die ID-Nummer der Schriftart an, die zum Formatieren des Textes verwendet wird. |
| [getFontName()](#getFontName--) | Gibt den Namen der Schriftart an, die zum Formatieren des Textes verwendet wird. Sie wird für Visio 2013 verwendet. |
| [getFontScale()](#getFontScale--) | Gibt die Schriftbreite an. |
| [getHighlight()](#getHighlight--) | Gibt die Hervorhebung an. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getLangID()](#getLangID--) | Gibt die Locale-ID (LCID) der Sprache an, in der die Zellformel, der Text, die benutzerdefinierte Eigenschaft oder der Kommentar eingegeben wurde. |
| [getLetterspace()](#getLetterspace--) | Gibt den Abstand zwischen zwei oder mehreren Zeichen an. |
| [getLocale()](#getLocale--) | Gibt das Gebietsschema des Textabschnitts für die Rechtschreibprüfung an. |
| [getLocalizeFont()](#getLocalizeFont--) | Gibt an, ob der Formtext lokalisiert (in eine andere Sprache übersetzt) werden soll. |
| [getOverline()](#getOverline--) | Gibt an, ob der Text eine Linie darüber hat. |
| [getPerpendicular()](#getPerpendicular--) | Gibt an, ob ein Textfeld senkrecht zum übrigen Text in einem Textblock erscheint. |
| [getPos()](#getPos--) | Gibt die Position des Textes der Shape relativ zur Grundlinie an. |
| [getRTLText()](#getRTLText--) | Bestimmt, ob die Textausrichtung des aktuellen Zeichenabschnitts von links nach rechts oder von rechts nach links verläuft. |
| [getSize()](#getSize--) | Gibt die Größe des Textes im Textblock der Form an. |
| [getStrikethru()](#getStrikethru--) | Gibt an, ob der Text als Durchgestrichen formatiert ist. |
| [getStyle()](#getStyle--) | Gibt die Zeichenformatierung an, die auf einen Textbereich im Textblock der Form angewendet wird. |
| [getUseVertical()](#getUseVertical--) | Bestimmt, ob der Zeichenabschnitt vertikal oder horizontal ist. |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | Gibt an, ob die Schriftart fett ist. |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | Gibt an, ob die Schriftart doppelter Durchstrich ist. |
| [isDoubleUnderline()](#isDoubleUnderline--) | Gibt an, ob die Schriftart doppelter Unterstrich ist. |
| [isItalic()](#isItalic--) | Gibt an, ob die Schriftart kursiv ist. |
| [isStrikethrough()](#isStrikethrough--) | Gibt an, ob die Schriftart durchgestrichen ist. |
| [isSubscript()](#isSubscript--) | Gibt an, ob die Schriftart tiefgestellt ist. |
| [isSuperscript()](#isSuperscript--) | Gibt an, ob die Schriftart hochgestellt ist. |
| [isUnderline()](#isUnderline--) | Gibt an, ob die Schriftart unterstrichen ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCase()](../../com.aspose.diagram/char\#getCase--) |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getColor()](../../com.aspose.diagram/char\#getColor--) |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--) |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--) |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--) |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--) |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--) |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/char\#getDel--) |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--) |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getFont()](../../com.aspose.diagram/char\#getFont--) |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getFontName()](../../com.aspose.diagram/char\#getFontName--) |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getFontScale()](../../com.aspose.diagram/char\#getFontScale--) |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getHighlight()](../../com.aspose.diagram/char\#getHighlight--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/char\#getIX--) |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLangID()](../../com.aspose.diagram/char\#getLangID--) |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--) |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLocale()](../../com.aspose.diagram/char\#getLocale--) |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--) |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getOverline()](../../com.aspose.diagram/char\#getOverline--) |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--) |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPos()](../../com.aspose.diagram/char\#getPos--) |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getRTLText()](../../com.aspose.diagram/char\#getRTLText--) |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSize()](../../com.aspose.diagram/char\#getSize--) |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--) |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStyle()](../../com.aspose.diagram/char\#getStyle--) |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


Gibt die ID-Nummer der Schriftart an, die zum Formatieren von Text mit asiatischen Zeichen verwendet wird.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


Sie gibt den Namen der asiatischen Schriftart an, die zum Formatieren des Textes verwendet wird. Sie wird für Visio 2013 verwendet.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


Bestimmt die Groß-/Kleinschreibung des Textes einer Form.

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


Wenn sie in einem Char-Element enthalten ist, das Color-Element.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Bestimmt den Transparenzgrad für die Textfarbe einer Ebene oder Form, von 0 (vollständig undurchsichtig) bis 1 (vollständig transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


Enthält die Nummer der Schriftart, die zum Formatieren von Text verwendet wird, der aus Zeichen komplexer Schriftsysteme besteht. Komplexe Schriftsysteme sind Sprachen, deren Zeichen Ligaturen oder Formenbildung erfordern, wie z. B. rechts‑nach‑links‑Sprachen (Arabisch, Farsi, Hebräisch und Urdu) und mehrere südasiatische Sprachen.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


Sie gibt den Namen der ComplexScript-Schriftart an, die zum Formatieren des Textes verwendet wird. Sie wird für Visio 2013 verwendet.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


Die Größe der Schrift, die zum Formatieren von Text verwendet wird, der aus komplexen Skriptzeichen besteht. Komplexe Skripte sind Sprachen, deren Zeichen Ligaturen oder Formenbildung erfordern, wie z. B. die rechts‑nach‑links‑Sprachen (Arabisch, Farsi, Hebräisch und Urdu) und mehrere südasiatische Sprachen.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


Gibt an, ob der Textbereich darunter einen doppelten Unterstrich hat.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


Bestimmt, ob der Text als doppelter Durchstrich formatiert ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


Gibt die ID-Nummer der Schriftart an, die zum Formatieren des Textes verwendet wird.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


Gibt den Namen der Schriftart an, die zum Formatieren des Textes verwendet wird. Sie wird für Visio 2013 verwendet.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


Gibt die Schriftbreite an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


Gibt die Hervorhebung an.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Gibt die Locale-ID (LCID) der Sprache an, in der die Zellformel, der Text, die benutzerdefinierte Eigenschaft oder der Kommentar eingegeben wurde. Für eine Liste der von Microsoft‑Office‑Anwendungen unterstützten Sprachen und ihrer entsprechenden Sprach‑IDs siehe das Element DocLangID.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


Gibt den Abstand zwischen zwei oder mehr Zeichen an. Der Abstand kann in Schritten von 1/20 Punkt hinzugefügt oder entfernt werden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


Gibt das Gebietsschema des Textabschnitts für die Rechtschreibprüfung an.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


Gibt an, ob der Formtext lokalisiert (in eine andere Sprache übersetzt) werden soll.

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


Gibt an, ob der Text eine Linie darüber hat.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


Gibt an, ob ein Textfeld senkrecht zum übrigen Text in einem Textblock erscheint.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


Gibt die Position des Textes der Shape relativ zur Grundlinie an.

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


Bestimmt, ob die Textausrichtung des aktuellen Zeichenabschnitts von links nach rechts oder von rechts nach links verläuft.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


Gibt die Größe des Textes im Textblock der Form an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


Gibt an, ob der Text als Durchgestrichen formatiert ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


Gibt die Zeichenformatierung an, die auf einen Textbereich im Textblock der Form angewendet wird.

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


Bestimmt, ob der Zeichenabschnitt vertikal oder horizontal ist.

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


Gibt an, ob die Schriftart fett ist.

**Returns:**
boolean
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


Gibt an, ob die Schriftart doppelter Durchstrich ist.

**Returns:**
boolean
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


Gibt an, ob die Schriftart doppelter Unterstrich ist.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Gibt an, ob die Schriftart kursiv ist.

**Returns:**
boolean
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


Gibt an, ob die Schriftart durchgestrichen ist.

**Returns:**
boolean
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Gibt an, ob die Schriftart tiefgestellt ist.

**Returns:**
boolean
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Gibt an, ob die Schriftart hochgestellt ist.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Gibt an, ob die Schriftart unterstrichen ist.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCase()](../../com.aspose.diagram/char\#getCase--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getColor()](../../com.aspose.diagram/char\#getColor--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/char\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getFont()](../../com.aspose.diagram/char\#getFont--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getFontName()](../../com.aspose.diagram/char\#getFontName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/char\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLangID()](../../com.aspose.diagram/char\#getLangID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLocale()](../../com.aspose.diagram/char\#getLocale--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getOverline()](../../com.aspose.diagram/char\#getOverline--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPos()](../../com.aspose.diagram/char\#getPos--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSize()](../../com.aspose.diagram/char\#getSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStyle()](../../com.aspose.diagram/char\#getStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

