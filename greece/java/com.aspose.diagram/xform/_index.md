---
title: XForm
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ελέγχουν τις ιδιότητες γραμμής για ένα σχήμα, όπως το βάρος του μοτίβου και το χρώμα.
type: docs
weight: 449
url: /el/java/com.aspose.diagram/xform/
---

**Inheritance:**
java.lang.Object
```
public class XForm
```

Περιέχει στοιχεία που ελέγχουν τις ιδιότητες γραμμής για ένα σχήμα, όπως το μοτίβο, το βάρος και το χρώμα. Αυτά τα στοιχεία καθορίζουν εάν τα άκρα της γραμμής είναι μορφοποιημένα (για παράδειγμα, με κεφαλή βέλους), το μέγεθος των μορφών άκρων γραμμής, την ακτίνα του στρογγυλεμένου κύκλου που εφαρμόζεται στη γραμμή και το στυλ άκρου γραμμής (στρογγυλό ή τετράγωνο).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Αντιπροσωπεύει την τρέχουσα γωνία περιστροφής του σχήματος σε σχέση με το γονικό του. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getFlipX()](#getFlipX--) | Δείχνει εάν το σχήμα έχει αντιστραφεί οριζόντια |
| [getFlipY()](#getFlipY--) | Δείχνει εάν το σχήμα έχει αντιστραφεί κάθετα. |
| [getHeight()](#getHeight--) | Καθορίζει το ύψος του σχήματος σε μονάδες σχεδίασης. |
| [getLocPinX()](#getLocPinX--) | Καθορίζει τη συντεταγμένη x της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του σχήματος. |
| [getLocPinY()](#getLocPinY--) | Καθορίζει τη συντεταγμένη y της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του σχήματος. |
| [getPinPos()](#getPinPos--) | Καθορίζει τη θέση της ακίδας του σχήματος |
| [getPinX()](#getPinX--) | Καθορίζει τη συντεταγμένη x της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του γονέα του. |
| [getPinY()](#getPinY--) | Καθορίζει τη συντεταγμένη y της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του γονέα του. |
| [getResizeMode()](#getResizeMode--) | Καθορίζει τη τρέχουσα ρύθμιση συμπεριφοράς αλλαγής μεγέθους για το σχήμα όταν βρίσκεται μέσα σε ομάδα. |
| [getWidth()](#getWidth--) | Περιέχει το πλάτος του σχετικού σχήματος σε μονάδες σχεδίασης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(DoubleValue value)](#setAngle-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAngle()](../../com.aspose.diagram/xform\#getAngle--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/xform\#getDel--) |
| [setFlipX(BoolValue value)](#setFlipX-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--) |
| [setFlipY(BoolValue value)](#setFlipY-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--) |
| [setHeight(DoubleValue value)](#setHeight-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHeight()](../../com.aspose.diagram/xform\#getHeight--) |
| [setLocPinX(DoubleValue value)](#setLocPinX-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--) |
| [setLocPinY(DoubleValue value)](#setLocPinY-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--) |
| [setPinPos(int value)](#setPinPos-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--) |
| [setPinX(DoubleValue value)](#setPinX-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPinX()](../../com.aspose.diagram/xform\#getPinX--) |
| [setPinY(DoubleValue value)](#setPinY-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPinY()](../../com.aspose.diagram/xform\#getPinY--) |
| [setResizeMode(ResizeMode value)](#setResizeMode-com.aspose.diagram.ResizeMode-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--) |
| [setWidth(DoubleValue value)](#setWidth-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWidth()](../../com.aspose.diagram/xform\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAngle() {#getAngle--}
```
public DoubleValue getAngle()
```


Αντιπροσωπεύει την τρέχουσα γωνία περιστροφής του σχήματος σε σχέση με το γονικό του.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getFlipX() {#getFlipX--}
```
public BoolValue getFlipX()
```


Δείχνει εάν το σχήμα έχει αντιστραφεί οριζόντια

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlipY() {#getFlipY--}
```
public BoolValue getFlipY()
```


Δείχνει εάν το σχήμα έχει αντιστραφεί κάθετα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHeight() {#getHeight--}
```
public DoubleValue getHeight()
```


Καθορίζει το ύψος του σχήματος σε μονάδες σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinX() {#getLocPinX--}
```
public DoubleValue getLocPinX()
```


Καθορίζει τη συντεταγμένη x της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του σχήματος. Η προεπιλεγμένη φόρμουλα για τον υπολογισμό του LocPinX είναι: F='Width\* 0.5'.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinY() {#getLocPinY--}
```
public DoubleValue getLocPinY()
```


Καθορίζει τη συντεταγμένη y της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του σχήματος. Η προεπιλεγμένη φόρμουλα για τον υπολογισμό του LocPinY είναι: F='Height \* 0.5'.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinPos() {#getPinPos--}
```
public int getPinPos()
```


Καθορίζει τη θέση της ακίδας του σχήματος

**Returns:**
int
### getPinX() {#getPinX--}
```
public DoubleValue getPinX()
```


Καθορίζει τη συντεταγμένη x της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του γονέα του.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinY() {#getPinY--}
```
public DoubleValue getPinY()
```


Καθορίζει τη συντεταγμένη y της ακίδας του σχήματος (κέντρο περιστροφής) σε σχέση με το αρχικό σημείο του γονέα του.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getResizeMode() {#getResizeMode--}
```
public ResizeMode getResizeMode()
```


Καθορίζει τη τρέχουσα ρύθμιση συμπεριφοράς αλλαγής μεγέθους για το σχήμα όταν βρίσκεται μέσα σε ομάδα.

**Returns:**
[ResizeMode](../../com.aspose.diagram/resizemode)
### getWidth() {#getWidth--}
```
public DoubleValue getWidth()
```


Περιέχει το πλάτος του σχετικού σχήματος σε μονάδες σχεδίασης.

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




### setAngle(DoubleValue value) {#setAngle-com.aspose.diagram.DoubleValue-}
```
public void setAngle(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAngle()](../../com.aspose.diagram/xform\#getAngle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/xform\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFlipX(BoolValue value) {#setFlipX-com.aspose.diagram.BoolValue-}
```
public void setFlipX(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFlipY(BoolValue value) {#setFlipY-com.aspose.diagram.BoolValue-}
```
public void setFlipY(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHeight(DoubleValue value) {#setHeight-com.aspose.diagram.DoubleValue-}
```
public void setHeight(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHeight()](../../com.aspose.diagram/xform\#getHeight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinX(DoubleValue value) {#setLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setLocPinX(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinY(DoubleValue value) {#setLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setLocPinY(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinPos(int value) {#setPinPos-int-}
```
public void setPinPos(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPinX(DoubleValue value) {#setPinX-com.aspose.diagram.DoubleValue-}
```
public void setPinX(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPinX()](../../com.aspose.diagram/xform\#getPinX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinY(DoubleValue value) {#setPinY-com.aspose.diagram.DoubleValue-}
```
public void setPinY(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPinY()](../../com.aspose.diagram/xform\#getPinY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setResizeMode(ResizeMode value) {#setResizeMode-com.aspose.diagram.ResizeMode-}
```
public void setResizeMode(ResizeMode value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResizeMode](../../com.aspose.diagram/resizemode) |  |

### setWidth(DoubleValue value) {#setWidth-com.aspose.diagram.DoubleValue-}
```
public void setWidth(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWidth()](../../com.aspose.diagram/xform\#getWidth--)

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

