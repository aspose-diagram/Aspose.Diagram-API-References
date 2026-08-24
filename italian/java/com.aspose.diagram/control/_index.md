---
title: Controllo
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi per le coordinate x e y di ciascuna maniglia di controllo definita per una forma e elementi che specificano il modo in cui la maniglia di controllo deve comportarsi.
type: docs
weight: 87
url: /it/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

Contiene elementi per le coordinate x e y di ogni maniglia di controllo definita per una forma, e elementi che specificano il modo in cui la maniglia di controllo dovrebbe comportarsi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Control()](#Control--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canGlue()](#canGlue--) | Determina se una maniglia di controllo può essere incollata ad altre forme. |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getPrompt()](#getPrompt--) | L'elemento Prompt specifica il testo descrittivo che appare come suggerimento quando il puntatore del mouse è fermo sopra la maniglia di controllo di una forma. |
| [getX()](#getX--) | La coordinata x che indica la posizione della maniglia di controllo di una forma. |
| [getXCon()](#getXCon--) | Specifica il tipo di comportamento che la coordinata x della maniglia di controllo presenta dopo che la maniglia è stata spostata. |
| [getXDyn()](#getXDyn--) | Specifica la coordinata x per il punto di ancoraggio di una maniglia di controllo in coordinate locali. |
| [getY()](#getY--) | La coordinata y che indica la posizione della maniglia di controllo di una forma. |
| [getYCon()](#getYCon--) | Specifica il tipo di comportamento che la coordinata x della maniglia di controllo presenta dopo che la maniglia è stata spostata. |
| [getYDyn()](#getYDyn--) | Specifica la coordinata y per il punto di ancoraggio di una maniglia di controllo in coordinate locali. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, consultare [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | Per la descrizione di questa proprietà, consultare [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | Per la descrizione di questa proprietà, consultare [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | Per la descrizione di questa proprietà, consultare [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


Costruttore.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


Determina se una maniglia di controllo può essere incollata ad altre forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Il nome dell'elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Il nome universale dell'elemento.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


L'elemento Prompt specifica il testo descrittivo che appare come suggerimento quando il puntatore del mouse è fermo sopra la maniglia di controllo di una forma.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


La coordinata x che indica la posizione della maniglia di controllo di una forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


Specifica il tipo di comportamento che la coordinata x della maniglia di controllo presenta dopo che la maniglia è stata spostata.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


Specifica la coordinata x del punto di ancoraggio di una maniglia di controllo in coordinate locali. Il punto di ancoraggio è usato per il rubber-banding durante le dinamiche.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


La coordinata y che indica la posizione della maniglia di controllo di una forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


Specifica il tipo di comportamento che la coordinata x della maniglia di controllo presenta dopo che la maniglia è stata spostata.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


Specifica la coordinata y del punto di ancoraggio di una maniglia di controllo in coordinate locali. Il punto di ancoraggio è usato per il rubber-banding durante le dinamiche.

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


Per la descrizione di questa proprietà, consultare [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, consultare [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, consultare [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


Per la descrizione di questa proprietà, consultare [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


Per la descrizione di questa proprietà, consultare [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


Per la descrizione di questa proprietà, consultare [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

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

