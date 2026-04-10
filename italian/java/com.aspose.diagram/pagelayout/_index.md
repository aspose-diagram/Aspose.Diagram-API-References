---
title: PageLayout
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene celle che controllano le impostazioni di layout della pagina per forme e connettori, come la spaziatura tra tutte le forme nella pagina, la spaziatura tra tutti i connettori nella pagina e lo stile di instradamento per tutti i connettori nella pagina.
type: docs
weight: 263
url: /it/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Contiene celle che controllano le impostazioni di layout della pagina per forme e connettori, come la spaziatura tra tutte le forme sulla pagina, la spaziatura tra tutti i connettori sulla pagina e lo stile di instradamento per tutti i connettori sulla pagina.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Determina la quantità di spazio verticale tra le forme nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Determina la quantità di spazio verticale tra le forme nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Specifica come le forme vengono posizionate sulla pagina quando le forme sono disposte dopo che l'utente seleziona Lay Out Shapes (menu Forma). |
| [getBlockSizeX()](#getBlockSizeX--) | Determina la dimensione del blocco verticale, l'area in cui ciascuna delle tue forme deve adattarsi nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno. |
| [getBlockSizeY()](#getBlockSizeY--) | Determina la quantità di spazio orizzontale tra le forme nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Determina quale forma è il genitore quando si utilizzano forme tramite maniglie di controllo. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDynamicsOff()](#getDynamicsOff--) | Specifica se le forme posizionabili si spostano e i connettori vengono riorientati attorno ad altre forme e connettori nella pagina di disegno. |
| [getEnableGrid()](#getEnableGrid--) | Specifica se Microsoft Visio dispone le forme basandosi su una griglia interna della pagina quando l'utente seleziona Disposizione forme (menu Forma). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Specifica quali connettori dinamici separare se si sovrappongono. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Specifica quali connettori dinamici allineare uno sopra l'altro se si sovrappongono. |
| [getLineJumpCode()](#getLineJumpCode--) | Specifica lo stile di salto di linea per tutti i connettori sulla pagina di disegno che non hanno uno stile di salto di linea locale. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Specifica la dimensione dei salti di linea sui segmenti orizzontali dei connettori dinamici nella pagina, come percentuale del valore dell'elemento LineToLineX (che specifica lo spazio orizzontale tra tutti i connettori nella pagina di disegno). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Specifica la dimensione dei salti di linea sui segmenti verticali dei connettori dinamici nella pagina, come percentuale del valore dell'elemento LineToLineY (che specifica lo spazio verticale tra tutti i connettori nella pagina di disegno). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Specifica la direzione dei salti di linea sui segmenti orizzontali dei connettori dinamici nella pagina di disegno per i quali non è stata applicata una direzione locale del salto. |
| [getLineRouteExt()](#getLineRouteExt--) | Specifica l'aspetto predefinito per tutti i connettori su una pagina. |
| [getLineToLineX()](#getLineToLineX--) | Specifica lo spazio orizzontale minimo tra i connettori dinamici nella pagina di disegno. |
| [getLineToLineY()](#getLineToLineY--) | Specifica lo spazio verticale minimo tra i connettori dinamici nella pagina di disegno. |
| [getLineToNodeX()](#getLineToNodeX--) | Specifica lo spazio verticale minimo tra i connettori dinamici e le forme nella pagina di disegno. |
| [getLineToNodeY()](#getLineToNodeY--) | Determina la dimensione del blocco orizzontale, l'area in cui ciascuna delle tue forme deve adattarsi nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Specifica la direzione dei salti di linea sui connettori dinamici verticali nella pagina di disegno per i quali non è stata applicata una direzione locale del salto. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Specifica lo spazio orizzontale minimo tra i connettori dinamici e le forme nella pagina di disegno. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Indica se le forme nella pagina possono essere divise automaticamente. |
| [getPlaceDepth()](#getPlaceDepth--) | Specifica se le forme posizionabili si allontanano quando l'utente trascina una forma posizionabile vicino a un'altra forma posizionabile nella pagina di disegno. |
| [getPlaceFlip()](#getPlaceFlip--) | Specifica come le forme posizionabili vengono capovolte e/o ruotate su una pagina quando le forme sono disposte usando il comando Lay Out Shapes in Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Specifica lo stile di instradamento e la direzione per tutti i connettori dinamici nella pagina di disegno che non hanno uno stile di instradamento locale. |
| [getPlowCode()](#getPlowCode--) | Determina i connettori dinamici a cui si desidera aggiungere salti. |
| [getResizePage()](#getResizePage--) | Specifica se ingrandire la pagina per includere il disegno dopo che l'utente seleziona Disposizione forme (menu Forme). |
| [getRouteStyle()](#getRouteStyle--) | Per un disegno disposto automaticamente, specifica il metodo con cui il disegno viene analizzato prima di creare il layout e determina il tipo di layout. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Determina la quantità di spazio verticale tra le forme nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Determina la quantità di spazio verticale tra le forme nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Specifica come le forme vengono posizionate sulla pagina quando le forme sono disposte dopo che l'utente seleziona Lay Out Shapes (menu Forma).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Determina la dimensione del blocco verticale, l'area in cui ciascuna delle tue forme deve adattarsi nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Determina la quantità di spazio orizzontale tra le forme nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Determina quale forma è il genitore quando si utilizzano forme tramite maniglie di controllo. Questo elemento imposta il comportamento per tutte le forme nella pagina di disegno.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Specifica se le forme posizionabili si spostano e i connettori vengono riorientati attorno ad altre forme e connettori nella pagina di disegno.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Specifica se Microsoft Visio dispone le forme basandosi su una griglia interna della pagina quando l'utente seleziona Disposizione forme (menu Forma).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Specifica quali connettori dinamici separare se si sovrappongono.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Specifica quali connettori dinamici allineare uno sopra l'altro se si sovrappongono.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Specifica lo stile di salto di linea per tutti i connettori sulla pagina di disegno che non hanno uno stile di salto di linea locale.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Specifica la dimensione dei salti di linea sui segmenti orizzontali dei connettori dinamici nella pagina, come percentuale del valore dell'elemento LineToLineX (che specifica lo spazio orizzontale tra tutti i connettori nella pagina di disegno). Il valore di questo elemento varia da 0 a 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Specifica la dimensione dei salti di linea sui segmenti verticali dei connettori dinamici nella pagina, come percentuale del valore dell'elemento LineToLineY (che specifica lo spazio verticale tra tutti i connettori nella pagina di disegno). Questo elemento può contenere un valore da 0 a 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Specifica la direzione dei salti di linea sui segmenti orizzontali dei connettori dinamici nella pagina di disegno per i quali non è stata applicata una direzione locale del salto.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Specifica l'aspetto predefinito per tutti i connettori su una pagina.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Specifica lo spazio orizzontale minimo tra i connettori dinamici nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Specifica lo spazio verticale minimo tra i connettori dinamici nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Specifica lo spazio verticale minimo tra i connettori dinamici e le forme nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Determina la dimensione del blocco orizzontale, l'area in cui ciascuna delle tue forme deve adattarsi nella pagina di disegno quando si utilizza Microsoft Visio per disporre le forme nella pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Specifica la direzione dei salti di linea sui connettori dinamici verticali nella pagina di disegno per i quali non è stata applicata una direzione locale del salto.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Specifica lo spazio orizzontale minimo tra i connettori dinamici e le forme nella pagina di disegno.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Indica se le forme nella pagina possono essere divise automaticamente.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Specifica se le forme posizionabili si allontanano quando l'utente trascina una forma posizionabile vicino a un'altra forma posizionabile nella pagina di disegno.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Specifies how placeable shapes flip and/or rotate on a page when shapes are laid out using the Lay Out Shapes command in Microsoft Visio. The following hexadecimal values are allowed.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Specifica lo stile di instradamento e la direzione per tutti i connettori dinamici nella pagina di disegno che non hanno uno stile di instradamento locale.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Determina i connettori dinamici a cui si desidera aggiungere salti.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Specifica se ingrandire la pagina per includere il disegno dopo che l'utente seleziona Disposizione forme (menu Forme).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Per un disegno disposto automaticamente, specifica il metodo con cui il disegno viene analizzato prima di creare il layout e determina il tipo di layout.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

