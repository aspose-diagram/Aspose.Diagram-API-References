---
title: Esterno
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che specificano la larghezza e l'altezza di un oggetto proveniente da un altro programma utilizzato in un documento Microsoft Visio.
type: docs
weight: 163
url: /it/java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Contiene elementi che specificano la larghezza e l'altezza di un oggetto proveniente da un altro programma utilizzato in un documento Microsoft Visio. Include anche elementi che specificano la distanza di offset dell'immagine dell'oggetto all'interno dei suoi bordi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getImgHeight()](#getImgHeight--) | Determina l'altezza dell'immagine dell'oggetto all'interno del suo bordo. |
| [getImgOffsetX()](#getImgOffsetX--) | Determina la distanza di spostamento orizzontale dell'oggetto dall'origine del suo bordo. |
| [getImgOffsetY()](#getImgOffsetY--) | Determina la distanza di spostamento verticale dell'oggetto dall'origine del suo bordo. |
| [getImgWidth()](#getImgWidth--) | Determina la larghezza dell'immagine dell'oggetto all'interno del suo bordo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/foreign\#getDel--) |
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
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


Determina l'altezza dell'immagine dell'oggetto all'interno del suo bordo. La formula predefinita è: F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


Determina la distanza di spostamento orizzontale dell'oggetto rispetto all'origine del bordo dell'oggetto. Il valore predefinito è 0; la formula predefinita è F="ImgWidth\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


Determina la distanza di spostamento verticale dell'oggetto rispetto all'origine del bordo dell'oggetto. Il valore predefinito è 0; la formula predefinita è F="ImgHeight\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


Determina la larghezza dell'immagine dell'oggetto all'interno del suo bordo. La formula predefinita è: F="Width\*1".

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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/foreign\#getDel--)

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

