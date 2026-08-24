---
title: DocumentSettings
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die Dokumenteinstellungen festlegen.
type: docs
weight: 126
url: /de/java/com.aspose.diagram/documentsettings/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSettings
```

Enthält Elemente, die Dokumenteinstellungen festlegen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachedToolbars()](#getAttachedToolbars--) | Eine MIME (Multipurpose Internet Mail Extensions) codierte Microsoft Visio-Benutzeroberflächen‑Datei (VSU), die benutzerdefinierte Symbolleisten darstellt. |
| [getClass()](#getClass--) |  |
| [getCustomMenusFile()](#getCustomMenusFile--) | Enthält den Namen der Microsoft Visio-Benutzeroberflächen‑Datei (.vsu), die benutzerdefinierte Menüs und Tastenkombinationen für ein Dokument definiert. |
| [getCustomToolbarsFile()](#getCustomToolbarsFile--) | Enthält den Namen der Microsoft Visio-Benutzeroberflächen‑Datei (.vsu), die benutzerdefinierte Symbolleisten und Statusleisten für ein Dokument definiert. |
| [getDefaultFillStyle()](#getDefaultFillStyle--) | Gibt die ID eines StyleSheet-Elements an. |
| [getDefaultGuideStyle()](#getDefaultGuideStyle--) | Gibt die ID eines StyleSheet-Elements an. |
| [getDefaultLineStyle()](#getDefaultLineStyle--) | Gibt die ID eines StyleSheet-Elements an. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Gibt die ID eines StyleSheet-Elements an. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Gibt an, ob die dynamische Rasterfunktion für ein Dokument oder Fenster aktiviert ist. |
| [getGlueSettings()](#getGlueSettings--) | Gibt die Objekte an, an die Formen geklebt werden, wenn Kleben im Dokument aktiviert ist. |
| [getProtectBkgnds()](#getProtectBkgnds--) | Gibt an, ob der Benutzer daran gehindert wird, Hintergrundseiten zu löschen oder zu bearbeiten. |
| [getProtectMasters()](#getProtectMasters--) | Gibt an, ob der Benutzer daran gehindert wird, Master zu erstellen, zu bearbeiten oder zu löschen. |
| [getProtectShapes()](#getProtectShapes--) | Gibt an, ob der Benutzer daran gehindert wird, Formen auszuwählen, deren LockSelect-Element auf 1 gesetzt ist. |
| [getProtectStyles()](#getProtectStyles--) | Gibt an, ob der Benutzer daran gehindert wird, Stile zu erstellen oder zu bearbeiten. |
| [getSnapAngles()](#getSnapAngles--) | Enthält eine Sammlung von SnapAngle-Elementen. |
| [getSnapExtensions()](#getSnapExtensions--) | Gibt an, ob eine bestimmte Snap‑Erweiterungseinstellung für das aktive Fenster aktiviert oder deaktiviert ist. |
| [getSnapSettings()](#getSnapSettings--) | Gibt die Objekte an, an die Formen einrasten, wenn das Einrasten im Fenster aktiv ist. |
| [getTopPage()](#getTopPage--) | Gibt die ID der Seite an, die angezeigt werden soll, wenn das Dokument von Microsoft Visio geöffnet wird. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachedToolbars(byte[] value)](#setAttachedToolbars-byte---) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\\#getAttachedToolbars--) |
| [setCustomMenusFile(String value)](#setCustomMenusFile-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\\#getCustomMenusFile--) |
| [setCustomToolbarsFile(String value)](#setCustomToolbarsFile-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\\#getCustomToolbarsFile--) |
| [setDefaultFillStyle(int value)](#setDefaultFillStyle-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultFillStyle--) |
| [setDefaultGuideStyle(int value)](#setDefaultGuideStyle-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultGuideStyle--) |
| [setDefaultLineStyle(int value)](#setDefaultLineStyle-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultLineStyle--) |
| [setDefaultTextStyle(int value)](#setDefaultTextStyle-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultTextStyle--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getGlueSettings()](../../com.aspose.diagram/documentsettings\\#getGlueSettings--) |
| [setProtectBkgnds(int value)](#setProtectBkgnds-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\\#getProtectBkgnds--) |
| [setProtectMasters(int value)](#setProtectMasters-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectMasters()](../../com.aspose.diagram/documentsettings\\#getProtectMasters--) |
| [setProtectShapes(int value)](#setProtectShapes-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectShapes()](../../com.aspose.diagram/documentsettings\\#getProtectShapes--) |
| [setProtectStyles(int value)](#setProtectStyles-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectStyles()](../../com.aspose.diagram/documentsettings\\#getProtectStyles--) |
| [setSnapAngles(FloatPointNumCollection value)](#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapAngles()](../../com.aspose.diagram/documentsettings\\#getSnapAngles--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapExtensions()](../../com.aspose.diagram/documentsettings\\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapSettings()](../../com.aspose.diagram/documentsettings\\#getSnapSettings--) |
| [setTopPage(int value)](#setTopPage-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTopPage()](../../com.aspose.diagram/documentsettings\\#getTopPage--) |
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
### getAttachedToolbars() {#getAttachedToolbars--}
```
public byte[] getAttachedToolbars()
```


Eine MIME (Multipurpose Internet Mail Extensions) codierte Microsoft Visio-Benutzeroberflächen‑Datei (VSU), die benutzerdefinierte Symbolleisten darstellt.

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomMenusFile() {#getCustomMenusFile--}
```
public String getCustomMenusFile()
```


Enthält den Namen der Microsoft Visio-Benutzeroberflächen‑Datei (.vsu), die benutzerdefinierte Menüs und Tastenkombinationen für ein Dokument definiert.

**Returns:**
java.lang.String
### getCustomToolbarsFile() {#getCustomToolbarsFile--}
```
public String getCustomToolbarsFile()
```


Enthält den Namen der Microsoft Visio-Benutzeroberflächen‑Datei (.vsu), die benutzerdefinierte Symbolleisten und Statusleisten für ein Dokument definiert.

**Returns:**
java.lang.String
### getDefaultFillStyle() {#getDefaultFillStyle--}
```
public int getDefaultFillStyle()
```


Gibt die ID eines StyleSheet-Elements an. Wenn der Benutzer das nächste Mal eine Form mit einem Zeichenwerkzeug erstellt, erbt die Form ihren Füllstil vom angegebenen StyleSheet-Element.

**Returns:**
int
### getDefaultGuideStyle() {#getDefaultGuideStyle--}
```
public int getDefaultGuideStyle()
```


Gibt die ID eines StyleSheet-Elements an. Wenn der Benutzer das nächste Mal eine Führungslinie erstellt, erbt die Führungslinie ihren Führungsstil vom angegebenen StyleSheet-Element.

**Returns:**
int
### getDefaultLineStyle() {#getDefaultLineStyle--}
```
public int getDefaultLineStyle()
```


Gibt die ID eines StyleSheet-Elements an. Wenn der Benutzer das nächste Mal eine Form mit einem Zeichenwerkzeug erstellt, erbt die Form ihren Linienstil vom angegebenen StyleSheet-Element.

**Returns:**
int
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public int getDefaultTextStyle()
```


