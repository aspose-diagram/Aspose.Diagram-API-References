---
title: Ebene
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die eine einzelne Ebene und deren Eigenschaften für eine Seite definieren.
type: docs
weight: 212
url: /de/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Enthält Elemente, die eine einzelne Ebene und deren Eigenschaften für eine Seite definieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Layer()](#Layer--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Gibt an, ob eine Ebene aktiv ist. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Der Index der Farbe in der Farbpalette, die zur Anzeige der Ebene verwendet wird, oder ein RGB-Wert, der eine benutzerdefinierte Farbe außerhalb der Farbpalette angibt (zum Beispiel \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Bestimmt den Transparenzgrad für die Textfarbe einer Ebene oder Form, von 0 (vollständig undurchsichtig) bis 1 (vollständig transparent). |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getGlue()](#getGlue--) | Gibt an, ob Formen, die zur Ebene gehören, angeheftet werden können. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getLock()](#getLock--) | Gibt an, ob Formen, die zur Ebene gehören, gegen Auswahl oder Bearbeitung gesperrt sind. |
| [getName()](#getName--) | Das Name-Element gibt den Namen einer Ebene an. |
| [getNameUniv()](#getNameUniv--) | Gibt den universellen Namen einer Ebene an. |
| [getPrint()](#getPrint--) | Gibt an, ob Formen, die zur Ebene gehören, beim Drucken der Zeichnung gedruckt werden. |
| [getSnap()](#getSnap--) | Gibt an, ob andere Formen an Formen, die der Ebene zugewiesen sind, einrasten können. |
| [getStatus()](#getStatus--) | Gibt an, ob die Ebene eine gültige Ebene für ein Dokument ist. |
| [getVisible()](#getVisible--) | Gibt an, ob Formen, die zur Ebene gehören, auf der Zeichenfläche sichtbar sind. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Ein Flag, das angibt, ob das Element lokal geprüft wurde. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Konstruktor.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Gibt an, ob eine Ebene aktiv ist. Formen, die nicht vorher einer Ebene zugewiesen wurden, werden beim Ablegen auf der Zeichenfläche den aktiven Ebene(n) zugewiesen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Der Index der Farbe in der Farbpalette, die zur Anzeige der Ebene verwendet wird, oder ein RGB-Wert, der eine benutzerdefinierte Farbe außerhalb der Farbpalette angibt (zum Beispiel \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Bestimmt den Transparenzgrad für die Textfarbe einer Ebene oder Form, von 0 (vollständig undurchsichtig) bis 1 (vollständig transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Gibt an, ob Formen, die zur Ebene gehören, angeheftet werden können.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Gibt an, ob Formen, die zur Ebene gehören, gegen Auswahl oder Bearbeitung gesperrt sind.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Das Name-Element gibt den Namen einer Ebene an.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Gibt den universellen Namen einer Ebene an.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Gibt an, ob Formen, die zur Ebene gehören, beim Drucken der Zeichnung gedruckt werden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Gibt an, ob andere Formen an Formen, die der Ebene zugewiesen sind, einrasten können. Formen, die der Ebene zugewiesen sind, können an andere Formen einrasten, aber andere Formen können nicht an ihnen einrasten.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Gibt an, ob die Ebene eine gültige Ebene für ein Dokument ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Gibt an, ob Formen, die zur Ebene gehören, auf der Zeichenfläche sichtbar sind.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Ein Flag, das angibt, ob das Element lokal geprüft wurde. Ein Wert von 1 bedeutet, dass das Element lokal geprüft wurde.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

