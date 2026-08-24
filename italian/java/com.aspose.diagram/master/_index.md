---
title: Master
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene gli elementi che definiscono un master per il documento.
type: docs
weight: 240
url: /it/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Contiene elementi che definiscono un master per il documento. Un master è una forma su uno stencil che utilizzi ripetutamente per creare disegni. Quando trascini una forma dallo stencil sulla pagina del disegno, la forma diventa un'istanza di quel master e una copia locale del master è inclusa nel documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Master()](#Master--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [dispose()](#dispose--) | Esegue operazioni definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Specifica se il testo del master nella finestra stencil è allineato a sinistra, a destra o al centro. |
| [getBaseID()](#getBaseID--) | Un GUID (identificatore unico globale) che identifica il master tra i documenti. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contiene un elemento Connect per ogni connessione tra due forme in un disegno. |
| [getHidden()](#getHidden--) | Specifica se il master è nascosto nell'interfaccia utente. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getIcon()](#getIcon--) | Specifica un'icona binaria codificata MIME (Multipurpose Internet Mail Extensions) (in formato .ico) per un elemento Master o MasterShortcut in un documento. |
| [getIconSize()](#getIconSize--) | La dimensione dell'icona dell'elemento. |
| [getIconUpdate()](#getIconUpdate--) | Specifica se l'icona è generata automaticamente dal master stesso. |
| [getMatchByName()](#getMatchByName--) | L'attributo MatchByName determina come Microsoft Visio decide se un master del documento è già presente quando un'istanza di un master viene rilasciata sulla pagina del disegno. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getPageSheet()](#getPageSheet--) | Contiene elementi che definiscono il foglio di pagina per un elemento Pagina o Master. |
| [getPatternFlags()](#getPatternFlags--) | L'attributo PatternFlags determina se un master si comporta come un modello personalizzato. |
| [getPrompt()](#getPrompt--) | La barra di stato e il suggerimento del tooltip per l'elemento. |
| [getShapes()](#getShapes--) | Raccolta di oggetti Shape. |
| [getUniqueID()](#getUniqueID--) | Un GUID che identifica il master all'interno del documento. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Per la descrizione di questa proprietà, vedere [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Per la descrizione di questa proprietà, vedere [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Per la descrizione di questa proprietà, vedere [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Per la descrizione di questa proprietà, vedere [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Per la descrizione di questa proprietà, vedere [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Per la descrizione di questa proprietà, vedere [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Per la descrizione di questa proprietà, vedere [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Per la descrizione di questa proprietà, vedere [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Per la descrizione di questa proprietà, vedere [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Costruttore.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profonda di questa istanza.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Esegue operazioni definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Specifica se il testo del master nella finestra stencil è allineato a sinistra, a destra o al centro.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


Un GUID (identificatore unico globale) che identifica il master tra i documenti.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Contiene un elemento Connect per ogni connessione tra due forme in un disegno.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Specifica se il master è nascosto nell'interfaccia utente.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Specifica un'icona binaria codificata MIME (Multipurpose Internet Mail Extensions) (in formato .ico) per un elemento Master o MasterShortcut in un documento.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


La dimensione dell'icona dell'elemento.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Specifica se l'icona è generata automaticamente dal master stesso.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


L'attributo MatchByName determina come Microsoft Visio decide se un master di documento è già presente quando un'istanza di un master viene rilasciata sulla pagina di disegno. Consente alle modifiche apportate a un master di documento di essere applicate alle nuove istanze del master, anche se le istanze vengono trascinate da un file stencil autonomo.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contiene elementi che definiscono il foglio di pagina per un elemento Pagina o Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


L'attributo PatternFlags determina se un master si comporta come un modello personalizzato.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


La barra di stato e il suggerimento del tooltip per l'elemento.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Raccolta di oggetti Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID che identifica il master all'interno del documento.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Per la descrizione di questa proprietà, vedere [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Per la descrizione di questa proprietà, vedere [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Per la descrizione di questa proprietà, vedere [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Per la descrizione di questa proprietà, vedere [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Per la descrizione di questa proprietà, vedere [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Per la descrizione di questa proprietà, vedere [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Per la descrizione di questa proprietà, vedere [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Per la descrizione di questa proprietà, vedere [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Per la descrizione di questa proprietà, vedere [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Per la descrizione di questa proprietà, vedere [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

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

