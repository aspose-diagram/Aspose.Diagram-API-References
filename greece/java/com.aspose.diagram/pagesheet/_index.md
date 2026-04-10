---
title: PageSheet
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο.
type: docs
weight: 270
url: /el/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Αντιγράφει το pagesheet από ένα αντικείμενο προέλευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Περιέχει μια συλλογή στοιχείων Act. |
| [getAnnotations()](#getAnnotations--) | Περιέχει στοιχεία που περιέχουν πληροφορίες σχετικά με σχόλια που εισήχθησαν σε μια σελίδα εγγράφου. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Περιέχει μια συλλογή από στοιχεία ConnectionABCD. |
| [getConnections()](#getConnections--) | Περιέχει μια συλλογή από στοιχεία Connection. |
| [getFillStyle()](#getFillStyle--) | Στοιχείο StyleSheet από το οποίο το PageSheet κληρονομεί τη μορφοποίηση γεμίσματος. |
| [getForeign()](#getForeign--) | Περιέχει στοιχεία που καθορίζουν το πλάτος και το ύψος ενός αντικειμένου από άλλο πρόγραμμα που χρησιμοποιείται σε έγγραφο Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE. |
| [getHyperlinks()](#getHyperlinks--) | Περιέχει μια συλλογή στοιχείων Hyperlink. |
| [getLayers()](#getLayers--) | Περιέχει μια συλλογή στοιχείων Layer. |
| [getLineStyle()](#getLineStyle--) | Στοιχείο StyleSheet από το οποίο το PageSheet κληρονομεί τη μορφοποίηση γραμμής. |
| [getPageLayout()](#getPageLayout--) | Περιέχει Diagram που ελέγχει τις ρυθμίσεις διάταξης σελίδας για σχήματα και συνδέσμους, όπως η απόσταση μεταξύ όλων των σχημάτων στη σελίδα, η απόσταση μεταξύ όλων των συνδέσμων στη σελίδα και το στυλ δρομολόγησης για όλους τους συνδέσμους στη σελίδα. |
| [getPageProps()](#getPageProps--) | Περιέχει Diagram που ελέγχει τα χαρακτηριστικά της σελίδας, όπως το πλάτος, το ύψος και την κλίμακα της σελίδας. |
| [getPrintProps()](#getPrintProps--) | Περιέχει στοιχεία που ελέγχουν πώς μορφοποιείται (εμφανίζεται) η σελίδα σχεδίου στη σελίδα του εκτυπωτή. |
| [getProps()](#getProps--) | Περιέχει μια συλλογή στοιχείων Prop. |
| [getRulerGrid()](#getRulerGrid--) | Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις των χαράγων και του πλέγματος της σελίδας. |
| [getScratchs()](#getScratchs--) | Περιέχει μια συλλογή από στοιχεία Scratch. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Περιέχει μια συλλογή στοιχείων SmartTagDef. |
| [getTextStyle()](#getTextStyle--) | Στοιχείο StyleSheet από το οποίο το PageSheet κληρονομεί τη μορφοποίηση κειμένου. |
| [getUniqueID()](#getUniqueID--) | Ένα GUID (παγκοσμίως μοναδικό αναγνωριστικό) για το στοιχείο. |
| [getUsers()](#getUsers--) | Περιέχει μια συλλογή από στοιχεία User. |
| [getXForm()](#getXForm--) | Περιέχει στοιχεία που καθορίζουν γενικές πληροφορίες τοποθέτησης για ένα σχήμα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Αντιγράφει το pagesheet από ένα αντικείμενο προέλευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Περιέχει μια συλλογή στοιχείων Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Περιέχει στοιχεία που περιέχουν πληροφορίες σχετικά με σχόλια που εισήχθησαν σε μια σελίδα εγγράφου.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Στοιχείο StyleSheet από το οποίο το PageSheet κληρονομεί τη μορφοποίηση γεμίσματος.

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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Περιέχει μια συλλογή στοιχείων Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Περιέχει μια συλλογή στοιχείων Layer.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Στοιχείο StyleSheet από το οποίο το PageSheet κληρονομεί τη μορφοποίηση γραμμής.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Περιέχει Diagram που ελέγχει τις ρυθμίσεις διάταξης σελίδας για σχήματα και συνδέσμους, όπως η απόσταση μεταξύ όλων των σχημάτων στη σελίδα, η απόσταση μεταξύ όλων των συνδέσμων στη σελίδα και το στυλ δρομολόγησης για όλους τους συνδέσμους στη σελίδα.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Περιέχει Diagram που ελέγχει τα χαρακτηριστικά της σελίδας, όπως το πλάτος, το ύψος και την κλίμακα της σελίδας.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Περιέχει στοιχεία που ελέγχουν πώς μορφοποιείται (εμφανίζεται) η σελίδα σχεδίου στη σελίδα του εκτυπωτή.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Περιέχει μια συλλογή στοιχείων Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Περιέχει στοιχεία που καθορίζουν τις ρυθμίσεις των χαράγων και του πλέγματος της σελίδας.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Περιέχει μια συλλογή από στοιχεία Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Περιέχει μια συλλογή στοιχείων SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Στοιχείο StyleSheet από το οποίο το PageSheet κληρονομεί τη μορφοποίηση κειμένου.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Ένα GUID (παγκοσμίως μοναδικό αναγνωριστικό) για το στοιχείο.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Περιέχει μια συλλογή από στοιχεία User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Περιέχει στοιχεία που καθορίζουν γενικές πληροφορίες τοποθέτησης για ένα σχήμα.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
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


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

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

