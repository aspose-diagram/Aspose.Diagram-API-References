---
title: ToggleButtonActiveXControl
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά έναν έλεγχο ActiveX ToggleButton.
type: docs
weight: 410
url: /el/java/com.aspose.diagram/togglebuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ToggleButtonActiveXControl extends ActiveXControl
```

Αναπαριστά έναν έλεγχο ActiveX ToggleButton.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | το πλήκτρο συντόμευσης για τον έλεγχο. |
| [getBackOleColor()](#getBackOleColor--) | το χρώμα ole του φόντου. |
| [getCaption()](#getCaption--) | το περιγραφικό κείμενο που εμφανίζεται σε έναν έλεγχο. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | τα δυαδικά δεδομένα του ελέγχου. |
| [getForeOleColor()](#getForeOleColor--) | το χρώμα ole του προσκηνίου. |
| [getHeight()](#getHeight--) | το ύψος του ελέγχου σε μονάδες σημείων. |
| [getIMEMode()](#getIMEMode--) | η προεπιλεγμένη λειτουργία χρόνου εκτέλεσης του Επεξεργαστή Μεθόδου Εισαγωγής για τον έλεγχο όταν λαμβάνει εστίαση. |
| [getMouseIcon()](#getMouseIcon--) | ένα προσαρμοσμένο εικονίδιο για εμφάνιση ως δείκτης ποντικιού για τον έλεγχο. |
| [getMousePointer()](#getMousePointer--) | ο τύπος του εικονιδίου που εμφανίζεται ως δείκτης ποντικιού για τον έλεγχο. |
| [getPicture()](#getPicture--) | τα δεδομένα της εικόνας. |
| [getPicturePosition()](#getPicturePosition--) | η θέση της εικόνας του ελέγχου σε σχέση με τη λεζάντα του. |
| [getSpecialEffect()](#getSpecialEffect--) | η ειδική επίδραση του ελέγχου. |
| [getType()](#getType--) | Αποκτά τον τύπο του ελέγχου ActiveX. |
| [getValue()](#getValue--) | Δείχνει αν ο έλεγχος είναι επιλεγμένος ή όχι. |
| [getWidth()](#getWidth--) | το πλάτος του ελέγχου σε μονάδες σημείου. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Δείχνει αν ο έλεγχος θα αλλάξει αυτόματα το μέγεθός του για να εμφανίσει όλο το περιεχόμενό του. |
| [isEnabled()](#isEnabled--) | Δείχνει αν ο έλεγχος μπορεί να λάβει την εστίαση και να ανταποκριθεί σε γεγονότα που δημιουργεί ο χρήστης. |
| [isLocked()](#isLocked--) | Δείχνει αν τα δεδομένα στο έλεγχο είναι κλειδωμένα για επεξεργασία. |
| [isTransparent()](#isTransparent--) | Δείχνει αν ο έλεγχος είναι διαφανής. |
| [isTripleState()](#isTripleState--) | Δείχνει πώς ο καθορισμένος έλεγχος θα εμφανίζει τιμές Null. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setTripleState(boolean value)](#setTripleState-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--) |
| [setValue(int value)](#setValue-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--) |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


το πλήκτρο συντόμευσης για τον έλεγχο.

**Returns:**
char
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


το χρώμα ole του φόντου.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


το περιγραφικό κείμενο που εμφανίζεται σε έναν έλεγχο.

**Returns:**
java.lang.String
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
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


η προεπιλεγμένη λειτουργία χρόνου εκτέλεσης του Επεξεργαστή Μεθόδου Εισαγωγής για τον έλεγχο όταν λαμβάνει εστίαση.

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
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


τα δεδομένα της εικόνας.

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


η θέση της εικόνας του ελέγχου σε σχέση με τη λεζάντα του.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


η ειδική επίδραση του ελέγχου.

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
public int getValue()
```


Δείχνει αν ο έλεγχος είναι επιλεγμένος ή όχι.

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
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


Δείχνει πώς ο καθορισμένος έλεγχος θα εμφανίζει τιμές Null.

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Ρύθμιση | Περιγραφή                                                                                                                                     |
| True    | Ο έλεγχος θα κυκλοφορεί μεταξύ των καταστάσεων για τιμές Yes, No και Null. Ο έλεγχος εμφανίζεται αμυδρός (γκρι) όταν η ιδιότητα Value του είναι ορισμένη σε Null. |
| False   | (Προεπιλογή) Ο έλεγχος θα κυκλοφορεί μεταξύ των καταστάσεων για τιμές Yes και No. Οι τιμές Null εμφανίζονται σαν τιμές No.                           |

|

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




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | char |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

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

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

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

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)

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

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

