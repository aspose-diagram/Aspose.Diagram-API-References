---
title: ComboBoxActiveXControl
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta un controllo ActiveX ComboBox.
type: docs
weight: 55
url: /it/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

Rappresenta un controllo ActiveX ComboBox.
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
| [getDropButtonStyle()](#getDropButtonStyle--) | Specifica il simbolo visualizzato sul pulsante a discesa |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Specifica il comportamento di selezione quando si entra nel controllo. |
| [getForeOleColor()](#getForeOleColor--) | il colore OLE del primo piano. |
| [getHeight()](#getHeight--) | l'altezza del controllo in unità di punti. |
| [getHideSelection()](#getHideSelection--) | Indica se il testo selezionato nel controllo appare evidenziato quando il controllo non ha il fuoco. |
| [getIMEMode()](#getIMEMode--) | la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco. |
| [getListRows()](#getListRows--) | Rappresenta il numero massimo di righe da visualizzare nell'elenco. |
| [getListStyle()](#getListStyle--) | l'aspetto visivo. |
| [getListWidth()](#getListWidth--) | la larghezza in unità di punti. |
| [getMatchEntry()](#getMatchEntry--) | Indica come un ListBox o ComboBox ricerca la sua lista mentre l'utente digita. |
| [getMaxLength()](#getMaxLength--) | il numero massimo di caratteri |
| [getMouseIcon()](#getMouseIcon--) | un'icona personalizzata da visualizzare come puntatore del mouse per il controllo. |
| [getMousePointer()](#getMousePointer--) | il tipo di icona visualizzata come puntatore del mouse per il controllo. |
| [getSelectionMargin()](#getSelectionMargin--) | Indica se l'utente può selezionare una riga di testo facendo clic nella zona a sinistra del testo. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Indica se le intestazioni di colonna sono visualizzate. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Specifica il simbolo visualizzato sul pulsante a discesa |
| [getSpecialEffect()](#getSpecialEffect--) | l'effetto speciale del controllo. |
| [getTextColumn()](#getTextColumn--) | Rappresenta la colonna in un ComboBox o ListBox da visualizzare all'utente. |
| [getType()](#getType--) | Ottiene il tipo del controllo ActiveX. |
| [getValue()](#getValue--) | il valore del controllo. |
| [getWidth()](#getWidth--) | la larghezza del controllo in unità di punti. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indica se il controllo ridimensionerà automaticamente per visualizzare tutto il contenuto. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Specifica l'unità di base utilizzata per estendere una selezione. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Indica se il trascinamento e il rilascio sono abilitati per il controllo. |
| [isEditable()](#isEditable--) | Indica se l'utente può digitare nel controllo. |
| [isEnabled()](#isEnabled--) | Indica se il controllo può ricevere il focus e rispondere agli eventi generati dall'utente. |
| [isLocked()](#isLocked--) | Indica se i dati nel controllo sono bloccati per la modifica. |
| [isTransparent()](#isTransparent--) | Indica se il controllo è trasparente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Per la descrizione di questa proprietà, vedere [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Per la descrizione di questa proprietà, vedere [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Per la descrizione di questa proprietà, vedere [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Per la descrizione di questa proprietà, vedere [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Per la descrizione di questa proprietà, vedere [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Per la descrizione di questa proprietà, vedere [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Per la descrizione di questa proprietà, vedere [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Per la descrizione di questa proprietà, vedere [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Per la descrizione di questa proprietà, vedere [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Per la descrizione di questa proprietà, vedere [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Per la descrizione di questa proprietà, vedere [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Per la descrizione di questa proprietà, vedere [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Per la descrizione di questa proprietà, vedere [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setListRows(int value)](#setListRows-int-) | Per la descrizione di questa proprietà, vedere [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) |
| [setListStyle(int value)](#setListStyle-int-) | Per la descrizione di questa proprietà, vedere [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Per la descrizione di questa proprietà, vedere [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Per la descrizione di questa proprietà, vedere [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Per la descrizione di questa proprietà, vedere [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Per la descrizione di questa proprietà, vedere [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Per la descrizione di questa proprietà, vedere [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | Per la descrizione di questa proprietà, vedere [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Per la descrizione di questa proprietà, vedere [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Per la descrizione di questa proprietà, vedere [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Per la descrizione di questa proprietà, vedere [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Per la descrizione di questa proprietà, vedere [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) |
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
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


Specifica il simbolo visualizzato sul pulsante a discesa

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


Specifica il comportamento di selezione all'ingresso del controllo. True specifica che la selezione rimane invariata rispetto all'ultima volta che il controllo era attivo. False specifica che tutto il testo nel controllo sarà selezionato all'ingresso del controllo.

**Returns:**
boolean
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
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


Indica se il testo selezionato nel controllo appare evidenziato quando il controllo non ha il fuoco.

**Returns:**
boolean
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco.

**Returns:**
int
### getListRows() {#getListRows--}
```
public int getListRows()
```


Rappresenta il numero massimo di righe da visualizzare nell'elenco.

**Returns:**
int
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
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


il numero massimo di caratteri

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
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


Indica se l'utente può selezionare una riga di testo facendo clic nella zona a sinistra del testo.

**Returns:**
boolean
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Indica se le intestazioni di colonna sono visualizzate.

**Returns:**
boolean
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


Specifica il simbolo visualizzato sul pulsante a discesa

**Returns:**
int
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
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


Specifica l'unità di base utilizzata per estendere una selezione. True specifica che l'unità di base è un singolo carattere. false specifica che l'unità di base è una parola intera.

**Returns:**
boolean
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


Indica se il trascinamento e il rilascio sono abilitati per il controllo.

**Returns:**
boolean
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


Indica se l'utente può digitare nel controllo.

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

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Per la descrizione di questa proprietà, vedere [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--)

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


Per la descrizione di questa proprietà, vedere [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Per la descrizione di questa proprietà, vedere [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Per la descrizione di questa proprietà, vedere [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Per la descrizione di questa proprietà, vedere [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Per la descrizione di questa proprietà, vedere [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Per la descrizione di questa proprietà, vedere [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Per la descrizione di questa proprietà, vedere [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Per la descrizione di questa proprietà, vedere [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


Per la descrizione di questa proprietà, vedere [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--)

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

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


Per la descrizione di questa proprietà, vedere [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


Per la descrizione di questa proprietà, vedere [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Per la descrizione di questa proprietà, vedere [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Per la descrizione di questa proprietà, vedere [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--)

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


Per la descrizione di questa proprietà, vedere [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Per la descrizione di questa proprietà, vedere [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--)

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

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Per la descrizione di questa proprietà, vedere [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Per la descrizione di questa proprietà, vedere [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Per la descrizione di questa proprietà, vedere [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Per la descrizione di questa proprietà, vedere [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--)

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


Per la descrizione di questa proprietà, vedere [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--)

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

