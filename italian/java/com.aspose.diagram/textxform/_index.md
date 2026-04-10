---
title: TextXForm
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che specificano le informazioni di posizionamento relative al blocco di testo di una forma.
type: docs
weight: 405
url: /it/java/com.aspose.diagram/textxform/
---

**Inheritance:**
java.lang.Object
```
public class TextXForm
```

Contiene elementi che specificano le informazioni di posizionamento del blocco di testo di una forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getTxtAngle()](#getTxtAngle--) | Specifica l'angolo di rotazione corrente del blocco di testo in relazione all'asse x della forma. |
| [getTxtHeight()](#getTxtHeight--) | Specifica l'altezza del blocco di testo. |
| [getTxtLocPinX()](#getTxtLocPinX--) | Specifica la coordinata x del centro di rotazione del blocco di testo in relazione all'origine del blocco di testo. |
| [getTxtLocPinY()](#getTxtLocPinY--) | Specifica la coordinata y del centro di rotazione del blocco di testo rispetto all'origine del blocco di testo. |
| [getTxtPinX()](#getTxtPinX--) | Specifica la coordinata x del centro di rotazione del blocco di testo in relazione all'origine della forma. |
| [getTxtPinY()](#getTxtPinY--) | Specifica la coordinata y del centro di rotazione del blocco di testo in relazione all'origine della forma. |
| [getTxtWidth()](#getTxtWidth--) | Specifica la larghezza del blocco di testo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/textxform\#getDel--) |
| [setTxtAngle(DoubleValue value)](#setTxtAngle-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--) |
| [setTxtHeight(DoubleValue value)](#setTxtHeight-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--) |
| [setTxtLocPinX(DoubleValue value)](#setTxtLocPinX-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--) |
| [setTxtLocPinY(DoubleValue value)](#setTxtLocPinY-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--) |
| [setTxtPinX(DoubleValue value)](#setTxtPinX-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--) |
| [setTxtPinY(DoubleValue value)](#setTxtPinY-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--) |
| [setTxtWidth(DoubleValue value)](#setTxtWidth-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getTxtAngle() {#getTxtAngle--}
```
public DoubleValue getTxtAngle()
```


Specifica l'angolo di rotazione corrente del blocco di testo in relazione all'asse x della forma. Il valore predefinito è 0 gradi.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtHeight() {#getTxtHeight--}
```
public DoubleValue getTxtHeight()
```


Specifica l'altezza del blocco di testo. La formula predefinita, che restituisce l'altezza della forma, è F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinX() {#getTxtLocPinX--}
```
public DoubleValue getTxtLocPinX()
```


Specifica la coordinata x del centro di rotazione del blocco di testo in relazione all'origine del blocco di testo. La formula predefinita, che restituisce il centro orizzontale del blocco di testo, è F="TxtWidth\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinY() {#getTxtLocPinY--}
```
public DoubleValue getTxtLocPinY()
```


Specifica la coordinata y del centro di rotazione del blocco di testo rispetto all'origine del blocco di testo. La formula predefinita, che restituisce il centro verticale del blocco di testo, è F="TxtHeight\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinX() {#getTxtPinX--}
```
public DoubleValue getTxtPinX()
```


Specifica la coordinata x del centro di rotazione del blocco di testo in relazione all'origine della forma. La formula predefinita, che restituisce il centro orizzontale della forma, è F="Width\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinY() {#getTxtPinY--}
```
public DoubleValue getTxtPinY()
```


Specifica la coordinata y del centro di rotazione del blocco di testo in relazione all'origine della forma. La formula predefinita, che restituisce il centro verticale della forma, è F="Height\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtWidth() {#getTxtWidth--}
```
public DoubleValue getTxtWidth()
```


Specifica la larghezza del blocco di testo. La formula predefinita, che restituisce la larghezza della forma, è F="Width\*1".

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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/textxform\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTxtAngle(DoubleValue value) {#setTxtAngle-com.aspose.diagram.DoubleValue-}
```
public void setTxtAngle(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtHeight(DoubleValue value) {#setTxtHeight-com.aspose.diagram.DoubleValue-}
```
public void setTxtHeight(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinX(DoubleValue value) {#setTxtLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinX(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinY(DoubleValue value) {#setTxtLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinY(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinX(DoubleValue value) {#setTxtPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinX(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinY(DoubleValue value) {#setTxtPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinY(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtWidth(DoubleValue value) {#setTxtWidth-com.aspose.diagram.DoubleValue-}
```
public void setTxtWidth(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--)

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

