---
title: PdfPermissions
second_title: Aspose.Diagram för Java API-referens
description: Anger användarbehörigheter för PDF‑dokumentet.
type: docs
weight: 280
url: /sv/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Anger användarbehörigheter för PDF‑dokumentet.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Tillåter alla operationer på PDF‑dokumentet. |
| [CONTENT_COPY](#CONTENT-COPY) | Tillåter kopiering eller på annat sätt extrahering av text och grafik från dokumentet, inklusive extrahering för tillgänglighetsändamål. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Tillåter extrahering av text och grafik för att stödja tillgänglighet för funktionshindrade användare eller för andra ändamål. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Tillåter inte några operationer på PDF‑dokumentet. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Tillåter sammansättning av dokumentet: infogning, rotation eller borttagning av sidor samt skapande av navigeringselement som bokmärken eller miniatyrbilder. |
| [FILL_IN](#FILL-IN) | Tillåter ifyllning av formulär och signering av dokumentet. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Tillåter utskrift av dokumentet i högsta möjliga upplösning. När RC4 40‑bitars kryptering används ignoreras detta alternativ och utskrift i hög upplösning tillåts när Printing är inställt. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Tillåter att lägga till eller ändra textanteckningar. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Tillåter att ändra dokumentets\u9225\u6a9a innehåll. |
| [PRINTING](#PRINTING) | Tillåter utskrift av dokumentet. |
## Metoder

| Metod | Beskrivning |
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


Tillåter alla operationer på PDF‑dokumentet.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Tillåter kopiering eller på annat sätt extrahering av text och grafik från dokumentet, inklusive extrahering för tillgänglighetsändamål.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Tillåter att extrahera text och grafik för att stödja tillgänglighet för funktionshindrade användare eller för andra ändamål. Vid användning av RC4 40-bitars kryptering ignoreras detta alternativ och tillgänglighet tillåts när som helst när ContentCopy är aktiverat.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Tillåter inte några operationer på PDF-dokumentet. Detta är standardvärdet.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Tillåter att montera dokumentet: infoga, rotera eller ta bort sidor samt skapa navigeringselement såsom bokmärken eller miniatyrbilder. Vid användning av RC4 40-bitars kryptering ignoreras detta alternativ och dokumentmontering tillåts när ModifyContents är aktiverat.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Tillåter ifyllning av formulär och signering av dokumentet. Vid användning av RC4 40-bitars kryptering ignoreras detta alternativ och ifyllning av formulär tillåts när som helst när ModifyAnnotations är aktiverat.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Tillåter utskrift av dokumentet i högsta möjliga upplösning. När RC4 40‑bitars kryptering används ignoreras detta alternativ och utskrift i hög upplösning tillåts när Printing är inställt.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Tillåter att lägga till eller ändra textanteckningar. Vid användning av RC4 40-bitars kryptering tillåter detta alternativ även ifyllning av formulärfält.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Tillåter att ändra dokumentets\u9225\u6a9a innehåll.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Tillåter utskrift av dokumentet.

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

