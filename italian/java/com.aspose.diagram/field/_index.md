---
title: Campo
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che specificano funzioni e formule inserite nel testo delle forme.
type: docs
weight: 147
url: /it/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

Contiene elementi che specificano funzioni e formule inserite nel testo della forma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Field()](#Field--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Determina il calendario utilizzato per le proprietà personalizzate, i campi di testo e le formule degli elementi. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDisplayValue()](#getDisplayValue--) | Ottiene il valore stringa formattato di questo campo. |
| [getEditMode()](#getEditMode--) | Riservato per uso futuro. |
| [getFormat()](#getFormat--) | L'elemento Format specifica la formattazione per un campo di testo che è una stringa, numero, data o ora, durata o valuta. |
| [getIX()](#getIX--) | L'indice basato su zero dell'elemento all'interno del suo elemento genitore. |
| [getObjectKind()](#getObjectKind--) | Indica il tipo di campo di testo. |
| [getType()](#getType--) | Tipo specifica un tipo di dati per il valore del campo di testo. |
| [getUICat()](#getUICat--) | Specifica la categoria di un campo inserito nelle versioni di Microsoft Visio precedenti a Visio 2000. |
| [getUICod()](#getUICod--) | Specifica il codice di un campo inserito nelle versioni di Microsoft Visio precedenti a Visio 2000. |
| [getUIFmt()](#getUIFmt--) | Specifica il formato di un campo inserito nelle versioni di Microsoft Visio precedenti a Visio 2000. |
| [getValue()](#getValue--) | Contiene il valore per un campo di testo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


Ottiene il valore stringa formattato di questo campo.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


Riservato per uso futuro.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


L'elemento Format specifica la formattazione per un campo di testo che è una stringa, un numero, una data o ora, una durata o una valuta. Il tipo di campo di testo è specificato nell'elemento Type corrispondente.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basato su zero dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


Indica il tipo di campo di testo.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Tipo specifica un tipo di dati per il valore del campo di testo.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Specifica la categoria di un campo inserito nelle versioni di Microsoft Visio precedenti a Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Specifica il codice di un campo inserito nelle versioni di Microsoft Visio precedenti a Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Specifica il formato di un campo inserito nelle versioni di Microsoft Visio precedenti a Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


Contiene il valore per un campo di testo.

**Returns:**
[Value](../../com.aspose.diagram/value)
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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Per la descrizione di questa proprietà, vedere [getIX()](../../com.aspose.diagram/field\#getIX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

