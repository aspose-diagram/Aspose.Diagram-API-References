---
title: ComboBoxActiveXControl
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αντιπροσωπεύει έναν έλεγχο ComboBox ActiveX.
type: docs
weight: 55
url: /el/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

Αντιπροσωπεύει έναν έλεγχο ComboBox ActiveX.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | το χρώμα ole του φόντου. |
| [getBorderOleColor()](#getBorderOleColor--) | το χρώμα ole του φόντου. |
| [getBorderStyle()](#getBorderStyle--) | ο τύπος του περιγράμματος που χρησιμοποιείται από τον έλεγχο. |
| [getBoundColumn()](#getBoundColumn--) | Αναπαριστά πώς καθορίζεται η ιδιότητα Value για ένα ComboBox ή ListBox όταν η τιμή της ιδιότητας MultiSelect είναι (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Αναπαριστά τον αριθμό των στηλών που θα εμφανιστούν σε ένα ComboBox ή ListBox. |
| [getColumnWidths()](#getColumnWidths--) | το πλάτος της στήλης. |
| [getData()](#getData--) | τα δυαδικά δεδομένα του ελέγχου. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Καθορίζει το σύμβολο που εμφανίζεται στο κουμπί πτώσης. |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Καθορίζει τη συμπεριφορά επιλογής κατά την είσοδο στον έλεγχο. |
| [getForeOleColor()](#getForeOleColor--) | το χρώμα ole του προσκηνίου. |
| [getHeight()](#getHeight--) | το ύψος του ελέγχου σε μονάδες σημείων. |
| [getHideSelection()](#getHideSelection--) | Δείχνει αν το επιλεγμένο κείμενο στον έλεγχο εμφανίζεται επισημασμένο όταν ο έλεγχος δεν έχει εστίαση. |
| [getIMEMode()](#getIMEMode--) | η προεπιλεγμένη λειτουργία χρόνου εκτέλεσης του Επεξεργαστή Μεθόδου Εισαγωγής για τον έλεγχο όταν λαμβάνει εστίαση. |
| [getListRows()](#getListRows--) | Αντιπροσωπεύει τον μέγιστο αριθμό γραμμών που θα εμφανιστούν στη λίστα. |
| [getListStyle()](#getListStyle--) | η οπτική εμφάνιση. |
| [getListWidth()](#getListWidth--) | το πλάτος σε μονάδες σημείων. |
| [getMatchEntry()](#getMatchEntry--) | Δείχνει πώς ένα ListBox ή ComboBox αναζητά τη λίστα του καθώς ο χρήστης πληκτρολογεί. |
| [getMaxLength()](#getMaxLength--) | ο μέγιστος αριθμός χαρακτήρων |
| [getMouseIcon()](#getMouseIcon--) | ένα προσαρμοσμένο εικονίδιο για εμφάνιση ως δείκτης ποντικιού για τον έλεγχο. |
| [getMousePointer()](#getMousePointer--) | ο τύπος του εικονιδίου που εμφανίζεται ως δείκτης ποντικιού για τον έλεγχο. |
| [getSelectionMargin()](#getSelectionMargin--) | Δείχνει αν ο χρήστης μπορεί να επιλέξει μια γραμμή κειμένου κάνοντας κλικ στην περιοχή στα αριστερά του κειμένου. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Δείχνει αν εμφανίζονται οι επικεφαλίδες των στηλών. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Καθορίζει το σύμβολο που εμφανίζεται στο κουμπί πτώσης. |
| [getSpecialEffect()](#getSpecialEffect--) | η ειδική επίδραση του ελέγχου. |
| [getTextColumn()](#getTextColumn--) | Αντιπροσωπεύει τη στήλη σε ένα ComboBox ή ListBox που θα εμφανιστεί στον χρήστη. |
| [getType()](#getType--) | Αποκτά τον τύπο του ελέγχου ActiveX. |
| [getValue()](#getValue--) | η τιμή του ελέγχου. |
| [getWidth()](#getWidth--) | το πλάτος του ελέγχου σε μονάδες σημείου. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Δείχνει αν ο έλεγχος θα αλλάξει αυτόματα το μέγεθός του για να εμφανίσει όλο το περιεχόμενό του. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Καθορίζει τη βασική μονάδα που χρησιμοποιείται για την επέκταση μιας επιλογής. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Δείχνει αν η μεταφορά και απόθεση είναι ενεργοποιημένη για τον έλεγχο. |
| [isEditable()](#isEditable--) | Δείχνει αν ο χρήστης μπορεί να πληκτρολογήσει στο έλεγχο. |
| [isEnabled()](#isEnabled--) | Δείχνει αν ο έλεγχος μπορεί να λάβει την εστίαση και να ανταποκριθεί σε γεγονότα που δημιουργεί ο χρήστης. |
| [isLocked()](#isLocked--) | Δείχνει αν τα δεδομένα στο έλεγχο είναι κλειδωμένα για επεξεργασία. |
| [isTransparent()](#isTransparent--) | Δείχνει αν ο έλεγχος είναι διαφανής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setListRows(int value)](#setListRows-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) |
| [setListStyle(int value)](#setListStyle-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


το χρώμα ole του φόντου.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


το χρώμα ole του φόντου.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


ο τύπος του περιγράμματος που χρησιμοποιείται από τον έλεγχο.

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Αναπαριστά πώς καθορίζεται η ιδιότητα Value για ένα ComboBox ή ListBox όταν η τιμή της ιδιότητας MultiSelect είναι (fmMultiSelectSingle).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


Αναπαριστά τον αριθμό των στηλών που θα εμφανιστούν σε ένα ComboBox ή ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


το πλάτος της στήλης.

**Returns:**
double
### getData() {#getData--}
```
public byte[] getData()
```


τα δυαδικά δεδομένα του ελέγχου.

**Returns:**
byte[]
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


Καθορίζει το σύμβολο που εμφανίζεται στο κουμπί πτώσης.

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


Καθορίζει τη συμπεριφορά επιλογής κατά την είσοδο στον έλεγχο. True καθορίζει ότι η επιλογή παραμένει αμετάβλητη από την τελευταία φορά που ο έλεγχος ήταν ενεργός. False καθορίζει ότι όλο το κείμενο στον έλεγχο θα επιλεγεί κατά την είσοδο στον έλεγχο.

**Returns:**
boolean
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


Το χρώμα ole του προσκηνίου. Δεν εφαρμόζεται στον έλεγχο Image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


το ύψος του ελέγχου σε μονάδες σημείων.

**Returns:**
double
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


Δείχνει αν το επιλεγμένο κείμενο στον έλεγχο εμφανίζεται επισημασμένο όταν ο έλεγχος δεν έχει εστίαση.

**Returns:**
boolean
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


η προεπιλεγμένη λειτουργία χρόνου εκτέλεσης του Επεξεργαστή Μεθόδου Εισαγωγής για τον έλεγχο όταν λαμβάνει εστίαση.

**Returns:**
int
### getListRows() {#getListRows--}
```
public int getListRows()
```


Αντιπροσωπεύει τον μέγιστο αριθμό γραμμών που θα εμφανιστούν στη λίστα.

**Returns:**
int
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


η οπτική εμφάνιση.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


το πλάτος σε μονάδες σημείων.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Δείχνει πώς ένα ListBox ή ComboBox αναζητά τη λίστα του καθώς ο χρήστης πληκτρολογεί.

**Returns:**
int
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


ο μέγιστος αριθμός χαρακτήρων

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


ένα προσαρμοσμένο εικονίδιο για εμφάνιση ως δείκτης ποντικιού για τον έλεγχο.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


ο τύπος του εικονιδίου που εμφανίζεται ως δείκτης ποντικιού για τον έλεγχο.

**Returns:**
int
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


Δείχνει αν ο χρήστης μπορεί να επιλέξει μια γραμμή κειμένου κάνοντας κλικ στην περιοχή στα αριστερά του κειμένου.

**Returns:**
boolean
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Δείχνει αν εμφανίζονται οι επικεφαλίδες των στηλών.

**Returns:**
boolean
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


Καθορίζει το σύμβολο που εμφανίζεται στο κουμπί πτώσης.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


η ειδική επίδραση του ελέγχου.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Αντιπροσωπεύει τη στήλη σε ένα ComboBox ή ListBox που θα εμφανιστεί στον χρήστη.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Αποκτά τον τύπο του ελέγχου ActiveX.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


η τιμή του ελέγχου.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```


το πλάτος του ελέγχου σε μονάδες σημείου.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


Δείχνει αν ο έλεγχος θα αλλάξει αυτόματα το μέγεθός του για να εμφανίσει όλο το περιεχόμενό του.

**Returns:**
boolean
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


Καθορίζει τη βασική μονάδα που χρησιμοποιείται για την επέκταση μιας επιλογής. True καθορίζει ότι η βασική μονάδα είναι ένας μεμονωμένος χαρακτήρας. false καθορίζει ότι η βασική μονάδα είναι μια ολόκληρη λέξη.

**Returns:**
boolean
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


Δείχνει αν η μεταφορά και απόθεση είναι ενεργοποιημένη για τον έλεγχο.

**Returns:**
boolean
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


Δείχνει αν ο χρήστης μπορεί να πληκτρολογήσει στο έλεγχο.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Δείχνει αν ο έλεγχος μπορεί να λάβει την εστίαση και να ανταποκριθεί σε γεγονότα που δημιουργεί ο χρήστης.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Δείχνει αν τα δεδομένα στο έλεγχο είναι κλειδωμένα για επεξεργασία.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Δείχνει αν ο έλεγχος είναι διαφανής.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

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

