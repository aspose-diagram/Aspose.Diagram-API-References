---
title: Έλεγχος
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία για τις συντεταγμένες x και y κάθε χειριστηρίου ελέγχου που ορίζεται για ένα σχήμα και στοιχεία που καθορίζουν τον τρόπο συμπεριφοράς του χειριστηρίου ελέγχου.
type: docs
weight: 87
url: /el/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

Περιέχει στοιχεία για τις συντεταγμένες x και y κάθε χειριστηρίου ελέγχου που ορίζεται για ένα σχήμα, καθώς και στοιχεία που καθορίζουν τον τρόπο συμπεριφοράς του χειριστηρίου ελέγχου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Control()](#Control--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canGlue()](#canGlue--) | Καθορίζει εάν ένα χειριστήριο ελέγχου μπορεί να κολλήσει σε άλλα σχήματα. |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getID()](#getID--) | Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο. |
| [getIX()](#getIX--) | Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου. |
| [getName()](#getName--) | Το όνομα του στοιχείου. |
| [getNameU()](#getNameU--) | Το καθολικό όνομα του στοιχείου. |
| [getPrompt()](#getPrompt--) | Το στοιχείο Prompt καθορίζει το περιγραφικό κείμενο που εμφανίζεται ως υπόδειξη εργαλείου όταν ο δείκτης του ποντικιού παραμένει πάνω από το χειριστήριο ελέγχου ενός σχήματος. |
| [getX()](#getX--) | Η συντεταγμένη x που υποδεικνύει τη θέση του χειριστηρίου ελέγχου ενός σχήματος. |
| [getXCon()](#getXCon--) | Καθορίζει τον τύπο συμπεριφοράς που παρουσιάζει η συντεταγμένη x του χειριστηρίου ελέγχου μετά τη μετακίνηση του χειριστηρίου. |
| [getXDyn()](#getXDyn--) | Καθορίζει τη συντεταγμένη x για το σημείο άγκυρας ενός χειριστηρίου ελέγχου σε τοπικές συντεταγμένες. |
| [getY()](#getY--) | Η συντεταγμένη y που υποδεικνύει τη θέση του χειριστηρίου ελέγχου ενός σχήματος. |
| [getYCon()](#getYCon--) | Καθορίζει τον τύπο συμπεριφοράς που παρουσιάζει η συντεταγμένη x του χειριστηρίου ελέγχου μετά τη μετακίνηση του χειριστηρίου. |
| [getYDyn()](#getYDyn--) | Καθορίζει τη συντεταγμένη y για το σημείο άγκυρας ενός χειριστηρίου ελέγχου σε τοπικές συντεταγμένες. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


Κατασκευαστής.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


Καθορίζει εάν ένα χειριστήριο ελέγχου μπορεί να κολλήσει σε άλλα σχήματα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Το όνομα του στοιχείου.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Το καθολικό όνομα του στοιχείου.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Το στοιχείο Prompt καθορίζει το περιγραφικό κείμενο που εμφανίζεται ως υπόδειξη εργαλείου όταν ο δείκτης του ποντικιού παραμένει πάνω από το χειριστήριο ελέγχου ενός σχήματος.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


Η συντεταγμένη x που υποδεικνύει τη θέση του χειριστηρίου ελέγχου ενός σχήματος.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


Καθορίζει τον τύπο συμπεριφοράς που παρουσιάζει η συντεταγμένη x του χειριστηρίου ελέγχου μετά τη μετακίνηση του χειριστηρίου.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


Καθορίζει τη συντεταγμένη x για το σημείο αγκύρωσης μιας λαβής ελέγχου σε τοπικές συντεταγμένες. Το σημείο αγκύρωσης χρησιμοποιείται για ελαστική σύνδεση κατά τη διάρκεια της δυναμικής.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Η συντεταγμένη y που υποδεικνύει τη θέση του χειριστηρίου ελέγχου ενός σχήματος.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


Καθορίζει τον τύπο συμπεριφοράς που παρουσιάζει η συντεταγμένη x του χειριστηρίου ελέγχου μετά τη μετακίνηση του χειριστηρίου.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


Καθορίζει τη συντεταγμένη y για το σημείο αγκύρωσης μιας λαβής ελέγχου σε τοπικές συντεταγμένες. Το σημείο αγκύρωσης χρησιμοποιείται για ελαστική σύνδεση κατά τη διάρκεια της δυναμικής.

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