Gibt die ID eines StyleSheet-Elements an. Wenn der Benutzer das nächste Mal eine Form mit einem Zeichenwerkzeug erstellt, erbt die Form ihren Textstil vom angegebenen StyleSheet-Element.

**Returns:**
int
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Gibt an, ob die dynamische Rasterfunktion für ein Dokument oder Fenster aktiviert ist.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Gibt die Objekte an, an die Formen geklebt werden, wenn Kleben im Dokument aktiviert ist.

**Returns:**
int
### getProtectBkgnds() {#getProtectBkgnds--}
```
public int getProtectBkgnds()
```


Gibt an, ob der Benutzer daran gehindert wird, Hintergrundseiten zu löschen oder zu bearbeiten.

**Returns:**
int
### getProtectMasters() {#getProtectMasters--}
```
public int getProtectMasters()
```


Gibt an, ob der Benutzer daran gehindert wird, Master zu erstellen, zu bearbeiten oder zu löschen. Unabhängig von dieser Einstellung kann der Benutzer weiterhin Instanzen von Master erstellen.

**Returns:**
int
### getProtectShapes() {#getProtectShapes--}
```
public int getProtectShapes()
```


Gibt an, ob der Benutzer daran gehindert wird, Formen auszuwählen, deren LockSelect-Element auf 1 gesetzt ist.

