---
title: Prop
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi per definire proprietà personalizzate ed elementi per associare dati a una forma.
type: docs
weight: 309
url: /it/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Contiene elementi per definire proprietà personalizzate ed elementi per associare dati a una forma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Prop()](#Prop--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Determina il calendario utilizzato per le proprietà personalizzate, i campi di testo e le formule degli elementi. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getFormat()](#getFormat--) | L'elemento Format specifica la formattazione di una proprietà personalizzata che è una stringa, un elenco fisso, un numero, un elenco variabile, una data o ora, una durata o una valuta. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getInvisible()](#getInvisible--) | L'elemento Invisible specifica se la proprietà personalizzata è visibile nella finestra di dialogo Proprietà personalizzate in Microsoft Visio. |
| [getLabel()](#getLabel--) | Specifica l'etichetta che appare agli utenti nella finestra di dialogo Proprietà personalizzate. |
| [getLangID()](#getLangID--) | Indica l'ID locale (LCID) della lingua in cui è stata inserita la formula della cella, il testo, la proprietà personalizzata o il commento. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getPrompt()](#getPrompt--) | L'elemento Prompt specifica il testo descrittivo o istruttivo che appare agli utenti nella finestra di dialogo Proprietà personalizzate quando la proprietà è selezionata. |
| [getSortKey()](#getSortKey--) | Specifica una chiave che determina l'ordine in cui le proprietà personalizzate sono elencate nell'interfaccia utente dell'applicazione. |
| [getType()](#getType--) | Tipo specifica un tipo di dati per il valore della proprietà personalizzata. |
| [getValue()](#getValue--) | Contiene dati XML ben formati specifici della soluzione, con prefisso in uno spazio dei nomi esplicito e memorizzati con un documento. |
| [getVerify()](#getVerify--) | Specifica se all'utente viene chiesto di inserire informazioni sulla proprietà personalizzata per una forma quando viene creata un'istanza o la forma è duplicata o copiata. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Costruttore.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Crea una copia profonda di questa istanza.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Determina il calendario utilizzato per le proprietà personalizzate, i campi di testo e le formule degli elementi.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


L'elemento Format specifica la formattazione di una proprietà personalizzata che è una stringa, un elenco fisso, un numero, un elenco variabile, una data o ora, una durata o una valuta. Il tipo di proprietà personalizzata è specificato nell'elemento Type corrispondente.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
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


L'elemento Invisible specifica se la proprietà personalizzata è visibile nella finestra di dialogo Proprietà personalizzate in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Specifica l'etichetta che appare agli utenti nella finestra di dialogo Proprietà personalizzate.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indica l'ID locale (LCID) della lingua in cui è stata inserita la formula della cella, il testo, la proprietà personalizzata o il commento.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


L'elemento Prompt specifica il testo descrittivo o istruttivo che appare agli utenti nella finestra di dialogo Proprietà personalizzate quando la proprietà è selezionata. Questo testo appare anche come suggerimento quando il puntatore del mouse è posizionato sopra la proprietà nella finestra Proprietà personalizzate.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Specifica una chiave che determina l'ordine in cui le proprietà personalizzate sono elencate nell'interfaccia utente dell'applicazione.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Tipo specifica un tipo di dati per il valore della proprietà personalizzata.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Contiene dati XML ben formati specifici della soluzione, con prefisso in uno spazio dei nomi esplicito e memorizzati con un documento.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Specifica se all'utente viene chiesto di inserire informazioni sulla proprietà personalizzata per una forma quando viene creata un'istanza o la forma è duplicata o copiata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

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

