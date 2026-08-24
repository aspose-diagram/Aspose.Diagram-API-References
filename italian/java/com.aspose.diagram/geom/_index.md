---
title: Geom
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che specificano le coordinate dei vertici per le linee e gli archi che compongono la forma.
type: docs
weight: 169
url: /it/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

Contiene elementi che specificano le coordinate dei vertici per le linee e gli archi che compongono la forma. Se la forma ha più di un percorso, esiste un elemento Geom per ciascun percorso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Geom()](#Geom--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | Raccolta di coordinate. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | Restituisce il valore IX per il prossimo membro della raccolta di coordinate della forma. |
| [getNoFill()](#getNoFill--) | Specifica se un percorso può essere riempito. |
| [getNoLine()](#getNoLine--) | Specifica se una linea è disegnata attorno al contorno del percorso. |
| [getNoQuickDrag()](#getNoQuickDrag--) | Determina se una forma può essere selezionata o trascinata quando l'utente fa clic sull'area riempita definita dalla sezione Geometry. |
| [getNoShow()](#getNoShow--) | Specifica se un percorso è visualizzato nella pagina di disegno. |
| [getNoSnap()](#getNoSnap--) | Specifica se altre forme si agganciano a un percorso. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


Raccolta di coordinate. Mostra la sequenza di coordinate.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
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
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


Restituisce il valore IX per il prossimo membro della raccolta di coordinate della forma.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


Specifica se un percorso può essere riempito.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


Specifica se una linea è disegnata attorno al contorno del percorso.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


Determina se una forma può essere selezionata o trascinata quando l'utente fa clic sull'area riempita definita dalla sezione Geometry.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


Specifica se un percorso è visualizzato nella pagina di disegno.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


Specifica se altre forme si agganciano a un percorso.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

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

