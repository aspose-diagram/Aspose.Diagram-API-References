---
title: Shape
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ορίζουν ένα σχήμα σε μια κύρια σελίδα ή σε στοιχείο ομαδοποιημένου σχήματος.
type: docs
weight: 355
url: /el/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Περιέχει στοιχεία που ορίζουν ένα σχήμα σε ένα Master, Page ή στοιχείο σχήματος ομάδας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Shape()](#Shape--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [bringForward()](#bringForward--) | Μετακινεί το σχήμα μία θέση μπροστά στη σειρά z. |
| [bringToFront()](#bringToFront--) | Μετακινεί το σχήμα στην κορυφή της σειράς z. |
| [centerDrawing()](#centerDrawing--) | Κεντράρει το σχήμα σε σχέση με το μέγεθος της σελίδας. |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Επιστρέφει έναν πίνακα που περιέχει τα αναγνωριστικά (IDs) των σχημάτων που είναι συνδεδεμένα με το σχήμα. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Επιστρέφει έναν πίνακα που περιέχει τα αναγνωριστικά των σχημάτων που εξαρτώνται από ένα σχήμα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Αποκτά τον έλεγχο ActiveX. |
| [getActs()](#getActs--) | Περιέχει μια συλλογή στοιχείων Act. |
| [getAlign()](#getAlign--) | Δείχνει την ευθυγράμμιση ενός σχήματος σε σχέση με τον οδηγό ή το σημείο οδηγού στο οποίο το σχήμα είναι κολλημένο. |
| [getChars()](#getChars--) | Περιέχει μια συλλογή από στοιχεία Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Περιέχει μια συλλογή από στοιχεία ConnectionABCD. |
| [getConnections()](#getConnections--) | Περιέχει μια συλλογή από στοιχεία Connection. |
| [getConnectorRule()](#getConnectorRule--) | Επιστρέφει ένα connectorRule που περιέχει το αναγνωριστικό του σχήματος και τη σύνδεση που είναι συνδεδεμένη με το σχήμα. |
| [getConnectorsType()](#getConnectorsType--) | Αποκτήστε τον τύπο των συνδέσμων. |
| [getControlData()](#getControlData--) | Αποκτά τα δεδομένα του ελέγχου. |
| [getControls()](#getControls--) | Περιέχει μια συλλογή στοιχείων Control. |
| [getData1()](#getData1--) | Περιέχει μια αυθαίρετη τιμή συμβολοσειράς που χρησιμοποιείται για την παροχή πρόσθετων πληροφοριών σχετικά με ένα σχήμα. |
| [getData2()](#getData2--) | Περιέχει μια αυθαίρετη τιμή συμβολοσειράς που χρησιμοποιείται για την παροχή πρόσθετων πληροφοριών σχετικά με ένα σχήμα. |
| [getData3()](#getData3--) | Περιέχει μια αυθαίρετη τιμή συμβολοσειράς που χρησιμοποιείται για την παροχή πρόσθετων πληροφοριών σχετικά με ένα σχήμα. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getDiagram()](#getDiagram--) | Βασικό στοιχείο της ιεραρχίας αντικειμένων Visio. |
| [getDisplayText()](#getDisplayText--) | Αποκτήστε το κείμενο που εμφανίζεται στη διεπαφή. |
| [getEvent()](#getEvent--) | Περιέχει στοιχεία που καθορίζουν τύπους που ελέγχουν τα γεγονότα σχήματος. |
| [getFields()](#getFields--) | Περιέχει μια συλλογή στοιχείων Field. |
| [getFill()](#getFill--) | Περιέχει τις τρέχουσες τιμές μορφοποίησης γεμίσματος για το σχήμα και τη σκιά του σχήματος, συμπεριλαμβανομένου του μοτίβου, του χρώματος προσκηνίου και του χρώματος φόντου. |
| [getFillStyle()](#getFillStyle--) | Το StyleSheet από το οποίο αυτό το σχήμα κληρονομεί τη μορφοποίηση γεμίσματος. |
| [getForeign()](#getForeign--) | Περιέχει στοιχεία που καθορίζουν το πλάτος και το ύψος ενός αντικειμένου από άλλο πρόγραμμα που χρησιμοποιείται σε έγγραφο Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE. |
| [getGeoms()](#getGeoms--) | Περιέχει μια συλλογή στοιχείων Geom. |
| [getGroup()](#getGroup--) | Περιέχει στοιχεία που ελέγχουν πώς προσθέτετε σχήματα σε μια ομάδα, μετακινείτε μέλη μιας ομάδας και επιλέγετε ομάδες. |
| [getHelp()](#getHelp--) | Περιέχει στοιχεία που καθορίζουν το θέμα του αρχείου βοήθειας του στοιχείου Shape και τις πληροφορίες πνευματικών δικαιωμάτων. |
| [getHyperlinks()](#getHyperlinks--) | Περιέχει μια συλλογή στοιχείων Hyperlink. |
| [getID()](#getID--) | Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο. |
| [getImage()](#getImage--) | Περιέχει τις τιμές γάμμα, φωτεινότητας, αντίθεσης, θολώματος, ενίσχυσης, αποθορυβοποίησης και διαφάνειας για ένα bitmap. |
| [getInheritChars()](#getInheritChars--) | Περιέχει τις τιμές χαρακτήρων για το σχήμα που κληρονομούνται από το κύριο σχήμα. |
| [getInheritFill()](#getInheritFill--) | Περιέχει τις τιμές μορφοποίησης γεμίσματος για το σχήμα που κληρονομούνται από το γονικό στυλ και το κύριο σχήμα. |
| [getInheritGeoms()](#getInheritGeoms--) | Περιέχει τις τιμές Geoms για το σχήμα που κληρονομείται από το master shape. |
| [getInheritLine()](#getInheritLine--) | Περιέχει τις τιμές μορφοποίησης γραμμής για το σχήμα που κληρονομείται από το γονικό στυλ και το master shape. |
| [getInheritParas()](#getInheritParas--) | Περιέχει τα paras για το σχήμα που κληρονομείται από το γονικό στυλ και το master shape. |
| [getInheritProps()](#getInheritProps--) | Περιέχει τα props για το σχήμα που κληρονομείται από το master shape. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Περιέχει τις τιμές textblock για το σχήμα που κληρονομείται από το γονικό στυλ και το master shape. |
| [getInheritUsers()](#getInheritUsers--) | Περιέχει τους χρήστες για το σχήμα που κληρονομείται από το master shape. |
| [getLayerMem()](#getLayerMem--) | Περιέχει το στοιχείο LayerMember, το οποίο καθορίζει κάθε στρώμα στο οποίο έχει ανατεθεί το σχήμα. |
| [getLayout()](#getLayout--) | Περιέχει στοιχεία που ελέγχουν τη θέση του σχήματος και τις ρυθμίσεις δρομολόγησης συνδέσμων. |
| [getLine()](#getLine--) | Περιέχει στοιχεία που ελέγχουν τις ιδιότητες γραμμής για ένα σχήμα, όπως το μοτίβο, το πάχος και το χρώμα. |
| [getLineStyle()](#getLineStyle--) | StyleSheet από το οποίο αυτό το σχήμα κληρονομεί τη μορφοποίηση γραμμής |
| [getMaster()](#getMaster--) | Το Master από το οποίο το σχήμα κληρονομεί τα δεδομένα του. |
| [getMasterShape()](#getMasterShape--) | Αυτό το χαρακτηριστικό μπορεί να υπάρχει μόνο σε σχήματα που είναι μέλη ενός group shape, και το group είναι μια παρουσία του master. |
| [getMisc()](#getMisc--) | Περιέχει στοιχεία που καθορίζουν το θέμα του αρχείου βοήθειας του στοιχείου Shape και τις πληροφορίες πνευματικών δικαιωμάτων. |
| [getName()](#getName--) | Το όνομα του στοιχείου. |
| [getNameU()](#getNameU--) | Το καθολικό όνομα του στοιχείου. |
| [getOneD()](#getOneD--) | Καθορίζει εάν το σχήμα συμπεριφέρεται ως αντικείμενο μονοδιάστατο (1-D). |
| [getPage()](#getPage--) | Βασικό στοιχείο της ιεραρχίας αντικειμένων Visio. |
| [getParas()](#getParas--) | Περιέχει μια συλλογή από στοιχεία Para. |
| [getParentShape()](#getParentShape--) | Γονέας του σχήματος. |
| [getProps()](#getProps--) | Περιέχει μια συλλογή στοιχείων Prop. |
| [getProtection()](#getProtection--) | Το κλείδωμα βοηθά στην αποφυγή ακούσιων αλλαγών στο σχήμα, αλλά δεν εμποδίζει το Microsoft Visio από την επαναφορά τιμών σε άλλες περιπτώσεις. |
| [getPureText()](#getPureText--) | Λάβετε τη συμβολοσειρά κειμένου |
| [getRootShape()](#getRootShape--) | Επιστρέφει το σχήμα κορυφαίου επιπέδου μιας παρουσίασης εάν αυτό το σχήμα είναι μέρος μιας παρουσίασης master. |
| [getScratchs()](#getScratchs--) | Περιέχει μια συλλογή από στοιχεία Scratch. |
| [getShapes()](#getShapes--) | Περιέχει μια συλλογή στοιχείων Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Περιέχει μια συλλογή στοιχείων SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | Περιέχει μια συλλογή στοιχείων Tab. |
| [getText()](#getText--) | Περιέχει το κείμενο ενός σχήματος. |
| [getTextBlock()](#getTextBlock--) | Περιέχει στοιχεία που καθορίζουν την ευθυγράμμιση, τα περιθώρια και τις προεπιλεγμένες θέσεις διακοπής καρτέλας του κειμένου σε ένα μπλοκ κειμένου σχήματος. |
| [getTextStyle()](#getTextStyle--) | StyleSheet από το οποίο αυτό το σχήμα κληρονομεί τη μορφοποίηση κειμένου. |
| [getTextXForm()](#getTextXForm--) | Περιέχει στοιχεία που καθορίζουν πληροφορίες τοποθέτησης για το μπλοκ κειμένου ενός σχήματος. |
| [getThreeDFormat()](#getThreeDFormat--) | Λαμβάνει το ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Καθορίζει εάν το σχήμα συμπεριφέρεται ως αντικείμενο διδιάστατο (2-D). |
| [getType()](#getType--) | Ο τύπος ενός σχήματος. |
| [getUniqueID()](#getUniqueID--) | Ένα GUID (παγκοσμίως μοναδικό αναγνωριστικό) που έχει εκχωρηθεί στο σχήμα. |
| [getUsers()](#getUsers--) | Περιέχει μια συλλογή από στοιχεία User. |
| [getXForm()](#getXForm--) | Περιέχει στοιχεία που καθορίζουν γενικές πληροφορίες τοποθέτησης για ένα σχήμα. |
| [getXForm1D()](#getXForm1D--) | Περιέχει τις συντεταγμένες x και y του αρχικού και του τελικού σημείου ενός 1‑Δ σχήματος. |
| [getZOrderIndex()](#getZOrderIndex--) | Επιστρέφει το δείκτη ενός σχήματος στη σειρά z, εκτός του guide shape. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Επιστρέφει έναν πίνακα που περιέχει τα αναγνωριστικά των σχημάτων που είναι κολλημένα σε ένα σχήμα. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Δείχνει εάν αυτά τα δύο σχήματα είναι συνδεδεμένα. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Δείχνει εάν αυτό το σχήμα περιέχει άλλο σχήμα. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Δείχνει εάν αυτά τα δύο σχήματα είναι κολλημένα. |
| [isInGroup()](#isInGroup--) | Δείχνει εάν αυτό το σχήμα βρίσκεται σε ένα group shape. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Δείχνει εάν αυτό το σχήμα διασταυρώνεται με άλλο σχήμα. |
| [isTextEmpty()](#isTextEmpty--) | Υποδεικνύει εάν το σχήμα έχει κείμενο και εάν το κείμενο είναι κενό ή όχι. |
| [move(double dX, double dY)](#move-double-double-) | Μετακινεί το σχήμα κατά dX και dY ίντσες από την τρέχουσα θέση. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Μετακινεί το σχήμα σε νέα απόλυτη θέση στη σελίδα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Ανανεώνει τη θέση του σχήματος, συμπεριλαμβανομένων των xform, connection και geom, όταν αλλάζει το κείμενο του σχήματος ή άλλων. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Αντικαθιστά τη συμβολοσειρά κειμένου ενός σχήματος. |
| [sendBackward()](#sendBackward--) | Μετακινεί το σχήμα μία θέση πίσω στη σειρά z. |
| [sendToBack()](#sendToBack--) | Μετακινεί το σχήμα στο τέλος της σειράς z. |
| [setAngle(double angle)](#setAngle-double-) | Ορίζει νέα γωνία του σχήματος. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Ορίστε τύπο συνδετήρων |
| [setData1(String value)](#setData1-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Ορίζει νέο ύψος του σχήματος. |
| [setID(long value)](#setID-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Εφαρμόστε ένα προεπιλεγμένο θέμα σε αυτό το σχήμα |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος quickstyle σε αυτό το σχήμα |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | pply μια προεπιλεγμένη παραλλαγή θέματος quickstyle σε αυτό το σχήμα, όπως οι επιλογές στυλ θέματος στη λίστα πτυσσόμενων επιλογών στυλ σχήματος |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος σε αυτό το σχήμα |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Ορίζει νέο πλάτος του σχήματος. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Δημιουργεί το html του σχήματος και το αποθηκεύει σε ροή με την καθορισμένη μορφή. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Δημιουργεί το html του σχήματος και το αποθηκεύει σε ροή με την καθορισμένη μορφή. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Δημιουργεί το html και το αποθηκεύει σε αρχείο. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Δημιουργεί την εικόνα του σχήματος και την αποθηκεύει σε ροή με την καθορισμένη μορφή. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Δημιουργεί την εικόνα του σχήματος και την αποθηκεύει σε ροή με την καθορισμένη μορφή. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Δημιουργεί την εικόνα του σχήματος και την αποθηκεύει σε αρχείο. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Δημιουργεί το pdf του σχήματος και το αποθηκεύει σε ροή. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Δημιουργεί το pdf του σχήματος και το αποθηκεύει σε ροή. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Αποθηκεύει το σχήμα σε αρχείο pdf. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Αποθηκεύει το σχήμα σε αρχείο svg. |
| [ungroup()](#ungroup--) | Αποομαδοποίηση Σχήματος |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Κατασκευαστής.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Μετακινεί το σχήμα μία θέση μπροστά στη σειρά z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Μετακινεί το σχήμα στην κορυφή της σειράς z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Κεντράρει το σχήμα σε σχέση με το μέγεθος της σελίδας.

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Επιστρέφει έναν πίνακα που περιέχει τα αναγνωριστικά (IDs) των σχημάτων που είναι συνδεδεμένα με το σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σημαία | int | Φιλτράρει τον πίνακα των επιστρεφόμενων IDs σχήματος με βάση την κατεύθυνση των συνδετήρων. Δείτε τις Παρατηρήσεις για τις πιθανές τιμέςAspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Φιλτράρει τον πίνακα των επιστρεφόμενων IDs σχήματος περιορίζοντάς τον στα IDs των σχημάτων που ταιριάζουν με το καθορισμένο categoryString. |

**Returns:**
long[] - πίνακας IDs τύπου long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Επιστρέφει έναν πίνακα που περιέχει τα αναγνωριστικά των σχημάτων που εξαρτώνται από ένα σχήμα.

**Returns:**
long[] - πίνακας IDs τύπου long.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Αποκτά τον έλεγχο ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Περιέχει μια συλλογή στοιχείων Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Δείχνει την ευθυγράμμιση ενός σχήματος σε σχέση με την οδηγία ή το σημείο οδηγίας στο οποίο το σχήμα είναι κολλημένο. Το στοιχείο Align εμφανίζεται μόνο για σχήματα που είναι κολλημένα σε οδηγίες ή σημεία οδηγίας.

**Returns:**
[Align](../../com.aspose.diagram/align)
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
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
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
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Επιστρέφει ένα connectorRule που περιέχει το αναγνωριστικό του σχήματος και τη σύνδεση που είναι συνδεδεμένη με το σχήμα.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Αποκτήστε τον τύπο των συνδέσμων.

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Αποκτά τα δεδομένα του ελέγχου.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Περιέχει μια συλλογή στοιχείων Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Περιέχει μια αυθαίρετη τιμή συμβολοσειράς που χρησιμοποιείται για την παροχή πρόσθετων πληροφοριών σχετικά με ένα σχήμα.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Περιέχει μια αυθαίρετη τιμή συμβολοσειράς που χρησιμοποιείται για την παροχή πρόσθετων πληροφοριών σχετικά με ένα σχήμα.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Περιέχει μια αυθαίρετη τιμή συμβολοσειράς που χρησιμοποιείται για την παροχή πρόσθετων πληροφοριών σχετικά με ένα σχήμα.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο έχει διαγραφεί τοπικά.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Βασικό στοιχείο της ιεραρχίας αντικειμένων Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Αποκτήστε το κείμενο που εμφανίζεται στη διεπαφή.

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Περιέχει στοιχεία που καθορίζουν τύπους που ελέγχουν τα γεγονότα σχήματος.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Περιέχει μια συλλογή στοιχείων Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
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


Το StyleSheet από το οποίο αυτό το σχήμα κληρονομεί τη μορφοποίηση γεμίσματος.

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
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Περιέχει μια συλλογή στοιχείων Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Περιέχει μια συλλογή στοιχείων Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Περιέχει τις τιμές γάμμα, φωτεινότητας, αντίθεσης, θολώματος, ενίσχυσης, αποθορυβοποίησης και διαφάνειας για ένα bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Περιέχει τις τιμές χαρακτήρων για το σχήμα που κληρονομούνται από το κύριο σχήμα.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Περιέχει τις τιμές μορφοποίησης γεμίσματος για το σχήμα που κληρονομούνται από το γονικό στυλ και το κύριο σχήμα.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Περιέχει τις τιμές Geoms για το σχήμα που κληρονομείται από το master shape.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Περιέχει τις τιμές μορφοποίησης γραμμής για το σχήμα που κληρονομείται από το γονικό στυλ και το master shape.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Περιέχει τα paras για το σχήμα που κληρονομείται από το γονικό στυλ και το master shape.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Περιέχει τα props για το σχήμα που κληρονομείται από το master shape.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Περιέχει τις τιμές textblock για το σχήμα που κληρονομείται από το γονικό στυλ και το master shape.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Περιέχει τους χρήστες για το σχήμα που κληρονομείται από το master shape.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Περιέχει το στοιχείο LayerMember, το οποίο καθορίζει κάθε στρώμα στο οποίο έχει ανατεθεί το σχήμα.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
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


StyleSheet από το οποίο αυτό το σχήμα κληρονομεί τη μορφοποίηση γραμμής

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Το Master από το οποίο το σχήμα κληρονομεί τα δεδομένα του.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Αυτό το χαρακτηριστικό μπορεί να υπάρχει μόνο σε σχήματα που είναι μέλη ενός group shape, και η ομάδα είναι ένα αντίγραφο ενός master. Το χαρακτηριστικό περιέχει ένα ID που αναφέρεται στο αντίστοιχο υπο-σχήμα στον master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
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
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Καθορίζει εάν το shape λειτουργεί ως αντικείμενο μονοδιάστατο (1‑Δ). Μόνο για ανάγνωση.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Βασικό στοιχείο της ιεραρχίας αντικειμένων Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Περιέχει μια συλλογή από στοιχεία Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Γονέας του σχήματος.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Περιέχει μια συλλογή στοιχείων Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Το κλείδωμα βοηθά στην αποτροπή ακούσιων αλλαγών στο σχήμα, αλλά δεν εμποδίζει το Microsoft Visio από το να επαναφέρει τιμές σε άλλες περιστάσεις. Επίσης, δεν προστατεύει από αλλαγές που γίνονται στο παράθυρο ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Λάβετε τη συμβολοσειρά κειμένου

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Επιστρέφει το shape ανώτερου επιπέδου μιας παρουσίας εάν αυτό το shape αποτελεί μέρος μιας παρουσίας master. Μόνο για ανάγνωση.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Περιέχει μια συλλογή από στοιχεία Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Περιέχει μια συλλογή στοιχείων Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Περιέχει μια συλλογή στοιχείων SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Περιέχει μια συλλογή στοιχείων Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Περιέχει το κείμενο ενός σχήματος.

**Returns:**
[Text](../../com.aspose.diagram/text)
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


StyleSheet από το οποίο αυτό το σχήμα κληρονομεί τη μορφοποίηση κειμένου.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Περιέχει στοιχεία που καθορίζουν πληροφορίες τοποθέτησης για το μπλοκ κειμένου ενός σχήματος.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Λαμβάνει το ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Καθορίζει εάν το σχήμα συμπεριφέρεται ως αντικείμενο διδιάστατο (2-D).

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Ο τύπος ενός shape. Μπορεί να είναι μία από τις παρακάτω τιμές: Group, Shape, Guide ή Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Ένα GUID (παγκοσμίως μοναδικό αναγνωριστικό) που έχει εκχωρηθεί στο σχήμα.

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
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Περιέχει τις συντεταγμένες x και y του αρχικού και του τελικού σημείου ενός σχήματος 1‑Δ. Αυτό το στοιχείο εμφανίζεται μόνο για σχήματα 1‑Δ.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Επιστρέφει το δείκτη ενός σχήματος στη σειρά z, εκτός του guide shape.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Επιστρέφει έναν πίνακα που περιέχει τα αναγνωριστικά των σχημάτων που είναι κολλημένα σε ένα σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σημαία | int | Η διαστατικότητα και η κατεύθυνση των σημείων σύνδεσης των shapes που θα επιστραφούν. Δείτε τις Παρατηρήσεις για τις πιθανές τιμές Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Φιλτράρει τον πίνακα των επιστρεφόμενων IDs σχήματος περιορίζοντάς τον στα IDs των σχημάτων που ταιριάζουν με το καθορισμένο categoryString. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Προαιρετικό: επιπλέον shape στο οποίο πρέπει επίσης να κολλήσουν τα επιστρεφόμενα shapes, μπορεί να είναι [Shape](../../com.aspose.diagram/shape) ή null. |

**Returns:**
long[] - πίνακας IDs τύπου long.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


Δείχνει εάν αυτά τα δύο σχήματα είναι συνδεδεμένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Δείχνει εάν αυτό το σχήμα περιέχει άλλο σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Δείχνει εάν αυτά τα δύο σχήματα είναι κολλημένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Δείχνει εάν αυτό το σχήμα βρίσκεται σε ένα group shape.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Δείχνει εάν αυτό το σχήμα διασταυρώνεται με άλλο σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Υποδεικνύει εάν το σχήμα έχει κείμενο και εάν το κείμενο είναι κενό ή όχι.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Μετακινεί το σχήμα κατά dX και dY ίντσες από την τρέχουσα θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dX | double | X offset τύπου double. |
| dY | double | Y offset τύπου double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Μετακινεί το σχήμα σε νέα απόλυτη θέση στη σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newPinX | double | Νέα συντεταγμένη x του pin του shape (κέντρο περιστροφής) σε σχέση με την αρχή του γονέα του. double. |
| newPinY | double | Νέα συντεταγμένη y του pin του shape (κέντρο περιστροφής) σε σχέση με την αρχή του γονέα του. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Ανανεώνει τη θέση του shape συμπεριλαμβανομένων των xform, connection και geom όταν αλλάζει το κείμενο του shape ή άλλων. Θα συλλέξουμε τα δεδομένα του shape όπως το κείμενο του shape και στη συνέχεια θα υπολογίσουμε τη θέση του shape. Αυτή η μέθοδος χρησιμοποιείται μόνο για την ανανέωση των δεδομένων του shape.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Αντικαθιστά τη συμβολοσειρά κειμένου ενός σχήματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Μετακινεί το σχήμα μία θέση πίσω στη σειρά z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Μετακινεί το σχήμα στο τέλος της σειράς z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Ορίζει νέα γωνία του shape. Η μονάδα της γωνίας είναι το radian.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | double | Νέα γωνία της οποίας η μονάδα είναι radian και όχι degree. double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Ορίστε τύπο συνδετήρων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Ορίζει νέο ύψος του σχήματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Εφαρμόστε ένα προεπιλεγμένο θέμα σε αυτό το σχήμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος quickstyle σε αυτό το σχήμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


pply μια προεπιλεγμένη παραλλαγή θέματος quickstyle σε αυτό το σχήμα, όπως οι επιλογές στυλ θέματος στη λίστα πτυσσόμενων επιλογών στυλ σχήματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος σε αυτό το σχήμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Ορίζει νέο πλάτος του σχήματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Δημιουργεί το html του σχήματος και το αποθηκεύει σε ροή με την καθορισμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Δημιουργεί το html του σχήματος και το αποθηκεύει σε ροή με την καθορισμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Δημιουργεί το html και το αποθηκεύει σε αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Δημιουργεί την εικόνα του σχήματος και την αποθηκεύει σε ροή με την καθορισμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Δημιουργεί την εικόνα του σχήματος και την αποθηκεύει σε ροή με την καθορισμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Δημιουργεί το pdf του σχήματος και το αποθηκεύει σε ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Δημιουργεί το pdf του σχήματος και το αποθηκεύει σε ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Αποθηκεύει το σχήμα σε αρχείο pdf.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


Αποθηκεύει το σχήμα σε αρχείο svg.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Αποομαδοποίηση Σχήματος

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

