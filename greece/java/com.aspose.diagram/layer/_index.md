---
title: Layer
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ορίζουν ένα ενιαίο στρώμα και τις ιδιότητές του για μια σελίδα.
type: docs
weight: 212
url: /el/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Περιέχει στοιχεία που ορίζουν ένα ενιαίο στρώμα και τις ιδιότητές του για μια σελίδα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Layer()](#Layer--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Καθορίζει εάν ένα στρώμα είναι ενεργό. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ο δείκτης του χρώματος στον πίνακα χρωμάτων που χρησιμοποιείται για την εμφάνιση του στρώματος ή μια τιμή RGB που καθορίζει προσαρμοσμένο χρώμα που δεν υπάρχει στον πίνακα χρωμάτων (για παράδειγμα, \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Καθορίζει το βαθμό διαφάνειας για το χρώμα κειμένου ενός στρώματος ή σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές). |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getGlue()](#getGlue--) | Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο μπορούν να κολληθούν. |
| [getIX()](#getIX--) | Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου. |
| [getLock()](#getLock--) | Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο είναι κλειδωμένα ώστε να μην μπορούν να επιλεγούν ή να επεξεργαστούν. |
| [getName()](#getName--) | Το στοιχείο Name καθορίζει το όνομα ενός επιπέδου. |
| [getNameUniv()](#getNameUniv--) | Καθορίζει το καθολικό όνομα ενός επιπέδου. |
| [getPrint()](#getPrint--) | Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο εκτυπώνονται όταν εκτυπώνεται το σχέδιο. |
| [getSnap()](#getSnap--) | Καθορίζει εάν άλλα σχήματα μπορούν να snap σε σχήματα που έχουν ανατεθεί στο επίπεδο. |
| [getStatus()](#getStatus--) | Καθορίζει εάν το επίπεδο είναι έγκυρο επίπεδο για ένα έγγραφο. |
| [getVisible()](#getVisible--) | Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο είναι ορατά στη σελίδα του σχεδίου. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει ελεγχθεί τοπικά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Κατασκευαστής.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Καθορίζει εάν ένα επίπεδο είναι ενεργό. Τα σχήματα που δεν έχουν προανατεθεί σε επίπεδα ανατίθενται στο ενεργό(ά) επίπεδο(α) όταν τοποθετούνται στη σελίδα του σχεδίου.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Ο δείκτης του χρώματος στον πίνακα χρωμάτων που χρησιμοποιείται για την εμφάνιση του στρώματος ή μια τιμή RGB που καθορίζει προσαρμοσμένο χρώμα που δεν υπάρχει στον πίνακα χρωμάτων (για παράδειγμα, \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Καθορίζει το βαθμό διαφάνειας για το χρώμα κειμένου ενός στρώματος ή σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο μπορούν να κολληθούν.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο είναι κλειδωμένα ώστε να μην μπορούν να επιλεγούν ή να επεξεργαστούν.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Το στοιχείο Name καθορίζει το όνομα ενός επιπέδου.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Καθορίζει το καθολικό όνομα ενός επιπέδου.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο εκτυπώνονται όταν εκτυπώνεται το σχέδιο.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Καθορίζει εάν άλλα σχήματα μπορούν να snap σε σχήματα που έχουν ανατεθεί στο επίπεδο. Τα σχήματα που έχουν ανατεθεί στο επίπεδο μπορούν να snap σε άλλα σχήματα, αλλά άλλα σχήματα δεν μπορούν να snap σε αυτά.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Καθορίζει εάν το επίπεδο είναι έγκυρο επίπεδο για ένα έγγραφο.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Καθορίζει εάν τα σχήματα που ανήκουν στο επίπεδο είναι ορατά στη σελίδα του σχεδίου.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Μία σημαία που υποδεικνύει εάν το στοιχείο έχει ελεγχθεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο ελέγχθηκε τοπικά.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/layer\#getIX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

