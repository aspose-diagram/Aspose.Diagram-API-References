---
title: InterpolationMode
second_title: Αναφορά API του Aspose.Diagram για Java
description: Η απαρίθμηση InterpolationMode καθορίζει τον αλγόριθμο που χρησιμοποιείται όταν οι εικόνες κλιμακώνονται ή περιστρέφονται.
type: docs
weight: 206
url: /el/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

Η απαρίθμηση InterpolationMode καθορίζει τον αλγόριθμο που χρησιμοποιείται όταν οι εικόνες κλιμακώνονται ή περιστρέφονται.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BICUBIC](#BICUBIC) | Καθορίζει διπλοκυβική παρεμβολή. |
| [BILINEAR](#BILINEAR) | Καθορίζει διγραμμική παρεμβολή. |
| [DEFAULT](#DEFAULT) | Καθορίζει την προεπιλεγμένη λειτουργία. |
| [HIGH](#HIGH) | Καθορίζει παρεμβολή υψηλής ποιότητας. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | Καθορίζει υψηλής ποιότητας, διπλοκυβική παρεμβολή. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | Καθορίζει υψηλής ποιότητας, διγραμμική παρεμβολή. |
| [INVALID](#INVALID) | Ισοδυναμεί με το στοιχείο Invalid της απαρίθμησης QualityMode. |
| [LOW](#LOW) | Καθορίζει παρεμβολή χαμηλής ποιότητας. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | Καθορίζει παρεμβολή πλησιέστερου γείτονα. |
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
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


Καθορίζει διπλοκυβική παρεμβολή. Δεν γίνεται προφίλτρου. Αυτή η λειτουργία δεν είναι κατάλληλη για τη σμίκρυνση μιας εικόνας κάτω από το 25 τοις εκατό του αρχικού της μεγέθους.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


Καθορίζει διγραμμική παρεμβολή. Δεν γίνεται προφίλτρου. Αυτή η λειτουργία δεν είναι κατάλληλη για τη σμίκρυνση μιας εικόνας κάτω από το 50 τοις εκατό του αρχικού της μεγέθους.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


Καθορίζει την προεπιλεγμένη λειτουργία.

### HIGH {#HIGH}
```
public static final int HIGH
```


Καθορίζει παρεμβολή υψηλής ποιότητας.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


Καθορίζει υψηλής ποιότητας, διπλοκυβική παρεμβολή. Πραγματοποιείται προφίλτρου για να εξασφαλιστεί η σμίκρυνση υψηλής ποιότητας. Αυτή η λειτουργία παράγει τις εικόνες υψηλότερης ποιότητας μετά τον μετασχηματισμό.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


Καθορίζει υψηλής ποιότητας, διγραμμική παρεμβολή. Πραγματοποιείται προφίλτρου για να εξασφαλιστεί η σμίκρυνση υψηλής ποιότητας.

### INVALID {#INVALID}
```
public static final int INVALID
```


Ισοδυναμεί με το στοιχείο Invalid της απαρίθμησης QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


Καθορίζει παρεμβολή χαμηλής ποιότητας.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


Καθορίζει παρεμβολή πλησιέστερου γείτονα.

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

