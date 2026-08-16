---
title: ComboBoxActiveXControl
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt een ComboBox ActiveX-besturingselement voor.
type: docs
weight: 55
url: /nl/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

Stelt een ComboBox ActiveX-besturingselement voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | de ole-kleur van de achtergrond. |
| [getBorderOleColor()](#getBorderOleColor--) | de ole-kleur van de achtergrond. |
| [getBorderStyle()](#getBorderStyle--) | het type rand dat door de control wordt gebruikt. |
| [getBoundColumn()](#getBoundColumn--) | Geeft weer hoe de Value-eigenschap wordt bepaald voor een ComboBox of ListBox wanneer de waarde van de MultiSelect-eigenschap (fmMultiSelectSingle) is. |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Geeft het aantal kolommen weer dat moet worden weergegeven in een ComboBox of ListBox. |
| [getColumnWidths()](#getColumnWidths--) | de breedte van de kolom. |
| [getData()](#getData--) | de binaire gegevens van de control. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Specificeert het symbool dat wordt weergegeven op de vervolgknop |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Specificeert het selectiegedrag bij het betreden van de control. |
| [getForeOleColor()](#getForeOleColor--) | de ole-kleur van de voorgrond. |
| [getHeight()](#getHeight--) | de hoogte van de control in punten. |
| [getHideSelection()](#getHideSelection--) | Geeft aan of geselecteerde tekst in de control gemarkeerd wordt wanneer de control geen focus heeft. |
| [getIMEMode()](#getIMEMode--) | de standaard runtime-modus van de Input Method Editor voor de control wanneer deze focus krijgt. |
| [getListRows()](#getListRows--) | Geeft het maximale aantal rijen weer dat in de lijst moet worden weergegeven. |
| [getListStyle()](#getListStyle--) | het visuele uiterlijk. |
| [getListWidth()](#getListWidth--) | de breedte in eenheid van punten. |
| [getMatchEntry()](#getMatchEntry--) | Geeft aan hoe een ListBox of ComboBox zijn lijst doorzoekt terwijl de gebruiker typt. |
| [getMaxLength()](#getMaxLength--) | het maximale aantal tekens |
| [getMouseIcon()](#getMouseIcon--) | een aangepast pictogram om als muiscursor voor de besturingselement weer te geven. |
| [getMousePointer()](#getMousePointer--) | het type pictogram dat als muiscursor voor de besturingselement wordt weergegeven. |
| [getSelectionMargin()](#getSelectionMargin--) | Geeft aan of de gebruiker een regel tekst kan selecteren door te klikken in het gebied links van de tekst. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Geeft aan of kolomkoppen worden weergegeven. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Specificeert het symbool dat wordt weergegeven op de vervolgknop |
| [getSpecialEffect()](#getSpecialEffect--) | het speciale effect van het besturingselement. |
| [getTextColumn()](#getTextColumn--) | Geeft de kolom in een ComboBox of ListBox weer die aan de gebruiker wordt getoond. |
| [getType()](#getType--) | Haalt het type van het ActiveX-besturingselement op. |
| [getValue()](#getValue--) | de waarde van het besturingselement. |
| [getWidth()](#getWidth--) | de breedte van het besturingselement in eenheid van punten. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Geeft aan of het besturingselement automatisch van grootte verandert om de volledige inhoud weer te geven. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Specificeert de basiseenheid die wordt gebruikt om een selectie uit te breiden. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Geeft aan of slepen en neerzetten is ingeschakeld voor het besturingselement. |
| [isEditable()](#isEditable--) | Geeft aan of de gebruiker in het besturingselement kan typen. |
| [isEnabled()](#isEnabled--) | Geeft aan of het besturingselement de focus kan ontvangen en kan reageren op door de gebruiker gegenereerde gebeurtenissen. |
| [isLocked()](#isLocked--) | Geeft aan of gegevens in het besturingselement vergrendeld zijn voor bewerking. |
| [isTransparent()](#isTransparent--) | Geeft aan of het besturingselement transparant is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Voor de beschrijving van deze eigenschap, zie [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Voor de beschrijving van deze eigenschap, zie [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Voor de beschrijving van deze eigenschap, zie [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Voor de beschrijving van deze eigenschap, zie [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Voor de beschrijving van deze eigenschap, zie [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Voor de beschrijving van deze eigenschap, zie [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Voor de beschrijving van deze eigenschap, zie [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Voor de beschrijving van deze eigenschap, zie [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Voor de beschrijving van deze eigenschap, zie [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Voor de beschrijving van deze eigenschap, zie [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Voor de beschrijving van deze eigenschap, zie [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Voor de beschrijving van deze eigenschap, zie [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Voor de beschrijving van deze eigenschap, zie [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Voor de beschrijving van deze eigenschap, zie [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Voor de beschrijving van deze eigenschap, zie [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setListRows(int value)](#setListRows-int-) | Voor de beschrijving van deze eigenschap, zie [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) |
| [setListStyle(int value)](#setListStyle-int-) | Voor de beschrijving van deze eigenschap, zie [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Voor de beschrijving van deze eigenschap, zie [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Voor de beschrijving van deze eigenschap, zie [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Voor de beschrijving van deze eigenschap, zie [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Voor de beschrijving van deze eigenschap, zie [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Voor de beschrijving van deze eigenschap, zie [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Voor de beschrijving van deze eigenschap, zie [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Voor de beschrijving van deze eigenschap, zie [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Voor de beschrijving van deze eigenschap, zie [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Voor de beschrijving van deze eigenschap, zie [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Voor de beschrijving van deze eigenschap, zie [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Voor de beschrijving van deze eigenschap, zie [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) |
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
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


de ole-kleur van de achtergrond.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


het type rand dat door de control wordt gebruikt.

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Geeft weer hoe de Value-eigenschap wordt bepaald voor een ComboBox of ListBox wanneer de waarde van de MultiSelect-eigenschap (fmMultiSelectSingle) is.

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


Geeft het aantal kolommen weer dat moet worden weergegeven in een ComboBox of ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


de breedte van de kolom.

**Returns:**
double
### getData() {#getData--}
```
public byte[] getData()
```


de binaire gegevens van de control.

**Returns:**
byte[]
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


Specificeert het symbool dat wordt weergegeven op de vervolgknop

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


Specificeert het selectiegedrag bij het betreden van het besturingselement. True geeft aan dat de selectie ongewijzigd blijft ten opzichte van de laatste keer dat het besturingselement actief was. False geeft aan dat alle tekst in het besturingselement wordt geselecteerd bij het betreden van het besturingselement.

**Returns:**
boolean
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
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


Geeft aan of geselecteerde tekst in de control gemarkeerd wordt wanneer de control geen focus heeft.

**Returns:**
boolean
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


de standaard runtime-modus van de Input Method Editor voor de control wanneer deze focus krijgt.

**Returns:**
int
### getListRows() {#getListRows--}
```
public int getListRows()
```


Geeft het maximale aantal rijen weer dat in de lijst moet worden weergegeven.

**Returns:**
int
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


het visuele uiterlijk.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


de breedte in eenheid van punten.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Geeft aan hoe een ListBox of ComboBox zijn lijst doorzoekt terwijl de gebruiker typt.

**Returns:**
int
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


het maximale aantal tekens

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
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


Geeft aan of de gebruiker een regel tekst kan selecteren door te klikken in het gebied links van de tekst.

**Returns:**
boolean
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Geeft aan of kolomkoppen worden weergegeven.

**Returns:**
boolean
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


Specificeert het symbool dat wordt weergegeven op de vervolgknop

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


het speciale effect van het besturingselement.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Geeft de kolom in een ComboBox of ListBox weer die aan de gebruiker wordt getoond.

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
public String getValue()
```


de waarde van het besturingselement.

**Returns:**
java.lang.String
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
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


Specificeert de basiseenheid die wordt gebruikt om een selectie uit te breiden. True geeft aan dat de basiseenheid één teken is. false geeft aan dat de basiseenheid een heel woord is.

**Returns:**
boolean
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


Geeft aan of slepen en neerzetten is ingeschakeld voor het besturingselement.

**Returns:**
boolean
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


Geeft aan of de gebruiker in het besturingselement kan typen.

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

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--)

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

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Voor de beschrijving van deze eigenschap, zie [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Voor de beschrijving van deze eigenschap, zie [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Voor de beschrijving van deze eigenschap, zie [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Voor de beschrijving van deze eigenschap, zie [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Voor de beschrijving van deze eigenschap, zie [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--)

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

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


Voor de beschrijving van deze eigenschap, zie [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Voor de beschrijving van deze eigenschap, zie [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Voor de beschrijving van deze eigenschap, zie [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--)

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

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Voor de beschrijving van deze eigenschap, zie [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--)

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

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Voor de beschrijving van deze eigenschap, zie [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

