---
title: Window
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά ένα ανοιχτό παράθυρο σε μια παρουσία του Microsoft Visio.
type: docs
weight: 444
url: /el/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Αντιπροσωπεύει ένα ανοιχτό παράθυρο σε μια παρουσία του Microsoft Visio. Αυτό το στοιχείο περιέχει τις πληροφορίες που απαιτούνται για την ακριβή αναδημιουργία ενός παραθύρου διεπαφής χρήστη στον χώρο εργασίας της εφαρμογής όταν το αρχείο DatadiagramML ανοίγει αρχικά από το Visio.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Window()](#Window--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Αναγνωριστικό (ID) του περιέκτη: Σελίδα, Φύλλο ή Master. |
| [getContainerType()](#getContainerType--) | Μπορεί να είναι μία από τις ακόλουθες τιμές: Document, Page ή Master. |
| [getDocument()](#getDocument--) | Διαδρομή αρχείου του εγγράφου που εμφανίζεται σε αυτό το παράθυρο. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Καθορίζει εάν η λειτουργία δυναμικού πλέγματος είναι ενεργοποιημένη για ένα έγγραφο ή παράθυρο. |
| [getGlueSettings()](#getGlueSettings--) | Καθορίζει τα αντικείμενα στα οποία τα σχήματα κολλούν όταν η κόλλα είναι ενεργοποιημένη στο έγγραφο. |
| [getID()](#getID--) | Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο. |
| [getMaster()](#getMaster--) | Αναγνωριστικό (ID) του Master εάν αυτό το παράθυρο εμφανίζει ένα master. |
| [getPage()](#getPage--) | Αναγνωριστικό (ID) της Σελίδας εάν αυτό το παράθυρο εμφανίζει μια σελίδα. |
| [getParentWindow()](#getParentWindow--) | Αναγνωριστικό (ID) του παραθύρου στο οποίο περιέχεται αυτό το παράθυρο stencil. |
| [getReadOnly()](#getReadOnly--) | Σημαία μόνο για ανάγνωση εάν αυτό το stencil δεν είναι stencil εγγράφου. |
| [getSheet()](#getSheet--) | Αναγνωριστικό (ID) του φύλλου στον περιέκτη. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Καθορίζει εάν τα σημεία σύνδεσης εμφανίζονται σε ένα παράθυρο. |
| [getShowGrid()](#getShowGrid--) | Καθορίζει εάν εμφανίζεται πλέγμα στο παράθυρο σχεδίασης. |
| [getShowGuides()](#getShowGuides--) | Καθορίζει εάν εμφανίζονται οδηγίες στο παράθυρο σχεδίασης. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Καθορίζει εάν εμφανίζονται αλλαγές σελίδας σε ένα παράθυρο. |
| [getShowRulers()](#getShowRulers--) | Καθορίζει εάν εμφανίζονται χάρακες στο παράθυρο σχεδίασης. |
| [getSnapAngles()](#getSnapAngles--) | Περιέχει μια συλλογή στοιχείων SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Καθορίζει εάν μια συγκεκριμένη ρύθμιση επέκτασης προσκόλλησης είναι ενεργοποιημένη ή απενεργοποιημένη για το ενεργό παράθυρο. |
| [getSnapSettings()](#getSnapSettings--) | Καθορίζει τα αντικείμενα στα οποία τα σχήματα προσκολλώνται όταν η προσκόλληση είναι ενεργή στο παράθυρο. |
| [getStencilGroup()](#getStencilGroup--) | Καθορίζει την ομάδα των συγχωνευμένων παραθύρων stencil των οποίων το παράθυρο είναι μέλος. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Περιέχει έναν ακέραιο που καθορίζει τη σχετική θέση ενός stencil μέσα σε μια ομάδα σε ένα παράθυρο. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Καθορίζει το πλάτος του ελέγχου καρτέλας σελίδας ενός παραθύρου σχεδίασης (ως κλάσμα του συνολικού πλάτους του παραθύρου σχεδίασης). |
| [getViewCenterX()](#getViewCenterX--) | Προαιρετικό διπλό. |
| [getViewCenterY()](#getViewCenterY--) | Προαιρετικό διπλό. |
| [getViewScale()](#getViewScale--) | Προαιρετικό διπλό. |
| [getWindowHeight()](#getWindowHeight--) | Ύψος του ορθογωνίου παραθύρου. |
| [getWindowLeft()](#getWindowLeft--) | Αριστερή συντεταγμένη του ορθογωνίου παραθύρου. |
| [getWindowState()](#getWindowState--) | Αυτό το χαρακτηριστικό μπορεί να είναι άθροισμα των ακόλουθων τιμών. |
| [getWindowTop()](#getWindowTop--) | Άνω συντεταγμένη του ορθογωνίου παραθύρου. |
| [getWindowType()](#getWindowType--) | Μια απαριθμημένη τιμή που μπορεί να είναι μία από τις ακόλουθες: Drawing, Sheet, Stencil ή Icon. Ένα στοιχείο Window με WindowType='Stencil' πρέπει να εμφανίζεται μετά το γονικό του παράθυρο σχεδίασης (WindowType='Drawing') και πριν από οποιαδήποτε άλλα στοιχεία παραθύρων σχεδίασης. |
| [getWindowWidth()](#getWindowWidth--) | Πλάτος του ορθογωνίου παραθύρου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


Αναγνωριστικό (ID) του περιέκτη: Σελίδα, Φύλλο ή Κύριο. Σχετικό και απαραίτητο μόνο εάν έχει καθοριστεί το ContainerType.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Μπορεί να είναι μία από τις ακόλουθες τιμές: Document, Page ή Master. Ισχύει μόνο όταν το WindowType ορίζεται ως Drawing ή Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Διαδρομή αρχείου του εγγράφου που εμφανίζεται σε αυτό το παράθυρο. Αυτό το χαρακτηριστικό είναι σχετικό για παράθυρα των οποίων το WindowType έχει οριστεί ως Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Καθορίζει εάν η λειτουργία δυναμικού πλέγματος είναι ενεργοποιημένη για ένα έγγραφο ή παράθυρο.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Καθορίζει τα αντικείμενα στα οποία τα σχήματα κολλούν όταν η κόλλα είναι ενεργοποιημένη στο έγγραφο.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Αναγνωριστικό (ID) του Master εάν αυτό το παράθυρο εμφανίζει ένα master.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


Αναγνωριστικό σελίδας εάν αυτό το παράθυρο εμφανίζει μια σελίδα. Σχετικό μόνο όταν το WindowType έχει οριστεί ως Drawing και το ContainerType ως Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


Αναγνωριστικό παραθύρου στο οποίο περιέχεται αυτό το stencil παράθυρο. Σχετικό μόνο όταν το WindowType έχει οριστεί ως Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Σημαία μόνο για ανάγνωση εάν αυτό το stencil δεν είναι stencil εγγράφου.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


Αναγνωριστικό φύλλου στον περιέκτη. Σχετικό μόνο όταν ο Container έχει οριστεί ως Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Καθορίζει εάν τα σημεία σύνδεσης εμφανίζονται σε ένα παράθυρο.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Καθορίζει εάν εμφανίζεται πλέγμα στο παράθυρο σχεδίασης.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Καθορίζει εάν εμφανίζονται οδηγίες στο παράθυρο σχεδίασης.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Καθορίζει εάν εμφανίζονται αλλαγές σελίδας σε ένα παράθυρο.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Καθορίζει εάν εμφανίζονται χάρακες στο παράθυρο σχεδίασης.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Περιέχει μια συλλογή στοιχείων SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Καθορίζει εάν μια συγκεκριμένη ρύθμιση επέκτασης προσκόλλησης είναι ενεργοποιημένη ή απενεργοποιημένη για το ενεργό παράθυρο. Η τιμή μπορεί να είναι το άθροισμα των τιμών στον παρακάτω πίνακα.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Καθορίζει τα αντικείμενα στα οποία προσαρμόζονται τα σχήματα όταν η προσαρμογή είναι ενεργή στο παράθυρο. Η τιμή μπορεί να είναι το άθροισμα των τιμών στον παρακάτω πίνακα.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Καθορίζει την ομάδα των συγχωνευμένων stencil παραθύρων της οποίας το παράθυρο είναι μέλος. Αυτό το χαρακτηριστικό είναι σχετικό μόνο για στοιχεία Window των οποίων το χαρακτηριστικό WindowType είναι Stencil και μόνο εάν το stencil παράθυρο αποτελεί μέρος μιας συγχωνευμένης ομάδας stencil παραθύρων. Όλα τα stencil παράθυρα που ανήκουν στην ίδια συγχωνευμένη ομάδα έχουν την ίδια τιμή στοιχείου StencilGroup.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Περιέχει έναν ακέραιο που καθορίζει τη σχετική θέση ενός stencil μέσα σε μια ομάδα σε ένα παράθυρο.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Καθορίζει το πλάτος του ελέγχου καρτέλας σελίδας ενός παραθύρου σχεδίασης (ως κλάσμα του συνολικού πλάτους του παραθύρου σχεδίασης).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Προαιρετικό διπλό.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Προαιρετικό διπλό.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Προαιρετικό διπλό.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Ύψος του ορθογωνίου παραθύρου.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Αριστερή συντεταγμένη του ορθογωνίου παραθύρου.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Αυτό το χαρακτηριστικό μπορεί να είναι άθροισμα των ακόλουθων τιμών.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Άνω συντεταγμένη του ορθογωνίου παραθύρου.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Μια απαριθμημένη τιμή που μπορεί να είναι μία από τις ακόλουθες: Drawing, Sheet, Stencil ή Icon. Ένα στοιχείο Window με WindowType='Stencil' πρέπει να εμφανίζεται μετά το γονικό του παράθυρο σχεδίασης (WindowType='Drawing') και πριν από οποιαδήποτε άλλα στοιχεία παραθύρων σχεδίασης.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Πλάτος του ορθογωνίου παραθύρου.

**Returns:**
long
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




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

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

