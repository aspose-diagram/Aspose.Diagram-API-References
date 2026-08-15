---
title: ComboBoxActiveXControl
second_title: Aspose.Diagram för Java API-referens
description: Representerar en ComboBox ActiveX-kontroll.
type: docs
weight: 55
url: /sv/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

Representerar en ComboBox ActiveX-kontroll.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | ole-färgen för bakgrunden. |
| [getBorderOleColor()](#getBorderOleColor--) | ole-färgen för bakgrunden. |
| [getBorderStyle()](#getBorderStyle--) | typen av ram som används av kontrollen. |
| [getBoundColumn()](#getBoundColumn--) | Representerar hur Value‑egenskapen bestäms för en ComboBox eller ListBox när MultiSelect‑egenskapens värde (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Representerar antalet kolumner som ska visas i en ComboBox eller ListBox. |
| [getColumnWidths()](#getColumnWidths--) | bredden på kolumnen. |
| [getData()](#getData--) | den binära datan för kontrollen. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Anger symbolen som visas på nedrullningsknappen |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Anger urvalsbeteende när kontrollen aktiveras. |
| [getForeOleColor()](#getForeOleColor--) | ole-färgen för förgrunden. |
| [getHeight()](#getHeight--) | höjden på kontrollen i enheter av punkter. |
| [getHideSelection()](#getHideSelection--) | Indikerar om markerad text i kontrollen visas markerad när kontrollen inte har fokus. |
| [getIMEMode()](#getIMEMode--) | standardkörningsläget för Input Method Editor för kontrollen när den får fokus. |
| [getListRows()](#getListRows--) | Representerar det maximala antalet rader som ska visas i listan. |
| [getListStyle()](#getListStyle--) | det visuella utseendet. |
| [getListWidth()](#getListWidth--) | bredden i enheten punkter. |
| [getMatchEntry()](#getMatchEntry--) | Indikerar hur en ListBox eller ComboBox söker i sin lista när användaren skriver. |
| [getMaxLength()](#getMaxLength--) | det maximala antalet tecken |
| [getMouseIcon()](#getMouseIcon--) | en anpassad ikon som visas som muspekare för kontrollen. |
| [getMousePointer()](#getMousePointer--) | typen av ikon som visas som muspekare för kontrollen. |
| [getSelectionMargin()](#getSelectionMargin--) | Indikerar om användaren kan markera en textrad genom att klicka i området till vänster om texten. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Indikerar om kolumnrubriker visas. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Anger symbolen som visas på nedrullningsknappen |
| [getSpecialEffect()](#getSpecialEffect--) | den speciella effekten för kontrollen. |
| [getTextColumn()](#getTextColumn--) | Representerar kolumnen i en ComboBox eller ListBox som ska visas för användaren. |
| [getType()](#getType--) | Hämtar typen av ActiveX-kontrollen. |
| [getValue()](#getValue--) | värdet för kontrollen. |
| [getWidth()](#getWidth--) | kontrollens bredd i enheten punkt. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indikerar om kontrollen automatiskt kommer att ändra storlek för att visa hela innehållet. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Anger den grundläggande enheten som används för att utöka en markering. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Indikerar om dra‑och‑släpp är aktiverat för kontrollen. |
| [isEditable()](#isEditable--) | Indikerar om användaren kan skriva i kontrollen. |
| [isEnabled()](#isEnabled--) | Indikerar om kontrollen kan ta emot fokus och svara på händelser som genereras av användaren. |
| [isLocked()](#isLocked--) | Indikerar om data i kontrollen är låst för redigering. |
| [isTransparent()](#isTransparent--) | Indikerar om kontrollen är transparent. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | För beskrivningen av denna egenskap, se [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | För beskrivningen av denna egenskap, se [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | För beskrivningen av denna egenskap, se [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | För beskrivningen av denna egenskap, se [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | För beskrivningen av den här egenskapen, se [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | För beskrivningen av den här egenskapen, se [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | För beskrivningen av den här egenskapen, se [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | För beskrivningen av den här egenskapen, se [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | För beskrivningen av den här egenskapen, se [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | För beskrivningen av den här egenskapen, se [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | För beskrivningen av den här egenskapen, se [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | För beskrivningen av den här egenskapen, se [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | För beskrivningen av den här egenskapen, se [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | För beskrivningen av den här egenskapen, se [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | För beskrivningen av den här egenskapen, se [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | För beskrivningen av den här egenskapen, se [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | För beskrivningen av den här egenskapen, se [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setListRows(int value)](#setListRows-int-) | För beskrivningen av den här egenskapen, se [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) |
| [setListStyle(int value)](#setListStyle-int-) | För beskrivningen av den här egenskapen, se [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | För beskrivningen av den här egenskapen, se [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | För beskrivningen av den här egenskapen, se [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) |
| [setMaxLength(int value)](#setMaxLength-int-) | För beskrivningen av den här egenskapen, se [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | För beskrivningen av den här egenskapen, se [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | För beskrivningen av den här egenskapen, se [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | För beskrivningen av den här egenskapen, se [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | För beskrivningen av den här egenskapen, se [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | För beskrivningen av den här egenskapen, se [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | För beskrivningen av den här egenskapen, se [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | För beskrivningen av den här egenskapen, se [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | För beskrivningen av den här egenskapen, se [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | För beskrivningen av den här egenskapen, se [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) |
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
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Representerar hur Value‑egenskapen bestäms för en ComboBox eller ListBox när MultiSelect‑egenskapens värde (fmMultiSelectSingle).

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


Representerar antalet kolumner som ska visas i en ComboBox eller ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


bredden på kolumnen.

**Returns:**
double
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
### getListRows() {#getListRows--}
```
public int getListRows()
```


Representerar det maximala antalet rader som ska visas i listan.

**Returns:**
int
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


det visuella utseendet.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


bredden i enheten punkter.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Indikerar hur en ListBox eller ComboBox söker i sin lista när användaren skriver.

**Returns:**
int
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
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


Indikerar om användaren kan markera en textrad genom att klicka i området till vänster om texten.

**Returns:**
boolean
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Indikerar om kolumnrubriker visas.

**Returns:**
boolean
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
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Representerar kolumnen i en ComboBox eller ListBox som ska visas för användaren.

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
public String getValue()
```


värdet för kontrollen.

**Returns:**
java.lang.String
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

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


För beskrivningen av denna egenskap, se [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--)

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


För beskrivningen av denna egenskap, se [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


För beskrivningen av den här egenskapen, se [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


För beskrivningen av den här egenskapen, se [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


För beskrivningen av den här egenskapen, se [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


För beskrivningen av den här egenskapen, se [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


För beskrivningen av den här egenskapen, se [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


För beskrivningen av den här egenskapen, se [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


För beskrivningen av den här egenskapen, se [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--)

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


För beskrivningen av den här egenskapen, se [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--)

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


För beskrivningen av den här egenskapen, se [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--)

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

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


För beskrivningen av den här egenskapen, se [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


För beskrivningen av den här egenskapen, se [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


För beskrivningen av den här egenskapen, se [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


För beskrivningen av den här egenskapen, se [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


För beskrivningen av den här egenskapen, se [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


För beskrivningen av den här egenskapen, se [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--)

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

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


För beskrivningen av den här egenskapen, se [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


För beskrivningen av den här egenskapen, se [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


För beskrivningen av den här egenskapen, se [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


För beskrivningen av den här egenskapen, se [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


För beskrivningen av den här egenskapen, se [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--)

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

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


För beskrivningen av den här egenskapen, se [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

