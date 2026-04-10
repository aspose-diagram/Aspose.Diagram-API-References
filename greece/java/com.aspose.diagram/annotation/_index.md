---
title: Σχόλιο
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που περιέχουν πληροφορίες σχετικά με σχόλια που εισήχθησαν σε μια σελίδα εγγράφου.
type: docs
weight: 20
url: /el/java/com.aspose.diagram/annotation/
---

**Inheritance:**
java.lang.Object
```
public class Annotation
```

Περιέχει στοιχεία που περιέχουν πληροφορίες σχετικά με σχόλια που εισήχθησαν σε μια σελίδα εγγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Περιέχει το κείμενο του σχολίου σε μορφή συμβολοσειράς για ένα σχήμα. |
| [getDate()](#getDate--) | Καθορίζει πότε δημιουργήθηκε ένα σχόλιο |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getEditDate()](#getEditDate--) | Καθορίζει πότε το σχόλιο άλλαξε τελευταία φορά |
| [getIX()](#getIX--) | Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου. |
| [getLangID()](#getLangID--) | Δείχνει το αναγνωριστικό τοπικής ρύθμισης (LCID) της γλώσσας στην οποία εισήχθη ο τύπος κελιού, το κείμενο, η προσαρμοσμένη ιδιότητα ή το σχόλιο. |
| [getMarkerIndex()](#getMarkerIndex--) | Καθορίζει τον αριθμό δείκτη που έχει εκχωρηθεί σε έναν δείκτη σχολίου. |
| [getReviewerID()](#getReviewerID--) | Περιέχει τον αριθμό ταυτότητας του ελεγκτή που προσθέτει σημειώσεις στο έγγραφο. |
| [getShapeID()](#getShapeID--) | Το αναγνωριστικό σχήματος του σχολίου. |
| [getX()](#getX--) | Η συντεταγμένη x του δείκτη σχολίου σε συντεταγμένες σελίδας. |
| [getY()](#getY--) | Η συντεταγμένη y του δείκτη σχολίου σε συντεταγμένες σελίδας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/annotation\#getDel--) |
| [setIX(int value)](#setIX-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/annotation\#getIX--) |
| [setShapeID(int value)](#setShapeID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getComment() {#getComment--}
```
public Str2Value getComment()
```


Περιέχει το κείμενο του σχολίου σε μορφή συμβολοσειράς για ένα σχήμα.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDate() {#getDate--}
```
public DateValue getDate()
```


Καθορίζει πότε δημιουργήθηκε ένα σχόλιο

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getEditDate() {#getEditDate--}
```
public DateValue getEditDate()
```


Καθορίζει πότε το σχόλιο άλλαξε τελευταία φορά

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getIX() {#getIX--}
```
public int getIX()
```


Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Δείχνει το αναγνωριστικό τοπικής ρύθμισης (LCID) της γλώσσας στην οποία εισήχθη ο τύπος κελιού, το κείμενο, η προσαρμοσμένη ιδιότητα ή το σχόλιο.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getMarkerIndex() {#getMarkerIndex--}
```
public IntValue getMarkerIndex()
```


Καθορίζει τον αριθμό δείκτη που έχει εκχωρηθεί σε έναν δείκτη σχολίου.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


Περιέχει τον αριθμό ταυτότητας του ελεγκτή που προσθέτει σημειώσεις στο έγγραφο.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getShapeID() {#getShapeID--}
```
public int getShapeID()
```


Το αναγνωριστικό σχήματος του σχολίου.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


Η συντεταγμένη x του δείκτη σχολίου σε συντεταγμένες σελίδας.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Η συντεταγμένη y του δείκτη σχολίου σε συντεταγμένες σελίδας.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/annotation\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/annotation\#getIX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShapeID(int value) {#setShapeID-int-}
```
public void setShapeID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--)

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

