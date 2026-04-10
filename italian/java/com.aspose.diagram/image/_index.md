---
title: Immagine
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene i valori di gamma, luminosità, contrasto, sfocatura, nitidezza, riduzione del rumore e trasparenza per un bitmap.
type: docs
weight: 196
url: /it/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Contiene i valori di gamma, luminosità, contrasto, sfocatura, nitidezza, riduzione del rumore e trasparenza per un bitmap.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Sfoca o ammorbidisce un'immagine bitmap. |
| [getBrightness()](#getBrightness--) | Regola la luminosità di un'immagine bitmap. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Specifica il contrasto di un'immagine bitmap. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDenoise()](#getDenoise--) | Rimuove il rumore (pixel con livelli di colore distribuiti casualmente) da un'immagine bitmap. |
| [getGamma()](#getGamma--) | Regola o corregge l'intensità di un'immagine per un particolare dispositivo di output, come un monitor o uno scanner. |
| [getSharpen()](#getSharpen--) | Specifica la quantità di nitidezza per un'immagine bitmap. |
| [getTransparency()](#getTransparency--) | Specifica il livello di trasparenza per il colore di un livello, da 0 (opaco) a 1 (completamente trasparente). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/image\#getDel--) |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Sfoca o ammorbidisce un'immagine bitmap. L'elemento Blur contiene un valore compreso tra 0 e 1; il valore predefinito è 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Regola la luminosità di un'immagine bitmap. L'elemento Brightness contiene un valore compreso tra 0 e 1; il valore predefinito è 0,5.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


Specifica il contrasto di un'immagine bitmap. L'elemento Contrast contiene un valore compreso tra 0 e 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Rimuove il rumore (pixel con livelli di colore distribuiti casualmente) da un'immagine bitmap.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Regola o corregge l'intensità di un'immagine per un particolare dispositivo di output, come un monitor o uno scanner. Il valore predefinito è 1 (nessuna correzione.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Specifica la quantità di nitidezza per un'immagine bitmap. La nitidezza di un'immagine la mette a fuoco aumentando il contrasto dei pixel adiacenti.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Specifica il livello di trasparenza per il colore di un livello, da 0 (opaco) a 1 (completamente trasparente).

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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/image\#getDel--)

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

