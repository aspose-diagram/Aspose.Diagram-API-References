---
title: Schutz
second_title: Aspose.Diagram for Java API-Referenz
description: Sperren hilft, unbeabsichtigte Änderungen an der Form zu verhindern, verhindert jedoch nicht, dass Microsoft Visio Werte unter anderen Umständen zurücksetzt.
type: docs
weight: 312
url: /de/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Das Sperren hilft, unbeabsichtigte Änderungen an der Form zu verhindern, verhindert jedoch nicht, dass Microsoft Visio Werte unter anderen Umständen zurücksetzt. Es schützt auch nicht vor Änderungen, die im ShapeSheet‑Fenster vorgenommen werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getLockAspect()](#getLockAspect--) | Gibt an, ob das Seitenverhältnis der Form gesperrt ist. |
| [getLockBegin()](#getLockBegin--) | Gibt an, ob der Anfangspunkt einer 1-D-Form an einem bestimmten Ort gesperrt ist. |
| [getLockCalcWH()](#getLockCalcWH--) | Gibt an, ob das Auswahlrechteck einer Form gesperrt ist, sodass es nicht neu berechnet wird, wenn ein Scheitelpunkt bearbeitet oder ein Elementtyp im Geom-Element geändert wird. |
| [getLockCrop()](#getLockCrop--) | Gibt an, ob ein fremdes Objekt daran gehindert wird, mit dem Zuschneidewerkzeug in Microsoft Visio beschnitten zu werden. |
| [getLockCustProp()](#getLockCustProp--) | Bestimmt, ob der Benutzer benutzerdefinierte Eigenschaften in der Benutzeroberfläche (UI) über das Dialogfeld „Define Custom Properties“ hinzufügen, löschen oder ändern kann. |
| [getLockDelete()](#getLockDelete--) | Gibt an, ob eine Form vor dem Löschen geschützt ist. |
| [getLockEnd()](#getLockEnd--) | Gibt an, ob der Endpunkt einer 1-D-Form an einem bestimmten Ort gesperrt ist. |
| [getLockFormat()](#getLockFormat--) | Gibt an, ob die Formatierung einer Form gesperrt ist, sodass sie nicht geändert werden kann. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Ermöglicht es einer Unterform, Formatierungsänderungen zu blockieren, die auf eine übergeordnete Gruppierungsform in der Visio-Benutzeroberfläche angewendet werden und sonst auf einzelne Gruppierungsformen heruntergereicht würden. |
| [getLockGroup()](#getLockGroup--) | Gibt an, ob eine Gruppe gesperrt ist, sodass sie nicht aufgelöst werden kann. |
| [getLockHeight()](#getLockHeight--) | Gibt an, ob die Höhe der Form gesperrt ist. |
| [getLockMoveX()](#getLockMoveX--) | Gibt an, ob die horizontale Position der Form gesperrt ist, sodass sie nicht horizontal verschoben werden kann. |
| [getLockMoveY()](#getLockMoveY--) | Gibt an, ob die vertikale Position der Form gesperrt ist, sodass sie nicht vertikal verschoben werden kann. |
| [getLockRotate()](#getLockRotate--) | Gibt an, ob die Form daran gehindert wird, mit dem Rotationswerkzeug oder den Befehlen „Rotate Left“ bzw. „Rotate Right“ in Microsoft Visio gedreht zu werden. |
| [getLockSelect()](#getLockSelect--) | Gibt an, ob das Auswahlrechteck einer Form gesperrt ist, sodass es nicht neu berechnet wird, wenn ein Scheitelpunkt bearbeitet oder ein Elementtyp im Geom-Element geändert wird. |
| [getLockTextEdit()](#getLockTextEdit--) | Gibt an, ob der Text einer Form gesperrt ist, sodass er nicht bearbeitet werden kann. |
| [getLockThemeColors()](#getLockThemeColors--) | Verhindert, dass Benutzer Themenfarben auf die Form anwenden. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Verhindert, dass Benutzer Themen‑Effekte auf die Form anwenden. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Gibt an, ob die Scheitelpunkte einer Form gesperrt sind, sodass sie mit keinen Werkzeugen in der Symbolleiste bearbeitet werden können. |
| [getLockWidth()](#getLockWidth--) | Gibt an, ob die Breite der Form gesperrt ist, sodass sie beim Ändern der Größe der Form unverändert bleibt. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Gibt an, ob das Seitenverhältnis der Form gesperrt ist. Wenn gesperrt, kann die Form nur proportional skaliert werden; sie kann nicht in einer einzigen Dimension skaliert werden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Gibt an, ob der Anfangspunkt einer 1-D-Form an einem bestimmten Ort gesperrt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Gibt an, ob das Auswahlrechteck einer Form gesperrt ist, sodass es nicht neu berechnet wird, wenn ein Scheitelpunkt bearbeitet oder ein Elementtyp im Geom-Element geändert wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Gibt an, ob ein fremdes Objekt daran gehindert wird, mit dem Zuschneidewerkzeug in Microsoft Visio beschnitten zu werden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Bestimmt, ob der Benutzer benutzerdefinierte Eigenschaften in der Benutzeroberfläche (UI) über das Dialogfeld „Define Custom Properties“ hinzufügen, löschen oder ändern kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Gibt an, ob eine Form vor dem Löschen geschützt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Gibt an, ob der Endpunkt einer 1-D-Form an einem bestimmten Ort gesperrt ist.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Gibt an, ob die Formatierung einer Form gesperrt ist, sodass sie nicht geändert werden kann. Insbesondere schützt dieses Element vor Änderungen der Text‑, Linien‑ und Füllformatierung oder davor, welches Style‑Element die Form erbt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Ermöglicht es einer Unterform, Formatierungsänderungen zu blockieren, die auf eine übergeordnete Gruppierungsform in der Visio-Benutzeroberfläche angewendet werden und sonst auf einzelne Gruppierungsformen heruntergereicht würden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Gibt an, ob eine Gruppe gesperrt ist, sodass sie nicht aufgelöst werden kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Gibt an, ob die Höhe der Form gesperrt ist. Wenn gesperrt, bleibt ihre Höhe beim Ändern der Größe der Form unverändert.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Gibt an, ob die horizontale Position der Form gesperrt ist, sodass sie nicht horizontal verschoben werden kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Gibt an, ob die vertikale Position der Form gesperrt ist, sodass sie nicht vertikal verschoben werden kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Gibt an, ob die Form daran gehindert wird, mit dem Rotationswerkzeug oder den Befehlen „Rotate Left“ bzw. „Rotate Right“ in Microsoft Visio gedreht zu werden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Gibt an, ob das Auswahlrechteck einer Form gesperrt ist, sodass es nicht neu berechnet wird, wenn ein Scheitelpunkt bearbeitet oder ein Elementtyp im Geom-Element geändert wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Gibt an, ob der Text einer Form gesperrt ist, sodass er nicht bearbeitet werden kann. Der Text kann jedoch weiterhin formatiert werden, indem ein Stil angewendet wird, über die Stil‑Optionen im Register Schriftart des Text‑Dialogfelds.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Verhindert, dass Benutzer Themenfarben auf die Form anwenden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Verhindert, dass Benutzer Themen‑Effekte auf die Form anwenden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Gibt an, ob die Scheitelpunkte einer Form gesperrt sind, sodass sie mit keinen Werkzeugen in der Symbolleiste bearbeitet werden können.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Gibt an, ob die Breite der Form gesperrt ist, sodass sie beim Ändern der Größe der Form unverändert bleibt.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

