---
title: PdfPermissions
second_title: Riferimento API di Aspose.Diagram per Java
description: Specifica i permessi dell'utente per il documento PDF.
type: docs
weight: 280
url: /it/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Specifica i permessi dell'utente per il documento PDF.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Consente tutte le operazioni sul documento PDF. |
| [CONTENT_COPY](#CONTENT-COPY) | Consente la copia o l'estrazione di testo e grafica dal documento, inclusa l'estrazione per scopi di accessibilità. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Consente l'estrazione di testo e grafica a supporto dell'accessibilità per utenti disabili o per altri scopi. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Non consente alcuna operazione sul documento PDF. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Consente l'assemblaggio del documento: inserimento, rotazione o eliminazione di pagine e creazione di elementi di navigazione come segnalibri o miniature. |
| [FILL_IN](#FILL-IN) | Consente la compilazione di moduli e la firma del documento. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Consente la stampa del documento alla massima risoluzione possibile. Quando si utilizza la crittografia RC4 a 40 bit, questa opzione è ignorata e la stampa ad alta risoluzione è consentita quando Printing è impostato. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Consente di aggiungere o modificare annotazioni di testo. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Consente di modificare i contenuti del documento\u9225\u6a9a. |
| [PRINTING](#PRINTING) | Consente di stampare il documento. |
## Metodi

| Metodo | Descrizione |
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


Consente tutte le operazioni sul documento PDF.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Consente la copia o l'estrazione di testo e grafica dal documento, inclusa l'estrazione per scopi di accessibilità.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Consente di estrarre testo e grafica a supporto dell'accessibilità per utenti disabili o per altri scopi. Quando si utilizza la crittografia RC4 a 40 bit, questa opzione è ignorata e l'accessibilità è consentita ogni volta che è impostato ContentCopy.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Non consente alcuna operazione sul documento PDF. Questo è il valore predefinito.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Consente di assemblare il documento: inserire, ruotare o eliminare pagine e creare elementi di navigazione come segnalibri o miniature. Quando si utilizza la crittografia RC4 a 40 bit, questa opzione è ignorata e l'assemblaggio del documento è consentito quando è impostato ModifyContents.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Consente di compilare i moduli e firmare il documento. Quando si utilizza la crittografia RC4 a 40 bit, questa opzione è ignorata e la compilazione del modulo è consentita ogni volta che è impostato ModifyAnnotations.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Consente la stampa del documento alla massima risoluzione possibile. Quando si utilizza la crittografia RC4 a 40 bit, questa opzione è ignorata e la stampa ad alta risoluzione è consentita quando Printing è impostato.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Consente di aggiungere o modificare annotazioni di testo. Quando si utilizza la crittografia RC4 a 40 bit, questa opzione consente anche di compilare i campi del modulo.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Consente di modificare i contenuti del documento\u9225\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Consente di stampare il documento.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

