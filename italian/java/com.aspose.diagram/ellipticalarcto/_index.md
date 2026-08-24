---
title: EllipticalArcTo
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che specificano informazioni su un arco ellittico.
type: docs
weight: 140
url: /it/java/com.aspose.diagram/ellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class EllipticalArcTo extends Coordinate
```

Contiene elementi che specificano informazioni su un arco ellittico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EllipticalArcTo()](#EllipticalArcTo--) | Crea un'istanza della classe [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | La coordinata x del punto di controllo dell'arco. |
| [getB()](#getB--) | La coordinata y del punto di controllo di un arco. |
| [getC()](#getC--) | L'angolo dell'asse maggiore di un arco rispetto all'asse x del suo genitore. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Il rapporto tra l'asse maggiore e l'asse minore di un arco. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getX()](#getX--) | La coordinata x del vertice finale di un arco ellittico. |
| [getY()](#getY--) | La coordinata y del vertice finale di un arco ellittico. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, consultare [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipticalArcTo() {#EllipticalArcTo--}
```
public EllipticalArcTo()
```


Crea un'istanza della classe [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


La coordinata x del punto di controllo dell'arco. Il punto di controllo è meglio posizionato circa a metà tra i vertici iniziale e finale dell'arco. Altrimenti, l'arco potrebbe ingrandirsi in modo estremo per passare attraverso il punto di controllo, con risultati imprevedibili.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


La coordinata y del punto di controllo di un arco.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


L'angolo dell'asse maggiore di un arco rispetto all'asse x del suo genitore.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


Il rapporto tra l'asse maggiore e l'asse minore di un arco. Nonostante il significato comune di questi termini, l'asse maggiore non deve necessariamente essere più grande dell'asse minore, quindi questo rapporto non deve necessariamente superare 1. Impostare questo elemento su un valore minore o uguale a 0 o maggiore di 1000 può portare a risultati imprevedibili.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


La coordinata x del vertice finale di un arco ellittico.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


La coordinata y del vertice finale di un arco ellittico.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Per la descrizione di questa proprietà, consultare [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--)

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

