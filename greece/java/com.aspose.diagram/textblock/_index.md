---
title: TextBlock
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που καθορίζουν τα περιθώρια στοίχισης και τις προεπιλεγμένες θέσεις των στηλοθετών του κειμένου σε ένα μπλοκ κειμένου σχήματος.
type: docs
weight: 400
url: /el/java/com.aspose.diagram/textblock/
---

**Inheritance:**
java.lang.Object
```
public class TextBlock
```

Περιέχει στοιχεία που καθορίζουν την ευθυγράμμιση, τα περιθώρια και τις προεπιλεγμένες θέσεις διακοπής καρτέλας του κειμένου σε ένα μπλοκ κειμένου σχήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Καθορίζει την απόσταση μεταξύ του κάτω ορίου του μπλοκ κειμένου και της τελευταίας γραμμής κειμένου που περιέχει. |
| [getClass()](#getClass--) |  |
| [getDefaultTabStop()](#getDefaultTabStop--) | Καθορίζει το διάστημα των προεπιλεγμένων στηλοθετών σε ένα μπλοκ κειμένου. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getLeftMargin()](#getLeftMargin--) | Καθορίζει την απόσταση μεταξύ του αριστερού ορίου του μπλοκ κειμένου και του κειμένου που περιέχει. |
| [getRightMargin()](#getRightMargin--) | Καθορίζει την απόσταση μεταξύ του δεξιού ορίου του μπλοκ κειμένου και του κειμένου που περιέχει. |
| [getTextBkgnd()](#getTextBkgnd--) | Καθορίζει το χρώμα φόντου του κειμένου για ένα σχήμα. |
| [getTextBkgndTrans()](#getTextBkgndTrans--) | Καθορίζει το επίπεδο διαφάνειας για το χρώμα φόντου του μπλοκ κειμένου ενός σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές). |
| [getTextDirection()](#getTextDirection--) | Καθορίζει την κατεύθυνση των χαρακτήρων σε ένα μπλοκ κειμένου. |
| [getTopMargin()](#getTopMargin--) | Καθορίζει την απόσταση μεταξύ του άνω ορίου του μπλοκ κειμένου και της πρώτης γραμμής κειμένου που περιέχει. |
| [getVerticalAlign()](#getVerticalAlign--) | Καθορίζει την κατακόρυφη στοίχιση του κειμένου μέσα στο μπλοκ κειμένου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBottomMargin(DoubleValue value)](#setBottomMargin-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--) |
| [setDefaultTabStop(DoubleValue value)](#setDefaultTabStop-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/textblock\#getDel--) |
| [setLeftMargin(DoubleValue value)](#setLeftMargin-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--) |
| [setRightMargin(DoubleValue value)](#setRightMargin-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--) |
| [setTextBkgnd(ColorValue value)](#setTextBkgnd-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--) |
| [setTextBkgndTrans(DoubleValue value)](#setTextBkgndTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--) |
| [setTextDirection(TextDirection value)](#setTextDirection-com.aspose.diagram.TextDirection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--) |
| [setTopMargin(DoubleValue value)](#setTopMargin-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--) |
| [setVerticalAlign(VerticalAlign value)](#setVerticalAlign-com.aspose.diagram.VerticalAlign-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--) |
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
### getBottomMargin() {#getBottomMargin--}
```
public DoubleValue getBottomMargin()
```


Καθορίζει την απόσταση μεταξύ του κάτω άκρου του μπλοκ κειμένου και της τελευταίας γραμμής κειμένου που περιέχει. Η προεπιλογή είναι 4 pt. Αυτή η τιμή είναι ανεξάρτητη από την κλίμακα του σχεδίου. Εάν το σχέδιο κλιμακωθεί, το κάτω περιθώριο παραμένει το ίδιο.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultTabStop() {#getDefaultTabStop--}
```
public DoubleValue getDefaultTabStop()
```


Καθορίζει το διάστημα των προεπιλεγμένων στηλοθετών σε ένα μπλοκ κειμένου.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getLeftMargin() {#getLeftMargin--}
```
public DoubleValue getLeftMargin()
```


Καθορίζει την απόσταση μεταξύ του αριστερού άκρου του μπλοκ κειμένου και του κειμένου που περιέχει. Αυτή η τιμή είναι ανεξάρτητη από την κλίμακα του σχεδίου. Εάν το σχέδιο κλιμακωθεί, το αριστερό περιθώριο παραμένει το ίδιο.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRightMargin() {#getRightMargin--}
```
public DoubleValue getRightMargin()
```


Καθορίζει την απόσταση μεταξύ του δεξιού άκρου του μπλοκ κειμένου και του κειμένου που περιέχει. Αυτή η τιμή είναι ανεξάρτητη από την κλίμακα του σχεδίου. Εάν το σχέδιο κλιμακωθεί, το δεξιό περιθώριο παραμένει το ίδιο.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextBkgnd() {#getTextBkgnd--}
```
public ColorValue getTextBkgnd()
```


Καθορίζει το χρώμα φόντου του κειμένου για ένα σχήμα.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getTextBkgndTrans() {#getTextBkgndTrans--}
```
public DoubleValue getTextBkgndTrans()
```


Καθορίζει το επίπεδο διαφάνειας για το χρώμα φόντου του μπλοκ κειμένου ενός σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextDirection() {#getTextDirection--}
```
public TextDirection getTextDirection()
```


Καθορίζει την κατεύθυνση των χαρακτήρων σε ένα μπλοκ κειμένου.

**Returns:**
[TextDirection](../../com.aspose.diagram/textdirection)
### getTopMargin() {#getTopMargin--}
```
public DoubleValue getTopMargin()
```


Καθορίζει την απόσταση μεταξύ του άνω ορίου του μπλοκ κειμένου και της πρώτης γραμμής κειμένου που περιέχει.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getVerticalAlign() {#getVerticalAlign--}
```
public VerticalAlign getVerticalAlign()
```


Καθορίζει την κατακόρυφη στοίχιση του κειμένου μέσα στο μπλοκ κειμένου.

**Returns:**
[VerticalAlign](../../com.aspose.diagram/verticalalign)
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




### setBottomMargin(DoubleValue value) {#setBottomMargin-com.aspose.diagram.DoubleValue-}
```
public void setBottomMargin(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDefaultTabStop(DoubleValue value) {#setDefaultTabStop-com.aspose.diagram.DoubleValue-}
```
public void setDefaultTabStop(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/textblock\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLeftMargin(DoubleValue value) {#setLeftMargin-com.aspose.diagram.DoubleValue-}
```
public void setLeftMargin(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRightMargin(DoubleValue value) {#setRightMargin-com.aspose.diagram.DoubleValue-}
```
public void setRightMargin(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextBkgnd(ColorValue value) {#setTextBkgnd-com.aspose.diagram.ColorValue-}
```
public void setTextBkgnd(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setTextBkgndTrans(DoubleValue value) {#setTextBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setTextBkgndTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextDirection(TextDirection value) {#setTextDirection-com.aspose.diagram.TextDirection-}
```
public void setTextDirection(TextDirection value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextDirection](../../com.aspose.diagram/textdirection) |  |

### setTopMargin(DoubleValue value) {#setTopMargin-com.aspose.diagram.DoubleValue-}
```
public void setTopMargin(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setVerticalAlign(VerticalAlign value) {#setVerticalAlign-com.aspose.diagram.VerticalAlign-}
```
public void setVerticalAlign(VerticalAlign value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VerticalAlign](../../com.aspose.diagram/verticalalign) |  |

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

