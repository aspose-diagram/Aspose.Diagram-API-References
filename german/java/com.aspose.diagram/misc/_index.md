---
title: Misc
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält verschiedene Elemente von Formen und Gruppen, wie solche, die die Auswahlhervorhebung und Sichtbarkeit steuern.
type: docs
weight: 247
url: /de/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Enthält verschiedene Elemente von Formen und Gruppen, wie solche, die die Auswahlhervorhebung und Sichtbarkeit steuern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Enthält eine von Microsoft Visio erzeugte Trigger-Formel, die bestimmt, ob der Anfangspunkt einer 1‑D‑Form verschoben werden soll, um ihre Verbindung zu einer anderen Form beizubehalten. |
| [getCalendar()](#getCalendar--) | Bestimmt den Kalender, der für benutzerdefinierte Eigenschaften, Textfelder und Formeln von Elementen verwendet wird. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Enthält den Kommentartext im Zeichenkettenformat für eine Form. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Bestimmt den Prozentsatz, um den eine Form skaliert wird, wenn sie auf die Zeichenfläche gezogen wird. |
| [getDynFeedback()](#getDynFeedback--) | Gibt den Typ des visuellen Feedbacks an, das Benutzern beim Ziehen eines Connectors bereitgestellt wird. |
| [getEndTrigger()](#getEndTrigger--) | Enthält eine von Microsoft Visio erzeugte Trigger-Formel. |
| [getGlueType()](#getGlueType--) | Gibt an, ob dynamisches (Form-zu-Form) Kleben beim Verbinden mit einer Form erlaubt ist. |
| [getHideText()](#getHideText--) | Blendet den Text einer Form aus. |
| [getLangID()](#getLangID--) | Gibt die Locale-ID (LCID) der Sprache an, in der die Zellformel, der Text, die benutzerdefinierte Eigenschaft oder der Kommentar eingegeben wurde. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Bestimmt, ob Formen lokalisiert werden (ob ihr LangID-Element zurückgesetzt wird), wenn sie zwischen Dokumenten kopiert werden. |
| [getNoAlignBox()](#getNoAlignBox--) | Gibt an, ob das Auswahlrechteck angezeigt wird, wenn die Form ausgewählt ist. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Gibt an, ob Steuerungsgriffe angezeigt werden, wenn die Form ausgewählt ist. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Gibt an, ob eine Form dynamisch ihre Größe ändert oder rotiert, während der Benutzer sie manipuliert. |
| [getNoObjHandles()](#getNoObjHandles--) | Gibt an, ob Auswahlgriffe angezeigt werden, wenn die Form ausgewählt ist. |
| [getNonPrinting()](#getNonPrinting--) | Gibt an, ob eine ausgewählte Form gedruckt werden kann. |
| [getObjType()](#getObjType--) | Gibt an, ob Objekte in Diagrammen platzierbar oder routbar sind, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden. |
| [getShapeKeywords()](#getShapeKeywords--) | Enthält Suchbegriffe, die benutzerdefinierten Masterformen zugewiesen wurden. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Gibt an, ob das Auswahlrechteck einer Form neu berechnet werden soll, sobald ein Steuerungsgriff verschoben wird. |
| [getWalkPreference()](#getWalkPreference--) | Gibt an, ob ein Endpunkt einer 1‑D‑Form zu einem horizontalen oder vertikalen Verbindungspunkt der Form, an die sie geklebt ist, mit dynamischem Kleben verschoben wird, wenn die Form in eine mehrdeutige Position bewegt wird. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Gibt an, ob die Form zu einer Gruppe hinzugefügt werden kann, indem sie auf die Gruppe gezogen wird. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Zeigt an, ob die Werte der angegebenen Zellen in einer Masterform die Werte (einschließlich lokaler Werte) einer ersetzten Form während eines Formersetzungs‑Vorgangs überschreiben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/misc\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Enthält eine von Microsoft Visio erzeugte Trigger-Formel, die bestimmt, ob der Anfangspunkt einer 1‑D‑Form verschoben werden soll, um ihre Verbindung zu einer anderen Form beizubehalten.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getComment() {#getComment--}
```
public Str2Value getComment()
```


Enthält den Kommentartext im Zeichenkettenformat für eine Form.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Bestimmt den Prozentsatz, um den eine Form skaliert wird, wenn sie auf die Zeichenfläche gezogen wird.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Gibt den Typ des visuellen Feedbacks an, das Benutzern beim Ziehen eines Connectors bereitgestellt wird.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Enthält eine von Microsoft Visio erzeugte Trigger-Formel. Diese Trigger-Formel bestimmt, ob der Endpunkt einer 1‑D‑Form verschoben werden soll, um ihre Verbindung zu einer anderen Form beizubehalten.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Gibt an, ob dynamisches (Form-zu-Form) Kleben beim Verbinden mit einer Form erlaubt ist.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Blendet den Text für eine Form aus. Sie können den Text anzeigen, Eigenschaften bearbeiten und Stile auf den Text im Textblock anwenden, obwohl die Änderungen erst sichtbar werden, wenn Sie das HideText-Element auf 0 setzen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Gibt die Locale-ID (LCID) der Sprache an, in der die Zellformel, der Text, die benutzerdefinierte Eigenschaft oder der Kommentar eingegeben wurde.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Bestimmt, ob Formen lokalisiert werden (ob ihr LangID-Element zurückgesetzt wird), wenn sie zwischen Dokumenten kopiert werden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Gibt an, ob das Auswahlrechteck angezeigt wird, wenn die Form ausgewählt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Gibt an, ob Steuerungsgriffe angezeigt werden, wenn die Form ausgewählt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Gibt an, ob eine Form dynamisch ihre Größe ändert oder rotiert, während der Benutzer sie manipuliert.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Gibt an, ob Auswahlgriffe angezeigt werden, wenn die Form ausgewählt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Gibt an, ob eine ausgewählte Form gedruckt werden kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Gibt an, ob Objekte in Diagrammen platzierbar oder routbar sind, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Enthält Suchbegriffe, die benutzerdefinierten Masterformen zugewiesen wurden.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Gibt an, ob das Auswahlrechteck einer Form neu berechnet werden soll, sobald ein Steuerungsgriff verschoben wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Gibt an, ob ein Endpunkt einer 1‑D‑Form zu einem horizontalen oder vertikalen Verbindungspunkt der Form, an die sie geklebt ist, mit dynamischem Kleben verschoben wird, wenn die Form in eine mehrdeutige Position bewegt wird.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


Gibt an, ob die Form zu einer Gruppe hinzugefügt werden kann, indem sie auf die Gruppe gezogen wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Zeigt an, ob die Werte der angegebenen Zellen in einer Masterform die Werte (einschließlich lokaler Werte) einer ersetzten Form während eines Formersetzungs‑Vorgangs überschreiben.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

