---
title: Image
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient les valeurs de gamma, luminosité, contraste, flou, netteté, réduction du bruit et transparence pour un bitmap.
type: docs
weight: 196
url: /fr/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Contient les valeurs de gamma, de luminosité, de contraste, de flou, d’accentuation, de débruitage et de transparence d’un bitmap.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Floute ou adoucit une image bitmap. |
| [getBrightness()](#getBrightness--) | Ajuste la luminosité d'une image bitmap. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Spécifie le contraste d'une image bitmap. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDenoise()](#getDenoise--) | Supprime le bruit (pixels dont les niveaux de couleur sont distribués aléatoirement) d'une image bitmap. |
| [getGamma()](#getGamma--) | Ajuste ou corrige l'intensité d'une image pour un dispositif de sortie particulier, tel qu'un moniteur ou un scanner. |
| [getSharpen()](#getSharpen--) | Spécifie le degré de netteté d'une image bitmap. |
| [getTransparency()](#getTransparency--) | Spécifie le niveau de transparence d'une couleur de calque, de 0 (opaque) à 1 (complètement transparent). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Floute ou adoucit une image bitmap. L'élément Blur contient une valeur comprise entre 0 et 1 ; la valeur par défaut est 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Ajuste la luminosité d'une image bitmap. L'élément Brightness contient une valeur comprise entre 0 et 1 ; la valeur par défaut est 0,5.

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


Spécifie le contraste d'une image bitmap. L'élément Contrast contient une valeur comprise entre 0 et 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Supprime le bruit (pixels dont les niveaux de couleur sont distribués aléatoirement) d'une image bitmap.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Ajuste ou corrige l'intensité d'une image pour un dispositif de sortie particulier, tel qu'un moniteur ou un scanner. La valeur par défaut est 1 (pas de correction.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Spécifie le degré de netteté d'une image bitmap. Le renforcement de la netteté d'une image la rend plus nette en augmentant le contraste des pixels adjacents.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Spécifie le niveau de transparence d'une couleur de calque, de 0 (opaque) à 1 (complètement transparent).

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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

