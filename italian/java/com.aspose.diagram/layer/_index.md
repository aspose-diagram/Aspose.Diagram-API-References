---
title: Layer
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che definiscono un singolo livello e le sue proprietà per una pagina.
type: docs
weight: 212
url: /it/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Contiene elementi che definiscono un singolo livello e le sue proprietà per una pagina.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Layer()](#Layer--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Specifica se un livello è attivo. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | L'indice del colore nella tavola dei colori usato per visualizzare il livello o un valore RGB che specifica un colore personalizzato non presente nella tavola dei colori (ad esempio, \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Determina il grado di trasparenza del colore del testo di un livello o di una forma, da 0 (completamente opaco) a 1 (completamente trasparente). |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getGlue()](#getGlue--) | Specifica se le forme appartenenti al livello possono essere incollate. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getLock()](#getLock--) | Specifica se le forme appartenenti al livello sono bloccate dalla selezione o dalla modifica. |
| [getName()](#getName--) | L'elemento Name specifica il nome di un livello. |
| [getNameUniv()](#getNameUniv--) | Specifica il nome universale di un livello. |
| [getPrint()](#getPrint--) | Specifica se le forme appartenenti al livello vengono stampate quando il disegno è stampato. |
| [getSnap()](#getSnap--) | Specifica se altre forme possono agganciarsi alle forme assegnate al livello. |
| [getStatus()](#getStatus--) | Specifica se il livello è un livello valido per un documento. |
| [getVisible()](#getVisible--) | Specifica se le forme appartenenti al livello sono visibili nella pagina del disegno. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Un flag che indica se l'elemento è stato controllato localmente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Per la descrizione di questa proprietà, vedere [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Costruttore.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Specifica se un livello è attivo. Le forme che non sono preassegnate ai livelli vengono assegnate al(i) livello(i) attivo(i) quando vengono rilasciate sulla pagina del disegno.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


L'indice del colore nella tavola dei colori usato per visualizzare il livello o un valore RGB che specifica un colore personalizzato non presente nella tavola dei colori (ad esempio, \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Determina il grado di trasparenza del colore del testo di un livello o di una forma, da 0 (completamente opaco) a 1 (completamente trasparente).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Specifica se le forme appartenenti al livello possono essere incollate.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Specifica se le forme appartenenti al livello sono bloccate dalla selezione o dalla modifica.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


L'elemento Name specifica il nome di un livello.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Specifica il nome universale di un livello.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Specifica se le forme appartenenti al livello vengono stampate quando il disegno è stampato.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Specifica se altre forme possono agganciarsi alle forme assegnate al livello. Le forme assegnate al livello possono agganciarsi ad altre forme, ma le altre forme non possono agganciarsi a esse.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Specifica se il livello è un livello valido per un documento.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Specifica se le forme appartenenti al livello sono visibili nella pagina del disegno.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Un flag che indica se l'elemento è stato controllato localmente. Un valore di 1 indica che l'elemento è stato controllato localmente.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Per la descrizione di questa proprietà, vedere [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/layer\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

