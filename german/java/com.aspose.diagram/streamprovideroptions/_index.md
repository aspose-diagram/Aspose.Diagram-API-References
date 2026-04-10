---
title: StreamProviderOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Stellt die Stream-Optionen dar.
type: docs
weight: 390
url: /de/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

Stellt die Stream-Optionen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | Der Standardpfad (URL), der in der erzeugten HTML-Datei für die referenzierte Quelle gespeichert wird. |
| [getStream()](#getStream--) | Liest/Setzt den Ausgabestream zum Schreiben der gespeicherten Daten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | Der vom Benutzer benutzerdefinierte Pfad (URL), der in der erzeugten HTML-Datei für die referenzierte Quelle gespeichert wird. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
```


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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


Der Standardpfad (URL), der in der erzeugten HTML-Datei für die referenzierte Quelle gespeichert wird. Zum Beispiel werden die Blattdaten in xxx\_files/sheet001.htm gespeichert, die im Haupt-HTML-File verwendete URL sollte etwa so aussehen: "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


Liest/Setzt den Ausgabestream zum Schreiben der gespeicherten Daten.

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


Der vom Benutzer benutzerdefinierte Pfad (URL), der in der erzeugten HTML-Datei für die referenzierte Quelle gespeichert wird. Wenn er nicht vom Benutzer definiert wird, wird DefaultPath verwendet. Zum Beispiel werden die Blattdaten vom Benutzer nach d:/sheet001.htm gespeichert, die im Haupt-HTML-File verwendete URL sollte "d:/sheet001.htm" oder ein anderer gültiger relativer Pfad sein, der vom Haupt-HTML-File aus erreichbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.OutputStream |  |

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

