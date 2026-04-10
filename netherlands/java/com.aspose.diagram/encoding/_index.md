---
title: Encoding
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt een tekencodering voor.
type: docs
weight: 143
url: /nl/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

Stelt een tekencodering voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | Bepaalt of het opgegeven Encoding-object gelijk is aan de huidige instantie. |
| [equals(Object o)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan de huidige instantie. |
| [getASCII()](#getASCII--) | Haalt een codering op voor de ASCII (7-bit) tekenset. |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | Haalt een codering op voor het UTF-16-formaat met big-endian bytevolgorde. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Haalt een codering op voor de huidige ANSI-codepagina van het besturingssysteem. |
| [getEncoding(int codePage)](#getEncoding-int-) | Retourneert de codering die is gekoppeld aan de opgegeven codepagina-identificatie. |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | Retourneert een codering die is gekoppeld aan de opgegeven charset-naam. |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | Retourneert een codering die is gekoppeld aan het opgegeven charset-object. |
| [getUTF7()](#getUTF7--) | Haalt een codering op voor het UTF-7-formaat. |
| [getUTF8()](#getUTF8--) | Haalt een codering op voor het UTF-8-formaat. |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | Haalt een codering op voor het UTF-8-formaat zonder de UTF-8-identificatie. |
| [getUnicode()](#getUnicode--) | Haalt een codering op voor het UTF-16-formaat met little-endian bytevolgorde. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


Bepaalt of het opgegeven Encoding-object gelijk is aan de huidige instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | Het Encoding-object om te vergelijken met de huidige instantie. |

**Returns:**
boolean - true als de waarde gelijk is aan de huidige instantie; anders false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Bepaalt of het opgegeven Object gelijk is aan de huidige instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | java.lang.Object | Het object om te vergelijken met de huidige instantie. |

**Returns:**
boolean - true als de waarde een instantie is van Encoding en gelijk is aan de huidige instantie; anders false.
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


Haalt een codering op voor de ASCII (7-bit) tekenset.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


Haalt een codering op voor het UTF-16-formaat met big-endian bytevolgorde.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


Haalt een codering op voor de huidige ANSI-codepagina van het besturingssysteem.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


Retourneert de codering die is gekoppeld aan de opgegeven codepagina-identificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codePage | int | De codepagina‑identificatie van de gewenste codering. -or- 0, om de standaardcodering te gebruiken. |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


Retourneert een codering die is gekoppeld aan de opgegeven charset-naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charsetName | java.lang.String | opgegeven charset‑naam |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


Retourneert een codering die is gekoppeld aan het opgegeven charset-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| charset | java.nio.charset.Charset | opgegeven charset‑object |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


Haalt een codering op voor het UTF-7-formaat.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


Haalt een codering op voor het UTF-8-formaat.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


Haalt een codering op voor het UTF-8-formaat zonder de UTF-8-identificatie.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


Haalt een codering op voor het UTF-16-formaat met little-endian bytevolgorde.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

