---
title: DataRecordSet
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αποθηκεύει μορφές, ανανεώνει και εκθέτει δεδομένα που ελήφθησαν από μια βάση δεδομένων στο Microsoft Visio.
type: docs
weight: 113
url: /el/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Αποθηκεύει, μορφοποιεί, ανανεώνει και εκθέτει δεδομένα που ερωτήθηκαν από μια βάση δεδομένων στο Microsoft Visio.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Περιέχει XML που συμμορφώνεται με το κλασικό σχήμα XML του ADO για ένα σύνολο εγγραφών ADO και που περιγράφει τα δεδομένα στο σύνολο εγγραφών δεδομένων. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Ορίζει έναν κανόνα που συγκρίνει μια στήλη στο γονικό στοιχείο DataRecordset με ένα στοιχείο δεδομένων σχήματος από την τελευταία επιτυχημένη αυτόματη ενέργεια σύνδεσης που εκτελέστηκε στη διεπαφή χρήστη. |
| [getChecksum()](#getChecksum--) | Μια τιμή αθροίσματος ελέγχου, που δημιουργείται από το Visio, και βασίζεται σε ιδιότητες του συνόλου εγγραφών δεδομένων. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Η συμβολοσειρά εντολής που χρησιμοποιείται για την ερώτηση δεδομένων από την πηγή δεδομένων. |
| [getConnectionID()](#getConnectionID--) | Το αναγνωριστικό σύνδεσης για το σχετικό αντικείμενο DataConnection. |
| [getDataColumns()](#getDataColumns--) | Περιέχει όλα τα στοιχεία DataColumn σε ένα σύνολο εγγραφών δεδομένων. |
| [getID()](#getID--) | Το αναγνωριστικό του συνόλου εγγραφών δεδομένων, μοναδικό εντός του εγγράφου. |
| [getName()](#getName--) | Το εμφανιζόμενο (ή "φιλικό") όνομα του συνόλου εγγραφών δεδομένων. |
| [getNextRowID()](#getNextRowID--) | Το επόμενο διαθέσιμο αναγνωριστικό γραμμής Visio. |
| [getOptions()](#getOptions--) | Επιλογές που εφαρμόζονται στο σύνολο εγγραφών δεδομένων. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Αναγνωρίζει μία ή περισσότερες στήλες πρωτεύοντος κλειδιού στο σύνολο εγγραφών δεδομένων. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Δείχνει μια γραμμή στο σύνολο εγγραφών δεδομένων που συνδέεται με ένα σχήμα που βρίσκεται σε σύγκρουση μετά την ανανέωση του συνόλου εγγραφών δεδομένων. |
| [getRefreshInterval()](#getRefreshInterval--) | Πόσο συχνά (σε λεπτά) το Visio ανανεώνει αυτόματα το σύνολο εγγραφών δεδομένων. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Εάν η διεπαφή χρήστη για την εναρμόνιση δεδομένων πρέπει να απενεργοποιηθεί. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Εάν θα αντικατασταθούν οι αλλαγές του χρήστη στα στοιχεία δεδομένων σχήματος σε σχήματα που συνδέονται με δεδομένα όταν το σύνολο εγγραφών δεδομένων ανανεώνεται. |
| [getReplaceLinks()](#getReplaceLinks--) | Ορίζει πώς αντιμετωπίζονται οι σύνδεσμοι σχήματος-δεδομένων όταν τα σχήματα αντιγράφονται ή αποκόπτονται. 1 για αντικατάσταση των υπαρχόντων συνδέσμων στο σχήμα-στόχο. 0 για διατήρηση των υπαρχόντων συνδέσμων στο σχήμα-στόχο. |
| [getRowMaps()](#getRowMaps--) | Αντιστοιχίζει μια γραμμή του συνόλου εγγραφών δεδομένων σε ένα σχήμα. |
| [getRowOrder()](#getRowOrder--) | Εάν θα χρησιμοποιηθεί η σειρά των γραμμών στο σύνολο εγγραφών δεδομένων ως πρωτεύον κλειδί. |
| [getTimeRefreshed()](#getTimeRefreshed--) | Η ημερομηνία και ώρα που το σύνολο εγγραφών δεδομένων ανανεώθηκε τελευταία φορά. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Εκτελεί τη συμβολοσειρά ερώτησης που σχετίζεται με το συνδεδεμένο (μη βασισμένο σε XML) DataRecordset και ενημερώνει τα συνδεδεμένα σχήματα με νέα δεδομένα από την πηγή δεδομένων που επιστρέφεται από την ερώτηση. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
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
### getADOData() {#getADOData--}
```
public String getADOData()
```


Περιέχει XML που συμμορφώνεται με το κλασικό σχήμα XML του ADO για ένα σύνολο εγγραφών ADO και που περιγράφει τα δεδομένα στο σύνολο εγγραφών δεδομένων.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Ορίζει έναν κανόνα που συγκρίνει μια στήλη στο γονικό στοιχείο DataRecordset με ένα στοιχείο δεδομένων σχήματος από την τελευταία επιτυχημένη αυτόματη ενέργεια σύνδεσης που εκτελέστηκε στη διεπαφή χρήστη.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Μια τιμή αθροίσματος ελέγχου, που δημιουργείται από το Visio και βασίζεται στις ιδιότητες του συνόλου δεδομένων. Ορίστε αυτό το χαρακτηριστικό σε 0· το Visio επαναϋπολογίζει αυτήν την τιμή κατά την εκτέλεση.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


Η συμβολοσειρά εντολής που χρησιμοποιείται για την ερώτηση δεδομένων από την πηγή δεδομένων.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


Το αναγνωριστικό σύνδεσης για το σχετικό αντικείμενο DataConnection. Δεν υπάρχει για πηγές δεδομένων XML.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Περιέχει όλα τα στοιχεία DataColumn σε ένα σύνολο εγγραφών δεδομένων.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


Το αναγνωριστικό του συνόλου εγγραφών δεδομένων, μοναδικό εντός του εγγράφου.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Το εμφανιζόμενο (ή "φιλικό") όνομα του συνόλου εγγραφών δεδομένων.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


Το επόμενο διαθέσιμο αναγνωριστικό γραμμής Visio.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Επιλογές που εφαρμόζονται στο σύνολο δεδομένων. Οι πιθανές τιμές μπορούν να είναι οποιοσδήποτε συνδυασμός ενός ή περισσότερων από αυτά που εμφανίζονται στον παρακάτω πίνακα.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Αναγνωρίζει μία ή περισσότερες στήλες πρωτεύοντος κλειδιού στο σύνολο εγγραφών δεδομένων.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Δείχνει μια γραμμή στο σύνολο δεδομένων που συνδέεται με ένα σχήμα που βρίσκεται σε σύγκρουση μετά την ανανέωση του συνόλου δεδομένων. RowID - Δείχνει μια γραμμή στο σύνολο δεδομένων που συνδέεται με ένα σχήμα που βρίσκεται σε σύγκρουση μετά την ανανέωση του συνόλου δεδομένων. ShapeID - Αναγνωριστικό σχήματος (Shape ID) του σχήματος που εμπλέκεται στη σύγκρουση. PageID - Αναγνωριστικό σελίδας (Page ID) του σχήματος που εμπλέκεται στη σύγκρουση.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Πόσο συχνά (σε λεπτά) το Visio ανανεώνει αυτόματα το σύνολο δεδομένων. Αυτή η τιμή πρέπει να είναι 1 ή μεγαλύτερη.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Αν η διεπαφή χρήστη για την εναρμόνιση δεδομένων πρέπει να απενεργοποιηθεί. True (1) για απενεργοποίηση της διεπαφής χρήστη (UI). False (0) για ενεργοποίηση της UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Εάν θα αντικατασταθούν οι αλλαγές του χρήστη στα στοιχεία δεδομένων σχήματος σε σχήματα που συνδέονται με δεδομένα όταν το σύνολο εγγραφών δεδομένων ανανεώνεται.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Ορίζει πώς αντιμετωπίζονται οι σύνδεσμοι σχήματος-δεδομένων όταν τα σχήματα αντιγράφονται ή αποκόπτονται. 1 για αντικατάσταση των υπαρχόντων συνδέσμων στο σχήμα-στόχο. 0 για διατήρηση των υπαρχόντων συνδέσμων στο σχήμα-στόχο. Εάν αυτό το χαρακτηριστικό λείπει, το Visio ρωτά το χρήστη αν θα αντικαταστήσει τους συνδέσμους κατά την αντιγραφή ή την αποκοπή.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Αντιστοιχίζει μια γραμμή του συνόλου δεδομένων σε ένα σχήμα. RowID - Αναγνωριστικό γραμμής (Row ID) της γραμμής, μοναδικό εντός του συνόλου δεδομένων. ShapeID - Αναγνωριστικό σχήματος (Shape ID) του σχήματος που συνδέεται με τα δεδομένα στη γραμμή του συνόλου δεδομένων που προσδιορίζεται από το RowID. PageID - Αναγνωριστικό σελίδας (Page ID) του σχήματος που συνδέεται με τα δεδομένα στη γραμμή του συνόλου δεδομένων που προσδιορίζεται από το RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Αν θα χρησιμοποιηθεί η σειρά των γραμμών στο σύνολο δεδομένων ως πρωτεύον κλειδί. True (1) εάν τα αναγνωριστικά γραμμών καθορίζονται από τη σειρά των γραμμών. False (0) εάν τα αναγνωριστικά γραμμών καθορίζονται από τις τιμές στη στήλη(ές) του πρωτεύοντος κλειδιού του συνόλου δεδομένων.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


Η ημερομηνία και ώρα που το σύνολο εγγραφών δεδομένων ανανεώθηκε τελευταία φορά.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
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




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


Εκτελεί τη συμβολοσειρά ερώτησης που σχετίζεται με το συνδεδεμένο (μη βασισμένο σε XML) DataRecordset και ενημερώνει τα συνδεδεμένα σχήματα με νέα δεδομένα από την πηγή δεδομένων που επιστρέφεται από την ερώτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| connectionType | int | Ο τύπος του παρόχου που θα χρησιμοποιηθεί για τη σύνδεση Aspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

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

