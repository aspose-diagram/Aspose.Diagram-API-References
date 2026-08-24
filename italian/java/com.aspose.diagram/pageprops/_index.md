---
title: PageProps
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene celle che controllano gli attributi della pagina come larghezza, altezza e scala della pagina.
type: docs
weight: 268
url: /it/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Contiene celle che controllano gli attributi della pagina, come larghezza, altezza e scala della pagina.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Determina se la pagina di disegno si ridimensiona automaticamente per adattarsi al diagramma. |
| [getDrawingScale()](#getDrawingScale--) | Rappresenta il valore dell'unità di disegno nella scala di disegno corrente. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Specifica il tipo di scala di disegno da utilizzare per una pagina. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Specifica le dimensioni di disegno di una pagina. |
| [getInhibitSnap()](#getInhibitSnap--) | Specifica se le forme su una pagina in primo piano si agganciano ad altri oggetti sulla pagina e alle forme sulla pagina di sfondo. |
| [getPageHeight()](#getPageHeight--) | Specifica l'altezza della pagina in unità di disegno. |
| [getPageScale()](#getPageScale--) | Specifica il valore dell'unità di pagina predefinita nella scala di disegno corrente. |
| [getPageWidth()](#getPageWidth--) | Specifica la larghezza della pagina in unità di disegno. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Contiene un numero che specifica l'angolo della direzione obliqua quando viene applicato il tipo di ombra predefinito della pagina. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Specifica la distanza in unità di pagina di cui l'ombra proiettata di una forma è spostata orizzontalmente dalla forma. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Specifica la distanza in unità di pagina di cui l'ombra proiettata di una forma è spostata verticalmente dalla forma. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Specifica la percentuale per ingrandire o ridurre l'ombra di una forma. |
| [getShdwType()](#getShdwType--) | Indica il tipo di ombra predefinito per una pagina. |
| [getUIVisibility()](#getUIVisibility--) | Determina se il nome della pagina è esposto nell'interfaccia utente (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Determina se la pagina di disegno si ridimensiona automaticamente per adattarsi al diagramma.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Rappresenta il valore dell'unità di disegno nella scala di disegno corrente. La scala di disegno per la pagina è il rapporto dell'unità di pagina contenuta nell'elemento PageScale all'unità di disegno. Le unità di questo elemento determinano le unità di lunghezza predefinite (DL) per la pagina.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Specifica il tipo di scala di disegno da utilizzare per una pagina.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Specifica le dimensioni di disegno di una pagina.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Specifica se le forme su una pagina in primo piano si agganciano ad altri oggetti sulla pagina e alle forme sulla pagina di sfondo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Specifica l'altezza della pagina in unità di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Specifica il valore dell'unità di pagina predefinita nella scala di disegno corrente. La scala di disegno per la pagina è il rapporto dell'unità di pagina nell'elemento PageScale all'unità di disegno mostrata nell'elemento DrawingScale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Specifica la larghezza della pagina in unità di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Contiene un numero che specifica l'angolo della direzione obliqua quando viene applicato il tipo di ombra predefinito della pagina.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Specifica la distanza in unità di pagina di cui l'ombra proiettata di una forma è spostata orizzontalmente dalla forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Specifica la distanza in unità di pagina di cui l'ombra proiettata di una forma è spostata verticalmente dalla forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Specifica la percentuale per ingrandire o ridurre l'ombra di una forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Indica il tipo di ombra predefinito per una pagina.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Determina se il nome della pagina è esposto nell'interfaccia utente (UI). Un valore di uno indica che la pagina non è visibile; un valore di zero indica che la pagina è visibile.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

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

