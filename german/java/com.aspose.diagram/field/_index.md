---
title: Feld
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die Funktionen und Formeln angeben, die in den Text der Formen eingefügt wurden.
type: docs
weight: 147
url: /de/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

Enthält Elemente, die Funktionen und Formeln angeben, die in den Text der Form eingefügt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Field()](#Field--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Bestimmt den Kalender, der für benutzerdefinierte Eigenschaften, Textfelder und Formeln von Elementen verwendet wird. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDisplayValue()](#getDisplayValue--) | Liefert den formatierten Zeichenkettenwert dieses Feldes. |
| [getEditMode()](#getEditMode--) | Für zukünftige Verwendung reserviert. |
| [getFormat()](#getFormat--) | Das Formatelement gibt die Formatierung für ein Textfeld an, das eine Zeichenkette, Zahl, Datum oder Uhrzeit, Dauer oder Währung ist. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getObjectKind()](#getObjectKind--) | Gibt den Typ des Textfelds an. |
| [getType()](#getType--) | Typ gibt einen Datentyp für den Textfeldwert an. |
| [getUICat()](#getUICat--) | Gibt die Kategorie eines eingefügten Feldes in Versionen von Microsoft Visio vor Visio 2000 an. |
| [getUICod()](#getUICod--) | Gibt den Code eines eingefügten Feldes in Versionen von Microsoft Visio vor Visio 2000 an. |
| [getUIFmt()](#getUIFmt--) | Gibt das Format eines eingefügten Feldes in Versionen von Microsoft Visio vor Visio 2000 an. |
| [getValue()](#getValue--) | Es enthält den Wert für ein Textfeld. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/field\#getIX--) |
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


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Bestimmt den Kalender, der für benutzerdefinierte Eigenschaften, Textfelder und Formeln von Elementen verwendet wird.

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


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


Liefert den formatierten Zeichenkettenwert dieses Feldes.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


Für zukünftige Verwendung reserviert.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


Das Format-Element gibt die Formatierung für ein Textfeld an, das ein String, eine Zahl, ein Datum oder eine Uhrzeit, eine Dauer oder eine Währung ist. Der Typ des Textfelds wird im entsprechenden Typ-Element angegeben.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


Gibt den Typ des Textfelds an.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Typ gibt einen Datentyp für den Textfeldwert an.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Gibt die Kategorie eines eingefügten Feldes in Versionen von Microsoft Visio vor Visio 2000 an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Gibt den Code eines eingefügten Feldes in Versionen von Microsoft Visio vor Visio 2000 an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Gibt das Format eines eingefügten Feldes in Versionen von Microsoft Visio vor Visio 2000 an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


Es enthält den Wert für ein Textfeld.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/field\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

