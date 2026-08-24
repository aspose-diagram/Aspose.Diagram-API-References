---
title: PdfPermissions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Καθορίζει τα δικαιώματα χρήστη για το έγγραφο PDF.
type: docs
weight: 280
url: /el/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Καθορίζει τα δικαιώματα χρήστη για το έγγραφο PDF.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Επιτρέπει όλες τις λειτουργίες στο έγγραφο PDF. |
| [CONTENT_COPY](#CONTENT-COPY) | Επιτρέπει την αντιγραφή ή άλλου είδους εξαγωγή κειμένου και γραφικών από το έγγραφο, συμπεριλαμβανομένης της εξαγωγής για σκοπούς προσβασιμότητας. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | Επιτρέπει την εξαγωγή κειμένου και γραφικών σε υποστήριξη προσβασιμότητας για χρήστες με αναπηρίες ή για άλλους σκοπούς. |
| [DISALLOW_ALL](#DISALLOW-ALL) | Απαγορεύει όλες τις λειτουργίες στο έγγραφο PDF. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | Επιτρέπει τη συναρμολόγηση του εγγράφου: εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία στοιχείων πλοήγησης όπως σελιδοδείκτες ή μικρογραφίες. |
| [FILL_IN](#FILL-IN) | Επιτρέπει τη συμπλήρωση φορμών και την υπογραφή του εγγράφου. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | Επιτρέπει την εκτύπωση του εγγράφου στην υψηλότερη δυνατή ανάλυση. Όταν χρησιμοποιείται κρυπτογράφηση RC4 40-bit, αυτή η επιλογή αγνοείται και η εκτύπωση υψηλής ανάλυσης επιτρέπεται όταν η ιδιότητα Printing είναι ορισμένη. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | Επιτρέπει την προσθήκη ή τροποποίηση σχολίων κειμένου. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | Επιτρέπει τη τροποποίηση του περιεχομένου του εγγράφου\u9225\u6a9a. |
| [PRINTING](#PRINTING) | Επιτρέπει την εκτύπωση του εγγράφου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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


Επιτρέπει όλες τις λειτουργίες στο έγγραφο PDF.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


Επιτρέπει την αντιγραφή ή άλλου είδους εξαγωγή κειμένου και γραφικών από το έγγραφο, συμπεριλαμβανομένης της εξαγωγής για σκοπούς προσβασιμότητας.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


Επιτρέπει την εξαγωγή κειμένου και γραφικών για υποστήριξη προσβασιμότητας σε χρήστες με αναπηρία ή για άλλους σκοπούς. Όταν χρησιμοποιείται κρυπτογράφηση RC4 40-bit, αυτή η επιλογή αγνοείται και η προσβασιμότητα επιτρέπεται όποτε έχει οριστεί το ContentCopy.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


Απαγορεύει όλες τις λειτουργίες στο έγγραφο PDF. Αυτή είναι η προεπιλεγμένη τιμή.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


Επιτρέπει τη συναρμολόγηση του εγγράφου: εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία στοιχείων πλοήγησης όπως σελιδοδείκτες ή μικρογραφίες. Όταν χρησιμοποιείται κρυπτογράφηση RC4 40-bit, αυτή η επιλογή αγνοείται και η συναρμολόγηση του εγγράφου επιτρέπεται όταν έχει οριστεί το ModifyContents.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


Επιτρέπει τη συμπλήρωση φορμών και την υπογραφή του εγγράφου. Όταν χρησιμοποιείται κρυπτογράφηση RC4 40-bit, αυτή η επιλογή αγνοείται και η συμπλήρωση της φόρμας επιτρέπεται όποτε έχει οριστεί το ModifyAnnotations.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


Επιτρέπει την εκτύπωση του εγγράφου στην υψηλότερη δυνατή ανάλυση. Όταν χρησιμοποιείται κρυπτογράφηση RC4 40-bit, αυτή η επιλογή αγνοείται και η εκτύπωση υψηλής ανάλυσης επιτρέπεται όταν η ιδιότητα Printing είναι ορισμένη.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


Επιτρέπει την προσθήκη ή τροποποίηση σχολίων κειμένου. Όταν χρησιμοποιείται κρυπτογράφηση RC4 40-bit, αυτή η επιλογή επιτρέπει επίσης τη συμπλήρωση πεδίων φόρμας.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


Επιτρέπει τη τροποποίηση του περιεχομένου του εγγράφου\u9225\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


Επιτρέπει την εκτύπωση του εγγράφου.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

