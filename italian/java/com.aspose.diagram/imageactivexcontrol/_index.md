---
title: ImageActiveXControl
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta il controllo immagine.
type: docs
weight: 197
url: /it/java/com.aspose.diagram/imageactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ImageActiveXControl extends ActiveXControl
```

Rappresenta il controllo immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | il colore OLE dello sfondo. |
| [getBorderOleColor()](#getBorderOleColor--) | il colore OLE dello sfondo. |
| [getBorderStyle()](#getBorderStyle--) | il tipo di bordo usato dal controllo. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | i dati binari del controllo. |
| [getForeOleColor()](#getForeOleColor--) | il colore OLE del primo piano. |
| [getHeight()](#getHeight--) | l'altezza del controllo in unità di punti. |
| [getIMEMode()](#getIMEMode--) | la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco. |
| [getMouseIcon()](#getMouseIcon--) | un'icona personalizzata da visualizzare come puntatore del mouse per il controllo. |
| [getMousePointer()](#getMousePointer--) | il tipo di icona visualizzata come puntatore del mouse per il controllo. |
| [getPicture()](#getPicture--) | i dati dell'immagine. |
| [getPictureAlignment()](#getPictureAlignment--) | l'allineamento dell'immagine all'interno del Form o dell'Image. |
| [getPictureSizeMode()](#getPictureSizeMode--) | come visualizzare l'immagine. |
| [getSpecialEffect()](#getSpecialEffect--) | l'effetto speciale del controllo. |
| [getType()](#getType--) | Ottiene il tipo del controllo ActiveX. |
| [getWidth()](#getWidth--) | la larghezza del controllo in unità di punti. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indica se il controllo ridimensionerà automaticamente per visualizzare tutto il contenuto. |
| [isEnabled()](#isEnabled--) | Indica se il controllo può ricevere il focus e rispondere agli eventi generati dall'utente. |
| [isLocked()](#isLocked--) | Indica se i dati nel controllo sono bloccati per la modifica. |
| [isTiled()](#isTiled--) | Indica se l'immagine è ripetuta sullo sfondo. |
| [isTransparent()](#isTransparent--) | Indica se il controllo è trasparente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Per la descrizione di questa proprietà, vedere [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Per la descrizione di questa proprietà, vedere [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Per la descrizione di questa proprietà, vedere [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Per la descrizione di questa proprietà, vedere [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Per la descrizione di questa proprietà, vedere [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Per la descrizione di questa proprietà, vedere [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | Per la descrizione di questa proprietà, vedere [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--) |
| [setPictureAlignment(int value)](#setPictureAlignment-int-) | Per la descrizione di questa proprietà, vedere [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--) |
| [setPictureSizeMode(int value)](#setPictureSizeMode-int-) | Per la descrizione di questa proprietà, vedere [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Per la descrizione di questa proprietà, vedere [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--) |
| [setTiled(boolean value)](#setTiled-boolean-) | Per la descrizione di questa proprietà, vedere [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Per la descrizione di questa proprietà, vedere [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


il colore OLE dello sfondo.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


il colore OLE dello sfondo.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


il tipo di bordo usato dal controllo.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


i dati binari del controllo.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


Il colore OLE del primo piano. Non si applica al controllo Image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


l'altezza del controllo in unità di punti.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


un'icona personalizzata da visualizzare come puntatore del mouse per il controllo.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


il tipo di icona visualizzata come puntatore del mouse per il controllo.

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


i dati dell'immagine.

**Returns:**
byte[]
### getPictureAlignment() {#getPictureAlignment--}
```
public int getPictureAlignment()
```


l'allineamento dell'immagine all'interno del Form o dell'Image.

**Returns:**
int
### getPictureSizeMode() {#getPictureSizeMode--}
```
public int getPictureSizeMode()
```


come visualizzare l'immagine.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


l'effetto speciale del controllo.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Ottiene il tipo del controllo ActiveX.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


la larghezza del controllo in unità di punti.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


Indica se il controllo ridimensionerà automaticamente per visualizzare tutto il contenuto.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Indica se il controllo può ricevere il focus e rispondere agli eventi generati dall'utente.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Indica se i dati nel controllo sono bloccati per la modifica.

**Returns:**
boolean
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Indica se l'immagine è ripetuta sullo sfondo.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indica se il controllo è trasparente.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Per la descrizione di questa proprietà, vedere [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Per la descrizione di questa proprietà, vedere [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Per la descrizione di questa proprietà, vedere [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Per la descrizione di questa proprietà, vedere [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Per la descrizione di questa proprietà, vedere [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Per la descrizione di questa proprietà, vedere [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Per la descrizione di questa proprietà, vedere [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Per la descrizione di questa proprietà, vedere [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


Per la descrizione di questa proprietà, vedere [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setPictureAlignment(int value) {#setPictureAlignment-int-}
```
public void setPictureAlignment(int value)
```


Per la descrizione di questa proprietà, vedere [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPictureSizeMode(int value) {#setPictureSizeMode-int-}
```
public void setPictureSizeMode(int value)
```


Per la descrizione di questa proprietà, vedere [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Per la descrizione di questa proprietà, vedere [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTiled(boolean value) {#setTiled-boolean-}
```
public void setTiled(boolean value)
```


Per la descrizione di questa proprietà, vedere [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Per la descrizione di questa proprietà, vedere [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

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

