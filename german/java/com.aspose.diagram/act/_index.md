---
title: Act
second_title: Aspose.Diagram for Java API-Referenz
description: Definiert benutzerdefinierte Befehlsnamen, die im Kontextmenü eines Objekts erscheinen, und legt die Aktionen fest, die die Befehle ausführen.
type: docs
weight: 11
url: /de/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Definiert benutzerdefinierte Befehlsnamen, die im Kontextmenü eines Objekts erscheinen, und legt die Aktionen fest, die die Befehle ausführen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Act()](#Act--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Enthält die Formel, die ausgeführt wird, wenn ein Benutzer den in dem entsprechenden Menü‑Element definierten Befehlsnamen anklickt. |
| [getBeginGroup()](#getBeginGroup--) | Gibt an, ob über dieser Aktion ein Trennzeichen im Menü eingefügt wird. |
| [getButtonFace()](#getButtonFace--) | Identifiziert das Symbol, das neben einem Eintrag im Kontextmenü angezeigt wird. |
| [getChecked()](#getChecked--) | Bestimmt, ob neben dem Befehlsnamen im Kontextmenü einer Form ein Häkchen angezeigt wird. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDisabled()](#getDisabled--) | Das deaktivierte Element bestimmt, ob der Befehlsname im Kontextmenü angezeigt wird. |
| [getFlyoutChild()](#getFlyoutChild--) | Bestimmt, ob die Aktionszeile ein untergeordnetes Flyout‑Menü der letzten darüber liegenden Zeile ist, die kein Flyout‑Kind ist. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getInvisible()](#getInvisible--) | Das unsichtbare Element gibt an, ob die Aktion im Smart‑Tag oder Kontextmenü sichtbar ist. |
| [getMenu()](#getMenu--) | Gibt den Namen des Befehls an, der im Kontextmenü einer Form oder Seite erscheint. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getReadOnly()](#getReadOnly--) | Bestimmt, ob die Aktion im Smart‑Tag oder Kontextmenü schreibgeschützt ist. |
| [getSortKey()](#getSortKey--) | Gibt eine Zahl an, die die Reihenfolge der Aktionen bestimmt, die im Kontext‑ oder Smart‑Tag‑Menü angezeigt werden. |
| [getTagName()](#getTagName--) | Sie enthält den Namen des Smart-Tags, dem die Aktion zugeordnet ist. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Enthält die Formel, die ausgeführt wird, wenn ein Benutzer den in dem entsprechenden Menü‑Element definierten Befehlsnamen anklickt.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Gibt an, ob über dieser Aktion ein Trennzeichen im Menü eingefügt wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Identifiziert das Symbol, das neben einem Eintrag im Kontextmenü angezeigt wird.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Bestimmt, ob neben dem Befehlsnamen im Kontextmenü einer Form ein Häkchen angezeigt wird.

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


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


Das deaktivierte Element bestimmt, ob der Befehlsname im Kontextmenü angezeigt wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Bestimmt, ob die Aktionszeile ein untergeordnetes Flyout‑Menü der letzten darüber liegenden Zeile ist, die kein Flyout‑Kind ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Das unsichtbare Element gibt an, ob die Aktion im Smart‑Tag oder Kontextmenü sichtbar ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Gibt den Namen des Befehls an, der im Kontextmenü einer Form oder Seite erscheint.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Bestimmt, ob die Aktion im Smart‑Tag oder Kontextmenü schreibgeschützt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Gibt eine Zahl an, die die Reihenfolge der Aktionen bestimmt, die im Kontext‑ oder Smart‑Tag‑Menü angezeigt werden.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


Sie enthält den Namen des Smart-Tags, dem die Aktion zugeordnet ist.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/act\#getNameU--)

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

