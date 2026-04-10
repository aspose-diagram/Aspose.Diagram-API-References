---
title: Para
second_title: Riferimento API di Aspose.Diagram per Java
description: Contains the paragraph formatting elements for the shapes text such as indents line spacing bullets and horizontal alignment of paragraphs.
type: docs
weight: 274
url: /it/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

Contiene gli elementi di formattazione del paragrafo per il testo della forma, come rientri, interlinea, elenchi puntati e allineamento orizzontale dei paragrafi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Para()](#Para--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | Determina lo stile del punto elenco. |
| [getBulletFont()](#getBulletFont--) | Represents the number of the font used to format the text when a custom bullet string is specified and the value in the Bullet element is non-zero. |
| [getBulletFontSize()](#getBulletFontSize--) | Specifies the size of a bullet. |
| [getBulletStr()](#getBulletStr--) | "Used to create a custom bullet style. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getFlags()](#getFlags--) | Indicates whether the text direction is left to right or right to left. |
| [getHorzAlign()](#getHorzAlign--) | Specifica l'allineamento orizzontale del testo nel blocco di testo della forma. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getIndFirst()](#getIndFirst--) | Specifies the distance the first line of each paragraph in the shape's text block is indented from the left indent of the paragraph. |
| [getIndLeft()](#getIndLeft--) | Specifies the distance all lines of text in a paragraph are indented from the left margin of the text block. |
| [getIndRight()](#getIndRight--) | Specifica la distanza di rientro di tutte le linee di testo in un paragrafo dal margine destro del blocco di testo. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | Specifica se il carattere del punto elenco deve essere localizzato (tradotto in un'altra lingua). |
| [getSpAfter()](#getSpAfter--) | Specifica la quantità di spazio inserita dopo ogni paragrafo nel blocco di testo della forma. |
| [getSpBefore()](#getSpBefore--) | Specifica la quantità di spazio inserita prima di ogni paragrafo nel blocco di testo della forma. |
| [getSpLine()](#getSpLine--) | Specifica la distanza tra una linea di testo e l'altra, dove il 100% corrisponde all'altezza di una linea di testo. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | Rappresenta la distanza tra la prima riga del paragrafo e il punto elenco. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | Per la descrizione di questa proprietà, consultare [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, consultare [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | Per la descrizione di questa proprietà, consultare [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, consultare [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | Per la descrizione di questa proprietà, consultare [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | Per la descrizione di questa proprietà, consultare [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


Determina lo stile del punto elenco.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


Represents the number of the font used to format the text when a custom bullet string is specified and the value in the Bullet element is non-zero.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


Specifies the size of a bullet.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"Utilizzato per creare uno stile di punto elenco personalizzato. Inserire lo stile come stringa (tra virgolette). Ad esempio, è possibile inserire la stringa, \"\"ooo.\"\""

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


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


Indicates whether the text direction is left to right or right to left.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


Specifica l'allineamento orizzontale del testo nel blocco di testo della forma.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


Specifica la distanza di rientro della prima riga di ogni paragrafo nel blocco di testo della forma dall'indentazione sinistra del paragrafo. Questo valore è indipendente dalla scala del disegno. Se il disegno è scalato, l'indentazione della prima riga rimane invariata.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


Specifica la distanza di rientro di tutte le linee di testo in un paragrafo dal margine sinistro del blocco di testo. Questo valore è indipendente dalla scala del disegno. Se il disegno è scalato, l'indentazione sinistra rimane invariata.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


Specifica la distanza di rientro di tutte le righe di testo in un paragrafo dal margine destro del blocco di testo. Questo valore è indipendente dalla scala del disegno. Se il disegno è scalato, il rientro destro rimane lo stesso.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


Specifica se il carattere del punto elenco deve essere localizzato (tradotto in un'altra lingua).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


Specifica la quantità di spazio inserita dopo ogni paragrafo nel blocco di testo della forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


Specifica la quantità di spazio inserita prima di ogni paragrafo nel blocco di testo della forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


Specifica la distanza tra una linea di testo e l'altra, dove il 100% corrisponde all'altezza di una linea di testo.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


Rappresenta la distanza tra la prima riga del paragrafo e il punto elenco.

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


Per la descrizione di questa proprietà, consultare [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


Per la descrizione di questa proprietà, consultare [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


Per la descrizione di questa proprietà, consultare [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


Per la descrizione di questa proprietà, consultare [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


Per la descrizione di questa proprietà, consultare [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


Per la descrizione di questa proprietà, consultare [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

**Parameters:**
| Parametro | Tipo | Descrizione |
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

