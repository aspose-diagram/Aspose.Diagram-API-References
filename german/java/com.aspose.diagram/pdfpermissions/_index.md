---
title: PdfPermissions
second_title: Aspose.Diagram for Java API-Referenz
description: Gibt die Benutzerberechtigungen für das PDF‑Dokument an.
type: docs
weight: 280
url: /de/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Gibt die Benutzerberechtigungen für das PDF‑Dokument an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Erlaubt alle Vorgänge am PDF-Dokument. |
| [CONTENT_COPY](#CONTENT-COPY) | Erlaubt das Kopieren oder anderweitige Extrahieren von Text und Grafiken aus dem Dokument, einschließlich der Extraktion für Barrierefreiheitszwecke. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Erlaubt das Extrahieren von Text und Grafiken zur Unterstützung der Barrierefreiheit für behinderte Nutzer oder zu anderen Zwecken. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Verweigert alle Vorgänge am PDF-Dokument. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Erlaubt das Zusammenstellen des Dokuments: Einfügen, Drehen oder Löschen von Seiten sowie das Erstellen von Navigationselementen wie Lesezeichen oder Miniaturbildern. |
| [FILL_IN](#FILL-IN) | Erlaubt das Ausfüllen von Formularen und das Signieren des Dokuments. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Erlaubt das Drucken des Dokuments in höchstmöglicher Auflösung. Bei Verwendung von RC4 40‑Bit‑Verschlüsselung wird diese Option ignoriert und das Drucken in hoher Auflösung ist erlaubt, wenn Printing gesetzt ist. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Ermöglicht das Hinzufügen oder Ändern von Textanmerkungen. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Ermöglicht das Ändern des Dokuments\u9225\u6a9a-Inhalts. |
| [PRINTING](#PRINTING) | Ermöglicht das Drucken des Dokuments. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Erlaubt alle Vorgänge am PDF-Dokument.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Erlaubt das Kopieren oder anderweitige Extrahieren von Text und Grafiken aus dem Dokument, einschließlich der Extraktion für Barrierefreiheitszwecke.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Ermöglicht das Extrahieren von Text und Grafiken zur Unterstützung der Barrierefreiheit für behinderte Benutzer oder für andere Zwecke. Bei Verwendung von RC4‑40‑Bit‑Verschlüsselung wird diese Option ignoriert und die Barrierefreiheit ist immer erlaubt, wenn ContentCopy gesetzt ist.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Verweigert alle Vorgänge am PDF-Dokument. Dies ist der Standardwert.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Ermöglicht das Zusammenstellen des Dokuments: Einfügen, Drehen oder Löschen von Seiten sowie das Erstellen von Navigationselementen wie Lesezeichen oder Miniaturbildern. Bei Verwendung von RC4‑40‑Bit‑Verschlüsselung wird diese Option ignoriert und das Zusammenstellen des Dokuments ist erlaubt, wenn ModifyContents gesetzt ist.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Ermöglicht das Ausfüllen von Formularen und das Signieren des Dokuments. Bei Verwendung von RC4‑40‑Bit‑Verschlüsselung wird diese Option ignoriert und das Ausfüllen von Formularen ist immer erlaubt, wenn ModifyAnnotations gesetzt ist.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Erlaubt das Drucken des Dokuments in höchstmöglicher Auflösung. Bei Verwendung von RC4 40‑Bit‑Verschlüsselung wird diese Option ignoriert und das Drucken in hoher Auflösung ist erlaubt, wenn Printing gesetzt ist.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Ermöglicht das Hinzufügen oder Ändern von Textanmerkungen. Bei Verwendung von RC4‑40‑Bit‑Verschlüsselung erlaubt diese Option zudem das Ausfüllen von Formularfeldern.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Ermöglicht das Ändern des Dokuments\u9225\u6a9a-Inhalts.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Ermöglicht das Drucken des Dokuments.

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

