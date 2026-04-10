---
title: TextBoxActiveXControl
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά έναν έλεγχο ActiveX πλαισίου κειμένου.
type: docs
weight: 401
url: /el/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

Αναπαριστά έναν έλεγχο ActiveX πλαισίου κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | το χρώμα ole του φόντου. |
| [getBorderOleColor()](#getBorderOleColor--) | το χρώμα ole του φόντου. |
| [getBorderStyle()](#getBorderStyle--) | ο τύπος του περιγράμματος που χρησιμοποιείται από τον έλεγχο. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | τα δυαδικά δεδομένα του ελέγχου. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Καθορίζει το σύμβολο που εμφανίζεται στο κουμπί πτώσης. |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Καθορίζει τη συμπεριφορά επιλογής κατά την είσοδο στον έλεγχο. |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | Καθορίζει τη συμπεριφορά του πλήκτρου ENTER. |
| [getForeOleColor()](#getForeOleColor--) | το χρώμα ole του προσκηνίου. |
| [getHeight()](#getHeight--) | το ύψος του ελέγχου σε μονάδες σημείων. |
| [getHideSelection()](#getHideSelection--) | Δείχνει αν το επιλεγμένο κείμενο στον έλεγχο εμφανίζεται επισημασμένο όταν ο έλεγχος δεν έχει εστίαση. |
| [getIMEMode()](#getIMEMode--) | η προεπιλεγμένη λειτουργία χρόνου εκτέλεσης του Επεξεργαστή Μεθόδου Εισαγωγής για τον έλεγχο όταν λαμβάνει εστίαση. |
| [getIntegralHeight()](#getIntegralHeight--) | Δείχνει αν ο έλεγχος θα εμφανίζει μόνο πλήρεις γραμμές κειμένου χωρίς να εμφανίζει μερικές γραμμές. |
| [getMaxLength()](#getMaxLength--) | ο μέγιστος αριθμός χαρακτήρων |
| [getMouseIcon()](#getMouseIcon--) | ένα προσαρμοσμένο εικονίδιο για εμφάνιση ως δείκτης ποντικιού για τον έλεγχο. |
| [getMousePointer()](#getMousePointer--) | ο τύπος του εικονιδίου που εμφανίζεται ως δείκτης ποντικιού για τον έλεγχο. |
| [getPasswordChar()](#getPasswordChar--) | Ένας χαρακτήρας που θα εμφανίζεται στη θέση των χαρακτήρων που εισάγονται. |
| [getScrollBars()](#getScrollBars--) | Δείχνει αν ο έλεγχος έχει κάθετες γραμμές κύλισης, οριζόντιες γραμμές κύλισης, και τα δύο ή κανένα. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Καθορίζει το σύμβολο που εμφανίζεται στο κουμπί πτώσης. |
| [getSpecialEffect()](#getSpecialEffect--) | η ειδική επίδραση του ελέγχου. |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | Δείχνει αν οι χαρακτήρες Tab επιτρέπονται στο κείμενο του ελέγχου. |
| [getText()](#getText--) | Κείμενο του ελέγχου. |
| [getType()](#getType--) | Αποκτά τον τύπο του ελέγχου ActiveX. |
| [getWidth()](#getWidth--) | το πλάτος του ελέγχου σε μονάδες σημείου. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Δείχνει αν ο έλεγχος θα αλλάξει αυτόματα το μέγεθός του για να εμφανίσει όλο το περιεχόμενό του. |
| [isAutoTab()](#isAutoTab--) | Δείχνει εάν η εστίαση θα μετακινηθεί αυτόματα στο επόμενο στοιχείο ελέγχου όταν ο χρήστης εισάγει το μέγιστο αριθμό χαρακτήρων. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Καθορίζει τη βασική μονάδα που χρησιμοποιείται για την επέκταση μιας επιλογής. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Δείχνει αν η μεταφορά και απόθεση είναι ενεργοποιημένη για τον έλεγχο. |
| [isEditable()](#isEditable--) | Δείχνει αν ο χρήστης μπορεί να πληκτρολογήσει στο έλεγχο. |
| [isEnabled()](#isEnabled--) | Δείχνει αν ο έλεγχος μπορεί να λάβει την εστίαση και να ανταποκριθεί σε γεγονότα που δημιουργεί ο χρήστης. |
| [isLocked()](#isLocked--) | Δείχνει αν τα δεδομένα στο έλεγχο είναι κλειδωμένα για επεξεργασία. |
| [isMultiLine()](#isMultiLine--) | Δείχνει εάν το στοιχείο ελέγχου μπορεί να εμφανίσει περισσότερες από μία γραμμές κειμένου. |
| [isTransparent()](#isTransparent--) | Δείχνει αν ο έλεγχος είναι διαφανής. |
| [isWordWrapped()](#isWordWrapped--) | Δείχνει αν το περιεχόμενο του ελέγχου θα αναδιπλώνεται αυτόματα στο τέλος μιας γραμμής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) |
| [setPasswordChar(char value)](#setPasswordChar-char-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) |
| [setText(String value)](#setText-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


Καθορίζει τη συμπεριφορά του πλήκτρου ENTER. Η τιμή True υποδεικνύει ότι το πάτημα του ENTER θα δημιουργήσει μια νέα γραμμή. Η τιμή False υποδεικνύει ότι το πάτημα του ENTER θα μετακινήσει την εστίαση στο επόμενο αντικείμενο στη σειρά καρτελών.

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
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Δείχνει αν ο έλεγχος θα εμφανίζει μόνο πλήρεις γραμμές κειμένου χωρίς να εμφανίζει μερικές γραμμές.

**Returns:**
boolean
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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


Ένας χαρακτήρας που θα εμφανίζεται στη θέση των χαρακτήρων που εισάγονται.

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Δείχνει αν ο έλεγχος έχει κάθετες γραμμές κύλισης, οριζόντιες γραμμές κύλισης, και τα δύο ή κανένα.

**Returns:**
int
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
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


Δείχνει αν οι χαρακτήρες Tab επιτρέπονται στο κείμενο του ελέγχου.

**Returns:**
boolean
### getText() {#getText--}
```
public String getText()
```


Κείμενο του ελέγχου.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public int getType()
```


Αποκτά τον τύπο του ελέγχου ActiveX.

**Returns:**
int
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


Δείχνει εάν η εστίαση θα μετακινηθεί αυτόματα στο επόμενο στοιχείο ελέγχου όταν ο χρήστης εισάγει το μέγιστο αριθμό χαρακτήρων.

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


Δείχνει εάν το στοιχείο ελέγχου μπορεί να εμφανίσει περισσότερες από μία γραμμές κειμένου.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Δείχνει αν ο έλεγχος είναι διαφανής.

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Δείχνει αν το περιεχόμενο του ελέγχου θα αναδιπλώνεται αυτόματα στο τέλος μιας γραμμής.

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

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--)

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--)

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--)

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--)

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

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--)

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

