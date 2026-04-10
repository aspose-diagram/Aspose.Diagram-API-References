---
title: Εικόνα
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει τις τιμές γάμμα, φωτεινότητας, αντίθεσης, θολώματος, όξυνσης, αποθορυβοποίησης και διαφάνειας για ένα bitmap.
type: docs
weight: 196
url: /el/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Περιέχει τις τιμές γάμμα, φωτεινότητας, αντίθεσης, θολώματος, ενίσχυσης, αποθορυβοποίησης και διαφάνειας για ένα bitmap.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Θολώνει ή μαλακώνει μια bitmap εικόνα. |
| [getBrightness()](#getBrightness--) | Ρυθμίζει τη φωτεινότητα μιας bitmap εικόνας. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Καθορίζει την αντίθεση μιας bitmap εικόνας. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getDenoise()](#getDenoise--) | Αφαιρεί τον θόρυβο (pixel που έχουν τυχαία κατανεμημένα επίπεδα χρώματος) από μια bitmap εικόνα. |
| [getGamma()](#getGamma--) | Ρυθμίζει ή διορθώνει την ένταση μιας εικόνας για μια συγκεκριμένη συσκευή εξόδου, όπως οθόνη ή σαρωτής. |
| [getSharpen()](#getSharpen--) | Καθορίζει το ποσό για την όξυνση μιας bitmap εικόνας. |
| [getTransparency()](#getTransparency--) | Καθορίζει το επίπεδο διαφάνειας για ένα χρώμα στρώσης, από 0 (αδιαφανές) έως 1 (πλήρως διαφανές). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/image\#getDel--) |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Θολώνει ή μαλακώνει μια bitmap εικόνα. Το στοιχείο Blur περιέχει μια τιμή μεταξύ 0 και 1· η προεπιλεγμένη τιμή είναι 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Ρυθμίζει τη φωτεινότητα μιας bitmap εικόνας. Το στοιχείο Brightness περιέχει μια τιμή μεταξύ 0 και 1· η προεπιλεγμένη τιμή είναι 0,5.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


Καθορίζει την αντίθεση μιας bitmap εικόνας. Το στοιχείο Contrast περιέχει μια τιμή μεταξύ 0 και 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Αφαιρεί τον θόρυβο (pixel που έχουν τυχαία κατανεμημένα επίπεδα χρώματος) από μια bitmap εικόνα.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Ρυθμίζει ή διορθώνει την ένταση μιας εικόνας για μια συγκεκριμένη συσκευή εξόδου, όπως οθόνη ή σαρωτής. Η προεπιλεγμένη τιμή είναι 1 (χωρίς διόρθωση.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Καθορίζει το ποσό για την όξυνση μιας bitmap εικόνας. Η όξυνση μιας εικόνας την εστιάζει αυξάνοντας την αντίθεση των γειτονικών pixel.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Καθορίζει το επίπεδο διαφάνειας για ένα χρώμα στρώσης, από 0 (αδιαφανές) έως 1 (πλήρως διαφανές).

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/image\#getDel--)

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

