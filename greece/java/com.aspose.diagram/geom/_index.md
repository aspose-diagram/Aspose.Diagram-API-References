---
title: Geom
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που καθορίζουν τις συντεταγμένες των κορυφών για τις γραμμές και τις τόξα που σχηματίζουν το σχήμα.
type: docs
weight: 169
url: /el/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

Περιέχει στοιχεία που καθορίζουν τις συντεταγμένες των κορυφών για τις γραμμές και τις καμπύλες που σχηματίζουν το σχήμα. Εάν το σχήμα έχει περισσότερα από ένα μονοπάτια, υπάρχει ένα στοιχείο Geom για κάθε μονοπάτι.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Geom()](#Geom--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | Συλλογή συντεταγμένων. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getIX()](#getIX--) | Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | Επιστρέφει την τιμή IX για το επόμενο μέλος της συλλογής συντεταγμένων του σχήματος. |
| [getNoFill()](#getNoFill--) | Καθορίζει εάν ένα μονοπάτι μπορεί να γεμίσει. |
| [getNoLine()](#getNoLine--) | Καθορίζει εάν σχεδιάζεται μια γραμμή γύρω από το όριο του μονοπατιού. |
| [getNoQuickDrag()](#getNoQuickDrag--) | Καθορίζει εάν ένα σχήμα μπορεί να επιλεγεί ή να μετακινηθεί όταν ο χρήστης κάνει κλικ στην γεμισμένη περιοχή που ορίζεται από την ενότητα Geometry. |
| [getNoShow()](#getNoShow--) | Καθορίζει εάν ένα μονοπάτι εμφανίζεται στη σελίδα σχεδίασης. |
| [getNoSnap()](#getNoSnap--) | Καθορίζει εάν άλλα σχήματα προσαρμόζονται σε ένα μονοπάτι. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
```


Κατασκευαστής.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας.

**Returns:**
java.lang.Object -
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
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


Συλλογή συντεταγμένων. Εμφανίζει τη σειρά των συντεταγμένων.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου.

**Returns:**
int
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


Επιστρέφει την τιμή IX για το επόμενο μέλος της συλλογής συντεταγμένων του σχήματος.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


Καθορίζει εάν ένα μονοπάτι μπορεί να γεμίσει.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


Καθορίζει εάν σχεδιάζεται μια γραμμή γύρω από το όριο του μονοπατιού.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


Καθορίζει εάν ένα σχήμα μπορεί να επιλεγεί ή να μετακινηθεί όταν ο χρήστης κάνει κλικ στην γεμισμένη περιοχή που ορίζεται από την ενότητα Geometry.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


Καθορίζει εάν ένα μονοπάτι εμφανίζεται στη σελίδα σχεδίασης.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


Καθορίζει εάν άλλα σχήματα προσαρμόζονται σε ένα μονοπάτι.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

