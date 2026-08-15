---
title: Fält
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som specificerar funktioner och formler som infogats i formens text.
type: docs
weight: 147
url: /sv/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

Innehåller element som specificerar funktioner och formler som infogas i formens text.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Field()](#Field--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Bestämmer den kalender som används för anpassade egenskaper, textfält och elementformler. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDisplayValue()](#getDisplayValue--) | Hämtar det formaterade strängvärdet för detta fält. |
| [getEditMode()](#getEditMode--) | Reserverad för framtida användning. |
| [getFormat()](#getFormat--) | Format‑elementet specificerar formateringen för ett textfält som är en sträng, ett tal, datum eller tid, varaktighet eller valuta. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getObjectKind()](#getObjectKind--) | Anger typen av textfält. |
| [getType()](#getType--) | Typ anger en datatyp för textfältets värde. |
| [getUICat()](#getUICat--) | Specificerar kategorin för ett infogat fält i versioner av Microsoft Visio tidigare än Visio 2000. |
| [getUICod()](#getUICod--) | Specificerar koden för ett infogat fält i versioner av Microsoft Visio tidigare än Visio 2000. |
| [getUIFmt()](#getUIFmt--) | Specificerar formatet för ett infogat fält i versioner av Microsoft Visio tidigare än Visio 2000. |
| [getValue()](#getValue--) | Den innehåller värdet för ett textfält. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Bestämmer den kalender som används för anpassade egenskaper, textfält och elementformler.

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


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


Hämtar det formaterade strängvärdet för detta fält.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


Reserverad för framtida användning.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


Format‑elementet anger formateringen för ett textfält som är en sträng, ett tal, ett datum eller en tid, en varaktighet eller en valuta. Textfältstypen anges i motsvarande Type‑element.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


Anger typen av textfält.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Typ anger en datatyp för textfältets värde.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Specificerar kategorin för ett infogat fält i versioner av Microsoft Visio tidigare än Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Specificerar koden för ett infogat fält i versioner av Microsoft Visio tidigare än Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Specificerar formatet för ett infogat fält i versioner av Microsoft Visio tidigare än Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


Den innehåller värdet för ett textfält.

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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/field\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

