---
title: ScrollBarActiveXControl
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt het ScrollBar-besturingselement voor.
type: docs
weight: 352
url: /nl/java/com.aspose.diagram/scrollbaractivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol), [com.aspose.diagram.SpinButtonActiveXControl](../../com.aspose.diagram/spinbuttonactivexcontrol)
```
public class ScrollBarActiveXControl extends SpinButtonActiveXControl
```

Stelt het ScrollBar-besturingselement voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | de ole-kleur van de achtergrond. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | de binaire gegevens van de control. |
| [getForeOleColor()](#getForeOleColor--) | de ole-kleur van de voorgrond. |
| [getHeight()](#getHeight--) | de hoogte van de control in punten. |
| [getIMEMode()](#getIMEMode--) | de standaard runtime-modus van de Input Method Editor voor de control wanneer deze focus krijgt. |
| [getLargeChange()](#getLargeChange--) | de hoeveelheid waarmee de eigenschap Position verandert |
| [getMax()](#getMax--) | de maximaal aanvaardbare waarde. |
| [getMin()](#getMin--) | de minimaal aanvaardbare waarde. |
| [getMouseIcon()](#getMouseIcon--) | een aangepast pictogram om als muiscursor voor de besturingselement weer te geven. |
| [getMousePointer()](#getMousePointer--) | het type pictogram dat als muiscursor voor de besturingselement wordt weergegeven. |
| [getOrientation()](#getOrientation--) | of de SpinButton of ScrollBar verticaal of horizontaal georiënteerd is. |
| [getPosition()](#getPosition--) | de waarde. |
| [getSmallChange()](#getSmallChange--) | de hoeveelheid waarmee de eigenschap Position verandert |
| [getType()](#getType--) | Haalt het type van het ActiveX-besturingselement op. |
| [getWidth()](#getWidth--) | de breedte van het besturingselement in eenheid van punten. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Geeft aan of het besturingselement automatisch van grootte verandert om de volledige inhoud weer te geven. |
| [isEnabled()](#isEnabled--) | Geeft aan of het besturingselement de focus kan ontvangen en kan reageren op door de gebruiker gegenereerde gebeurtenissen. |
| [isLocked()](#isLocked--) | Geeft aan of gegevens in het besturingselement vergrendeld zijn voor bewerking. |
| [isTransparent()](#isTransparent--) | Geeft aan of het besturingselement transparant is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Voor de beschrijving van deze eigenschap, zie [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Voor de beschrijving van deze eigenschap, zie [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Voor de beschrijving van deze eigenschap, zie [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Voor de beschrijving van deze eigenschap, zie [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLargeChange(int value)](#setLargeChange-int-) | Voor de beschrijving van deze eigenschap, zie [getLargeChange()](../../com.aspose.diagram/scrollbaractivexcontrol\#getLargeChange--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Voor de beschrijving van deze eigenschap, zie [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMax(int value)](#setMax-int-) | Voor de beschrijving van deze eigenschap, zie [getMax()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMax--) |
| [setMin(int value)](#setMin-int-) | Voor de beschrijving van deze eigenschap, zie [getMin()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMin--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Voor de beschrijving van deze eigenschap, zie [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Voor de beschrijving van deze eigenschap, zie [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setOrientation(int value)](#setOrientation-int-) | Voor de beschrijving van deze eigenschap, zie [getOrientation()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getOrientation--) |
| [setPosition(int value)](#setPosition-int-) | Voor de beschrijving van deze eigenschap, zie [getPosition()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getPosition--) |
| [setSmallChange(int value)](#setSmallChange-int-) | Voor de beschrijving van deze eigenschap, zie [getSmallChange()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getSmallChange--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Voor de beschrijving van deze eigenschap, zie [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Voor de beschrijving van deze eigenschap, zie [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


de ole-kleur van de achtergrond.

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


de binaire gegevens van de control.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


de OLE-kleur van de voorgrond. Niet van toepassing op Image-besturingselement.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


de hoogte van de control in punten.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


de standaard runtime-modus van de Input Method Editor voor de control wanneer deze focus krijgt.

**Returns:**
int
### getLargeChange() {#getLargeChange--}
```
public int getLargeChange()
```


de hoeveelheid waarmee de eigenschap Position verandert

**Returns:**
int
### getMax() {#getMax--}
```
public int getMax()
```


de maximaal aanvaardbare waarde.

**Returns:**
int
### getMin() {#getMin--}
```
public int getMin()
```


de minimaal aanvaardbare waarde.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


een aangepast pictogram om als muiscursor voor de besturingselement weer te geven.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


het type pictogram dat als muiscursor voor de besturingselement wordt weergegeven.

**Returns:**
int
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


of de SpinButton of ScrollBar verticaal of horizontaal georiënteerd is.

**Returns:**
int
### getPosition() {#getPosition--}
```
public int getPosition()
```


de waarde.

**Returns:**
int
### getSmallChange() {#getSmallChange--}
```
public int getSmallChange()
```


de hoeveelheid waarmee de eigenschap Position verandert

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Haalt het type van het ActiveX-besturingselement op.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


de breedte van het besturingselement in eenheid van punten.

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


Geeft aan of het besturingselement automatisch van grootte verandert om de volledige inhoud weer te geven.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Geeft aan of het besturingselement de focus kan ontvangen en kan reageren op door de gebruiker gegenereerde gebeurtenissen.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Geeft aan of gegevens in het besturingselement vergrendeld zijn voor bewerking.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Geeft aan of het besturingselement transparant is.

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


Voor de beschrijving van deze eigenschap, zie [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Voor de beschrijving van deze eigenschap, zie [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Voor de beschrijving van deze eigenschap, zie [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Voor de beschrijving van deze eigenschap, zie [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLargeChange(int value) {#setLargeChange-int-}
```
public void setLargeChange(int value)
```


Voor de beschrijving van deze eigenschap, zie [getLargeChange()](../../com.aspose.diagram/scrollbaractivexcontrol\#getLargeChange--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMax(int value) {#setMax-int-}
```
public void setMax(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMax()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMax--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMin(int value) {#setMin-int-}
```
public void setMin(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMin()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMin--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Voor de beschrijving van deze eigenschap, zie [getOrientation()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getOrientation--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPosition(int value) {#setPosition-int-}
```
public void setPosition(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPosition()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getPosition--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSmallChange(int value) {#setSmallChange-int-}
```
public void setSmallChange(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSmallChange()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getSmallChange--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Voor de beschrijving van deze eigenschap, zie [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

