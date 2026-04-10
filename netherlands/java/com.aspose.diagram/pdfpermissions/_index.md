---
title: PdfPermissions
second_title: Aspose.Diagram voor Java API-referentie
description: Specificeert gebruikersrechten voor PDF‑document.
type: docs
weight: 280
url: /nl/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Specificeert gebruikersrechten voor PDF‑document.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Staat alle bewerkingen op het PDF-document toe. |
| [CONTENT_COPY](#CONTENT-COPY) | Staat kopiëren of anderszins extraheren van tekst en afbeeldingen uit het document toe, inclusief extractie voor toegankelijkheidsdoeleinden. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Staat het extraheren van tekst en afbeeldingen ter ondersteuning van toegankelijkheid voor gehandicapte gebruikers of voor andere doeleinden toe. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Verbiedt alle bewerkingen op het PDF-document. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Staat het samenstellen van het document toe: pagina's invoegen, roteren of verwijderen en navigatie‑elementen zoals bladwijzers of miniatuur‑afbeeldingen maken. |
| [FILL_IN](#FILL-IN) | Staat het invullen van formulieren en ondertekenen van het document toe. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Staat het afdrukken van het document op de hoogst mogelijke resolutie toe. Bij gebruik van RC4 40‑bits encryptie wordt deze optie genegeerd en is afdrukken op hoge resolutie toegestaan wanneer Printing is ingesteld. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Staat toe om tekstannotaties toe te voegen of te wijzigen. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Staat toe om de inhoud van het document\u9225\u6a9a te wijzigen. |
| [PRINTING](#PRINTING) | Staat toe om het document af te drukken. |
## Methoden

| Methode | Beschrijving |
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


Staat alle bewerkingen op het PDF-document toe.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Staat kopiëren of anderszins extraheren van tekst en afbeeldingen uit het document toe, inclusief extractie voor toegankelijkheidsdoeleinden.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Staat toe om tekst en grafische elementen te extraheren ter ondersteuning van toegankelijkheid voor gehandicapte gebruikers of voor andere doeleinden. Bij gebruik van RC4 40-bit encryptie wordt deze optie genegeerd en is toegankelijkheid toegestaan wanneer ContentCopy is ingesteld.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Verbiedt alle bewerkingen op het PDF-document. Dit is de standaardwaarde.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Staat toe om het document samen te stellen: pagina's in te voegen, te roteren of te verwijderen en navigatie‑elementen zoals bladwijzers of miniatuurafbeeldingen te maken. Bij gebruik van RC4 40-bit encryptie wordt deze optie genegeerd en is het samenstellen van het document toegestaan wanneer ModifyContents is ingesteld.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Staat toe om formulieren in te vullen en het document te ondertekenen. Bij gebruik van RC4 40-bit encryptie wordt deze optie genegeerd en is het invullen van formulieren toegestaan wanneer ModifyAnnotations is ingesteld.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Staat het afdrukken van het document op de hoogst mogelijke resolutie toe. Bij gebruik van RC4 40‑bits encryptie wordt deze optie genegeerd en is afdrukken op hoge resolutie toegestaan wanneer Printing is ingesteld.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Staat toe om tekstannotaties toe te voegen of te wijzigen. Bij gebruik van RC4 40-bit encryptie staat deze optie ook toe om formulier‑velden in te vullen.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Staat toe om de inhoud van het document\u9225\u6a9a te wijzigen.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Staat toe om het document af te drukken.

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

