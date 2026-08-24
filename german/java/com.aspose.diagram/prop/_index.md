---
title: Prop
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente zur Definition benutzerdefinierter Eigenschaften und Elemente zur Zuordnung von Daten zu einer Form.
type: docs
weight: 309
url: /de/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Enthält Elemente zur Definition benutzerdefinierter Eigenschaften und Elemente zur Zuordnung von Daten zu einer Form.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Prop()](#Prop--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Bestimmt den Kalender, der für benutzerdefinierte Eigenschaften, Textfelder und Formeln von Elementen verwendet wird. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getFormat()](#getFormat--) | Format element specifies the formatting of a custom property that is a string, fixed list, number, variable list, date or time, duration, or currency. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getInvisible()](#getInvisible--) | Invisible element specifies whether the custom property is visible in the Custom Properties dialog box in Microsoft Visio. |
| [getLabel()](#getLabel--) | Specifies the label that appears to users in the Custom Properties dialog box. |
| [getLangID()](#getLangID--) | Gibt die Locale-ID (LCID) der Sprache an, in der die Zellformel, der Text, die benutzerdefinierte Eigenschaft oder der Kommentar eingegeben wurde. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getPrompt()](#getPrompt--) | Prompt element specifies descriptive or instructional text that appears to users in the Custom Properties dialog box when the property is selected. |
| [getSortKey()](#getSortKey--) | It specifies a key that determines the order in which custom properties are listed in the application's user interface. |
| [getType()](#getType--) | Typ gibt einen Datentyp für den benutzerdefinierten Eigenschaftswert an. |
| [getValue()](#getValue--) | Enthält lösungsspezifische, wohlgeformte XML‑Daten, die in einem expliziten Namensraum vorangestellt sind und zusammen mit einem Dokument gespeichert werden. |
| [getVerify()](#getVerify--) | Specifies whether the user is queried to enter custom property information for a shape when an instance is created or the shape is duplicated or copied. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Das Format-Element gibt die Formatierung einer benutzerdefinierten Eigenschaft an, die ein Zeichenfolge, eine feste Liste, eine Zahl, eine variable Liste, ein Datum oder eine Uhrzeit, eine Dauer oder eine Währung ist. Der Typ der benutzerdefinierten Eigenschaft wird im entsprechenden Typ-Element angegeben.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible element specifies whether the custom property is visible in the Custom Properties dialog box in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Specifies the label that appears to users in the Custom Properties dialog box.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Gibt die Locale-ID (LCID) der Sprache an, in der die Zellformel, der Text, die benutzerdefinierte Eigenschaft oder der Kommentar eingegeben wurde.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getName() {#getName--}
```
public String getName()
```


Der Name des Elements.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Der universelle Name des Elements.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Das Prompt-Element gibt beschreibenden oder anleitenden Text an, der Benutzern im Dialogfeld „Benutzerdefinierte Eigenschaften“ angezeigt wird, wenn die Eigenschaft ausgewählt ist. Dieser Text erscheint auch als Tooltip, wenn der Mauszeiger über der Eigenschaft im Fenster „Benutzerdefinierte Eigenschaften“ verweilt.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


It specifies a key that determines the order in which custom properties are listed in the application's user interface.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Typ gibt einen Datentyp für den benutzerdefinierten Eigenschaftswert an.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Enthält lösungsspezifische, wohlgeformte XML‑Daten, die in einem expliziten Namensraum vorangestellt sind und zusammen mit einem Dokument gespeichert werden.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Specifies whether the user is queried to enter custom property information for a shape when an instance is created or the shape is duplicated or copied.

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


For the description of this property, please see [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

