---
title: Line
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che specificano informazioni generali di posizionamento su una forma.
type: docs
weight: 221
url: /it/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

Contiene elementi che specificano informazioni generali di posizionamento su una forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | Indica se una linea ha una punta di freccia o altro formato di estremità della linea al suo primo vertice. |
| [getBeginArrowSize()](#getBeginArrowSize--) | Determina la dimensione della punta di freccia all'inizio della linea. |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | Specifica il CompoundType della linea della forma. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getEndArrow()](#getEndArrow--) | Indica se una linea ha una punta di freccia o altro formato di estremità della linea all'ultimo vertice. |
| [getEndArrowSize()](#getEndArrowSize--) | Specifica la dimensione della punta di freccia alla fine della linea. |
| [getGradientLine()](#getGradientLine--) | Contiene i valori attuali di formattazione della linea gradiente per la forma |
| [getLineCap()](#getLineCap--) | Specifica se una linea ha estremità arrotondate o quadrate. |
| [getLineColor()](#getLineColor--) | Specifica il colore della linea della forma. |
| [getLineColorTrans()](#getLineColorTrans--) | Specifica il livello di trasparenza del colore della linea di una forma, da 0 (opaco) a 1 (completamente trasparente). |
| [getLinePattern()](#getLinePattern--) | Specifica il modello di linea della forma |
| [getLineWeight()](#getLineWeight--) | Specifica lo spessore della linea di una forma. |
| [getRounding()](#getRounding--) | Specifica il raggio dell'arco di arrotondamento applicato dove due segmenti contigui di un percorso si incontrano. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | Per la descrizione di questa proprietà, vedere [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | Per la descrizione di questa proprietà, vedere [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | Per la descrizione di questa proprietà, vedere [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | Per la descrizione di questa proprietà, vedere [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | Per la descrizione di questa proprietà, vedere [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | Per la descrizione di questa proprietà, vedere [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | Per la descrizione di questa proprietà, vedere [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


Indica se una linea ha una punta di freccia o altro formato di estremità della linea al suo primo vertice. Inserire un numero da 0 a 45 o la funzione USE con il nome di un'estremità di linea personalizzata.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


Determina la dimensione della punta della freccia all'inizio della linea. Inserisci un numero da 0 a 6.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


Specifica il CompoundType della linea della forma.

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


Indica se una linea ha una punta di freccia o altro formato di estremità della linea all'ultimo vertice.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


Specifica la dimensione della punta di freccia alla fine della linea.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


Contiene i valori attuali di formattazione della linea gradiente per la forma

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


Specifica se una linea ha estremità arrotondate o quadrate.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


Specifica il colore della linea della forma.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


Specifica il livello di trasparenza del colore della linea di una forma, da 0 (opaco) a 1 (completamente trasparente). Il valore predefinito è 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


Specifica il modello di linea della forma

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


Specifica lo spessore della linea di una forma. Lo spessore della linea è indipendente dalla scala del disegno. Se il disegno viene scalato, lo spessore della linea rimane invariato.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


Specifica il raggio dell'arco di arrotondamento applicato dove due segmenti contigui di un percorso si incontrano. Ad esempio, l'arrotondamento può essere usato per dare a un rettangolo angoli arrotondati.

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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


Per la descrizione di questa proprietà, vedere [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


Per la descrizione di questa proprietà, vedere [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


Per la descrizione di questa proprietà, vedere [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


Per la descrizione di questa proprietà, vedere [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


Per la descrizione di questa proprietà, vedere [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


Per la descrizione di questa proprietà, vedere [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


Per la descrizione di questa proprietà, vedere [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


Per la descrizione di questa proprietà, vedere [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


Per la descrizione di questa proprietà, vedere [getRounding()](../../com.aspose.diagram/line\#getRounding--)

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

