---
title: Διάγραμμα
second_title: Αναφορά API του Aspose.Diagram για Java
description: Βασικό στοιχείο της ιεραρχίας αντικειμένων Visio.
type: docs
weight: 117
url: /el/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Βασικό στοιχείο της ιεραρχίας αντικειμένων Visio.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από το αρχείο. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από τη ροή. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από τη ροή χρησιμοποιώντας προκαθορισμένη μορφή. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από τη ροή χρησιμοποιώντας προκαθορισμένες επιλογές φόρτωσης αρχείου. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από το αρχείο χρησιμοποιώντας προκαθορισμένη μορφή. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από το αρχείο χρησιμοποιώντας προκαθορισμένες επιλογές φόρτωσης αρχείου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Προσθέτει master στο διάγραμμα από το πηγαίο διάγραμμα με το Όνομα ή NameU του master. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Προσθέτει master στο διάγραμμα από τη ροή προτύπου με το ID του master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Προσθέτει master στο διάγραμμα από τη ροή προτύπου με το Όνομα ή NameU του master. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Προσθέτει master στο διάγραμμα από το αρχείο προτύπου με το ID του master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Προσθέτει master στο διάγραμμα από το αρχείο προτύπου με το Όνομα ή NameU του master. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Adds shape created by master to specific page. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Adds shape created by master on page with defined PinX and PinY. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Συνδυάζει ένα άλλο αντικείμενο Diagram. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Αντιγράφει το Theme από ένα πηγαίο Diagram. |
| [dispose()](#dispose--) | Εκτελεί εργασίες που ορίζονται από την εφαρμογή, σχετικές με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Εξάγει το διάγραμμα από τη ροή vsd σε μορφή ροής vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Εξάγει το διάγραμμα από τη ροή vsd σε μορφή αρχείου *.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Εξάγει το διάγραμμα από το αρχείο vsd σε μορφή ροής vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Εξάγει το διάγραμμα από το vsd σε μορφή vdw. |
| [getActivePage()](#getActivePage--) | Καθορίζει τη ενεργή σελίδα |
| [getBuildnum()](#getBuildnum--) | Ο αριθμός κατασκευής της παρουσίας Visio που χρησιμοποιήθηκε για τη δημιουργία του εγγράφου. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Περιέχει τον πίνακα χρωμάτων του εγγράφου. |
| [getDataConnections()](#getDataConnections--) | Περιέχει τα στοιχεία DataConnection για το έγγραφο. |
| [getDataRecordSets()](#getDataRecordSets--) | Η συλλογή των αντικειμένων DataRecordset που σχετίζονται με ένα αντικείμενο Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Λάβετε τη διαδρομή του φακέλου Default Fonts |
| [getDocLangID()](#getDocLangID--) | Το μοναδικό ID της γλώσσας διεπαφής χρήστη που έχει καθορίσει ο χρήστης στις Προτιμήσεις Γλώσσας του Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | Περιέχει στοιχεία ιδιοτήτων εγγράφου όπως ο τίτλος του εγγράφου, ο συγγραφέας κ.λπ. |
| [getDocumentSettings()](#getDocumentSettings--) | Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις του εγγράφου. |
| [getDocumentSheet()](#getDocumentSheet--) | Καθορίζει τη δομή ShapeSheet ενός εγγράφου. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Περιέχει ένα MIME (Multipurpose Internet Mail Extensions) κωδικοποιημένο MAPI έντυπο δρομολόγησης email για το έγγραφο. |
| [getEventItems()](#getEventItems--) | Περιέχει ένα στοιχείο EventItem για κάθε γεγονός στο οποίο πρέπει να ανταποκριθεί ένα αντικείμενο. |
| [getFonts()](#getFonts--) | Περιέχει μια συλλογή στοιχείων Font |
| [getHeaderFooter()](#getHeaderFooter--) | Περιέχει στοιχεία για την κεφαλίδα και το υποσέλιδο του εγγράφου. |
| [getInterruptMonitor()](#getInterruptMonitor--) | ο παρακολουθητής διακοπής. |
| [getKey()](#getKey--) | Δείχνει εάν το έγγραφο έχει τροποποιηθεί εκτός του Visio. |
| [getMasters()](#getMasters--) | Συλλογή αντικειμένων Master. |
| [getMetric()](#getMetric--) | Καθορίζει εάν θα χρησιμοποιηθούν μετρικές μονάδες στο σχέδιο. |
| [getPages()](#getPages--) | Συλλογή αντικειμένων Page. |
| [getRibbonX()](#getRibbonX--) | Η συμβολοσειρά Ribbon XML που περνιέται στο έγγραφο για την προσαρμογή της διεπαφής χρήστη του ribbon. |
| [getSolutionXMLs()](#getSolutionXMLs--) | Τιμή XML. |
| [getStart()](#getStart--) | Δείχνει εάν το έγγραφο έχει τροποποιηθεί εκτός του Visio. |
| [getStyleSheets()](#getStyleSheets--) | Συλλογή αντικειμένων StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | Λάβετε τα αχρησιμοποίητα Styles |
| [getUserCustomUI()](#getUserCustomUI--) | Η συμβολοσειρά Ribbon XML που περνιέται στο έγγραφο για την προσαρμογή της γραμμής εργαλείων Quick Access ή του ribbon. |
| [getValidation()](#getValidation--) | Αποθηκεύει πληροφορίες σχετικά με την επικύρωση διαγράμματος για το έγγραφο. |
| [getVbProjectData()](#getVbProjectData--) | Περιέχει τα δεδομένα του έργου Microsoft Visual Basic for Applications σε μορφή κωδικοποιημένη με MIME (Multipurpose Internet Mail Extensions). |
| [getVbaProject()](#getVbaProject--) | Λαμβάνει το VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Ο αριθμός έκδοσης της παρουσίας Visio. |
| [getWindows()](#getWindows--) | Περιέχει τα στοιχεία Window για ένα έγγραφο. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Δείχνει εάν αυτό το διάγραμμα περιέχει κρυφές πληροφορίες. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Διατάσσει τα σχήματα και/ή επαναδρομολογεί τους συνδέσμους για όλες τις σελίδες του διαγράμματος. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Εκτυπώστε ολόκληρο το έγγραφο στον καθορισμένο εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Εκτυπώστε ολόκληρο το έγγραφο στον καθορισμένο εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Εκτυπώνει το έγγραφο, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης και ένα όνομα εγγράφου. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Εκτυπώνει το έγγραφο, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης και ένα όνομα εγγράφου. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Αφαιρέστε τις αχρησιμοποίητες πληροφορίες |
| [removeMacro()](#removeMacro--) | Αφαιρεί το VBA/μακρο από αυτό το διάγραμμα. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Αποθηκεύστε το διάγραμμα στη ροή. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Αποθηκεύστε το διάγραμμα στη ροή. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Αποθηκεύει το έγγραφο σε αρχείο χρησιμοποιώντας τις καθορισμένες επιλογές αποθήκευσης. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Αποθηκεύει τα δεδομένα του διαγράμματος στο αρχείο. |
| [setBuildnum(long value)](#setBuildnum-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Δείχνει τη διαδρομή του φακέλου γραμματοσειρών |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από το αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | java.lang.String | Το όνομα του αρχείου. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από τη ροή χρησιμοποιώντας προκαθορισμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων. |
| μορφή | int | Τα δεδομένα Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από τη ροή χρησιμοποιώντας προκαθορισμένες επιλογές φόρτωσης αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Τα δεδομένα [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από το αρχείο χρησιμοποιώντας προκαθορισμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | java.lang.String | Το όνομα του αρχείου. |
| μορφή | int | Η μορφή αρχείου. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Δημόσιος κατασκευαστής κλάσης, φορτώνει το διάγραμμα από το αρχείο χρησιμοποιώντας προκαθορισμένες επιλογές φόρτωσης αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | java.lang.String | Το όνομα του αρχείου. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Τα δεδομένα [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Προσθέτει master στο διάγραμμα από το πηγαίο διάγραμμα με το Όνομα ή NameU του master.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | Διάγραμμα προέλευσης. |
| masterName | java.lang.String | Το Όνομα του Master ή NameU. |

**Returns:**
int - Το μοναδικό ID του master μέσα στη συλλογή masters σε αυτό το διάγραμμα.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Προσθέτει master στο διάγραμμα από τη ροή προτύπου με το ID του master.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templateStream | java.io.InputStream | ροή προτύπου. |
| masterID | int | Το μοναδικό ID του master μέσα στη συλλογή masters στο πρότυπο. |

**Returns:**
int - Το μοναδικό ID του master μέσα στη συλλογή masters σε αυτό το διάγραμμα.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Προσθέτει master στο διάγραμμα από τη ροή προτύπου με το Όνομα ή NameU του master.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templateStream | java.io.InputStream | ροή προτύπου. |
| masterName | java.lang.String | Το Όνομα του Master ή NameU. |

**Returns:**
int - Το μοναδικό ID του master μέσα στη συλλογή masters σε αυτό το διάγραμμα.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Προσθέτει master στο διάγραμμα από το αρχείο προτύπου με το ID του master.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templateFilePath | java.lang.String | Διαδρομή προς το αρχείο προτύπου (μπορεί να είναι μορφή vdx, vst ή vsd). |
| masterID | int | Το μοναδικό ID του master μέσα στη συλλογή masters στο πρότυπο. |

**Returns:**
int - Το μοναδικό ID του master μέσα στη συλλογή masters σε αυτό το διάγραμμα.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Προσθέτει master στο διάγραμμα από το αρχείο προτύπου με το Όνομα ή NameU του master.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templateFilePath | java.lang.String | Διαδρομή προς το αρχείο προτύπου (μπορεί να είναι μορφή vdx, vst ή vsd). |
| masterName | java.lang.String | Το Όνομα του Master ή NameU. |

**Returns:**
int - Το μοναδικό ID του master μέσα στη συλλογή masters σε αυτό το διάγραμμα.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Adds shape created by master to specific page.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Νέο αντικείμενο σχήματος[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Όνομα του Master. |
| pageNumber | int | Δείκτης της σελίδας. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Adds shape created by master on page with defined PinX,PinY,Width and Height.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος σε ίντσες. |
| height | double | Καθορίζει το ύψος του σχήματος σε ίντσες. |
| masterName | java.lang.String | Όνομα του Master. |
| pageNumber | int | Δείκτης της σελίδας. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Adds shape created by master on page with defined PinX and PinY.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| masterName | java.lang.String | Όνομα του Master. |
| pageNumber | int | Δείκτης της σελίδας. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Συνδυάζει ένα άλλο αντικείμενο Diagram.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Άλλο αντικείμενο Diagram. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Αντιγράφει το Theme από ένα πηγαίο Diagram.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | Διάγραμμα προέλευσης. |

### dispose() {#dispose--}
```
public void dispose()
```


Εκτελεί εργασίες που ορίζονται από την εφαρμογή, σχετικές με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων.

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Εξάγει το διάγραμμα από τη ροή vsd σε μορφή ροής vdw. Δεν έχει υλοποιηθεί ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputVsd | java.io.InputStream | ροή vsd. |
| outputVdw | java.io.InputStream | ροή vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Εξάγει το διάγραμμα από τη ροή vsd σε μορφή αρχείου \*.vdw. Δεν έχει υλοποιηθεί ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputVsd | java.io.InputStream | Όνομα αρχείου \*.vsd. |
| outputVdw | java.lang.String | ροή vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Εξάγει το διάγραμμα από το αρχείο vsd σε μορφή ροής vdw. Δεν έχει υλοποιηθεί ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputVsd | java.lang.String | Όνομα αρχείου \*.vsd. |
| outputVdw | java.io.InputStream | ροή vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Εξάγει το διάγραμμα από vsd σε μορφή vdw. Δεν έχει υλοποιηθεί ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputVsd | java.lang.String | Όνομα αρχείου \*.vsd. |
| outputVdw | java.lang.String | Όνομα αρχείου \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Καθορίζει τη ενεργή σελίδα

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Ο αριθμός κατασκευής της παρουσίας Visio που χρησιμοποιήθηκε για τη δημιουργία του εγγράφου.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


Περιέχει τον πίνακα χρωμάτων του εγγράφου. Κάθε έγγραφο περιέχει έναν μοναδικό πίνακα χρωμάτων, ο οποίος παραθέτει τα 24 τυπικά χρώματα που είναι διαθέσιμα για εφαρμογή σε αντικείμενα όπως σχήματα, κείμενο και στρώματα στο έγγραφο.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Περιέχει τα στοιχεία DataConnection για το έγγραφο.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Η συλλογή των αντικειμένων DataRecordset που σχετίζονται με ένα αντικείμενο Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Λάβετε τη διαδρομή του φακέλου Default Fonts

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


Το μοναδικό ID της γλώσσας διεπαφής χρήστη που έχει καθορίσει ο χρήστης στις Προτιμήσεις Γλώσσας του Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Περιέχει στοιχεία ιδιοτήτων εγγράφου όπως ο τίτλος του εγγράφου, ο συγγραφέας κ.λπ.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις του εγγράφου.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Καθορίζει τη δομή ShapeSheet ενός εγγράφου.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Περιέχει ένα MIME (Multipurpose Internet Mail Extensions) κωδικοποιημένο MAPI έντυπο δρομολόγησης email για το έγγραφο.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Περιέχει ένα στοιχείο EventItem για κάθε γεγονός στο οποίο πρέπει να ανταποκριθεί ένα αντικείμενο.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Περιέχει μια συλλογή στοιχείων Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Περιέχει στοιχεία για την κεφαλίδα και το υποσέλιδο του εγγράφου.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


ο παρακολουθητής διακοπής.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Δείχνει εάν το έγγραφο έχει τροποποιηθεί εκτός του Visio. Εάν υπάρχει, το Visio θα ελέγξει πλήρως το περιεχόμενο του αρχείου. Παραλείψτε για αρχεία που δημιουργείτε εκτός του Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Συλλογή αντικειμένων Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Καθορίζει εάν θα χρησιμοποιηθούν μετρικές μονάδες στο σχέδιο. Ορίστε αυτήν την ιδιότητα σε True (1) για χρήση μετρικών μονάδων· ορίστε την σε False (0) για χρήση αγγλικών μονάδων.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Συλλογή αντικειμένων Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


Η συμβολοσειρά Ribbon XML που περνιέται στο έγγραφο για την προσαρμογή της διεπαφής χρήστη του ribbon.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


Τιμή XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Δείχνει εάν το έγγραφο έχει τροποποιηθεί εκτός του Visio. Εάν υπάρχει, το Visio θα ελέγξει πλήρως το περιεχόμενο του αρχείου. Παραλείψτε για αρχεία που δημιουργείτε εκτός του Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Συλλογή αντικειμένων StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Λάβετε τα αχρησιμοποίητα Styles

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


Η συμβολοσειρά Ribbon XML που περνιέται στο έγγραφο για την προσαρμογή της γραμμής εργαλείων Quick Access ή του ribbon.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Αποθηκεύει πληροφορίες σχετικά με την επικύρωση διαγράμματος για το έγγραφο.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Περιέχει τα δεδομένα του έργου Microsoft Visual Basic for Applications σε μορφή κωδικοποιημένη με MIME (Multipurpose Internet Mail Extensions).

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Λαμβάνει το VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Ο αριθμός έκδοσης της παρουσίας Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Περιέχει τα στοιχεία Window για ένα έγγραφο.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Δείχνει εάν αυτό το διάγραμμα περιέχει κρυφές πληροφορίες.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Διατάσσει τα σχήματα και/ή επαναδρομολογεί τους συνδέσμους για όλες τις σελίδες του διαγράμματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Χρησιμοποιώντας το [LayoutOptions](../../com.aspose.diagram/layoutoptions) για να διαμορφώσετε τις επιλογές διάταξης. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


Εκτυπώνει ολόκληρο το έγγραφο στον καθορισμένο εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. Εάν το printerName είναι Null ή κενό, θα χρησιμοποιηθεί ο προεπιλεγμένος εκτυπωτής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| printerName | java.lang.String | Το όνομα του εκτυπωτή. Μπορεί να είναι Null. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Εκτυπώνει ολόκληρο το έγγραφο στον καθορισμένο εκτυπωτή, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης. Εάν το printerName είναι Null ή κενό, θα χρησιμοποιηθεί ο προεπιλεγμένος εκτυπωτής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| printerName | java.lang.String | Το όνομα του εκτυπωτή. Μπορεί να είναι Null. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Οι επιλογές εκτύπωσης. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Εκτυπώνει το έγγραφο, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης και ένα όνομα εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| printerName | java.lang.String | Το όνομα του εκτυπωτή. Μπορεί να είναι Null. |
| documentName | java.lang.String | Το όνομα του εγγράφου που θα εμφανίζεται (π.χ., σε παράθυρο διαλόγου κατάστασης εκτύπωσης ή στην ουρά εκτυπωτή) κατά την εκτύπωση του εγγράφου. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Εκτυπώνει το έγγραφο, χρησιμοποιώντας τον τυπικό (χωρίς διεπαφή χρήστη) ελεγκτή εκτύπωσης και ένα όνομα εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| printerName | java.lang.String | Το όνομα του εκτυπωτή. Μπορεί να είναι Null. |
| documentName | java.lang.String | Το όνομα του εγγράφου που θα εμφανίζεται (π.χ., σε παράθυρο διαλόγου κατάστασης εκτύπωσης ή στην ουρά εκτυπωτή) κατά την εκτύπωση του εγγράφου. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Οι επιλογές εκτύπωσης. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Αφαιρέστε τις αχρησιμοποίητες πληροφορίες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Αφαιρεί το VBA/μακρο από αυτό το διάγραμμα.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Αποθηκεύστε το διάγραμμα στη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | The file stream. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | The save options. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Αποθηκεύστε το διάγραμμα στη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | The file stream. |
| μορφή | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Αποθηκεύει το έγγραφο σε αρχείο χρησιμοποιώντας τις καθορισμένες επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | java.lang.String | Το όνομα του αρχείου. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) save diagram options. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Αποθηκεύει τα δεδομένα του διαγράμματος στο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | java.lang.String | Το όνομα του αρχείου. |
| μορφή | int | Aspose.Diagram.SaveFileFormat save file format. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Δείχνει τη διαδρομή του φακέλου γραμματοσειρών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

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

