---
title: Διάφορα
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει διάφορα στοιχεία σχημάτων και ομάδων, όπως αυτά που ελέγχουν την επισήμανση επιλογής και την ορατότητα.
type: docs
weight: 247
url: /el/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Περιέχει διάφορα στοιχεία σχημάτων και ομάδων, όπως αυτά που ελέγχουν την επισήμανση επιλογής και την ορατότητα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Περιέχει έναν τύπο ενεργοποίησης (trigger formula) που δημιουργείται από το Microsoft Visio και καθορίζει αν πρέπει να μετακινηθεί το αρχικό σημείο ενός 1‑Δ σχήματος για να διατηρηθεί η σύνδεσή του με άλλο σχήμα. |
| [getCalendar()](#getCalendar--) | Καθορίζει το ημερολόγιο που χρησιμοποιείται για προσαρμοσμένες ιδιότητες, πεδία κειμένου και τύπους στοιχείων. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Περιέχει το κείμενο του σχολίου σε μορφή συμβολοσειράς για ένα σχήμα. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Καθορίζει το ποσοστό κατά το οποίο κλιμακώνεται ένα σχήμα όταν το τοποθετείτε στη σελίδα σχεδίασης. |
| [getDynFeedback()](#getDynFeedback--) | Καθορίζει τον τύπο της οπτικής ανάδρασης που παρέχεται στους χρήστες όταν σύρουν έναν σύνδεσμο. |
| [getEndTrigger()](#getEndTrigger--) | Περιέχει έναν τύπο ενεργοποίησης (trigger formula) που δημιουργείται από το Microsoft Visio. |
| [getGlueType()](#getGlueType--) | Καθορίζει αν επιτρέπεται η δυναμική (σχήμα-σε-σχήμα) κόλλα κατά τη σύνδεση με ένα σχήμα. |
| [getHideText()](#getHideText--) | Κρύβει το κείμενο ενός σχήματος. |
| [getLangID()](#getLangID--) | Δείχνει το αναγνωριστικό τοπικής ρύθμισης (LCID) της γλώσσας στην οποία εισήχθη ο τύπος κελιού, το κείμενο, η προσαρμοσμένη ιδιότητα ή το σχόλιο. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Καθορίζει αν τα σχήματα είναι τοπικοποιημένα (αν το στοιχείο LangID τους επανέρχεται) όταν αντιγράφονται μεταξύ εγγράφων. |
| [getNoAlignBox()](#getNoAlignBox--) | Καθορίζει αν εμφανίζεται το ορθογώνιο επιλογής όταν το σχήμα είναι επιλεγμένο. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Καθορίζει αν εμφανίζονται τα χειριστήρια ελέγχου όταν το σχήμα είναι επιλεγμένο. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Καθορίζει αν ένα σχήμα αλλάζει δυναμικά το μέγεθος ή περιστρέφεται καθώς ο χρήστης το χειρίζεται. |
| [getNoObjHandles()](#getNoObjHandles--) | Καθορίζει αν εμφανίζονται τα χειριστήρια επιλογής όταν το σχήμα είναι επιλεγμένο. |
| [getNonPrinting()](#getNonPrinting--) | Καθορίζει αν ένα επιλεγμένο σχήμα μπορεί να εκτυπωθεί. |
| [getObjType()](#getObjType--) | Καθορίζει εάν τα αντικείμενα είναι τοποθετήσιμα ή δρομολογήσιμα σε διαγράμματα όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη σχημάτων στη σελίδα σχεδίασης. |
| [getShapeKeywords()](#getShapeKeywords--) | Περιέχει λέξεις-κλειδιά αναζήτησης που έχουν εκχωρηθεί σε προσαρμοσμένα κύρια σχήματα. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Καθορίζει αν θα επαναϋπολογιστεί το ορθογώνιο επιλογής ενός σχήματος κάθε φορά που μετακινείται ένα χειριστήριο ελέγχου. |
| [getWalkPreference()](#getWalkPreference--) | Καθορίζει εάν ένα άκρο ενός σχήματος 1‑Δ μετακινείται σε οριζόντιο ή κατακόρυφο σημείο σύνδεσης στο σχήμα στο οποίο είναι κολλημένο, χρησιμοποιώντας δυναμική κόλλα, όταν το σχήμα μετακινείται σε ασαφή θέση. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Καθορίζει αν το σχήμα μπορεί να προστεθεί σε μια ομάδα σύροντάς το πάνω στην ομάδα. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Δείχνει αν οι τιμές των καθορισμένων κελιών σε ένα κύριο σχήμα αντικαθιστούν τις τιμές (συμπεριλαμβανομένων των τοπικών τιμών) ενός σχήματος που αντικαθίσταται κατά τη διάρκεια μιας λειτουργίας αντικατάστασης σχήματος. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Περιέχει έναν τύπο ενεργοποίησης (trigger formula) που δημιουργείται από το Microsoft Visio και καθορίζει αν πρέπει να μετακινηθεί το αρχικό σημείο ενός 1‑Δ σχήματος για να διατηρηθεί η σύνδεσή του με άλλο σχήμα.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Καθορίζει το ημερολόγιο που χρησιμοποιείται για προσαρμοσμένες ιδιότητες, πεδία κειμένου και τύπους στοιχείων.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Καθορίζει το ποσοστό κατά το οποίο κλιμακώνεται ένα σχήμα όταν το τοποθετείτε στη σελίδα σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Καθορίζει τον τύπο της οπτικής ανάδρασης που παρέχεται στους χρήστες όταν σύρουν έναν σύνδεσμο.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Περιέχει έναν τύπο ενεργοποίησης (trigger formula) που δημιουργείται από το Microsoft Visio. Αυτός ο τύπος ενεργοποίησης καθορίζει αν πρέπει να μετακινηθεί το τελικό σημείο ενός 1‑Δ σχήματος για να διατηρηθεί η σύνδεσή του με άλλο σχήμα.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Καθορίζει αν επιτρέπεται η δυναμική (σχήμα-σε-σχήμα) κόλλα κατά τη σύνδεση με ένα σχήμα.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Αποκρύπτει το κείμενο για ένα σχήμα. Μπορείτε να προβάλετε το κείμενο, να επεξεργαστείτε τις ιδιότητες και να εφαρμόσετε στυλ στο κείμενο στο μπλοκ κειμένου, αν και οι αλλαγές δεν θα εμφανιστούν μέχρι να ορίσετε το στοιχείο HideText σε 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Δείχνει το αναγνωριστικό τοπικής ρύθμισης (LCID) της γλώσσας στην οποία εισήχθη ο τύπος κελιού, το κείμενο, η προσαρμοσμένη ιδιότητα ή το σχόλιο.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Καθορίζει αν τα σχήματα είναι τοπικοποιημένα (αν το στοιχείο LangID τους επανέρχεται) όταν αντιγράφονται μεταξύ εγγράφων.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Καθορίζει αν εμφανίζεται το ορθογώνιο επιλογής όταν το σχήμα είναι επιλεγμένο.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Καθορίζει αν εμφανίζονται τα χειριστήρια ελέγχου όταν το σχήμα είναι επιλεγμένο.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Καθορίζει αν ένα σχήμα αλλάζει δυναμικά το μέγεθος ή περιστρέφεται καθώς ο χρήστης το χειρίζεται.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Καθορίζει αν εμφανίζονται τα χειριστήρια επιλογής όταν το σχήμα είναι επιλεγμένο.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Καθορίζει αν ένα επιλεγμένο σχήμα μπορεί να εκτυπωθεί.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Καθορίζει εάν τα αντικείμενα είναι τοποθετήσιμα ή δρομολογήσιμα σε διαγράμματα όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη σχημάτων στη σελίδα σχεδίασης.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Περιέχει λέξεις-κλειδιά αναζήτησης που έχουν εκχωρηθεί σε προσαρμοσμένα κύρια σχήματα.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Καθορίζει αν θα επαναϋπολογιστεί το ορθογώνιο επιλογής ενός σχήματος κάθε φορά που μετακινείται ένα χειριστήριο ελέγχου.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Καθορίζει εάν ένα άκρο ενός σχήματος 1‑Δ μετακινείται σε οριζόντιο ή κατακόρυφο σημείο σύνδεσης στο σχήμα στο οποίο είναι κολλημένο, χρησιμοποιώντας δυναμική κόλλα, όταν το σχήμα μετακινείται σε ασαφή θέση.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


Καθορίζει αν το σχήμα μπορεί να προστεθεί σε μια ομάδα σύροντάς το πάνω στην ομάδα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Δείχνει αν οι τιμές των καθορισμένων κελιών σε ένα κύριο σχήμα αντικαθιστούν τις τιμές (συμπεριλαμβανομένων των τοπικών τιμών) ενός σχήματος που αντικαθίσταται κατά τη διάρκεια μιας λειτουργίας αντικατάστασης σχήματος.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

