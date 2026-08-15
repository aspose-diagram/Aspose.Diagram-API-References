---
title: PdfEncryptionDetails
second_title: Aspose.Diagram för Java API-referens
description: Innehåller detaljer för en PDF‑kryptering.
type: docs
weight: 279
url: /sv/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

Innehåller detaljer för en PDF‑kryptering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | krypteringsläget. |
| [getOwnerPassword()](#getOwnerPassword--) | ägarlösenordet. |
| [getPermissions()](#getPermissions--) | behörigheterna. |
| [getUserPassword()](#getUserPassword--) | användarlösenordet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | För beskrivningen av denna egenskap, se [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | För beskrivningen av denna egenskap, se [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) |
| [setPermissions(int value)](#setPermissions-int-) | För beskrivningen av denna egenskap, se [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | För beskrivningen av denna egenskap, se [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


Konstruktor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
### getEncryptionAlgorithm() {#getEncryptionAlgorithm--}
```
public int getEncryptionAlgorithm()
```


krypteringsläget.

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


Ägarlösenordet. Att öppna dokumentet med rätt ägarlösenord (förutsatt att det inte är samma som användarlösenordet) ger full (ägare) åtkomst till dokumentet. Denna obegränsade åtkomst inkluderar möjligheten att ändra dokumentets\u9225\u6a9a lösenord och åtkomstbehörigheter.

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


behörigheterna.

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


Användarlösenordet. Att öppna dokumentet med rätt användarlösenord (eller öppna ett dokument som inte har ett användarlösenord) möjliggör ytterligare operationer enligt de användaråtkomstbehörigheter som anges i dokumentets\u9225\u6a9a krypteringsordbok.

**Returns:**
java.lang.String
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




### setEncryptionAlgorithm(int value) {#setEncryptionAlgorithm-int-}
```
public void setEncryptionAlgorithm(int value)
```


För beskrivningen av denna egenskap, se [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


För beskrivningen av denna egenskap, se [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


För beskrivningen av denna egenskap, se [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


För beskrivningen av denna egenskap, se [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

