---
title: StyleSheet
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά ένα στυλ που ορίζεται σε ένα έγγραφο.
type: docs
weight: 393
url: /el/java/com.aspose.diagram/stylesheet/
---

**Inheritance:**
java.lang.Object
```
public class StyleSheet
```

Αναπαριστά ένα στυλ που ορίζεται σε ένα έγγραφο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StyleSheet()](#StyleSheet--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChars()](#getChars--) | Περιέχει μια συλλογή από στοιχεία Char. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Περιέχει μια συλλογή από στοιχεία ConnectionABCD. |
| [getConnections()](#getConnections--) | Περιέχει μια συλλογή από στοιχεία Connection. |
| [getEvent()](#getEvent--) | Περιέχει στοιχεία που καθορίζουν τύπους που ελέγχουν τα γεγονότα σχήματος. |
| [getFill()](#getFill--) | Περιέχει τις τρέχουσες τιμές μορφοποίησης γεμίσματος για το σχήμα και τη σκιά του σχήματος, συμπεριλαμβανομένου του μοτίβου, του χρώματος προσκηνίου και του χρώματος φόντου. |
| [getFillStyle()](#getFillStyle--) | Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γεμίσματος. |
| [getForeign()](#getForeign--) | Περιέχει στοιχεία που καθορίζουν το πλάτος και το ύψος ενός αντικειμένου από άλλο πρόγραμμα που χρησιμοποιείται σε έγγραφο Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE. |
| [getGroup()](#getGroup--) | Περιέχει στοιχεία που ελέγχουν πώς προσθέτετε σχήματα σε μια ομάδα, μετακινείτε μέλη μιας ομάδας και επιλέγετε ομάδες. |
| [getHelp()](#getHelp--) | Περιέχει στοιχεία που καθορίζουν το θέμα του αρχείου βοήθειας του στοιχείου Shape και τις πληροφορίες πνευματικών δικαιωμάτων. |
| [getID()](#getID--) | Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο. |
| [getImage()](#getImage--) | Περιέχει τις τιμές γάμμα, φωτεινότητας, αντίθεσης, θολώματος, ενίσχυσης, αποθορυβοποίησης και διαφάνειας για ένα bitmap. |
| [getLayout()](#getLayout--) | Περιέχει στοιχεία που ελέγχουν τη θέση του σχήματος και τις ρυθμίσεις δρομολόγησης συνδέσμων. |
| [getLine()](#getLine--) | Περιέχει στοιχεία που ελέγχουν τις ιδιότητες γραμμής για ένα σχήμα, όπως το μοτίβο, το πάχος και το χρώμα. |
| [getLineStyle()](#getLineStyle--) | Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γραμμής. |
| [getMisc()](#getMisc--) | Περιέχει στοιχεία που καθορίζουν το θέμα του αρχείου βοήθειας του στοιχείου Shape και τις πληροφορίες πνευματικών δικαιωμάτων. |
| [getName()](#getName--) | Το όνομα του στοιχείου. |
| [getNameU()](#getNameU--) | Το καθολικό όνομα του στοιχείου. |
| [getPageLayout()](#getPageLayout--) | Περιέχει Diagram που ελέγχει τις ρυθμίσεις διάταξης σελίδας για σχήματα και συνδέσμους, όπως η απόσταση μεταξύ όλων των σχημάτων στη σελίδα, η απόσταση μεταξύ όλων των συνδέσμων στη σελίδα και το στυλ δρομολόγησης για όλους τους συνδέσμους στη σελίδα. |
| [getParas()](#getParas--) | Περιέχει μια συλλογή από στοιχεία Para. |
| [getProtection()](#getProtection--) | Το κλείδωμα βοηθά στην αποφυγή ακούσιων αλλαγών στο σχήμα, αλλά δεν εμποδίζει το Microsoft Visio από την επαναφορά τιμών σε άλλες περιπτώσεις. |
| [getRulerGrid()](#getRulerGrid--) | Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις των χαράγων και του πλέγματος της σελίδας. |
| [getStyleProp()](#getStyleProp--) | Περιέχει στοιχεία που ελέγχουν τη συμπεριφορά του στυλ, όπως το αν ένα στυλ περιλαμβάνει χαρακτηριστικά κειμένου, γραμμής και γεμίσματος. |
| [getTabsCollection()](#getTabsCollection--) | Περιέχει μια συλλογή στοιχείων Tab. |
| [getTextBlock()](#getTextBlock--) | Περιέχει στοιχεία που καθορίζουν την ευθυγράμμιση, τα περιθώρια και τις προεπιλεγμένες θέσεις διακοπής καρτέλας του κειμένου σε ένα μπλοκ κειμένου σχήματος. |
| [getTextStyle()](#getTextStyle--) | Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση κειμένου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--) |
| [setID(int value)](#setID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/stylesheet\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/stylesheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StyleSheet() {#StyleSheet--}
```
public StyleSheet()
```


Κατασκευαστής.

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
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Περιέχει μια συλλογή από στοιχεία Char.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Περιέχει μια συλλογή από στοιχεία ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Περιέχει μια συλλογή από στοιχεία Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Περιέχει στοιχεία που καθορίζουν τύπους που ελέγχουν τα γεγονότα σχήματος.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFill() {#getFill--}
```
public Fill getFill()
```


Περιέχει τις τρέχουσες τιμές μορφοποίησης γεμίσματος για το σχήμα και τη σκιά του σχήματος, συμπεριλαμβανομένου του μοτίβου, του χρώματος προσκηνίου και του χρώματος φόντου.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γεμίσματος.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Περιέχει στοιχεία που καθορίζουν το πλάτος και το ύψος ενός αντικειμένου από άλλο πρόγραμμα που χρησιμοποιείται σε έγγραφο Microsoft Visio. Περιλαμβάνει επίσης στοιχεία που καθορίζουν την απόσταση με την οποία η εικόνα του αντικειμένου είναι μετατοπισμένη εντός των περιγραμμάτων του.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Περιέχει στοιχεία που ελέγχουν πώς προσθέτετε σχήματα σε μια ομάδα, μετακινείτε μέλη μιας ομάδας και επιλέγετε ομάδες.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Περιέχει στοιχεία που καθορίζουν το θέμα του αρχείου βοήθειας του στοιχείου Shape και τις πληροφορίες πνευματικών δικαιωμάτων.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getID() {#getID--}
```
public int getID()
```


Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο.

**Returns:**
int
### getImage() {#getImage--}
```
public Image getImage()
```


Περιέχει τις τιμές γάμμα, φωτεινότητας, αντίθεσης, θολώματος, ενίσχυσης, αποθορυβοποίησης και διαφάνειας για ένα bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Περιέχει στοιχεία που ελέγχουν τη θέση του σχήματος και τις ρυθμίσεις δρομολόγησης συνδέσμων.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Περιέχει στοιχεία που ελέγχουν τις ιδιότητες γραμμής για ένα σχήμα, όπως το μοτίβο, το βάρος και το χρώμα. Αυτά τα στοιχεία καθορίζουν εάν τα άκρα της γραμμής είναι μορφοποιημένα (για παράδειγμα, με κεφαλή βέλους), το μέγεθος των μορφών άκρων γραμμής, την ακτίνα του στρογγυλεμένου κύκλου που εφαρμόζεται στη γραμμή και το στυλ άκρου γραμμής (στρογγυλό ή τετράγωνο).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γραμμής.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Περιέχει στοιχεία που καθορίζουν το θέμα του αρχείου βοήθειας του στοιχείου Shape και τις πληροφορίες πνευματικών δικαιωμάτων.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Το όνομα του στοιχείου.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Το καθολικό όνομα του στοιχείου.

**Returns:**
java.lang.String
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Περιέχει Diagram που ελέγχει τις ρυθμίσεις διάταξης σελίδας για σχήματα και συνδέσμους, όπως η απόσταση μεταξύ όλων των σχημάτων στη σελίδα, η απόσταση μεταξύ όλων των συνδέσμων στη σελίδα και το στυλ δρομολόγησης για όλους τους συνδέσμους στη σελίδα.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Περιέχει μια συλλογή από στοιχεία Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Το κλείδωμα βοηθά στην αποτροπή ακούσιων αλλαγών στο σχήμα, αλλά δεν εμποδίζει το Microsoft Visio από το να επαναφέρει τιμές σε άλλες περιστάσεις. Επίσης, δεν προστατεύει από αλλαγές που γίνονται στο παράθυρο ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις των χαράγων και του πλέγματος της σελίδας.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getStyleProp() {#getStyleProp--}
```
public StyleProp getStyleProp()
```


Περιέχει στοιχεία που ελέγχουν τη συμπεριφορά του στυλ, όπως το αν ένα στυλ περιλαμβάνει χαρακτηριστικά κειμένου, γραμμής και γεμίσματος.

**Returns:**
[StyleProp](../../com.aspose.diagram/styleprop)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Περιέχει μια συλλογή στοιχείων Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Περιέχει στοιχεία που καθορίζουν την ευθυγράμμιση, τα περιθώρια και τις προεπιλεγμένες θέσεις διακοπής καρτέλας του κειμένου σε ένα μπλοκ κειμένου σχήματος.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση κειμένου.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/stylesheet\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/stylesheet\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

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

