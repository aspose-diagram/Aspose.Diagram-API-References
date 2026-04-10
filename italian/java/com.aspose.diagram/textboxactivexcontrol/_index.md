---
title: TextBoxActiveXControl
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta un controllo ActiveX casella di testo.
type: docs
weight: 401
url: /it/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

Rappresenta un controllo ActiveX casella di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | il colore OLE dello sfondo. |
| [getBorderOleColor()](#getBorderOleColor--) | il colore OLE dello sfondo. |
| [getBorderStyle()](#getBorderStyle--) | il tipo di bordo usato dal controllo. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | i dati binari del controllo. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Specifica il simbolo visualizzato sul pulsante a discesa |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Specifica il comportamento di selezione quando si entra nel controllo. |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | Specifica il comportamento del tasto ENTER. |
| [getForeOleColor()](#getForeOleColor--) | il colore OLE del primo piano. |
| [getHeight()](#getHeight--) | l'altezza del controllo in unità di punti. |
| [getHideSelection()](#getHideSelection--) | Indica se il testo selezionato nel controllo appare evidenziato quando il controllo non ha il fuoco. |
| [getIMEMode()](#getIMEMode--) | la modalità di esecuzione predefinita dell'Input Method Editor per il controllo quando riceve il fuoco. |
| [getIntegralHeight()](#getIntegralHeight--) | Indica se il controllo mostrerà solo linee di testo complete senza mostrare linee parziali. |
| [getMaxLength()](#getMaxLength--) | il numero massimo di caratteri |
| [getMouseIcon()](#getMouseIcon--) | un'icona personalizzata da visualizzare come puntatore del mouse per il controllo. |
| [getMousePointer()](#getMousePointer--) | il tipo di icona visualizzata come puntatore del mouse per il controllo. |
| [getPasswordChar()](#getPasswordChar--) | un carattere da visualizzare al posto dei caratteri inseriti. |
| [getScrollBars()](#getScrollBars--) | Indica se il controllo ha barre di scorrimento verticali, barre di scorrimento orizzontali, entrambe o nessuna. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Specifica il simbolo visualizzato sul pulsante a discesa |
| [getSpecialEffect()](#getSpecialEffect--) | l'effetto speciale del controllo. |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | Indica se i caratteri di tabulazione sono consentiti nel testo del controllo. |
| [getText()](#getText--) | testo del controllo. |
| [getType()](#getType--) | Ottiene il tipo del controllo ActiveX. |
| [getWidth()](#getWidth--) | la larghezza del controllo in unità di punti. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indica se il controllo ridimensionerà automaticamente per visualizzare tutto il contenuto. |
| [isAutoTab()](#isAutoTab--) | Indica se il focus si sposterà automaticamente al controllo successivo quando l'utente inserisce il numero massimo di caratteri. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Specifica l'unità di base utilizzata per estendere una selezione. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Indica se il trascinamento e il rilascio sono abilitati per il controllo. |
| [isEditable()](#isEditable--) | Indica se l'utente può digitare nel controllo. |
| [isEnabled()](#isEnabled--) | Indica se il controllo può ricevere il focus e rispondere agli eventi generati dall'utente. |
| [isLocked()](#isLocked--) | Indica se i dati nel controllo sono bloccati per la modifica. |
| [isMultiLine()](#isMultiLine--) | Indica se il controllo può visualizzare più di una riga di testo. |
| [isTransparent()](#isTransparent--) | Indica se il controllo è trasparente. |
| [isWordWrapped()](#isWordWrapped--) | Indica se il contenuto del controllo avvolge automaticamente alla fine di una riga. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Per la descrizione di questa proprietà, vedere [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | Per la descrizione di questa proprietà, consultare [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Per la descrizione di questa proprietà, consultare [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Per la descrizione di questa proprietà, vedere [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Per la descrizione di questa proprietà, consultare [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Per la descrizione di questa proprietà, consultare [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Per la descrizione di questa proprietà, consultare [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Per la descrizione di questa proprietà, consultare [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Per la descrizione di questa proprietà, consultare [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Per la descrizione di questa proprietà, vedere [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Per la descrizione di questa proprietà, consultare [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | Per la descrizione di questa proprietà, consultare [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Per la descrizione di questa proprietà, vedere [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Per la descrizione di questa proprietà, vedere [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Per la descrizione di questa proprietà, consultare [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Per la descrizione di questa proprietà, vedere [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Per la descrizione di questa proprietà, consultare [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Per la descrizione di questa proprietà, consultare [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Per la descrizione di questa proprietà, vedere [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Per la descrizione di questa proprietà, vedere [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | Per la descrizione di questa proprietà, consultare [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) |
| [setPasswordChar(char value)](#setPasswordChar-char-) | Per la descrizione di questa proprietà, consultare [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Per la descrizione di questa proprietà, consultare [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Per la descrizione di questa proprietà, consultare [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Per la descrizione di questa proprietà, consultare [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | Per la descrizione di questa proprietà, consultare [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) |
| [setText(String value)](#setText-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Per la descrizione di questa proprietà, vedere [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Per la descrizione di questa proprietà, consultare [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) |
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
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


Specifica il comportamento del tasto INVIO. True indica che premendo INVIO verrà creata una nuova riga. False indica che premendo INVIO il focus si sposterà all'oggetto successivo nell'ordine di tabulazione.

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
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Indica se il controllo mostrerà solo linee di testo complete senza mostrare linee parziali.

**Returns:**
boolean
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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


un carattere da visualizzare al posto dei caratteri inseriti.

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Indica se il controllo ha barre di scorrimento verticali, barre di scorrimento orizzontali, entrambe o nessuna.

**Returns:**
int
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
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


Indica se i caratteri di tabulazione sono consentiti nel testo del controllo.

**Returns:**
boolean
### getText() {#getText--}
```
public String getText()
```


testo del controllo.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public int getType()
```


Ottiene il tipo del controllo ActiveX.

**Returns:**
int
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


Indica se il focus si sposterà automaticamente al controllo successivo quando l'utente inserisce il numero massimo di caratteri.

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


Indica se il controllo può visualizzare più di una riga di testo.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indica se il controllo è trasparente.

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Indica se il contenuto del controllo avvolge automaticamente alla fine di una riga.

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

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


Per la descrizione di questa proprietà, consultare [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Per la descrizione di questa proprietà, consultare [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--)

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


Per la descrizione di questa proprietà, consultare [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Per la descrizione di questa proprietà, consultare [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Per la descrizione di questa proprietà, consultare [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Per la descrizione di questa proprietà, consultare [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Per la descrizione di questa proprietà, consultare [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--)

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


Per la descrizione di questa proprietà, consultare [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


Per la descrizione di questa proprietà, consultare [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--)

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


Per la descrizione di questa proprietà, consultare [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--)

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

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


Per la descrizione di questa proprietà, consultare [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Per la descrizione di questa proprietà, vedere [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Per la descrizione di questa proprietà, consultare [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--)

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


Per la descrizione di questa proprietà, consultare [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


Per la descrizione di questa proprietà, consultare [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Per la descrizione di questa proprietà, consultare [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Per la descrizione di questa proprietà, consultare [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Per la descrizione di questa proprietà, consultare [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


Per la descrizione di questa proprietà, consultare [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Per la descrizione di questa proprietà, consultare [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Per la descrizione di questa proprietà, vedere [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Per la descrizione di questa proprietà, vedere [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Per la descrizione di questa proprietà, consultare [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

