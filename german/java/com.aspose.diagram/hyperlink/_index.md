---
title: Hyperlink
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente zum Erstellen mehrerer Sprünge zwischen einer Form oder Zeichenfläche und einer anderen Zeichenfläche, einer anderen Datei oder einer Website.
type: docs
weight: 193
url: /de/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Enthält Elemente zum Erstellen mehrerer Sprünge zwischen einer Form oder Zeichenfläche und einer anderen Zeichenfläche, einer anderen Datei oder einer Website.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Gibt eine URL-Adresse, einen DOS-Dateinamen oder einen UNC-Pfad an, zu dem gesprungen werden soll. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Gibt den Standard-Hyperlink für eine Form oder Seite an. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDescription()](#getDescription--) | Das Beschreibungselement enthält eine Textzeichenfolge, die den Hyperlink beschreibt. |
| [getExtraInfo()](#getExtraInfo--) | Enthält Informationen, die zur Auflösung einer URL verwendet werden, wie z. B. die Koordinaten einer Image-Map. |
| [getFrame()](#getFrame--) | Enthält den Namen eines Frames, auf den zugegriffen werden soll, wenn Microsoft Visio als aktives Dokument in einer Container-Anwendung geöffnet ist. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getInvisible()](#getInvisible--) | Unsichtbares Element gibt an, ob ein Hyperlink im Kontextmenü für eine Form oder Seite angezeigt wird. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getNewWindow()](#getNewWindow--) | Gibt an, ob Microsoft Visio ein Fenster an einem neuen Ort öffnet, wenn es einem Hyperlink folgt, um eine Webseite oder ein anderes Visio-Dokument zu öffnen. |
| [getSortKey()](#getSortKey--) | Unsichtbares Element gibt an, ob ein Hyperlink im Kontextmenü für eine Form oder Seite angezeigt wird. |
| [getSubAddress()](#getSubAddress--) | Gibt einen Ort im Zieldokument an, zu dem verlinkt werden soll. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Gibt eine URL-Adresse, einen DOS-Dateinamen oder einen UNC-Pfad an, zu dem gesprungen werden soll.

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


Gibt den Standard-Hyperlink für eine Form oder Seite an.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Das Beschreibungselement enthält eine Textzeichenfolge, die den Hyperlink beschreibt.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Enthält Informationen, die zur Auflösung einer URL verwendet werden, wie z. B. die Koordinaten einer Image-Map. Zum Beispiel würde x=41 y=7 die Koordinaten einer Image-Map angeben.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Enthält den Namen eines Frames, auf den zugegriffen werden soll, wenn Microsoft Visio als aktives Dokument in einer Container-Anwendung geöffnet ist. Der Standardwert ist eine leere Zeichenfolge.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Unsichtbares Element gibt an, ob ein Hyperlink im Kontextmenü für eine Form oder Seite angezeigt wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Gibt an, ob Microsoft Visio ein Fenster an einem neuen Ort öffnet, wenn es einem Hyperlink folgt, um eine Webseite oder ein anderes Visio-Dokument zu öffnen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Unsichtbares Element gibt an, ob ein Hyperlink im Kontextmenü für eine Form oder Seite angezeigt wird.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Gibt einen Ort im Zieldokument an, zu dem verlinkt werden soll.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