**Returns:**
int
### getProtectStyles() {#getProtectStyles--}
```
public int getProtectStyles()
```


Gibt an, ob der Benutzer daran gehindert wird, Stile zu erstellen oder zu bearbeiten. Unabhängig von dieser Einstellung kann der Benutzer jedoch weiterhin Stile anwenden.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Enthält eine Sammlung von SnapAngle-Elementen.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Gibt an, ob eine bestimmte Snap‑Erweiterungseinstellung für das aktive Fenster aktiviert oder deaktiviert ist.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Gibt die Objekte an, an die Formen einrasten, wenn das Einrasten im Fenster aktiv ist.

**Returns:**
int
### getTopPage() {#getTopPage--}
```
public int getTopPage()
```


Gibt die ID der Seite an, die angezeigt werden soll, wenn das Dokument von Microsoft Visio geöffnet wird.

**Returns:**
int
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




### setAttachedToolbars(byte[] value) {#setAttachedToolbars-byte---}
```
public void setAttachedToolbars(byte[] value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\\#getAttachedToolbars--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### setCustomMenusFile(String value) {#setCustomMenusFile-java.lang.String-}
```
public void setCustomMenusFile(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\\#getCustomMenusFile--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCustomToolbarsFile(String value) {#setCustomToolbarsFile-java.lang.String-}
```
public void setCustomToolbarsFile(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\\#getCustomToolbarsFile--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDefaultFillStyle(int value) {#setDefaultFillStyle-int-}
```
public void setDefaultFillStyle(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultFillStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDefaultGuideStyle(int value) {#setDefaultGuideStyle-int-}
```
public void setDefaultGuideStyle(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultGuideStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDefaultLineStyle(int value) {#setDefaultLineStyle-int-}
```
public void setDefaultLineStyle(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultLineStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDefaultTextStyle(int value) {#setDefaultTextStyle-int-}
```
public void setDefaultTextStyle(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\\#getDefaultTextStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\\#getDynamicGridEnabled--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getGlueSettings()](../../com.aspose.diagram/documentsettings\\#getGlueSettings--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setProtectBkgnds(int value) {#setProtectBkgnds-int-}
```
public void setProtectBkgnds(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\\#getProtectBkgnds--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setProtectMasters(int value) {#setProtectMasters-int-}
```
public void setProtectMasters(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectMasters()](../../com.aspose.diagram/documentsettings\\#getProtectMasters--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setProtectShapes(int value) {#setProtectShapes-int-}
```
public void setProtectShapes(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectShapes()](../../com.aspose.diagram/documentsettings\\#getProtectShapes--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setProtectStyles(int value) {#setProtectStyles-int-}
```
public void setProtectStyles(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getProtectStyles()](../../com.aspose.diagram/documentsettings\\#getProtectStyles--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSnapAngles(FloatPointNumCollection value) {#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-}
```
public void setSnapAngles(FloatPointNumCollection value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapAngles()](../../com.aspose.diagram/documentsettings\\#getSnapAngles--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection) |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapExtensions()](../../com.aspose.diagram/documentsettings\\#getSnapExtensions--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapSettings()](../../com.aspose.diagram/documentsettings\\#getSnapSettings--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTopPage(int value) {#setTopPage-int-}
```
public void setTopPage(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTopPage()](../../com.aspose.diagram/documentsettings\\#getTopPage--)

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

