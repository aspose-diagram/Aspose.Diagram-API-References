---
title: Connection
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi per un punto di connessione definito per la forma.
type: docs
weight: 78
url: /it/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

Contiene elementi per un punto di connessione definito per la forma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Connection()](#Connection--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | Specifica se il punto di connessione è generato automaticamente. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDirX()](#getDirX--) | Specifica la componente x del vettore di allineamento richiesto per un punto di connessione corrispondente. |
| [getDirY()](#getDirY--) | Specifica la componente y del vettore di allineamento richiesto per un punto di connessione corrispondente. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getPrompt()](#getPrompt--) | Contiene informazioni di prompt variabili, in base all'elemento in cui è contenuto. |
| [getType()](#getType--) | Specifica vari tipi, in base all'elemento in cui è contenuto. |
| [getX()](#getX--) | Specifica una coordinata x su una forma in coordinate locali. |
| [getY()](#getY--) | Specifica una coordinata y su una forma in coordinate locali. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/connection\#getDel--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/connection\#getID--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/connection\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getName()](../../com.aspose.diagram/connection\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getNameU()](../../com.aspose.diagram/connection\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


Specifica se il punto di connessione è generato automaticamente. Un valore di 1 indica che il punto di connessione è generato automaticamente.

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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


Specifica la componente x del vettore di allineamento richiesto per un punto di connessione corrispondente. L'elemento DirX è inoltre utilizzato per orientare la gamba collegata di un connettore dinamico.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


Specifica la componente y del vettore di allineamento richiesto per un punto di connessione corrispondente. L'elemento DirY è inoltre utilizzato per orientare la gamba collegata di un connettore dinamico.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Contiene informazioni di prompt variabili, in base all'elemento in cui è contenuto.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


Specifica vari tipi, in base all'elemento in cui è contenuto.

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


Specifica una coordinata x su una forma in coordinate locali.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Specifica una coordinata y su una forma in coordinate locali. Le coordinate locali sono quelle il cui riferimento è la forma, anziché la pagina.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/connection\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, consultare [getID()](../../com.aspose.diagram/connection\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, consultare [getIX()](../../com.aspose.diagram/connection\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, consultare [getName()](../../com.aspose.diagram/connection\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, consultare [getNameU()](../../com.aspose.diagram/connection\#getNameU--)

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

