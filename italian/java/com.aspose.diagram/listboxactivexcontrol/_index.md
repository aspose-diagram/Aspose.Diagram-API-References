---
title: ListBoxActiveXControl
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta un controllo ActiveX ListBox.
type: docs
weight: 234
url: /it/java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

Rappresenta un controllo ActiveX ListBox.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | il colore OLE dello sfondo. |
| [getBorderOleColor()](#getBorderOleColor--) | il colore OLE dello sfondo. |
| [getBorderStyle()](#getBorderStyle--) | il tipo di bordo usato dal controllo. |
| [getBoundColumn()](#getBoundColumn--) | Rappresenta come la proprietà Value viene determinata per una ComboBox o ListBox quando il valore della proprietà MultiSelect (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Rappresenta il numero di colonne da visualizzare in una ComboBox o ListBox. |
| [getColumnWidths()](#getColumnWidths--) | la larghezza della colonna. |
| [getData()](#getData--) | i dati binari del controllo. |
| [getForeOleColor()](#getForeOleColor--) | il colore OLE del primo piano. |
| [getHeight()](#getHeight--) | l'altezza del controllo in unità di punti. |
| [getIMEMode()](#getIMEMode--) | la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco. |
| [getIntegralHeight()](#getIntegralHeight--) | Indica se il controllo mostrerà solo linee di testo complete senza mostrare linee parziali. |
| [getListStyle()](#getListStyle--) | l'aspetto visivo. |
| [getListWidth()](#getListWidth--) | la larghezza in unità di punti. |
| [getMatchEntry()](#getMatchEntry--) | Indica come un ListBox o ComboBox ricerca la sua lista mentre l'utente digita. |
| [getMouseIcon()](#getMouseIcon--) | un'icona personalizzata da visualizzare come puntatore del mouse per il controllo. |
| [getMousePointer()](#getMousePointer--) | il tipo di icona visualizzata come puntatore del mouse per il controllo. |
| [getScrollBars()](#getScrollBars--) | Indica se il controllo ha barre di scorrimento verticali, barre di scorrimento orizzontali, entrambe o nessuna. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Indica se le intestazioni di colonna sono visualizzate. |
| [getSpecialEffect()](#getSpecialEffect--) | l'effetto speciale del controllo. |
| [getTextColumn()](#getTextColumn--) | Rappresenta la colonna in un ComboBox o ListBox da visualizzare all'utente. |
| [getType()](#getType--) | Ottiene il tipo del controllo ActiveX. |
| [getValue()](#getValue--) | il valore del controllo. |
| [getWidth()](#getWidth--) | la larghezza del controllo in unità di punti. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indica se il controllo ridimensionerà automaticamente per visualizzare tutto il contenuto. |
| [isEnabled()](#isEnabled--) | Indica se il controllo può ricevere il focus e rispondere agli eventi generati dall'utente. |
| [isLocked()](#isLocked--) | Indica se i dati nel controllo sono bloccati per la modifica. |
| [isTransparent()](#isTransparent--) | Indica se il controllo è trasparente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Per la descrizione di questa proprietà, vedere [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Per la descrizione di questa proprietà, vedere [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Per la descrizione di questa proprietà, vedere [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Per la descrizione di questa proprietà, vedere [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Per la descrizione di questa proprietà, vedere [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Per la descrizione di questa proprietà, vedere [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Per la descrizione di questa proprietà, vedere [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Per la descrizione di questa proprietà, vedere [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--) |
| [setListStyle(int value)](#setListStyle-int-) | Per la descrizione di questa proprietà, vedere [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Per la descrizione di questa proprietà, vedere [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Per la descrizione di questa proprietà, vedere [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Per la descrizione di questa proprietà, vedere [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Per la descrizione di questa proprietà, vedere [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Per la descrizione di questa proprietà, vedere [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Per la descrizione di questa proprietà, vedere [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Per la descrizione di questa proprietà, vedere [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Per la descrizione di questa proprietà, vedere [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Per la descrizione di questa proprietà, vedere [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


il colore OLE dello sfondo.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


il colore OLE dello sfondo.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


il tipo di bordo usato dal controllo.

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Rappresenta come la proprietà Value viene determinata per una ComboBox o ListBox quando il valore della proprietà MultiSelect (fmMultiSelectSingle).

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


Rappresenta il numero di colonne da visualizzare in una ComboBox o ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


la larghezza della colonna.

**Returns:**
double
### getData() {#getData--}
```
public byte[] getData()
```


i dati binari del controllo.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


Il colore OLE del primo piano. Non si applica al controllo Image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


l'altezza del controllo in unità di punti.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco.

**Returns:**
int
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Indica se il controllo mostrerà solo linee di testo complete senza mostrare linee parziali.

**Returns:**
boolean
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


l'aspetto visivo.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


la larghezza in unità di punti.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Indica come un ListBox o ComboBox ricerca la sua lista mentre l'utente digita.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


un'icona personalizzata da visualizzare come puntatore del mouse per il controllo.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


il tipo di icona visualizzata come puntatore del mouse per il controllo.

**Returns:**
int
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Indica se il controllo ha barre di scorrimento verticali, barre di scorrimento orizzontali, entrambe o nessuna.

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Indica se le intestazioni di colonna sono visualizzate.

**Returns:**
boolean
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


l'effetto speciale del controllo.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Rappresenta la colonna in un ComboBox o ListBox da visualizzare all'utente.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Ottiene il tipo del controllo ActiveX.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


il valore del controllo.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```


la larghezza del controllo in unità di punti.

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


Indica se il controllo ridimensionerà automaticamente per visualizzare tutto il contenuto.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Indica se il controllo può ricevere il focus e rispondere agli eventi generati dall'utente.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Indica se i dati nel controllo sono bloccati per la modifica.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indica se il controllo è trasparente.

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


Per la descrizione di questa proprietà, vedere [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Per la descrizione di questa proprietà, vedere [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Per la descrizione di questa proprietà, vedere [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Per la descrizione di questa proprietà, vedere [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Per la descrizione di questa proprietà, vedere [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Per la descrizione di questa proprietà, vedere [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Per la descrizione di questa proprietà, vedere [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Per la descrizione di questa proprietà, vedere [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Per la descrizione di questa proprietà, vedere [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


Per la descrizione di questa proprietà, vedere [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Per la descrizione di questa proprietà, vedere [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Per la descrizione di questa proprietà, vedere [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


Per la descrizione di questa proprietà, vedere [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Per la descrizione di questa proprietà, vedere [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Per la descrizione di questa proprietà, vedere [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Per la descrizione di questa proprietà, vedere [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Per la descrizione di questa proprietà, vedere [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Per la descrizione di questa proprietà, vedere [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Per la descrizione di questa proprietà, vedere [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Per la descrizione di questa proprietà, vedere [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Per la descrizione di questa proprietà, vedere [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

