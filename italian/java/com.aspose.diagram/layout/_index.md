---
title: Layout
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che controllano il posizionamento delle forme e le impostazioni di instradamento dei connettori.
type: docs
weight: 215
url: /it/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Contiene elementi che controllano il posizionamento delle forme e le impostazioni di instradamento dei connettori.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Determina quando un connettore viene ricalcolato. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Determina se un connettore salta quando due connettori si incrociano, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Determina la direzione del salto di linea per i salti di linea che si verificano su un segmento orizzontale di un connettore dinamico. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Determina la direzione del salto di linea per i salti di linea che si verificano su un segmento verticale di un connettore dinamico. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Determina lo stile del salto di linea per i salti di linea su un connettore dinamico. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Determina l'aspetto di un connettore. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDisplayLevel()](#getDisplayLevel--) | Determina la fascia di livello di visualizzazione (l'intervallo relativo del raggruppamento Z-order) per la forma. |
| [getRelationships()](#getRelationships--) | Memorizza le relazioni tra contenitori, elenchi, callout e forme. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Specifica il comportamento di posizionamento per una forma posizionabile. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Specifica se le forme posizionabili possono essere collocate sopra una forma quando l'utente seleziona Lay Out Shapes (menu Shapes). |
| [getShapePermeableX()](#getShapePermeableX--) | Specifica se un connettore può percorrere orizzontalmente una forma. |
| [getShapePermeableY()](#getShapePermeableY--) | Specifica se un connettore può percorrere verticalmente una forma. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Specifica come una forma posizionabile si capovolge e/o ruota nella pagina quando l'utente seleziona Disposizione forme (menu Forme). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Determina lo stile di posizionamento per i figli. |
| [getShapePlowCode()](#getShapePlowCode--) | Specifica se una forma posizionabile si allontana quando trascini un'altra forma posizionabile vicino alla forma nella pagina di disegno. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Specifica lo stile di instradamento e la direzione per un connettore nella pagina di disegno. |
| [getShapeSplit()](#getShapeSplit--) | Determina se questa forma può dividere forme che sono divisibili. |
| [getShapeSplittable()](#getShapeSplittable--) | Determina se questa forma 1-D può essere divisa. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Per la descrizione di questa proprietà, vedere [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Determina quando un connettore viene ricalcolato.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Determina se un connettore salta quando due connettori si incrociano,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Determina la direzione del salto di linea per i salti di linea che si verificano su un segmento orizzontale di un connettore dinamico.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Determina la direzione del salto di linea per i salti di linea che si verificano su un segmento verticale di un connettore dinamico.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Determina lo stile del salto di linea per i salti di linea su un connettore dinamico.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Determina l'aspetto di un connettore.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Determina la fascia di livello di visualizzazione (l'intervallo relativo del raggruppamento Z-order) per la forma.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Memorizza le relazioni tra contenitori, elenchi, callout e forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Specifica il comportamento di posizionamento per una forma posizionabile.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Specifica se le forme posizionabili possono essere collocate sopra una forma quando l'utente seleziona Lay Out Shapes (menu Shapes).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Specifica se un connettore può percorrere orizzontalmente una forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Specifica se un connettore può percorrere verticalmente una forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Specifica come una forma posizionabile si capovolge e/o ruota nella pagina quando l'utente seleziona Disposizione forme (menu Forme).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Determina lo stile di posizionamento per i figli.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Specifica se una forma posizionabile si allontana quando trascini un'altra forma posizionabile vicino alla forma nella pagina di disegno.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Specifica lo stile di instradamento e la direzione per un connettore nella pagina di disegno.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Determina se questa forma può dividere forme che sono divisibili.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Determina se questa forma 1-D può essere divisa.

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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Per la descrizione di questa proprietà, vedere [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

