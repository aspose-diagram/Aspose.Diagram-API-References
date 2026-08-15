---
title: ImageActiveXControl
second_title: Aspose.Diagram för Java API-referens
description: Representerar bildkontrollen.
type: docs
weight: 197
url: /sv/java/com.aspose.diagram/imageactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ImageActiveXControl extends ActiveXControl
```

Representerar bildkontrollen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | ole-färgen för bakgrunden. |
| [getBorderOleColor()](#getBorderOleColor--) | ole-färgen för bakgrunden. |
| [getBorderStyle()](#getBorderStyle--) | typen av ram som används av kontrollen. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | den binära datan för kontrollen. |
| [getForeOleColor()](#getForeOleColor--) | ole-färgen för förgrunden. |
| [getHeight()](#getHeight--) | höjden på kontrollen i enheter av punkter. |
| [getIMEMode()](#getIMEMode--) | standardkörningsläget för Input Method Editor för kontrollen när den får fokus. |
| [getMouseIcon()](#getMouseIcon--) | en anpassad ikon som visas som muspekare för kontrollen. |
| [getMousePointer()](#getMousePointer--) | typen av ikon som visas som muspekare för kontrollen. |
| [getPicture()](#getPicture--) | Bildens data. |
| [getPictureAlignment()](#getPictureAlignment--) | justeringen av bilden inuti Form eller Image. |
| [getPictureSizeMode()](#getPictureSizeMode--) | hur man visar bilden. |
| [getSpecialEffect()](#getSpecialEffect--) | den speciella effekten för kontrollen. |
| [getType()](#getType--) | Hämtar typen av ActiveX-kontrollen. |
| [getWidth()](#getWidth--) | kontrollens bredd i enheten punkt. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indikerar om kontrollen automatiskt kommer att ändra storlek för att visa hela innehållet. |
| [isEnabled()](#isEnabled--) | Indikerar om kontrollen kan ta emot fokus och svara på händelser som genereras av användaren. |
| [isLocked()](#isLocked--) | Indikerar om data i kontrollen är låst för redigering. |
| [isTiled()](#isTiled--) | Anger om bilden är kaklad över bakgrunden. |
| [isTransparent()](#isTransparent--) | Indikerar om kontrollen är transparent. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | För beskrivningen av den här egenskapen, se [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | För beskrivningen av denna egenskap, se [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | För beskrivningen av den här egenskapen, se [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | För beskrivningen av den här egenskapen, se [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | För beskrivningen av den här egenskapen, se [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | För beskrivningen av den här egenskapen, se [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | För beskrivningen av den här egenskapen, se [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | För beskrivningen av den här egenskapen, se [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | För beskrivningen av den här egenskapen, se [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | För beskrivningen av den här egenskapen, se [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--) |
| [setPictureAlignment(int value)](#setPictureAlignment-int-) | För beskrivningen av den här egenskapen, se [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--) |
| [setPictureSizeMode(int value)](#setPictureSizeMode-int-) | För beskrivningen av den här egenskapen, se [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | För beskrivningen av den här egenskapen, se [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--) |
| [setTiled(boolean value)](#setTiled-boolean-) | För beskrivningen av den här egenskapen, se [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | För beskrivningen av den här egenskapen, se [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | För beskrivningen av den här egenskapen, se [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


ole-färgen för bakgrunden.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


ole-färgen för bakgrunden.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


typen av ram som används av kontrollen.

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


den binära datan för kontrollen.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


OLE-färgen för förgrunden. Gäller inte för Image-kontrollen.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


höjden på kontrollen i enheter av punkter.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


standardkörningsläget för Input Method Editor för kontrollen när den får fokus.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


en anpassad ikon som visas som muspekare för kontrollen.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


typen av ikon som visas som muspekare för kontrollen.

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


Bildens data.

**Returns:**
byte[]
### getPictureAlignment() {#getPictureAlignment--}
```
public int getPictureAlignment()
```


justeringen av bilden inuti Form eller Image.

**Returns:**
int
### getPictureSizeMode() {#getPictureSizeMode--}
```
public int getPictureSizeMode()
```


hur man visar bilden.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


den speciella effekten för kontrollen.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Hämtar typen av ActiveX-kontrollen.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


kontrollens bredd i enheten punkt.

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


Indikerar om kontrollen automatiskt kommer att ändra storlek för att visa hela innehållet.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Indikerar om kontrollen kan ta emot fokus och svara på händelser som genereras av användaren.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Indikerar om data i kontrollen är låst för redigering.

**Returns:**
boolean
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Anger om bilden är kaklad över bakgrunden.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indikerar om kontrollen är transparent.

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


För beskrivningen av den här egenskapen, se [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


För beskrivningen av denna egenskap, se [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


För beskrivningen av den här egenskapen, se [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


För beskrivningen av den här egenskapen, se [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


För beskrivningen av den här egenskapen, se [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


För beskrivningen av den här egenskapen, se [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


För beskrivningen av den här egenskapen, se [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


För beskrivningen av den här egenskapen, se [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


För beskrivningen av den här egenskapen, se [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


För beskrivningen av den här egenskapen, se [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setPictureAlignment(int value) {#setPictureAlignment-int-}
```
public void setPictureAlignment(int value)
```


För beskrivningen av den här egenskapen, se [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPictureSizeMode(int value) {#setPictureSizeMode-int-}
```
public void setPictureSizeMode(int value)
```


För beskrivningen av den här egenskapen, se [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


För beskrivningen av den här egenskapen, se [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTiled(boolean value) {#setTiled-boolean-}
```
public void setTiled(boolean value)
```


För beskrivningen av den här egenskapen, se [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


För beskrivningen av den här egenskapen, se [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


För beskrivningen av den här egenskapen, se [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

