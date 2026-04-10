---
title: RadioButtonActiveXControl
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt een RadioButton ActiveX-besturingselement voor.
type: docs
weight: 313
url: /nl/java/com.aspose.diagram/radiobuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol), [com.aspose.diagram.ToggleButtonActiveXControl](../../com.aspose.diagram/togglebuttonactivexcontrol)
```
public class RadioButtonActiveXControl extends ToggleButtonActiveXControl
```

Stelt een RadioButton ActiveX-besturingselement voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | de sneltoets voor de besturingselement. |
| [getAlignment()](#getAlignment--) | de positie van het bijschrift ten opzichte van het besturingselement. |
| [getBackOleColor()](#getBackOleColor--) | de ole-kleur van de achtergrond. |
| [getCaption()](#getCaption--) | de beschrijvende tekst die op een besturingselement verschijnt. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | de binaire gegevens van de control. |
| [getForeOleColor()](#getForeOleColor--) | de ole-kleur van de voorgrond. |
| [getGroupName()](#getGroupName--) | de naam van de groep. |
| [getHeight()](#getHeight--) | de hoogte van de control in punten. |
| [getIMEMode()](#getIMEMode--) | de standaard runtime-modus van de Input Method Editor voor de control wanneer deze focus krijgt. |
| [getMouseIcon()](#getMouseIcon--) | een aangepast pictogram om als muiscursor voor de besturingselement weer te geven. |
| [getMousePointer()](#getMousePointer--) | het type pictogram dat als muiscursor voor de besturingselement wordt weergegeven. |
| [getPicture()](#getPicture--) | de gegevens van de afbeelding. |
| [getPicturePosition()](#getPicturePosition--) | de locatie van de afbeelding van het controle-element ten opzichte van de bijschrift. |
| [getSpecialEffect()](#getSpecialEffect--) | het speciale effect van het besturingselement. |
| [getType()](#getType--) | Haalt het type van het ActiveX-besturingselement op. |
| [getValue()](#getValue--) | Geeft aan of het controle-element is aangevinkt of niet. |
| [getWidth()](#getWidth--) | de breedte van het besturingselement in eenheid van punten. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Geeft aan of het besturingselement automatisch van grootte verandert om de volledige inhoud weer te geven. |
| [isEnabled()](#isEnabled--) | Geeft aan of het besturingselement de focus kan ontvangen en kan reageren op door de gebruiker gegenereerde gebeurtenissen. |
| [isLocked()](#isLocked--) | Geeft aan of gegevens in het besturingselement vergrendeld zijn voor bewerking. |
| [isTransparent()](#isTransparent--) | Geeft aan of het besturingselement transparant is. |
| [isTripleState()](#isTripleState--) | Geeft aan hoe het opgegeven controle-element Null-waarden weergeeft. |
| [isWordWrapped()](#isWordWrapped--) | Geeft aan of de inhoud van het controle-element automatisch wordt afgebroken aan het einde van een regel. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | Voor de beschrijving van deze eigenschap, zie [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--) |
| [setAlignment(int value)](#setAlignment-int-) | Voor de beschrijving van deze eigenschap, zie [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Voor de beschrijving van deze eigenschap, zie [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Voor de beschrijving van deze eigenschap, zie [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setGroupName(String value)](#setGroupName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--) |
| [setHeight(double value)](#setHeight-double-) | Voor de beschrijving van deze eigenschap, zie [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Voor de beschrijving van deze eigenschap, zie [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Voor de beschrijving van deze eigenschap, zie [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Voor de beschrijving van deze eigenschap, zie [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Voor de beschrijving van deze eigenschap, zie [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | Voor de beschrijving van deze eigenschap, zie [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | Voor de beschrijving van deze eigenschap, zie [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Voor de beschrijving van deze eigenschap, zie [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Voor de beschrijving van deze eigenschap, zie [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setTripleState(boolean value)](#setTripleState-boolean-) | Voor de beschrijving van deze eigenschap, zie [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--) |
| [setValue(int value)](#setValue-int-) | Voor de beschrijving van deze eigenschap, zie [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Voor de beschrijving van deze eigenschap, zie [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Voor de beschrijving van deze eigenschap, zie [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--) |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


de sneltoets voor de besturingselement.

**Returns:**
char
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


de positie van het bijschrift ten opzichte van het besturingselement.

**Returns:**
int
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


de ole-kleur van de achtergrond.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


de beschrijvende tekst die op een besturingselement verschijnt.

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
### getGroupName() {#getGroupName--}
```
public String getGroupName()
```


de naam van de groep.

**Returns:**
java.lang.String
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
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


de gegevens van de afbeelding.

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


de locatie van de afbeelding van het controle-element ten opzichte van de bijschrift.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


het speciale effect van het besturingselement.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Haalt het type van het ActiveX-besturingselement op.

**Returns:**
int
### getValue() {#getValue--}
```
public int getValue()
```


Geeft aan of het controle-element is aangevinkt of niet.

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
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


Geeft aan hoe het opgegeven controle-element Null-waarden weergeeft.

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Instelling | Beschrijving                                                                                                                                     |
| True    | Het controle-element doorloopt de toestanden voor Ja, Nee en Null-waarden. Het controle-element wordt gedimd (grijs) wanneer de eigenschap Value is ingesteld op Null. |
| False   | (Standaard) Het controle-element doorloopt de toestanden voor Ja- en Nee-waarden. Null-waarden worden weergegeven alsof het Nee-waarden zijn.                           |

|

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Geeft aan of de inhoud van het controle-element automatisch wordt afgebroken aan het einde van een regel.

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


Voor de beschrijving van deze eigenschap, zie [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | char |  |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Voor de beschrijving van deze eigenschap, zie [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


Voor de beschrijving van deze eigenschap, zie [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

### setGroupName(String value) {#setGroupName-java.lang.String-}
```
public void setGroupName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)

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

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Voor de beschrijving van deze eigenschap, zie [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Voor de beschrijving van deze eigenschap, zie [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

