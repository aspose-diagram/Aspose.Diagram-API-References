---
title: Hyperlink
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi per creare più collegamenti tra una forma o pagina di disegno e un'altra pagina di disegno, un altro file o un sito Web.
type: docs
weight: 193
url: /it/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Contiene gli elementi per creare più collegamenti tra una forma o una pagina di disegno e un'altra pagina di disegno, un altro file o un sito Web.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Specifica un indirizzo URL, un nome file DOS o un percorso UNC a cui saltare. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Specifica il collegamento ipertestuale predefinito per una forma o una pagina. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDescription()](#getDescription--) | L'elemento Description contiene una stringa di testo che descrive il collegamento ipertestuale. |
| [getExtraInfo()](#getExtraInfo--) | Contiene informazioni da utilizzare per risolvere un URL, come le coordinate di una mappa immagine. |
| [getFrame()](#getFrame--) | Contiene il nome di un frame da destinazione quando Microsoft Visio è aperto come documento attivo in un'applicazione contenitore. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getInvisible()](#getInvisible--) | L'elemento Invisible indica se un collegamento ipertestuale appare nel menu contestuale per una forma o una pagina. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getNewWindow()](#getNewWindow--) | Specifica se Microsoft Visio apre una finestra in una nuova posizione quando segue un collegamento ipertestuale per aprire una pagina Web o un altro documento Visio. |
| [getSortKey()](#getSortKey--) | L'elemento Invisible indica se un collegamento ipertestuale appare nel menu contestuale per una forma o una pagina. |
| [getSubAddress()](#getSubAddress--) | Specifica una posizione all'interno del documento di destinazione a cui collegarsi. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Specifica un indirizzo URL, un nome file DOS o un percorso UNC a cui saltare.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Specifica il collegamento ipertestuale predefinito per una forma o una pagina.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


L'elemento Description contiene una stringa di testo che descrive il collegamento ipertestuale.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Contiene informazioni da utilizzare per risolvere un URL, come le coordinate di una mappa immagine. Per esempio, x=41 y=7 specificerebbe le coordinate di una mappa immagine.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Contiene il nome di un frame da destinazione quando Microsoft Visio è aperto come documento attivo in un'applicazione contenitore. Il valore predefinito è una stringa vuota.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


L'elemento Invisible indica se un collegamento ipertestuale appare nel menu contestuale per una forma o una pagina.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Specifica se Microsoft Visio apre una finestra in una nuova posizione quando segue un collegamento ipertestuale per aprire una pagina Web o un altro documento Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


L'elemento Invisible indica se un collegamento ipertestuale appare nel menu contestuale per una forma o una pagina.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Specifica una posizione all'interno del documento di destinazione a cui collegarsi.

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


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, consultare [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, consultare [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

