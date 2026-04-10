---
title: Act
second_title: Riferimento API di Aspose.Diagram per Java
description: Definisce i nomi dei comandi personalizzati che appaiono nel menu di scelta rapida di un oggetto e specifica le azioni che i comandi eseguono.
type: docs
weight: 11
url: /it/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Definisce nomi di comandi personalizzati che appaiono nel menu contestuale di un oggetto e specifica le azioni che i comandi eseguono.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Act()](#Act--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Contiene la formula da eseguire quando l'utente fa clic sul nome del comando definito nell'elemento Menu corrispondente. |
| [getBeginGroup()](#getBeginGroup--) | Indica se un separatore è inserito nel menu sopra questa azione. |
| [getButtonFace()](#getButtonFace--) | Identifica l'icona che appare accanto a un elemento nel menu di scelta rapida. |
| [getChecked()](#getChecked--) | Determina se un segno di spunta è visualizzato accanto al nome del comando nel menu di scelta rapida di una forma. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDisabled()](#getDisabled--) | L'elemento Disabled determina se il nome del comando è visualizzato nel menu di scelta rapida. |
| [getFlyoutChild()](#getFlyoutChild--) | Determina se la riga di azione è un menu a comparsa figlio dell'ultima riga sopra di essa che non è un figlio a comparsa. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getInvisible()](#getInvisible--) | L'elemento Invisible indica se l'azione è visibile sullo smart tag o sul menu di scelta rapida. |
| [getMenu()](#getMenu--) | Specifica il nome del comando che appare nel menu di scelta rapida per una forma o una pagina. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getReadOnly()](#getReadOnly--) | Determina se l'azione su uno smart tag o sul menu di scelta rapida è in sola lettura. |
| [getSortKey()](#getSortKey--) | Specifica un numero che determina l'ordine delle azioni che appaiono in un menu di scelta rapida o smart tag. |
| [getTagName()](#getTagName--) | Contiene il nome del tag intelligente a cui è associata l'azione. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
```


Costruttore.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profonda di questa istanza.

**Returns:**
java.lang.Object -
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Contiene la formula da eseguire quando l'utente fa clic sul nome del comando definito nell'elemento Menu corrispondente.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Indica se un separatore è inserito nel menu sopra questa azione.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Identifica l'icona che appare accanto a un elemento nel menu di scelta rapida.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Determina se un segno di spunta è visualizzato accanto al nome del comando nel menu di scelta rapida di una forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


L'elemento Disabled determina se il nome del comando è visualizzato nel menu di scelta rapida.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Determina se la riga di azione è un menu a comparsa figlio dell'ultima riga sopra di essa che non è un figlio a comparsa.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


L'elemento Invisible indica se l'azione è visibile sullo smart tag o sul menu di scelta rapida.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Specifica il nome del comando che appare nel menu di scelta rapida per una forma o una pagina.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getName() {#getName--}
```
public String getName()
```


Il nome dell'elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Il nome universale dell'elemento.

**Returns:**
java.lang.String
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Determina se l'azione su uno smart tag o sul menu di scelta rapida è in sola lettura.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Specifica un numero che determina l'ordine delle azioni che appaiono in un menu di scelta rapida o smart tag.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


Contiene il nome del tag intelligente a cui è associata l'azione.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/act\#getNameU--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

