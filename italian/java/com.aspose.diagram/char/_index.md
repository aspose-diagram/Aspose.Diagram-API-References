---
title: Char
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene gli attributi di formattazione per il testo delle forme, come colore del carattere, stile del testo, maiuscole/minuscole, posizione relativa alla linea di base e dimensione in punti.
type: docs
weight: 45
url: /it/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

Contiene gli attributi di formattazione per il testo della forma, come carattere, colore, stile del testo, maiuscolo/minuscolo, posizione relativa alla linea di base e dimensione in punti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Char()](#Char--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | Specifica il numero ID del carattere utilizzato per formattare il testo contenente caratteri asiatici. |
| [getAsianFontName()](#getAsianFontName--) | Specifica il nome del carattere asiatico del carattere usato per formattare il testo. È utilizzato per Visio 2013. |
| [getCase()](#getCase--) | Determina il maiuscolo/minuscolo del testo di una forma. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Quando è contenuto in un elemento Char, l'elemento Color. |
| [getColorTrans()](#getColorTrans--) | Determina il grado di trasparenza del colore del testo di un livello o di una forma, da 0 (completamente opaco) a 1 (completamente trasparente). |
| [getComplexScriptFont()](#getComplexScriptFont--) | Contiene il numero del carattere utilizzato per formattare il testo composto da caratteri di script complessi. |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | Specifica il nome del carattere ComplexScript del carattere usato per formattare il testo. È utilizzato per Visio 2013. |
| [getComplexScriptSize()](#getComplexScriptSize--) | La dimensione del carattere utilizzato per formattare il testo composto da caratteri di script complessi. |
| [getDblUnderline()](#getDblUnderline--) | Specifica se l'intervallo di testo ha una doppia sottolineatura sotto di esso. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | Determina se il testo è formattato con doppia barratura. |
| [getFont()](#getFont--) | Specifica il numero ID del carattere usato per formattare il testo. |
| [getFontName()](#getFontName--) | Specifica il nome del carattere usato per formattare il testo. È utilizzato per Visio 2013 |
| [getFontScale()](#getFontScale--) | Specifica la larghezza del carattere. |
| [getHighlight()](#getHighlight--) | Specifica l'evidenziazione. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getLangID()](#getLangID--) | Indica l'ID locale (LCID) della lingua in cui è stata inserita la formula della cella, il testo, la proprietà personalizzata o il commento. |
| [getLetterspace()](#getLetterspace--) | Specifica la quantità di spazio tra due o più caratteri. |
| [getLocale()](#getLocale--) | Specifica la localizzazione dell'intervallo di testo per scopi di correzione ortografica. |
| [getLocalizeFont()](#getLocalizeFont--) | Specifica se il testo della forma deve essere localizzato (tradotto in un'altra lingua). |
| [getOverline()](#getOverline--) | Specifica se il testo ha una linea sopra di esso. |
| [getPerpendicular()](#getPerpendicular--) | Specifica se un campo di testo appare perpendicolare al resto del testo in un blocco di testo. |
| [getPos()](#getPos--) | Specifica la posizione del testo della forma rispetto alla linea di base. |
| [getRTLText()](#getRTLText--) | Determina se la direzione del testo dell'intervallo di caratteri corrente è da sinistra a destra o da destra a sinistra. |
| [getSize()](#getSize--) | Specifica la dimensione del testo nel blocco di testo della forma. |
| [getStrikethru()](#getStrikethru--) | Specifica se il testo è formattato con barratura. |
| [getStyle()](#getStyle--) | Specifica la formattazione dei caratteri applicata a un intervallo di testo nel blocco di testo della forma. |
| [getUseVertical()](#getUseVertical--) | Determina se l'intervallo di caratteri è verticale o orizzontale. |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | Indica se il carattere è in grassetto. |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | Indica se il carattere ha doppia barratura. |
| [isDoubleUnderline()](#isDoubleUnderline--) | Indica se il carattere ha doppia sottolineatura. |
| [isItalic()](#isItalic--) | Indica se il carattere è in corsivo. |
| [isStrikethrough()](#isStrikethrough--) | Indica se il carattere è barrato. |
| [isSubscript()](#isSubscript--) | Indica se il carattere è pedice. |
| [isSuperscript()](#isSuperscript--) | Indica se il carattere è apice. |
| [isUnderline()](#isUnderline--) | Indica se il carattere è sottolineato. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | Per la descrizione di questa proprietà, vedere [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | Per la descrizione di questa proprietà, vedere [getCase()](../../com.aspose.diagram/char\#getCase--) |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | Per la descrizione di questa proprietà, vedere [getColor()](../../com.aspose.diagram/char\#getColor--) |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--) |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--) |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | Per la descrizione di questa proprietà, vedere [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--) |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--) |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/char\#getDel--) |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--) |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getFont()](../../com.aspose.diagram/char\#getFont--) |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | Per la descrizione di questa proprietà, vedere [getFontName()](../../com.aspose.diagram/char\#getFontName--) |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getFontScale()](../../com.aspose.diagram/char\#getFontScale--) |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getHighlight()](../../com.aspose.diagram/char\#getHighlight--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/char\#getIX--) |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getLangID()](../../com.aspose.diagram/char\#getLangID--) |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--) |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | Per la descrizione di questa proprietà, vedere [getLocale()](../../com.aspose.diagram/char\#getLocale--) |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | Per la descrizione di questa proprietà, vedere [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--) |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getOverline()](../../com.aspose.diagram/char\#getOverline--) |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | Per la descrizione di questa proprietà, vedere [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--) |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | Per la descrizione di questa proprietà, vedere [getPos()](../../com.aspose.diagram/char\#getPos--) |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getRTLText()](../../com.aspose.diagram/char\#getRTLText--) |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getSize()](../../com.aspose.diagram/char\#getSize--) |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--) |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | Per la descrizione di questa proprietà, vedere [getStyle()](../../com.aspose.diagram/char\#getStyle--) |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
```


Costruttore.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profonda di questa istanza.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


Specifica il numero ID del carattere utilizzato per formattare il testo contenente caratteri asiatici.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


Specifica il nome del carattere asiatico del carattere usato per formattare il testo. È utilizzato per Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


Determina il maiuscolo/minuscolo del testo di una forma.

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


Quando è contenuto in un elemento Char, l'elemento Color.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Determina il grado di trasparenza del colore del testo di un livello o di una forma, da 0 (completamente opaco) a 1 (completamente trasparente).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


Contiene il numero del font utilizzato per formattare il testo composto da caratteri di script complessi. Gli script complessi sono lingue i cui caratteri richiedono legature o modellazione, come le lingue da destra a sinistra (arabo, farsi, ebraico e urdu) e diverse lingue dell'Asia meridionale.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


Specifica il nome del carattere ComplexScript del carattere usato per formattare il testo. È utilizzato per Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


La dimensione del carattere usata per formattare il testo composto da caratteri di script complessi. Gli script complessi sono lingue i cui caratteri richiedono legature o modellazione, come le lingue da destra a sinistra (arabo, farsi, ebraico e urdu) e diverse lingue dell'Asia meridionale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


Specifica se l'intervallo di testo ha una doppia sottolineatura sotto di esso.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


Determina se il testo è formattato con doppia barratura.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


Specifica il numero ID del carattere usato per formattare il testo.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


Specifica il nome del carattere usato per formattare il testo. È utilizzato per Visio 2013

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


Specifica la larghezza del carattere.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


Specifica l'evidenziazione.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indica l'ID locale (LCID) della lingua in cui è stata inserita la formula della cella, il testo, la proprietà personalizzata o il commento. Per un elenco delle lingue supportate dalle applicazioni Microsoft Office e i relativi ID lingua, vedere l'elemento DocLangID.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


Specifica la quantità di spazio tra due o più caratteri. Lo spazio può essere aggiunto o sottratto in incrementi di 1/20 di punto.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


Specifica la localizzazione dell'intervallo di testo per scopi di correzione ortografica.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


Specifica se il testo della forma deve essere localizzato (tradotto in un'altra lingua).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


Specifica se il testo ha una linea sopra di esso.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


Specifica se un campo di testo appare perpendicolare al resto del testo in un blocco di testo.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


Specifica la posizione del testo della forma rispetto alla linea di base.

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


Determina se la direzione del testo dell'intervallo di caratteri corrente è da sinistra a destra o da destra a sinistra.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


Specifica la dimensione del testo nel blocco di testo della forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


Specifica se il testo è formattato con barratura.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


Specifica la formattazione dei caratteri applicata a un intervallo di testo nel blocco di testo della forma.

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


Determina se l'intervallo di caratteri è verticale o orizzontale.

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


Indica se il carattere è in grassetto.

**Returns:**
boolean
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


Indica se il carattere ha doppia barratura.

**Returns:**
boolean
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


Indica se il carattere ha doppia sottolineatura.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Indica se il carattere è in corsivo.

**Returns:**
boolean
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


Indica se il carattere è barrato.

**Returns:**
boolean
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Indica se il carattere è pedice.

**Returns:**
boolean
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Indica se il carattere è apice.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indica se il carattere è sottolineato.

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


Per la descrizione di questa proprietà, vedere [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


Per la descrizione di questa proprietà, vedere [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


Per la descrizione di questa proprietà, vedere [getCase()](../../com.aspose.diagram/char\#getCase--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


Per la descrizione di questa proprietà, vedere [getColor()](../../com.aspose.diagram/char\#getColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


Per la descrizione di questa proprietà, vedere [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


Per la descrizione di questa proprietà, vedere [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/char\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


Per la descrizione di questa proprietà, vedere [getFont()](../../com.aspose.diagram/char\#getFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


Per la descrizione di questa proprietà, vedere [getFontName()](../../com.aspose.diagram/char\#getFontName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/char\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


Per la descrizione di questa proprietà, vedere [getLangID()](../../com.aspose.diagram/char\#getLangID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


Per la descrizione di questa proprietà, vedere [getLocale()](../../com.aspose.diagram/char\#getLocale--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


Per la descrizione di questa proprietà, vedere [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getOverline()](../../com.aspose.diagram/char\#getOverline--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


Per la descrizione di questa proprietà, vedere [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


Per la descrizione di questa proprietà, vedere [getPos()](../../com.aspose.diagram/char\#getPos--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getSize()](../../com.aspose.diagram/char\#getSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


Per la descrizione di questa proprietà, vedere [getStyle()](../../com.aspose.diagram/char\#getStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

