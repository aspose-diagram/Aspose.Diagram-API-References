---
title: CommandButtonActiveXControl
second_title: Aspose.Diagram for Java API-Referenz
description: Stellt eine Befehlsschaltfläche dar.
type: docs
weight: 56
url: /de/java/com.aspose.diagram/commandbuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class CommandButtonActiveXControl extends ActiveXControl
```

Stellt eine Befehlsschaltfläche dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | Die Beschleunigungstaste für das Steuerelement. |
| [getBackOleColor()](#getBackOleColor--) | die OLE‑Farbe des Hintergrunds. |
| [getCaption()](#getCaption--) | Der beschreibende Text, der auf einem Steuerelement erscheint. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | die Binärdaten des Steuerelements. |
| [getForeOleColor()](#getForeOleColor--) | die OLE‑Farbe des Vordergrunds. |
| [getHeight()](#getHeight--) | die Höhe des Steuerelements in Punkt‑Einheiten. |
| [getIMEMode()](#getIMEMode--) | der Standard‑Laufzeitmodus des Input Method Editors für das Steuerelement, wenn es den Fokus erhält. |
| [getMouseIcon()](#getMouseIcon--) | ein benutzerdefiniertes Symbol, das als Mauszeiger für das Steuerelement angezeigt wird. |
| [getMousePointer()](#getMousePointer--) | der Typ des als Mauszeiger für das Steuerelement angezeigten Symbols. |
| [getPicture()](#getPicture--) | Die Daten des Bildes. |
| [getPicturePosition()](#getPicturePosition--) | Der Ort des Bildes des Steuerelements relativ zu seiner Beschriftung. |
| [getTakeFocusOnClick()](#getTakeFocusOnClick--) | Gibt an, ob das Steuerelement den Fokus erhält, wenn es angeklickt wird. |
| [getType()](#getType--) | Ermittelt den Typ des ActiveX-Steuerelements. |
| [getWidth()](#getWidth--) | die Breite des Steuerelements in Punkt-Einheiten. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Gibt an, ob das Steuerelement automatisch die Größe ändert, um seinen gesamten Inhalt anzuzeigen. |
| [isEnabled()](#isEnabled--) | Gibt an, ob das Steuerelement den Fokus erhalten und auf benutzergenerierte Ereignisse reagieren kann. |
| [isLocked()](#isLocked--) | Gibt an, ob Daten im Steuerelement für die Bearbeitung gesperrt sind. |
| [isTransparent()](#isTransparent--) | Gibt an, ob das Steuerelement transparent ist. |
| [isWordWrapped()](#isWordWrapped--) | Gibt an, ob der Inhalt des Steuerelements am Zeilenende automatisch umbrochen wird. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAccelerator()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getAccelerator--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCaption()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPicture()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPicturePosition()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicturePosition--) |
| [setTakeFocusOnClick(boolean value)](#setTakeFocusOnClick-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTakeFocusOnClick()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getTakeFocusOnClick--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isWordWrapped()](../../com.aspose.diagram/commandbuttonactivexcontrol\#isWordWrapped--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


Die Beschleunigungstaste für das Steuerelement.

**Returns:**
char
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


die OLE‑Farbe des Hintergrunds.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


Der beschreibende Text, der auf einem Steuerelement erscheint.

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


die Binärdaten des Steuerelements.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


Die OLE-Farbe des Vordergrunds. Gilt nicht für das Image-Steuerelement.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


die Höhe des Steuerelements in Punkt‑Einheiten.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


der Standard‑Laufzeitmodus des Input Method Editors für das Steuerelement, wenn es den Fokus erhält.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


ein benutzerdefiniertes Symbol, das als Mauszeiger für das Steuerelement angezeigt wird.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


der Typ des als Mauszeiger für das Steuerelement angezeigten Symbols.

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


Die Daten des Bildes.

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


Der Ort des Bildes des Steuerelements relativ zu seiner Beschriftung.

**Returns:**
int
### getTakeFocusOnClick() {#getTakeFocusOnClick--}
```
public boolean getTakeFocusOnClick()
```


Gibt an, ob das Steuerelement den Fokus erhält, wenn es angeklickt wird.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Ermittelt den Typ des ActiveX-Steuerelements.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


die Breite des Steuerelements in Punkt-Einheiten.

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


Gibt an, ob das Steuerelement automatisch die Größe ändert, um seinen gesamten Inhalt anzuzeigen.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Gibt an, ob das Steuerelement den Fokus erhalten und auf benutzergenerierte Ereignisse reagieren kann.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Gibt an, ob Daten im Steuerelement für die Bearbeitung gesperrt sind.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Gibt an, ob das Steuerelement transparent ist.

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Gibt an, ob der Inhalt des Steuerelements am Zeilenende automatisch umbrochen wird.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getAccelerator()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getAccelerator--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCaption()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getCaption--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPicture()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicture--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPicturePosition()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getPicturePosition--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTakeFocusOnClick(boolean value) {#setTakeFocusOnClick-boolean-}
```
public void setTakeFocusOnClick(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTakeFocusOnClick()](../../com.aspose.diagram/commandbuttonactivexcontrol\#getTakeFocusOnClick--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isWordWrapped()](../../com.aspose.diagram/commandbuttonactivexcontrol\#isWordWrapped--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

