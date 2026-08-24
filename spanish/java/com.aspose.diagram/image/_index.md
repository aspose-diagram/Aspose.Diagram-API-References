---
title: Imagen
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene los valores de gamma, brillo, contraste, desenfoque, nitidez, reducción de ruido y transparencia para un mapa de bits.
type: docs
weight: 196
url: /es/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Contiene los valores de gamma, brillo, contraste, desenfoque, nitidez, reducción de ruido y transparencia para un mapa de bits.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Desenfoca o suaviza una imagen de mapa de bits. |
| [getBrightness()](#getBrightness--) | Ajusta el brillo de una imagen de mapa de bits. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Especifica el contraste de una imagen de mapa de bits. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento ha sido eliminado localmente. |
| [getDenoise()](#getDenoise--) | Elimina el ruido (píxeles que tienen niveles de color distribuidos aleatoriamente) de una imagen de mapa de bits. |
| [getGamma()](#getGamma--) | Ajusta o corrige la intensidad de una imagen para un dispositivo de salida particular, como un monitor o escáner. |
| [getSharpen()](#getSharpen--) | Especifica la cantidad de nitidez a aplicar a una imagen de mapa de bits. |
| [getTransparency()](#getTransparency--) | Especifica el nivel de transparencia para un color de capa, de 0 (opaco) a 1 (completamente transparente). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, por favor vea [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Desenfoca o suaviza una imagen de mapa de bits. El elemento Blur contiene un valor entre 0 y 1; el valor predeterminado es 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Ajusta el brillo de una imagen de mapa de bits. El elemento Brightness contiene un valor entre 0 y 1; el valor predeterminado es 0.5.

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


Especifica el contraste de una imagen de mapa de bits. El elemento Contrast contiene un valor entre 0 y 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento ha sido eliminado localmente. Un valor de 1 indica que el elemento fue eliminado localmente.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Elimina el ruido (píxeles que tienen niveles de color distribuidos aleatoriamente) de una imagen de mapa de bits.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Ajusta o corrige la intensidad de una imagen para un dispositivo de salida particular, como un monitor o escáner. El valor predeterminado es 1 (sin corrección.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Especifica la cantidad de nitidez a aplicar a una imagen de mapa de bits. Enfocar una imagen aumenta el contraste de los píxeles adyacentes.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Especifica el nivel de transparencia para un color de capa, de 0 (opaco) a 1 (completamente transparente).

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


Para la descripción de esta propiedad, por favor vea [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

