---
title: DataColumn
second_title: Αναφορά API του Aspose.Diagram για Java
description: Ορίζει πώς εμφανίζεται μια στήλη δεδομένων στο παράθυρο Εξωτερικών Δεδομένων στη διεπαφή χρήστη του Visio και προσδιορίζει τα δεδομένα στη στήλη ορίζοντας τον τύπο δεδομένων και τη μορφοποίηση.
type: docs
weight: 108
url: /el/java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Ορίζει πώς εμφανίζεται μια στήλη δεδομένων στο παράθυρο Εξωτερικών Δεδομένων στη διεπαφή χρήστη του Visio και προσδιορίζει τα δεδομένα στη στήλη ορίζοντας τον τύπο δεδομένων και τη μορφοποίηση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DataColumn()](#DataColumn--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Αναγνωριστικό ημερολογίου της στήλης δεδομένων. |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | Εξωτερικό όνομα της στήλης δεδομένων. |
| [getCurrency()](#getCurrency--) | Αναγνωριστικό νομίσματος της στήλης δεδομένων. |
| [getDataType()](#getDataType--) | Τύπος των δεδομένων στη στήλη δεδομένων. |
| [getDegree()](#getDegree--) | Καθορίζει το βαθμό (δυνάμη) των μονάδων, για παράδειγμα τετράγωνο ή κύβο. |
| [getDisplayOrder()](#getDisplayOrder--) | Ορίζει τη θέση εμφάνισης της στήλης δεδομένων στο παράθυρο Εξωτερικά Δεδομένα, από την πιο αριστερή στήλη (0) έως την πιο δεξιά στήλη (μεγαλύτερη τιμή). |
| [getDisplayWidth()](#getDisplayWidth--) | Πλάτος της στήλης δεδομένων στο παράθυρο Εξωτερικά Δεδομένα. |
| [getHyperlink()](#getHyperlink--) | Καθορίζει αν η στήλη δεδομένων δημιουργεί υπερσύνδεσμο σε σχήμα όταν το σχήμα συνδέεται με δεδομένα. |
| [getLabel()](#getLabel--) | Ετικέτα της στήλης δεδομένων. |
| [getLangID()](#getLangID--) | Το αναγνωριστικό γλώσσας της στήλης δεδομένων |
| [getMapped()](#getMapped--) | Καθορίζει αν η στήλη είναι ορατή στο παράθυρο Εξωτερικά Δεδομένα. |
| [getName()](#getName--) | Εσωτερικό όνομα της στήλης δεδομένων. |
| [getOrigLabel()](#getOrigLabel--) | Ετικέτα στήλης που επιστρέφεται στο Visio από το υποκείμενο περιβάλλον ADO. |
| [getUnitType()](#getUnitType--) | Τύπος μονάδας των δεδομένων στη στήλη δεδομένων. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataColumn\#(getCalendar() & 0xFFFF)\} |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--) |
| [setCurrency(int value)](#setCurrency-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataColumn\#(getCurrency() & 0xFFFF)\} |
| [setDataType(int value)](#setDataType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataColumn\#(getDataType() & 0xFFFF)\} |
| [setDegree(long value)](#setDegree-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--) |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--) |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--) |
| [setHyperlink(int value)](#setHyperlink-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--) |
| [setLabel(String value)](#setLabel-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--) |
| [setLangID(long value)](#setLangID-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--) |
| [setMapped(int value)](#setMapped-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getName()](../../com.aspose.diagram/datacolumn\#getName--) |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--) |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


Αναγνωριστικό ημερολογίου της στήλης δεδομένων.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnNameID() {#getColumnNameID--}
```
public String getColumnNameID()
```


Εξωτερικό όνομα της στήλης δεδομένων. Εμφανίζεται στις επικεφαλίδες του παραθύρου Εξωτερικών Δεδομένων και στις ετικέτες στα γραφικά δεδομένων.

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


Αναγνωριστικό νομίσματος της στήλης δεδομένων.

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


Τύπος των δεδομένων στη στήλη δεδομένων.

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


Καθορίζει τον βαθμό (δυνάμη) των μονάδων, για παράδειγμα τετράγωνο ή κυβικό. Η προεπιλογή (απόσυρση του χαρακτηριστικού) είναι 1.

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


Ορίζει τη θέση εμφάνισης της στήλης δεδομένων στο παράθυρο Εξωτερικά Δεδομένα, από την πιο αριστερή στήλη (0) έως την πιο δεξιά στήλη (μεγαλύτερη τιμή).

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


Πλάτος της στήλης δεδομένων στο παράθυρο Εξωτερικά Δεδομένα.

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


Καθορίζει αν η στήλη δεδομένων δημιουργεί υπερσύνδεσμο σε σχήμα όταν το σχήμα συνδέεται με δεδομένα.

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


Ετικέτα της στήλης δεδομένων.

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


Το αναγνωριστικό γλώσσας της στήλης δεδομένων

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


Καθορίζει αν η στήλη είναι ορατή στο παράθυρο Εξωτερικών Δεδομένων. Αληθές (1) για να είναι η στήλη ορατή· ψευδές (0) για να μην είναι η στήλη ορατή. Η προεπιλογή (απόσυρση του χαρακτηριστικού) είναι η στήλη να είναι ορατή.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Εσωτερικό όνομα της στήλης δεδομένων. Χρησιμοποιείται ως όνομα γραμμής για το στοιχείο shape-data (προσαρμοσμένη ιδιότητα) που προστίθεται σε ένα σχήμα όταν το σχήμα συνδέεται με μια γραμμή δεδομένων.

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


Ετικέτα στήλης που επιστρέφεται στο Visio από το υποκείμενο περιβάλλον ADO.

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


Τύπος μονάδας των δεδομένων στη στήλη δεδομένων.

**Returns:**
java.lang.String
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




### setCalendar(int value) {#setCalendar-int-}
```
public void setCalendar(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataColumn\#(getCalendar() & 0xFFFF)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataColumn\#(getCurrency() & 0xFFFF)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataColumn\#(getDataType() & 0xFFFF)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getName()](../../com.aspose.diagram/datacolumn\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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

