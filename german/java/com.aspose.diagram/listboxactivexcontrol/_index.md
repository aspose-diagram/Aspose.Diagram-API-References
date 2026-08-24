---
title: ListBoxActiveXControl
second_title: Aspose.Diagram for Java API-Referenz
description: Stellt ein ListBox ActiveX-Steuerelement dar.
type: docs
weight: 234
url: /de/java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

Stellt ein ListBox ActiveX-Steuerelement dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | die OLE‑Farbe des Hintergrunds. |
| [getBorderOleColor()](#getBorderOleColor--) | die OLE‑Farbe des Hintergrunds. |
| [getBorderStyle()](#getBorderStyle--) | der von dem Steuerelement verwendete Randtyp. |
| [getBoundColumn()](#getBoundColumn--) | Gibt an, wie die Value‑Eigenschaft für ein ComboBox‑ oder ListBox‑Steuerelement bestimmt wird, wenn der Wert der MultiSelect‑Eigenschaft (fmMultiSelectSingle) ist. |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Gibt die Anzahl der Spalten an, die in einem ComboBox‑ oder ListBox‑Steuerelement angezeigt werden. |
| [getColumnWidths()](#getColumnWidths--) | die Breite der Spalte. |
| [getData()](#getData--) | die Binärdaten des Steuerelements. |
| [getForeOleColor()](#getForeOleColor--) | die OLE‑Farbe des Vordergrunds. |
| [getHeight()](#getHeight--) | die Höhe des Steuerelements in Punkt‑Einheiten. |
| [getIMEMode()](#getIMEMode--) | der Standard‑Laufzeitmodus des Input Method Editors für das Steuerelement, wenn es den Fokus erhält. |
| [getIntegralHeight()](#getIntegralHeight--) | Gibt an, ob das Steuerelement nur vollständige Textzeilen anzeigt, ohne Teilzeilen anzuzeigen. |
| [getListStyle()](#getListStyle--) | das visuelle Erscheinungsbild. |
| [getListWidth()](#getListWidth--) | die Breite in Punkt-Einheiten. |
| [getMatchEntry()](#getMatchEntry--) | Gibt an, wie eine ListBox oder ComboBox ihre Liste durchsucht, während der Benutzer tippt. |
| [getMouseIcon()](#getMouseIcon--) | ein benutzerdefiniertes Symbol, das als Mauszeiger für das Steuerelement angezeigt wird. |
| [getMousePointer()](#getMousePointer--) | der Typ des als Mauszeiger für das Steuerelement angezeigten Symbols. |
| [getScrollBars()](#getScrollBars--) | Gibt an, ob das Steuerelement vertikale Bildlaufleisten, horizontale Bildlaufleisten, beides oder keine hat. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Gibt an, ob Spaltenüberschriften angezeigt werden. |
| [getSpecialEffect()](#getSpecialEffect--) | der Spezialeffekt des Steuerelements. |
| [getTextColumn()](#getTextColumn--) | Stellt die Spalte in einer ComboBox oder ListBox dar, die dem Benutzer angezeigt wird. |
| [getType()](#getType--) | Ermittelt den Typ des ActiveX-Steuerelements. |
| [getValue()](#getValue--) | der Wert des Steuerelements. |
| [getWidth()](#getWidth--) | die Breite des Steuerelements in Punkt-Einheiten. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Gibt an, ob das Steuerelement automatisch die Größe ändert, um seinen gesamten Inhalt anzuzeigen. |
| [isEnabled()](#isEnabled--) | Gibt an, ob das Steuerelement den Fokus erhalten und auf benutzergenerierte Ereignisse reagieren kann. |
| [isLocked()](#isLocked--) | Gibt an, ob Daten im Steuerelement für die Bearbeitung gesperrt sind. |
| [isTransparent()](#isTransparent--) | Gibt an, ob das Steuerelement transparent ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--) |
| [setListStyle(int value)](#setListStyle-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


die OLE‑Farbe des Hintergrunds.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


die OLE‑Farbe des Hintergrunds.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


der von dem Steuerelement verwendete Randtyp.

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Gibt an, wie die Value‑Eigenschaft für ein ComboBox‑ oder ListBox‑Steuerelement bestimmt wird, wenn der Wert der MultiSelect‑Eigenschaft (fmMultiSelectSingle) ist.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


Gibt die Anzahl der Spalten an, die in einem ComboBox‑ oder ListBox‑Steuerelement angezeigt werden.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


die Breite der Spalte.

**Returns:**
double
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
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Gibt an, ob das Steuerelement nur vollständige Textzeilen anzeigt, ohne Teilzeilen anzuzeigen.

**Returns:**
boolean
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


das visuelle Erscheinungsbild.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


die Breite in Punkt-Einheiten.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Gibt an, wie eine ListBox oder ComboBox ihre Liste durchsucht, während der Benutzer tippt.

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
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Gibt an, ob das Steuerelement vertikale Bildlaufleisten, horizontale Bildlaufleisten, beides oder keine hat.

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Gibt an, ob Spaltenüberschriften angezeigt werden.

**Returns:**
boolean
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


der Spezialeffekt des Steuerelements.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Stellt die Spalte in einer ComboBox oder ListBox dar, die dem Benutzer angezeigt wird.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Ermittelt den Typ des ActiveX-Steuerelements.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


der Wert des Steuerelements.

**Returns:**
java.lang.String
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

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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

