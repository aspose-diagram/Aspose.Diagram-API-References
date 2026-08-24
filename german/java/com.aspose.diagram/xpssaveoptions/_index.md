---
title: XPSSaveOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu XPS.
type: docs
weight: 453
url: /de/java/com.aspose.diagram/xpssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XPSSaveOptions extends SaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu XPS.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XPSSaveOptions()](#XPSSaveOptions--) | Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um ein Dokument im Format Aspose.Diagram.SaveFileFormat zu speichern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie in PDF, Bild oder XPS als Block erscheinen. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definiert, ob die versteckte Seite exportiert werden soll oder nicht. |
| [getPageCount()](#getPageCount--) | die Anzahl der Seiten, die in XPS gerendert werden sollen. |
| [getPageIndex()](#getPageIndex--) | der nullbasierte Index der ersten zu rendernden Seite. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Gibt an, ob alle Seiten als Bild gespeichert werden oder nur der Vordergrund. |
| [getSaveFormat()](#getSaveFormat--) | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionen-Objekt verwendet wird. |
| [getWarningCallback()](#getWarningCallback--) | Warnungs-Callback. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XPSSaveOptions() {#XPSSaveOptions--}
```
public XPSSaveOptions()
```


Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um ein Dokument im Format Aspose.Diagram.SaveFileFormat zu speichern.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| saveFormat | int | Das Aspose.Diagram.SaveFileFormat, für das ein Save-Optionen-Objekt erstellt werden soll. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie im PDF, Bild oder XPS als Block erscheinen. Setzen Sie die DefaultFont, z. B. MingLiu oder MS Gothic, um diese Zeichen anzuzeigen.

**Returns:**
java.lang.String
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Definiert, ob versteckte Seiten exportiert werden sollen oder nicht. Standardwert ist true.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


die Anzahl der Seiten, die in XPS gerendert werden sollen. Standard ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Der nullbasierte Index der ersten zu rendernden Seite. Standard ist 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Legt fest, ob alle Seiten im Bild gespeichert werden oder nur der Vordergrund. Wenn true – werden nur Vordergrundseiten gerendert (mit Hintergrund, falls vorhanden). Wenn false – werden Vordergrundseiten gerendert (mit Hintergrund, falls vorhanden) und danach leere Hintergrundseiten. Kann nur true zurückgeben, wenn PageCount > 1. Der Standardwert ist false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionsobjekt verwendet wird. Kann nur Aspose.Diagram.SaveFileFormat sein.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


Warnungs-Callback.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

