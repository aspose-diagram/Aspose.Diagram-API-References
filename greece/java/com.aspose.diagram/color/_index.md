---
title: Color
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά ένα χρώμα ARGB (άλφα, κόκκινο, πράσινο, μπλε).
type: docs
weight: 51
url: /el/java/com.aspose.diagram/color/
---

**Inheritance:**
java.lang.Object
```
public class Color
```

Αντιπροσωπεύει ένα χρώμα ARGB (alpha, κόκκινο, πράσινο, μπλε).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Color()](#Color--) | συνάρτηση κατασκευής |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Δοκιμάζει αν το καθορισμένο αντικείμενο είναι αντικείμενο τύπου Color και είναι ισοδύναμο με αυτό το αντικείμενο. |
| [fromArgb(int argb)](#fromArgb-int-) | Δημιουργεί ένα αντικείμενο Color από μια 32‑bit τιμή ARGB. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Δημιουργεί ένα αντικείμενο Color από τις καθορισμένες 8‑bit τιμές χρώματος (κόκκινο, πράσινο και μπλε). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Δημιουργεί ένα αντικείμενο Color από τις τέσσερις τιμές των συστατικών ARGB (άλφα, κόκκινο, πράσινο και μπλε). |
| [getA()](#getA--) | Αποκτά την τιμή του συστατικού άλφα αυτού του αντικειμένου Color. |
| [getAliceBlue()](#getAliceBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getAqua()](#getAqua--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getAquamarine()](#getAquamarine--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getAzure()](#getAzure--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getB()](#getB--) | Αποκτά την τιμή του συστατικού μπλε αυτού του αντικειμένου Color. |
| [getBeige()](#getBeige--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBisque()](#getBisque--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlack()](#getBlack--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlue()](#getBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlueViolet()](#getBlueViolet--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBrown()](#getBrown--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getBurlyWood()](#getBurlyWood--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getCadetBlue()](#getCadetBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getChartreuse()](#getChartreuse--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getChocolate()](#getChocolate--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getCornsilk()](#getCornsilk--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getCrimson()](#getCrimson--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getCyan()](#getCyan--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkBlue()](#getDarkBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkCyan()](#getDarkCyan--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkGray()](#getDarkGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkGreen()](#getDarkGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkKhaki()](#getDarkKhaki--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkMagenta()](#getDarkMagenta--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkOrange()](#getDarkOrange--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkOrchid()](#getDarkOrchid--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkRed()](#getDarkRed--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSalmon()](#getDarkSalmon--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkViolet()](#getDarkViolet--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDeepPink()](#getDeepPink--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDimGray()](#getDimGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getDodgerBlue()](#getDodgerBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getEmpty()](#getEmpty--) | Λάβετε ένα κενό χρώμα που ορίζεται από το σύστημα. |
| [getFirebrick()](#getFirebrick--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getFloralWhite()](#getFloralWhite--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getForestGreen()](#getForestGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getFuchsia()](#getFuchsia--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getG()](#getG--) | Αποκτά την τιμή του συστατικού πράσινο αυτού του αντικειμένου Color. |
| [getGainsboro()](#getGainsboro--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getGhostWhite()](#getGhostWhite--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getGold()](#getGold--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getGoldenrod()](#getGoldenrod--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getGray()](#getGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getGreen()](#getGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getGreenYellow()](#getGreenYellow--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getHoneydew()](#getHoneydew--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getHotPink()](#getHotPink--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getIndianRed()](#getIndianRed--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getIndigo()](#getIndigo--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getIvory()](#getIvory--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getKhaki()](#getKhaki--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLavender()](#getLavender--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLavenderBlush()](#getLavenderBlush--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLawnGreen()](#getLawnGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLemonChiffon()](#getLemonChiffon--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightBlue()](#getLightBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightCoral()](#getLightCoral--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightCyan()](#getLightCyan--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightGray()](#getLightGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightGreen()](#getLightGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightPink()](#getLightPink--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSalmon()](#getLightSalmon--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSlateGray()](#getLightSlateGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightYellow()](#getLightYellow--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLime()](#getLime--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLimeGreen()](#getLimeGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getLinen()](#getLinen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMagenta()](#getMagenta--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMaroon()](#getMaroon--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumBlue()](#getMediumBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumOrchid()](#getMediumOrchid--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumPurple()](#getMediumPurple--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMidnightBlue()](#getMidnightBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMintCream()](#getMintCream--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMistyRose()](#getMistyRose--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getMoccasin()](#getMoccasin--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getNavajoWhite()](#getNavajoWhite--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getNavy()](#getNavy--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getOldLace()](#getOldLace--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getOlive()](#getOlive--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getOliveDrab()](#getOliveDrab--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getOrange()](#getOrange--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getOrangeRed()](#getOrangeRed--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getOrchid()](#getOrchid--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleGreen()](#getPaleGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPapayaWhip()](#getPapayaWhip--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPeachPuff()](#getPeachPuff--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPeru()](#getPeru--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPink()](#getPink--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPlum()](#getPlum--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPowderBlue()](#getPowderBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getPurple()](#getPurple--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getR()](#getR--) | Αποκτά την τιμή του συστατικού κόκκινο αυτού του αντικειμένου Color. |
| [getRed()](#getRed--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getRosyBrown()](#getRosyBrown--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getRoyalBlue()](#getRoyalBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSaddleBrown()](#getSaddleBrown--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSalmon()](#getSalmon--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSandyBrown()](#getSandyBrown--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSeaGreen()](#getSeaGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSeaShell()](#getSeaShell--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSienna()](#getSienna--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSilver()](#getSilver--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSkyBlue()](#getSkyBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSlateBlue()](#getSlateBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSlateGray()](#getSlateGray--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSnow()](#getSnow--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSpringGreen()](#getSpringGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getSteelBlue()](#getSteelBlue--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getTan()](#getTan--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getTeal()](#getTeal--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getThistle()](#getThistle--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getTomato()](#getTomato--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getTransparent()](#getTransparent--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getTurquoise()](#getTurquoise--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getViolet()](#getViolet--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getWheat()](#getWheat--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getWhite()](#getWhite--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getYellow()](#getYellow--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [getYellowGreen()](#getYellowGreen--) | Λάβετε ένα χρώμα που ορίζεται από το σύστημα. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο Color. |
| [isEmpty()](#isEmpty--) | Καθορίζει αν αυτό το αντικείμενο Color δεν έχει αρχικοποιηθεί. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb()](#toArgb--) | Αποκτά την 32‑bit τιμή ARGB αυτού του αντικειμένου Color. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Color() {#Color--}
```
public Color()
```


συνάρτηση κατασκευής

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δοκιμάζει αν το καθορισμένο αντικείμενο είναι αντικείμενο τύπου Color και είναι ισοδύναμο με αυτό το αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο προς δοκιμή. |

**Returns:**
boolean - true εάν το obj είναι αντικείμενο τύπου Color και ισοδύναμο με αυτό το αντικείμενο Color· διαφορετικά, false.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Δημιουργεί ένα αντικείμενο Color από μια 32‑bit τιμή ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb | int | Μια τιμή που καθορίζει την 32‑bit τιμή ARGB. |

**Returns:**
[Color](../../com.aspose.diagram/color) - The Color object that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Δημιουργεί ένα αντικείμενο Color από τις καθορισμένες 8‑bit τιμές χρώματος (κόκκινο, πράσινο και μπλε). Η τιμή άλφα είναι έμμεσα 255 (πλήρως αδιαφανής). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας 32‑bit τιμής για κάθε συστατικό χρώματος, η τιμή κάθε συστατικού περιορίζεται σε 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόκκινο | int | Η τιμή του κόκκινου συστατικού για το νέο αντικείμενο Color. Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | int | Η τιμή του πράσινου συστατικού για το νέο αντικείμενο Color. Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | int | Η τιμή του μπλε συστατικού για το νέο αντικείμενο Color. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.diagram/color) - The Color object that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Δημιουργεί ένα αντικείμενο Color από τις τέσσερις τιμές των συστατικών ARGB (alpha,red, green, and blue). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας 32‑bit τιμής για κάθε συστατικό, η τιμή κάθε συστατικού περιορίζεται σε 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| άλφα | int | Το συστατικό άλφα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| κόκκινο | int | Το κόκκινο συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | int | Το πράσινο συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | int | Το μπλε συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.diagram/color) - The Color object that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Αποκτά την τιμή του συστατικού άλφα αυτού του αντικειμένου Color.

**Returns:**
byte - Η τιμή του συστατικού άλφα αυτού του αντικειμένου Color.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Αποκτά την τιμή του συστατικού μπλε αυτού του αντικειμένου Color.

**Returns:**
byte - Η τιμή του μπλε συστατικού αυτού του αντικειμένου Color.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Λάβετε ένα κενό χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Αποκτά την τιμή του συστατικού πράσινο αυτού του αντικειμένου Color.

**Returns:**
byte - Η τιμή του πράσινου συστατικού αυτού του αντικειμένου Color.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Αποκτά την τιμή του συστατικού κόκκινο αυτού του αντικειμένου Color.

**Returns:**
byte - Η τιμή του κόκκινου συστατικού αυτού του αντικειμένου Color.
### getRed() {#getRed--}
```
public static Color getRed()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Λάβετε ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.diagram/color) - A Color object representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο Color.

**Returns:**
int - Μια ακέραια τιμή που καθορίζει τον κωδικό κατακερματισμού για αυτό το αντικείμενο Color.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Καθορίζει αν αυτό το αντικείμενο Color δεν έχει αρχικοποιηθεί.

**Returns:**
boolean - Αυτή η ιδιότητα επιστρέφει true εάν αυτό το χρώμα δεν έχει αρχικοποιηθεί· διαφορετικά, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArgb() {#toArgb--}
```
public int toArgb()
```


Αποκτά την 32‑bit τιμή ARGB αυτού του αντικειμένου Color.

**Returns:**
int - Η 32-bit τιμή ARGB αυτού του αντικειμένου Color.
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

