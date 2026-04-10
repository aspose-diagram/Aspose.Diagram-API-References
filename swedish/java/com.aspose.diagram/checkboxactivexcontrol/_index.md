---
title: CheckBoxActiveXControl
second_title: Aspose.Diagram för Java API-referens
description: Representerar en CheckBox ActiveX-kontroll.
type: docs
weight: 47
url: /sv/java/com.aspose.diagram/checkboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class CheckBoxActiveXControl extends ActiveXControl
```

Representerar en CheckBox ActiveX-kontroll.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | Acceleratortangenten för kontrollen. |
| [getAlignment()](#getAlignment--) | Positionen för Caption relativt kontrollen. |
| [getBackOleColor()](#getBackOleColor--) | ole-färgen för bakgrunden. |
| [getCaption()](#getCaption--) | Den beskrivande texten som visas på en kontroll. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | den binära datan för kontrollen. |
| [getForeOleColor()](#getForeOleColor--) | ole-färgen för förgrunden. |
| [getGroupName()](#getGroupName--) | Gruppens namn. |
| [getHeight()](#getHeight--) | höjden på kontrollen i enheter av punkter. |
| [getIMEMode()](#getIMEMode--) | standardkörningsläget för Input Method Editor för kontrollen när den får fokus. |
| [getMouseIcon()](#getMouseIcon--) | en anpassad ikon som visas som muspekare för kontrollen. |
| [getMousePointer()](#getMousePointer--) | typen av ikon som visas som muspekare för kontrollen. |
| [getPicture()](#getPicture--) | Bildens data. |
| [getPicturePosition()](#getPicturePosition--) | platsen för kontrollens bild relativt dess rubrik. |
| [getSpecialEffect()](#getSpecialEffect--) | den speciella effekten för kontrollen. |
| [getType()](#getType--) | Hämtar typen av ActiveX-kontrollen. |
| [getValue()](#getValue--) | Anger om kontrollen är markerad eller inte. |
| [getWidth()](#getWidth--) | kontrollens bredd i enheten punkt. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indikerar om kontrollen automatiskt kommer att ändra storlek för att visa hela innehållet. |
| [isChecked()](#isChecked--) | Anger om rutan är markerad. |
| [isEnabled()](#isEnabled--) | Indikerar om kontrollen kan ta emot fokus och svara på händelser som genereras av användaren. |
| [isLocked()](#isLocked--) | Indikerar om data i kontrollen är låst för redigering. |
| [isTransparent()](#isTransparent--) | Indikerar om kontrollen är transparent. |
| [isTripleState()](#isTripleState--) | Anger hur den angivna kontrollen kommer att visa Null‑värden. |
| [isWordWrapped()](#isWordWrapped--) | Anger om innehållet i kontrollen automatiskt radbryts i slutet av en rad. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | För beskrivningen av den här egenskapen, se [getAccelerator()](../../com.aspose.diagram/checkboxactivexcontrol\#getAccelerator--) |
| [setAlignment(int value)](#setAlignment-int-) | För beskrivningen av den här egenskapen, se [getAlignment()](../../com.aspose.diagram/checkboxactivexcontrol\#getAlignment--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | För beskrivningen av denna egenskap, se [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | För beskrivningen av denna egenskap, se [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | För beskrivningen av den här egenskapen, se [getCaption()](../../com.aspose.diagram/checkboxactivexcontrol\#getCaption--) |
| [setChecked(boolean value)](#setChecked-boolean-) | För beskrivningen av den här egenskapen, se [isChecked()](../../com.aspose.diagram/checkboxactivexcontrol\#isChecked--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | För beskrivningen av den här egenskapen, se [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | För beskrivningen av den här egenskapen, se [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setGroupName(String value)](#setGroupName-java.lang.String-) | För beskrivningen av den här egenskapen, se [getGroupName()](../../com.aspose.diagram/checkboxactivexcontrol\#getGroupName--) |
| [setHeight(double value)](#setHeight-double-) | För beskrivningen av den här egenskapen, se [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | För beskrivningen av den här egenskapen, se [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | För beskrivningen av den här egenskapen, se [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | För beskrivningen av den här egenskapen, se [getPicture()](../../com.aspose.diagram/checkboxactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | För beskrivningen av den här egenskapen, se [getPicturePosition()](../../com.aspose.diagram/checkboxactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | För beskrivningen av den här egenskapen, se [getSpecialEffect()](../../com.aspose.diagram/checkboxactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | För beskrivningen av den här egenskapen, se [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setTripleState(boolean value)](#setTripleState-boolean-) | För beskrivningen av den här egenskapen, se [isTripleState()](../../com.aspose.diagram/checkboxactivexcontrol\#isTripleState--) |
| [setValue(int value)](#setValue-int-) | För beskrivningen av den här egenskapen, se [getValue()](../../com.aspose.diagram/checkboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | För beskrivningen av den här egenskapen, se [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | För beskrivningen av den här egenskapen, se [isWordWrapped()](../../com.aspose.diagram/checkboxactivexcontrol\#isWordWrapped--) |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


Acceleratortangenten för kontrollen.

**Returns:**
char
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Positionen för Caption relativt kontrollen.

**Returns:**
int
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


ole-färgen för bakgrunden.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


Den beskrivande texten som visas på en kontroll.

**Returns:**
java.lang.String
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
### getGroupName() {#getGroupName--}
```
public String getGroupName()
```


Gruppens namn.

**Returns:**
java.lang.String
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
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


platsen för kontrollens bild relativt dess rubrik.

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
### getValue() {#getValue--}
```
public int getValue()
```


Anger om kontrollen är markerad eller inte.

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
### isChecked() {#isChecked--}
```
public boolean isChecked()
```


Anger om rutan är markerad.

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
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


Anger hur den angivna kontrollen kommer att visa Null‑värden.

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Inställning | Beskrivning                                                                                                                                     |
| True    | Kontrollen kommer att cykla genom tillstånd för Ja, Nej och Null‑värden. Kontrollen visas nedtonad (grå) när dess Value‑egenskap är satt till Null. |
| False   | (Standard) Kontrollen kommer att cykla genom tillstånd för Ja och Nej‑värden. Null‑värden visas som om de vore Nej‑värden.                           |

|

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Anger om innehållet i kontrollen automatiskt radbryts i slutet av en rad.

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




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


För beskrivningen av den här egenskapen, se [getAccelerator()](../../com.aspose.diagram/checkboxactivexcontrol\#getAccelerator--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char |  |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


För beskrivningen av den här egenskapen, se [getAlignment()](../../com.aspose.diagram/checkboxactivexcontrol\#getAlignment--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


För beskrivningen av den här egenskapen, se [getCaption()](../../com.aspose.diagram/checkboxactivexcontrol\#getCaption--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


För beskrivningen av den här egenskapen, se [isChecked()](../../com.aspose.diagram/checkboxactivexcontrol\#isChecked--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setGroupName(String value) {#setGroupName-java.lang.String-}
```
public void setGroupName(String value)
```


För beskrivningen av den här egenskapen, se [getGroupName()](../../com.aspose.diagram/checkboxactivexcontrol\#getGroupName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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


För beskrivningen av den här egenskapen, se [getPicture()](../../com.aspose.diagram/checkboxactivexcontrol\#getPicture--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


För beskrivningen av den här egenskapen, se [getPicturePosition()](../../com.aspose.diagram/checkboxactivexcontrol\#getPicturePosition--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


För beskrivningen av den här egenskapen, se [getSpecialEffect()](../../com.aspose.diagram/checkboxactivexcontrol\#getSpecialEffect--)

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

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


För beskrivningen av den här egenskapen, se [isTripleState()](../../com.aspose.diagram/checkboxactivexcontrol\#isTripleState--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


För beskrivningen av den här egenskapen, se [getValue()](../../com.aspose.diagram/checkboxactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


För beskrivningen av den här egenskapen, se [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


För beskrivningen av den här egenskapen, se [isWordWrapped()](../../com.aspose.diagram/checkboxactivexcontrol\#isWordWrapped--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

