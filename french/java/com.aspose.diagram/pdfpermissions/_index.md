---
title: PdfPermissions
second_title: Référence API d'Aspose.Diagram pour Java
description: Spécifie les autorisations utilisateur pour le document PDF.
type: docs
weight: 280
url: /fr/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Spécifie les autorisations utilisateur pour le document PDF.
## Champs

| Champ | Description |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Autorise toutes les opérations sur le document PDF. |
| [CONTENT_COPY](#CONTENT-COPY) | Autorise la copie ou l'extraction du texte et des graphiques du document, y compris l'extraction à des fins d'accessibilité. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Autorise l'extraction de texte et de graphiques pour soutenir l'accessibilité aux utilisateurs handicapés ou à d'autres fins. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Interdit toutes les opérations sur le document PDF. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Autorise l'assemblage du document : insertion, rotation ou suppression de pages et création d'éléments de navigation tels que des signets ou des images miniatures. |
| [FILL_IN](#FILL-IN) | Autorise le remplissage des formulaires et la signature du document. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Autorise l'impression du document à la résolution la plus élevée possible. Lors de l'utilisation du chiffrement RC4 40 bits, cette option est ignorée et l'impression haute résolution est autorisée lorsque l'option Printing est activée. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Autorise l'ajout ou la modification d'annotations de texte. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Autorise la modification du contenu du document\u9225\u6a9a. |
| [PRINTING](#PRINTING) | Autorise l'impression du document. |
## Méthodes

| Méthode | Description |
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


Autorise toutes les opérations sur le document PDF.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Autorise la copie ou l'extraction du texte et des graphiques du document, y compris l'extraction à des fins d'accessibilité.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Autorise l'extraction de texte et de graphiques afin de soutenir l'accessibilité pour les utilisateurs handicapés ou à d'autres fins. Lors de l'utilisation du chiffrement RC4 40 bits, cette option est ignorée et l'accessibilité est autorisée chaque fois que ContentCopy est défini.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Interdit toutes les opérations sur le document PDF. C'est la valeur par défaut.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Autorise l'assemblage du document : insertion, rotation ou suppression de pages et création d'éléments de navigation tels que des signets ou des images miniatures. Lors de l'utilisation du chiffrement RC4 40 bits, cette option est ignorée et l'assemblage du document est autorisé lorsque ModifyContents est défini.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Autorise le remplissage des formulaires et la signature du document. Lors de l'utilisation du chiffrement RC4 40 bits, cette option est ignorée et le remplissage du formulaire est autorisé chaque fois que ModifyAnnotations est défini.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Autorise l'impression du document à la résolution la plus élevée possible. Lors de l'utilisation du chiffrement RC4 40 bits, cette option est ignorée et l'impression haute résolution est autorisée lorsque l'option Printing est activée.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Autorise l'ajout ou la modification d'annotations de texte. Lors de l'utilisation du chiffrement RC4 40 bits, cette option autorise également le remplissage des champs de formulaire.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Autorise la modification du contenu du document\u9225\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Autorise l'impression du document.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

