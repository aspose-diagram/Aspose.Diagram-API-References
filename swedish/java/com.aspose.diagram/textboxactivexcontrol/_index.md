---
title: TextBoxActiveXControl
second_title: Aspose.Diagram för Java API-referens
description: Representerar en textlåda ActiveX‑kontroll.
type: docs
weight: 401
url: /sv/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

Representerar en textlåda ActiveX‑kontroll.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | ole-färgen för bakgrunden. |
| [getBorderOleColor()](#getBorderOleColor--) | ole-färgen för bakgrunden. |
| [getBorderStyle()](#getBorderStyle--) | typen av ram som används av kontrollen. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | den binära datan för kontrollen. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Anger symbolen som visas på nedrullningsknappen |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Anger urvalsbeteende när kontrollen aktiveras. |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | Anger beteendet för ENTER-tangenten. |
| [getForeOleColor()](#getForeOleColor--) | ole-färgen för förgrunden. |
| [getHeight()](#getHeight--) | höjden på kontrollen i enheter av punkter. |
| [getHideSelection()](#getHideSelection--) | Indikerar om markerad text i kontrollen visas markerad när kontrollen inte har fokus. |
| [getIMEMode()](#getIMEMode--) | standardkörningsläget för Input Method Editor för kontrollen när den får fokus. |
| [getIntegralHeight()](#getIntegralHeight--) | Indikerar om kontrollen endast visar kompletta textrader utan att visa några partiella rader. |
| [getMaxLength()](#getMaxLength--) | det maximala antalet tecken |
| [getMouseIcon()](#getMouseIcon--) | en anpassad ikon som visas som muspekare för kontrollen. |
| [getMousePointer()](#getMousePointer--) | typen av ikon som visas som muspekare för kontrollen. |
| [getPasswordChar()](#getPasswordChar--) | Ett tecken som ska visas i stället för de inmatade tecknen. |
| [getScrollBars()](#getScrollBars--) | Indikerar om kontrollen har vertikala rullningslister, horisontella rullningslister, båda eller ingen. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Anger symbolen som visas på nedrullningsknappen |
| [getSpecialEffect()](#getSpecialEffect--) | den speciella effekten för kontrollen. |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | Indikerar om tabulatortecken är tillåtna i kontrollens text. |
| [getText()](#getText--) | kontrollens text. |
| [getType()](#getType--) | Hämtar typen av ActiveX-kontrollen. |
| [getWidth()](#getWidth--) | kontrollens bredd i enheten punkt. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indikerar om kontrollen automatiskt kommer att ändra storlek för att visa hela innehållet. |
| [isAutoTab()](#isAutoTab--) | Anger om fokus automatiskt kommer att flyttas till nästa kontroll när användaren anger det maximala antalet tecken. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Anger den grundläggande enheten som används för att utöka en markering. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Indikerar om dra‑och‑släpp är aktiverat för kontrollen. |
| [isEditable()](#isEditable--) | Indikerar om användaren kan skriva i kontrollen. |
| [isEnabled()](#isEnabled--) | Indikerar om kontrollen kan ta emot fokus och svara på händelser som genereras av användaren. |
| [isLocked()](#isLocked--) | Indikerar om data i kontrollen är låst för redigering. |
| [isMultiLine()](#isMultiLine--) | Anger om kontrollen kan visa mer än en rad text. |
| [isTransparent()](#isTransparent--) | Indikerar om kontrollen är transparent. |
| [isWordWrapped()](#isWordWrapped--) | Anger om innehållet i kontrollen automatiskt radbryts i slutet av en rad. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | För beskrivningen av denna egenskap, se [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | För beskrivningen av denna egenskap, se [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | För beskrivningen av denna egenskap, se [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | För beskrivningen av denna egenskap, se [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | För beskrivningen av denna egenskap, se [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | För beskrivningen av denna egenskap, se [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | För beskrivningen av denna egenskap, se [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | För beskrivningen av denna egenskap, se [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | För beskrivningen av denna egenskap, se [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | För beskrivningen av den här egenskapen, se [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | För beskrivningen av denna egenskap, se [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | För beskrivningen av denna egenskap, se [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | För beskrivningen av den här egenskapen, se [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | För beskrivningen av den här egenskapen, se [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | För beskrivningen av denna egenskap, se [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | För beskrivningen av denna egenskap, se [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) |
| [setLocked(boolean value)](#setLocked-boolean-) | För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMaxLength(int value)](#setMaxLength-int-) | För beskrivningen av denna egenskap, se [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | För beskrivningen av den här egenskapen, se [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | För beskrivningen av den här egenskapen, se [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | För beskrivningen av denna egenskap, se [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) |
| [setPasswordChar(char value)](#setPasswordChar-char-) | För beskrivningen av denna egenskap, se [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) |
| [setScrollBars(int value)](#setScrollBars-int-) | För beskrivningen av denna egenskap, se [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | För beskrivningen av denna egenskap, se [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | För beskrivningen av denna egenskap, se [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | För beskrivningen av denna egenskap, se [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) |
| [setText(String value)](#setText-java.lang.String-) | För beskrivningen av denna egenskap, se [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | För beskrivningen av den här egenskapen, se [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | För beskrivningen av den här egenskapen, se [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | För beskrivningen av denna egenskap, se [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) |
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
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


Anger symbolen som visas på nedrullningsknappen

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


Anger markeringsbeteende när kontrollen aktiveras. True anger att markeringen förblir oförändrad sedan senaste gången kontrollen var aktiv. False anger att all text i kontrollen kommer att markeras när kontrollen aktiveras.

**Returns:**
boolean
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


Anger beteendet för ENTER-tangenten. Sant anger att trycka på ENTER skapar en ny rad. Falskt anger att trycka på ENTER flyttar fokus till nästa objekt i tabb-ordningen.

**Returns:**
boolean
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
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


Indikerar om markerad text i kontrollen visas markerad när kontrollen inte har fokus.

**Returns:**
boolean
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


standardkörningsläget för Input Method Editor för kontrollen när den får fokus.

**Returns:**
int
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Indikerar om kontrollen endast visar kompletta textrader utan att visa några partiella rader.

**Returns:**
boolean
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


det maximala antalet tecken

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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


Ett tecken som ska visas i stället för de inmatade tecknen.

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Indikerar om kontrollen har vertikala rullningslister, horisontella rullningslister, båda eller ingen.

**Returns:**
int
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


Anger symbolen som visas på nedrullningsknappen

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


den speciella effekten för kontrollen.

**Returns:**
int
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


Indikerar om tabulatortecken är tillåtna i kontrollens text.

**Returns:**
boolean
### getText() {#getText--}
```
public String getText()
```


kontrollens text.

**Returns:**
java.lang.String
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


Anger om fokus automatiskt kommer att flyttas till nästa kontroll när användaren anger det maximala antalet tecken.

**Returns:**
boolean
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


Anger den grundläggande enheten som används för att utöka en markering. True anger att den grundläggande enheten är ett enskilt tecken. false anger att den grundläggande enheten är ett helt ord.

**Returns:**
boolean
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


Indikerar om dra‑och‑släpp är aktiverat för kontrollen.

**Returns:**
boolean
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


Indikerar om användaren kan skriva i kontrollen.

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


Anger om kontrollen kan visa mer än en rad text.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indikerar om kontrollen är transparent.

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




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


För beskrivningen av denna egenskap, se [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


För beskrivningen av denna egenskap, se [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


För beskrivningen av denna egenskap, se [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--)

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


För beskrivningen av denna egenskap, se [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


För beskrivningen av denna egenskap, se [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


För beskrivningen av denna egenskap, se [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


För beskrivningen av denna egenskap, se [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


För beskrivningen av denna egenskap, se [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--)

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

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


För beskrivningen av denna egenskap, se [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


För beskrivningen av denna egenskap, se [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--)

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

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


För beskrivningen av denna egenskap, se [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


För beskrivningen av denna egenskap, se [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


För beskrivningen av denna egenskap, se [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--)

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


För beskrivningen av denna egenskap, se [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


För beskrivningen av denna egenskap, se [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


För beskrivningen av denna egenskap, se [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


För beskrivningen av denna egenskap, se [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


För beskrivningen av denna egenskap, se [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


För beskrivningen av denna egenskap, se [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


För beskrivningen av denna egenskap, se [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


För beskrivningen av denna egenskap, se [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--)

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

