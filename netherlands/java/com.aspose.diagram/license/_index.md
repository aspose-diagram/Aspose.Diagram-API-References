---
title: Licentie
second_title: Aspose.Diagram voor Java API-referentie
description: Biedt methoden om het component te licentiëren.
type: docs
weight: 219
url: /nl/java/com.aspose.diagram/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Biedt methoden om het component te licentiëren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licentieert het component. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licentieert het component. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initialiseert een nieuw exemplaar van deze klasse.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licentieert het component.

Gebruik deze methode om een licentie te laden vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Een stream die de licentie bevat. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licentieert het component.

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map van de componentassembly.

3. De map van de aanroepende assembly van de client.

4. De map van de entry-assembly.

5. Een ingebedde resource in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde resource in de aanroepende assembly van de client.

2. De map van het component‑jar‑bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | java.lang.String |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

