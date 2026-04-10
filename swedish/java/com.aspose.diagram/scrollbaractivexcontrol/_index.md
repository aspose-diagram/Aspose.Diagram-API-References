---
title: ScrollBarActiveXControl
second_title: Aspose.Diagram för Java API-referens
description: Representerar ScrollBar-kontrollen.
type: docs
weight: 352
url: /sv/java/com.aspose.diagram/scrollbaractivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol), [com.aspose.diagram.SpinButtonActiveXControl](../../com.aspose.diagram/spinbuttonactivexcontrol)
```
public class ScrollBarActiveXControl extends SpinButtonActiveXControl
```

Representerar ScrollBar-kontrollen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | ole-färgen för bakgrunden. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | den binära datan för kontrollen. |
| [getForeOleColor()](#getForeOleColor--) | ole-färgen för förgrunden. |
| [getHeight()](#getHeight--) | höjden på kontrollen i enheter av punkter. |
| [getIMEMode()](#getIMEMode--) | standardkörningsläget för Input Method Editor för kontrollen när den får fokus. |
| [getLargeChange()](#getLargeChange--) | det belopp med vilket Position-egenskapen ändras |
| [getMax()](#getMax--) | det maximala acceptabla värdet. |
| [getMin()](#getMin--) | det minsta acceptabla värdet. |
| [getMouseIcon()](#getMouseIcon--) | en anpassad ikon som visas som muspekare för kontrollen. |
| [getMousePointer()](#getMousePointer--) | typen av ikon som visas som muspekare för kontrollen. |
| [getOrientation()](#getOrientation--) | om SpinButton eller ScrollBar är orienterad vertikalt eller horisontellt. |
| [getPosition()](#getPosition--) | värdet. |
| [getSmallChange()](#getSmallChange--) | det belopp med vilket Position-egenskapen ändras |
| [getType()](#getType--) | Hämtar typen av ActiveX-kontrollen. |
| [getWidth()](#getWidth--) | kontrollens bredd i enheten punkt. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indikerar om kontrollen automatiskt kommer att ändra storlek för att visa hela innehållet. |
| [isEnabled()](#isEnabled--) | Indikerar om kontrollen kan ta emot fokus och svara på händelser som genereras av användaren. |
| [isLocked()](#isLocked--) | Indikerar om data i kontrollen är låst för redigering. |
| [isTransparent()](#isTransparent--) | Indikerar om kontrollen är transparent. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | För beskrivningen av denna egenskap, se [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | För beskrivningen av denna egenskap, se [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | För beskrivningen av den här egenskapen, se [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | För beskrivningen av den här egenskapen, se [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | För beskrivningen av den här egenskapen, se [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLargeChange(int value)](#setLargeChange-int-) | För beskrivningen av den här egenskapen, se [getLargeChange()](../../com.aspose.diagram/scrollbaractivexcontrol\#getLargeChange--) |
| [setLocked(boolean value)](#setLocked-boolean-) | För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMax(int value)](#setMax-int-) | För beskrivningen av den här egenskapen, se [getMax()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMax--) |
| [setMin(int value)](#setMin-int-) | För beskrivningen av den här egenskapen, se [getMin()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMin--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | För beskrivningen av den här egenskapen, se [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | För beskrivningen av den här egenskapen, se [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setOrientation(int value)](#setOrientation-int-) | För beskrivningen av den här egenskapen, se [getOrientation()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getOrientation--) |
| [setPosition(int value)](#setPosition-int-) | För beskrivningen av den här egenskapen, se [getPosition()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getPosition--) |
| [setSmallChange(int value)](#setSmallChange-int-) | För beskrivningen av den här egenskapen, se [getSmallChange()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getSmallChange--) |
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
### getLargeChange() {#getLargeChange--}
```
public int getLargeChange()
```


det belopp med vilket Position-egenskapen ändras

**Returns:**
int
### getMax() {#getMax--}
```
public int getMax()
```


det maximala acceptabla värdet.

**Returns:**
int
### getMin() {#getMin--}
```
public int getMin()
```


det minsta acceptabla värdet.

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
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


om SpinButton eller ScrollBar är orienterad vertikalt eller horisontellt.

**Returns:**
int
### getPosition() {#getPosition--}
```
public int getPosition()
```


värdet.

**Returns:**
int
### getSmallChange() {#getSmallChange--}
```
public int getSmallChange()
```


det belopp med vilket Position-egenskapen ändras

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


För beskrivningen av denna egenskap, se [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

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

### setLargeChange(int value) {#setLargeChange-int-}
```
public void setLargeChange(int value)
```


För beskrivningen av den här egenskapen, se [getLargeChange()](../../com.aspose.diagram/scrollbaractivexcontrol\#getLargeChange--)

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

### setMax(int value) {#setMax-int-}
```
public void setMax(int value)
```


För beskrivningen av den här egenskapen, se [getMax()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMax--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMin(int value) {#setMin-int-}
```
public void setMin(int value)
```


För beskrivningen av den här egenskapen, se [getMin()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMin--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


För beskrivningen av den här egenskapen, se [getOrientation()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getOrientation--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPosition(int value) {#setPosition-int-}
```
public void setPosition(int value)
```


För beskrivningen av den här egenskapen, se [getPosition()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getPosition--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSmallChange(int value) {#setSmallChange-int-}
```
public void setSmallChange(int value)
```


För beskrivningen av den här egenskapen, se [getSmallChange()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getSmallChange--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

