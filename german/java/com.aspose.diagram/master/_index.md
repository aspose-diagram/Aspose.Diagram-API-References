---
title: Master
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die einen Master für das Dokument definieren.
type: docs
weight: 240
url: /de/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Enthält Elemente, die einen Master für das Dokument definieren. Ein Master ist eine Form auf einer Schablone, die Sie wiederholt zum Erstellen von Zeichnungen verwenden. Wenn Sie eine Form von einer Schablone auf die Zeichenfläche ziehen, wird die Form zu einer Instanz dieses Masters, und eine lokale Kopie des Masters wird in das Dokument aufgenommen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Master()](#Master--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [dispose()](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Gibt an, ob der Text des Masters im Schablonenfenster linksbündig, rechtsbündig oder zentriert ausgerichtet ist. |
| [getBaseID()](#getBaseID--) | Eine GUID (global eindeutiger Bezeichner), die den Master über Dokumente hinweg identifiziert. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Enthält ein Connect-Element für jede Verbindung zwischen zwei Formen in einer Zeichnung. |
| [getHidden()](#getHidden--) | Gibt an, ob der Master in der Benutzeroberfläche ausgeblendet ist. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getIcon()](#getIcon--) | Gibt ein MIME (Multipurpose Internet Mail Extensions) codiertes Binär-Icon (im .ico-Format) für ein Master- oder MasterShortcut-Element in einem Dokument an. |
| [getIconSize()](#getIconSize--) | Die Größe des Icons des Elements. |
| [getIconUpdate()](#getIconUpdate--) | Gibt an, ob das Icon automatisch aus dem Master selbst generiert wird. |
| [getMatchByName()](#getMatchByName--) | Das MatchByName-Attribut bestimmt, wie Microsoft Visio entscheidet, ob ein Dokument-Master bereits vorhanden ist, wenn eine Instanz eines Masters auf die Zeichenfläche gezogen wird. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getPageSheet()](#getPageSheet--) | Enthält Elemente, die das Seitenblatt für ein Seiten‑ oder Master‑Element definieren. |
| [getPatternFlags()](#getPatternFlags--) | Das PatternFlags-Attribut bestimmt, ob ein Master sich wie ein benutzerdefiniertes Muster verhält. |
| [getPrompt()](#getPrompt--) | Die Statusleiste und der Tooltip geben Hinweise für das Element. |
| [getShapes()](#getShapes--) | Sammlung von Shape-Objekten. |
| [getUniqueID()](#getUniqueID--) | Eine GUID, die den Master im Dokument identifiziert. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Gibt an, ob der Text des Masters im Schablonenfenster linksbündig, rechtsbündig oder zentriert ausgerichtet ist.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


Eine GUID (global eindeutiger Bezeichner), die den Master über Dokumente hinweg identifiziert.

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


Enthält ein Connect-Element für jede Verbindung zwischen zwei Formen in einer Zeichnung.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Gibt an, ob der Master in der Benutzeroberfläche ausgeblendet ist.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Gibt ein MIME (Multipurpose Internet Mail Extensions) codiertes Binär-Icon (im .ico-Format) für ein Master- oder MasterShortcut-Element in einem Dokument an.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


Die Größe des Icons des Elements.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Gibt an, ob das Icon automatisch aus dem Master selbst generiert wird.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


Das MatchByName-Attribut bestimmt, wie Microsoft Visio entscheidet, ob ein Dokument-Master bereits vorhanden ist, wenn eine Instanz eines Masters auf die Zeichenfläche gezogen wird. Es ermöglicht, dass Änderungen an einem Dokument-Master auf neue Instanzen des Masters angewendet werden, selbst wenn die Instanzen aus einer eigenständigen Stencil-Datei gezogen werden.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Enthält Elemente, die das Seitenblatt für ein Seiten‑ oder Master‑Element definieren.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


Das PatternFlags-Attribut bestimmt, ob ein Master sich wie ein benutzerdefiniertes Muster verhält.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


Die Statusleiste und der Tooltip geben Hinweise für das Element.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Sammlung von Shape-Objekten.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Eine GUID, die den Master im Dokument identifiziert.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

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

