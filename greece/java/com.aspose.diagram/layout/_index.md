---
title: Διάταξη
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ελέγχουν τη θέση του σχήματος και τις ρυθμίσεις δρομολόγησης συνδέσμων.
type: docs
weight: 215
url: /el/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Περιέχει στοιχεία που ελέγχουν τη θέση του σχήματος και τις ρυθμίσεις δρομολόγησης συνδέσμων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Καθορίζει πότε ένας σύνδεσμος επαναδρομολογείται. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Καθορίζει εάν ένας σύνδεσμος πηδά όταν δύο σύνδεσμοι διασχίζουν, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Καθορίζει την κατεύθυνση του άλματος γραμμής για άλματα γραμμής που εμφανίζονται σε οριζόντιο τμήμα ενός δυναμικού συνδέσμου. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Καθορίζει την κατεύθυνση του άλματος γραμμής για άλματα γραμμής που εμφανίζονται σε κάθετο τμήμα ενός δυναμικού συνδέσμου. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Καθορίζει το στυλ του άλματος γραμμής για άλματα γραμμής σε έναν δυναμικό σύνδεσμο. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Καθορίζει την εμφάνιση ενός συνδέσμου. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getDisplayLevel()](#getDisplayLevel--) | Καθορίζει τη ζώνη επιπέδου εμφάνισης (το σχετικό εύρος ομαδοποίησης κατά σειρά Z) για το σχήμα. |
| [getRelationships()](#getRelationships--) | Αποθηκεύει τις σχέσεις μεταξύ δοχείων, λιστών, επεξηγήσεων και σχημάτων. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Καθορίζει τη συμπεριφορά τοποθέτησης για ένα τοποθετήσιμο σχήμα. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Καθορίζει εάν τα τοποθετήσιμα σχήματα μπορούν να τοποθετηθούν πάνω από ένα σχήμα όταν ο χρήστης επιλέγει Lay Out Shapes (μενού Shapes). |
| [getShapePermeableX()](#getShapePermeableX--) | Καθορίζει εάν ένας σύνδεσμος μπορεί να δρομολογηθεί οριζόντια μέσω ενός σχήματος. |
| [getShapePermeableY()](#getShapePermeableY--) | Καθορίζει εάν ένας σύνδεσμος μπορεί να δρομολογηθεί κάθετα μέσω ενός σχήματος. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Καθορίζει πώς ένα τοποθετήσιμο σχήμα αναστρέφεται και/ή περιστρέφεται στη σελίδα όταν ο χρήστης επιλέγει Lay Out Shapes (μενού Shapes). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Καθορίζει το στυλ τοποθέτησης για τα παιδιά. |
| [getShapePlowCode()](#getShapePlowCode--) | Καθορίζει εάν ένα τοποθετήσιμο σχήμα απομακρύνεται όταν σύρετε ένα άλλο τοποθετήσιμο σχήμα κοντά στο σχήμα στη σελίδα σχεδίασης. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Καθορίζει το στυλ δρομολόγησης και την κατεύθυνση για έναν σύνδεσμο στη σελίδα σχεδίασης. |
| [getShapeSplit()](#getShapeSplit--) | Καθορίζει εάν αυτό το σχήμα μπορεί να χωρίσει σχήματα που είναι διαχωρίσιμα. |
| [getShapeSplittable()](#getShapeSplittable--) | Καθορίζει εάν αυτό το 1‑Δ σχήμα μπορεί να χωριστεί. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Καθορίζει πότε ένας σύνδεσμος επαναδρομολογείται.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Καθορίζει εάν ένας σύνδεσμος πηδά όταν δύο σύνδεσμοι διασχίζουν,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Καθορίζει την κατεύθυνση του άλματος γραμμής για άλματα γραμμής που εμφανίζονται σε οριζόντιο τμήμα ενός δυναμικού συνδέσμου.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Καθορίζει την κατεύθυνση του άλματος γραμμής για άλματα γραμμής που εμφανίζονται σε κάθετο τμήμα ενός δυναμικού συνδέσμου.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Καθορίζει το στυλ του άλματος γραμμής για άλματα γραμμής σε έναν δυναμικό σύνδεσμο.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Καθορίζει την εμφάνιση ενός συνδέσμου.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Καθορίζει τη ζώνη επιπέδου εμφάνισης (το σχετικό εύρος ομαδοποίησης κατά σειρά Z) για το σχήμα.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Αποθηκεύει τις σχέσεις μεταξύ δοχείων, λιστών, επεξηγήσεων και σχημάτων.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Καθορίζει τη συμπεριφορά τοποθέτησης για ένα τοποθετήσιμο σχήμα.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Καθορίζει εάν τα τοποθετήσιμα σχήματα μπορούν να τοποθετηθούν πάνω από ένα σχήμα όταν ο χρήστης επιλέγει Lay Out Shapes (μενού Shapes).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Καθορίζει εάν ένας σύνδεσμος μπορεί να δρομολογηθεί οριζόντια μέσω ενός σχήματος.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Καθορίζει εάν ένας σύνδεσμος μπορεί να δρομολογηθεί κάθετα μέσω ενός σχήματος.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Καθορίζει πώς ένα τοποθετήσιμο σχήμα αναστρέφεται και/ή περιστρέφεται στη σελίδα όταν ο χρήστης επιλέγει Lay Out Shapes (μενού Shapes).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Καθορίζει το στυλ τοποθέτησης για τα παιδιά.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Καθορίζει εάν ένα τοποθετήσιμο σχήμα απομακρύνεται όταν σύρετε ένα άλλο τοποθετήσιμο σχήμα κοντά στο σχήμα στη σελίδα σχεδίασης.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Καθορίζει το στυλ δρομολόγησης και την κατεύθυνση για έναν σύνδεσμο στη σελίδα σχεδίασης.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Καθορίζει εάν αυτό το σχήμα μπορεί να χωρίσει σχήματα που είναι διαχωρίσιμα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Καθορίζει εάν αυτό το 1‑Δ σχήμα μπορεί να χωριστεί.

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

