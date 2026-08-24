---
title: Προστασία
second_title: Αναφορά API του Aspose.Diagram για Java
description: Το κλείδωμα βοηθά στην αποφυγή ακούσιων αλλαγών στο σχήμα, αλλά δεν εμποδίζει το Microsoft Visio από την επαναφορά τιμών σε άλλες περιπτώσεις.
type: docs
weight: 312
url: /el/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Το κλείδωμα βοηθά στην αποτροπή ακούσιων αλλαγών στο σχήμα, αλλά δεν εμποδίζει το Microsoft Visio από το να επαναφέρει τιμές σε άλλες περιστάσεις. Επίσης, δεν προστατεύει από αλλαγές που γίνονται στο παράθυρο ShapeSheet.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getLockAspect()](#getLockAspect--) | Καθορίζει εάν η αναλογία διαστάσεων του σχήματος είναι κλειδωμένη. |
| [getLockBegin()](#getLockBegin--) | Καθορίζει εάν το αρχικό σημείο ενός σχήματος 1-D είναι κλειδωμένο σε συγκεκριμένη θέση. |
| [getLockCalcWH()](#getLockCalcWH--) | Καθορίζει εάν το ορθογώνιο επιλογής ενός σχήματος είναι κλειδωμένο ώστε να μην μπορεί να επαναϋπολογιστεί όταν επεξεργάζεται μια κορυφή ή αλλάζει ο τύπος στοιχείου στο στοιχείο Geom. |
| [getLockCrop()](#getLockCrop--) | Καθορίζει εάν ένα εξωτερικό αντικείμενο είναι κλειδωμένο ώστε να μην μπορεί να περικοπεί με το εργαλείο Crop στο Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Καθορίζει εάν ο χρήστης μπορεί να προσθέσει, διαγράψει ή τροποποιήσει προσαρμοσμένες ιδιότητες στη διεπαφή χρήστη (UI) χρησιμοποιώντας το παράθυρο διαλόγου Define Custom Properties. |
| [getLockDelete()](#getLockDelete--) | Καθορίζει εάν ένα σχήμα είναι κλειδωμένο ώστε να μην μπορεί να διαγραφεί. |
| [getLockEnd()](#getLockEnd--) | Καθορίζει εάν το τελικό σημείο ενός σχήματος 1-D είναι κλειδωμένο σε συγκεκριμένη θέση. |
| [getLockFormat()](#getLockFormat--) | Καθορίζει εάν η μορφοποίηση ενός σχήματος είναι κλειδωμένη ώστε να μην μπορεί να αλλάξει. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Επιτρέπει σε ένα υποσχήμα να εμποδίζει τις αλλαγές μορφοποίησης που εφαρμόζονται σε ένα γονικό σχήμα ομάδας στη διεπαφή χρήστη του Visio και διαφορετικά θα διαδοθούν στα επιμέρους σχήματα ομάδας. |
| [getLockGroup()](#getLockGroup--) | Καθορίζει εάν μια ομάδα είναι κλειδωμένη ώστε να μην μπορεί να αποομαδοποιηθεί. |
| [getLockHeight()](#getLockHeight--) | Καθορίζει εάν το ύψος του σχήματος είναι κλειδωμένο. |
| [getLockMoveX()](#getLockMoveX--) | Καθορίζει εάν η οριζόντια θέση του σχήματος είναι κλειδωμένη ώστε να μην μπορεί να μετακινηθεί οριζόντια. |
| [getLockMoveY()](#getLockMoveY--) | Καθορίζει εάν η κάθετη θέση του σχήματος είναι κλειδωμένη ώστε να μην μπορεί να μετακινηθεί κάθετα. |
| [getLockRotate()](#getLockRotate--) | Καθορίζει εάν το σχήμα είναι κλειδωμένο ώστε να μην μπορεί να περιστραφεί με το εργαλείο Rotation ή τις εντολές Rotate Left ή Rotate Right στο Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Καθορίζει εάν το ορθογώνιο επιλογής ενός σχήματος είναι κλειδωμένο ώστε να μην μπορεί να επαναϋπολογιστεί όταν επεξεργάζεται μια κορυφή ή αλλάζει ο τύπος στοιχείου στο στοιχείο Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | Καθορίζει εάν το κείμενο ενός σχήματος είναι κλειδωμένο ώστε να μην μπορεί να επεξεργαστεί. |
| [getLockThemeColors()](#getLockThemeColors--) | Αποτρέπει τους χρήστες από την εφαρμογή χρωμάτων θέματος στο σχήμα. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Αποτρέπει τους χρήστες από την εφαρμογή εφέ θέματος στο σχήμα. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Καθορίζει εάν οι κορυφές ενός σχήματος είναι κλειδωμένες ώστε να μην μπορούν να επεξεργαστούν με κανένα εργαλείο στη γραμμή εργαλείων. |
| [getLockWidth()](#getLockWidth--) | Καθορίζει εάν το πλάτος του σχήματος είναι κλειδωμένο ώστε να παραμένει αμετάβλητο όταν το σχήμα αλλάζει μέγεθος. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Καθορίζει εάν η αναλογία διαστάσεων του σχήματος είναι κλειδωμένη. Εάν είναι κλειδωμένη, το σχήμα μπορεί να αλλάξει μέγεθος μόνο αναλογικά· δεν μπορεί να αλλάξει μέγεθος σε μία μόνο διάσταση.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Καθορίζει εάν το αρχικό σημείο ενός σχήματος 1-D είναι κλειδωμένο σε συγκεκριμένη θέση.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Καθορίζει εάν το ορθογώνιο επιλογής ενός σχήματος είναι κλειδωμένο ώστε να μην μπορεί να επαναϋπολογιστεί όταν επεξεργάζεται μια κορυφή ή αλλάζει ο τύπος στοιχείου στο στοιχείο Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Καθορίζει εάν ένα εξωτερικό αντικείμενο είναι κλειδωμένο ώστε να μην μπορεί να περικοπεί με το εργαλείο Crop στο Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Καθορίζει εάν ο χρήστης μπορεί να προσθέσει, διαγράψει ή τροποποιήσει προσαρμοσμένες ιδιότητες στη διεπαφή χρήστη (UI) χρησιμοποιώντας το παράθυρο διαλόγου Define Custom Properties.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Καθορίζει εάν ένα σχήμα είναι κλειδωμένο ώστε να μην μπορεί να διαγραφεί.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Καθορίζει εάν το τελικό σημείο ενός σχήματος 1-D είναι κλειδωμένο σε συγκεκριμένη θέση.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Καθορίζει εάν η μορφοποίηση ενός σχήματος είναι κλειδωμένη ώστε να μην μπορεί να αλλάξει. Συγκεκριμένα, αυτό το στοιχείο προστατεύει από την αλλαγή μορφοποίησης κειμένου, γραμμής και γεμίσματος, ή από την αλλαγή του στοιχείου Style από το οποίο κληρονομεί το σχήμα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Επιτρέπει σε ένα υποσχήμα να εμποδίζει τις αλλαγές μορφοποίησης που εφαρμόζονται σε ένα γονικό σχήμα ομάδας στη διεπαφή χρήστη του Visio και διαφορετικά θα διαδοθούν στα επιμέρους σχήματα ομάδας.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Καθορίζει εάν μια ομάδα είναι κλειδωμένη ώστε να μην μπορεί να αποομαδοποιηθεί.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Καθορίζει εάν το ύψος του σχήματος είναι κλειδωμένο. Εάν είναι κλειδωμένο, το ύψος του παραμένει αμετάβλητο όταν το σχήμα αλλάζει μέγεθος.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Καθορίζει εάν η οριζόντια θέση του σχήματος είναι κλειδωμένη ώστε να μην μπορεί να μετακινηθεί οριζόντια.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Καθορίζει εάν η κάθετη θέση του σχήματος είναι κλειδωμένη ώστε να μην μπορεί να μετακινηθεί κάθετα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Καθορίζει εάν το σχήμα είναι κλειδωμένο ώστε να μην μπορεί να περιστραφεί με το εργαλείο Rotation ή τις εντολές Rotate Left ή Rotate Right στο Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Καθορίζει εάν το ορθογώνιο επιλογής ενός σχήματος είναι κλειδωμένο ώστε να μην μπορεί να επαναϋπολογιστεί όταν επεξεργάζεται μια κορυφή ή αλλάζει ο τύπος στοιχείου στο στοιχείο Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Καθορίζει εάν το κείμενο ενός σχήματος είναι κλειδωμένο ώστε να μην μπορεί να επεξεργαστεί. Ωστόσο, το κείμενο μπορεί ακόμη να μορφοποιηθεί εφαρμόζοντας ένα στυλ, χρησιμοποιώντας τις επιλογές Style στην καρτέλα Γραμματοσειρά του διαλόγου Κείμενο.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Αποτρέπει τους χρήστες από την εφαρμογή χρωμάτων θέματος στο σχήμα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Αποτρέπει τους χρήστες από την εφαρμογή εφέ θέματος στο σχήμα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Καθορίζει εάν οι κορυφές ενός σχήματος είναι κλειδωμένες ώστε να μην μπορούν να επεξεργαστούν με κανένα εργαλείο στη γραμμή εργαλείων.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Καθορίζει εάν το πλάτος του σχήματος είναι κλειδωμένο ώστε να παραμένει αμετάβλητο όταν το σχήμα αλλάζει μέγεθος.

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

