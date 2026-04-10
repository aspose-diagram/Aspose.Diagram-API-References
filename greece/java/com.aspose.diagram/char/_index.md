---
title: Char
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει τα χαρακτηριστικά μορφοποίησης για το κείμενο των σχημάτων, όπως χρώμα γραμματοσειράς, στυλ κειμένου, πεζά/κεφαλαία, θέση σε σχέση με τη γραμμή βάσης και μέγεθος σε σημεία.
type: docs
weight: 45
url: /el/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

Περιέχει τα χαρακτηριστικά μορφοποίησης για το κείμενο του σχήματος, όπως γραμματοσειρά, χρώμα, στυλ κειμένου, μορφή, θέση σε σχέση με τη γραμμή βάσης και μέγεθος σημείου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Char()](#Char--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | Καθορίζει τον αριθμό ταυτότητας (ID) της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση κειμένου που περιέχει ασιατικούς χαρακτήρες. |
| [getAsianFontName()](#getAsianFontName--) | Καθορίζει το όνομα της ασιατικής γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση του κειμένου. Χρησιμοποιείται για το Visio 2013. |
| [getCase()](#getCase--) | Καθορίζει τη μορφή κεφαλαίων/πεζών του κειμένου ενός σχήματος. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Όταν περιλαμβάνεται σε ένα στοιχείο Char, το στοιχείο Color. |
| [getColorTrans()](#getColorTrans--) | Καθορίζει το βαθμό διαφάνειας για το χρώμα κειμένου ενός στρώματος ή σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές). |
| [getComplexScriptFont()](#getComplexScriptFont--) | Περιέχει τον αριθμό της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση κειμένου που αποτελείται από χαρακτήρες σύνθετης γραφής. |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | Καθορίζει το όνομα της γραμματοσειράς ComplexScript που χρησιμοποιείται για τη μορφοποίηση του κειμένου. Χρησιμοποιείται για το Visio 2013. |
| [getComplexScriptSize()](#getComplexScriptSize--) | Το μέγεθος της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση κειμένου που αποτελείται από χαρακτήρες σύνθετης γραφής. |
| [getDblUnderline()](#getDblUnderline--) | Καθορίζει αν η περιοχή του κειμένου έχει διπλή υπογράμμιση κάτω από αυτή. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | Καθορίζει εάν το κείμενο είναι μορφοποιημένο ως διπλή διαγράμμιση. |
| [getFont()](#getFont--) | Καθορίζει τον αριθμό ταυτότητας της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση του κειμένου. |
| [getFontName()](#getFontName--) | Καθορίζει το όνομα της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση του κειμένου. Χρησιμοποιείται για το Visio 2013. |
| [getFontScale()](#getFontScale--) | Καθορίζει το πλάτος της γραμματοσειράς. |
| [getHighlight()](#getHighlight--) | Καθορίζει την επισήμανση. |
| [getIX()](#getIX--) | Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου. |
| [getLangID()](#getLangID--) | Δείχνει το αναγνωριστικό τοπικής ρύθμισης (LCID) της γλώσσας στην οποία εισήχθη ο τύπος κελιού, το κείμενο, η προσαρμοσμένη ιδιότητα ή το σχόλιο. |
| [getLetterspace()](#getLetterspace--) | Καθορίζει το ποσό του διαστήματος μεταξύ δύο ή περισσότερων χαρακτήρων. |
| [getLocale()](#getLocale--) | Καθορίζει την τοπική ρύθμιση της σειράς κειμένου για σκοπούς ελέγχου ορθογραφίας. |
| [getLocalizeFont()](#getLocalizeFont--) | Καθορίζει εάν το κείμενο του σχήματος πρέπει να εντοπιστεί (να μεταφραστεί σε άλλη γλώσσα). |
| [getOverline()](#getOverline--) | Καθορίζει εάν το κείμενο έχει μια γραμμή πάνω του. |
| [getPerpendicular()](#getPerpendicular--) | Καθορίζει εάν ένα πεδίο κειμένου εμφανίζεται κάθετα στο υπόλοιπο κείμενο σε ένα μπλοκ κειμένου. |
| [getPos()](#getPos--) | Καθορίζει τη θέση του κειμένου του σχήματος σε σχέση με τη γραμμή βάσης. |
| [getRTLText()](#getRTLText--) | Καθορίζει εάν η κατεύθυνση του κειμένου της τρέχουσας σειράς χαρακτήρων είναι από αριστερά προς δεξιά ή από δεξιά προς αριστερά. |
| [getSize()](#getSize--) | Καθορίζει το μέγεθος του κειμένου στο μπλοκ κειμένου του σχήματος. |
| [getStrikethru()](#getStrikethru--) | Καθορίζει εάν το κείμενο είναι μορφοποιημένο ως διαγράμμιση. |
| [getStyle()](#getStyle--) | Καθορίζει τη μορφοποίηση χαρακτήρων που εφαρμόζεται σε μια περιοχή κειμένου στο μπλοκ κειμένου του σχήματος. |
| [getUseVertical()](#getUseVertical--) | Καθορίζει εάν η σειρά χαρακτήρων είναι κάθετη ή οριζόντια. |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | Δείχνει εάν η γραμματοσειρά είναι έντονη. |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | Δείχνει εάν η γραμματοσειρά είναι διπλή διαγράμμιση. |
| [isDoubleUnderline()](#isDoubleUnderline--) | Δείχνει εάν η γραμματοσειρά είναι διπλή υπογράμμιση. |
| [isItalic()](#isItalic--) | Δείχνει εάν η γραμματοσειρά είναι πλάγια. |
| [isStrikethrough()](#isStrikethrough--) | Δείχνει εάν η γραμματοσειρά είναι διαγράμμιση. |
| [isSubscript()](#isSubscript--) | Δείχνει εάν η γραμματοσειρά είναι υποδείκτης. |
| [isSuperscript()](#isSuperscript--) | Δείχνει εάν η γραμματοσειρά είναι υπέρδειξη. |
| [isUnderline()](#isUnderline--) | Δείχνει εάν η γραμματοσειρά είναι υπογραμμισμένη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCase()](../../com.aspose.diagram/char\#getCase--) |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColor()](../../com.aspose.diagram/char\#getColor--) |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--) |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--) |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--) |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--) |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/char\#getDel--) |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--) |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFont()](../../com.aspose.diagram/char\#getFont--) |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFontName()](../../com.aspose.diagram/char\#getFontName--) |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFontScale()](../../com.aspose.diagram/char\#getFontScale--) |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHighlight()](../../com.aspose.diagram/char\#getHighlight--) |
| [setIX(int value)](#setIX-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/char\#getIX--) |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLangID()](../../com.aspose.diagram/char\#getLangID--) |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--) |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocale()](../../com.aspose.diagram/char\#getLocale--) |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--) |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getOverline()](../../com.aspose.diagram/char\#getOverline--) |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--) |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPos()](../../com.aspose.diagram/char\#getPos--) |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getRTLText()](../../com.aspose.diagram/char\#getRTLText--) |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSize()](../../com.aspose.diagram/char\#getSize--) |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--) |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStyle()](../../com.aspose.diagram/char\#getStyle--) |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
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
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


Καθορίζει τον αριθμό ταυτότητας (ID) της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση κειμένου που περιέχει ασιατικούς χαρακτήρες.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


Καθορίζει το όνομα της ασιατικής γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση του κειμένου. Χρησιμοποιείται για το Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


Καθορίζει τη μορφή κεφαλαίων/πεζών του κειμένου ενός σχήματος.

**Returns:**
[Case](../../com.aspose.diagram/case)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Όταν περιλαμβάνεται σε ένα στοιχείο Char, το στοιχείο Color.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Καθορίζει το βαθμό διαφάνειας για το χρώμα κειμένου ενός στρώματος ή σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


Περιέχει τον αριθμό της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση κειμένου που αποτελείται από χαρακτήρες σύνθετων γραφών. Οι σύνθετες γραφές είναι γλώσσες των οποίων οι χαρακτήρες απαιτούν σύνδεση ή σχήμα, όπως οι γλώσσες από δεξιά προς τα αριστερά (Αραβικά, Φαρσί, Εβραϊκά και Ουρντού) και αρκετές νότιες ασιατικές γλώσσες.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


Καθορίζει το όνομα της γραμματοσειράς ComplexScript που χρησιμοποιείται για τη μορφοποίηση του κειμένου. Χρησιμοποιείται για το Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


The size of the font used to format text composed of complex script characters. Complex scripts are languages whose characters require ligation or shaping, such as the right-to-left languages (Arabic, Farsi, Hebrew, and Urdu) and several South Asian languages.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


Καθορίζει αν η περιοχή του κειμένου έχει διπλή υπογράμμιση κάτω από αυτή.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


Καθορίζει εάν το κείμενο είναι μορφοποιημένο ως διπλή διαγράμμιση.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


Καθορίζει τον αριθμό ταυτότητας της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση του κειμένου.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


Καθορίζει το όνομα της γραμματοσειράς που χρησιμοποιείται για τη μορφοποίηση του κειμένου. Χρησιμοποιείται για το Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


Καθορίζει το πλάτος της γραμματοσειράς.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


Καθορίζει την επισήμανση.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Ο δείκτης μηδενικής βάσης του στοιχείου εντός του γονικού του στοιχείου.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. For a list of languages supported by Microsoft Office applications and their corresponding language IDs, see the DocLangID element.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


Specifies the amount of space between two or more characters. Space can be added or subtracted in 1/20th point increments.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


Καθορίζει την τοπική ρύθμιση της σειράς κειμένου για σκοπούς ελέγχου ορθογραφίας.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


Καθορίζει εάν το κείμενο του σχήματος πρέπει να εντοπιστεί (να μεταφραστεί σε άλλη γλώσσα).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


Καθορίζει εάν το κείμενο έχει μια γραμμή πάνω του.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


Καθορίζει εάν ένα πεδίο κειμένου εμφανίζεται κάθετα στο υπόλοιπο κείμενο σε ένα μπλοκ κειμένου.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


Καθορίζει τη θέση του κειμένου του σχήματος σε σχέση με τη γραμμή βάσης.

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


Καθορίζει εάν η κατεύθυνση του κειμένου της τρέχουσας σειράς χαρακτήρων είναι από αριστερά προς δεξιά ή από δεξιά προς αριστερά.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


Καθορίζει το μέγεθος του κειμένου στο μπλοκ κειμένου του σχήματος.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


Καθορίζει εάν το κείμενο είναι μορφοποιημένο ως διαγράμμιση.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


Καθορίζει τη μορφοποίηση χαρακτήρων που εφαρμόζεται σε μια περιοχή κειμένου στο μπλοκ κειμένου του σχήματος.

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


Καθορίζει εάν η σειρά χαρακτήρων είναι κάθετη ή οριζόντια.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBold() {#isBold--}
```
public boolean isBold()
```


Δείχνει εάν η γραμματοσειρά είναι έντονη.

**Returns:**
boolean
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


Δείχνει εάν η γραμματοσειρά είναι διπλή διαγράμμιση.

**Returns:**
boolean
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


Δείχνει εάν η γραμματοσειρά είναι διπλή υπογράμμιση.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Δείχνει εάν η γραμματοσειρά είναι πλάγια.

**Returns:**
boolean
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


Δείχνει εάν η γραμματοσειρά είναι διαγράμμιση.

**Returns:**
boolean
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Δείχνει εάν η γραμματοσειρά είναι υποδείκτης.

**Returns:**
boolean
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Δείχνει εάν η γραμματοσειρά είναι υπέρδειξη.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Δείχνει εάν η γραμματοσειρά είναι υπογραμμισμένη.

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




### setAsianFont(IntValue value) {#setAsianFont-com.aspose.diagram.IntValue-}
```
public void setAsianFont(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCase()](../../com.aspose.diagram/char\#getCase--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColor()](../../com.aspose.diagram/char\#getColor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/char\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFont()](../../com.aspose.diagram/char\#getFont--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFontName()](../../com.aspose.diagram/char\#getFontName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIX()](../../com.aspose.diagram/char\#getIX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLangID()](../../com.aspose.diagram/char\#getLangID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocale()](../../com.aspose.diagram/char\#getLocale--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getOverline()](../../com.aspose.diagram/char\#getOverline--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPos()](../../com.aspose.diagram/char\#getPos--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSize()](../../com.aspose.diagram/char\#getSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getStyle()](../../com.aspose.diagram/char\#getStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

