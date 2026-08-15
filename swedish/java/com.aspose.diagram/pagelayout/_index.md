---
title: PageLayout
second_title: Aspose.Diagram för Java API-referens
description: Innehåller celler som styr sidlayoutinställningarna för former och anslutningar, såsom avstånd mellan alla former på sidan, avstånd mellan alla anslutningar på sidan och routningsstil för alla anslutningar på sidan.
type: docs
weight: 263
url: /sv/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Innehåller celler som styr sidlayoutinställningarna för former och anslutningar, såsom avstånd mellan alla former på sidan, avstånd mellan alla anslutningar på sidan och routningsstil för alla anslutningar på sidan.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Bestämmer mängden vertikalt utrymme mellan former på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Bestämmer mängden vertikalt utrymme mellan former på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Anger hur former placeras på sidan när former läggs ut när en användare väljer Lay Out Shapes (menyn Form). |
| [getBlockSizeX()](#getBlockSizeX--) | Bestämmer den vertikala blockstorleken, det område där var och en av dina former måste få plats på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan. |
| [getBlockSizeY()](#getBlockSizeY--) | Bestämmer mängden horisontellt utrymme mellan former på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Bestämmer vilken form som är förälder när du använder former med kontrollhandtag. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDynamicsOff()](#getDynamicsOff--) | Anger om placerbara former flyttar och anslutningar omdirigeras runt andra former och anslutningar på ritningssidan. |
| [getEnableGrid()](#getEnableGrid--) | Anger om Microsoft Visio placerar former baserat på ett internt sidrutnät när användaren väljer Lay Out Shapes (Shape menu). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Specificerar vilka dynamiska anslutningar som ska separeras om de ruttas ovanpå varandra. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Specificerar vilka dynamiska anslutningar som ska linjeras ovanpå varandra om de ruttas ovanpå varandra. |
| [getLineJumpCode()](#getLineJumpCode--) | Specificerar linjesprångsstilen för alla anslutningar på ritningssidan som inte har en lokal linjesprångsstil. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Anger storleken på linjsprång på horisontella segment av dynamiska anslutningar på sidan, som en procentandel av värdet för elementet LineToLineX (som anger det horisontella avståndet mellan alla anslutningar på ritningssidan). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Anger storleken på linjsprång på vertikala segment av dynamiska anslutningar på sidan, som en procentandel av värdet för elementet LineToLineY (som anger det vertikala avståndet mellan alla anslutningar på ritningssidan). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Anger riktningen för linjsprång på horisontella segment av dynamiska anslutningar på ritningssidan där du inte har angett en lokal hoppdirektion. |
| [getLineRouteExt()](#getLineRouteExt--) | Specificerar standardutseendet för alla anslutningar på en sida. |
| [getLineToLineX()](#getLineToLineX--) | Anger det minsta horisontella avståndet mellan dynamiska anslutningar på ritningssidan. |
| [getLineToLineY()](#getLineToLineY--) | Anger det minsta vertikala avståndet mellan dynamiska anslutningar på ritningssidan. |
| [getLineToNodeX()](#getLineToNodeX--) | Anger det minsta vertikala avståndet mellan dynamiska anslutningar och former på ritningssidan. |
| [getLineToNodeY()](#getLineToNodeY--) | Bestämmer den horisontella blockstorleken, det område där var och en av dina former måste få plats på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Anger riktningen för linjsprång på vertikala dynamiska anslutningar på ritningssidan där du inte har angett en lokal hoppdirektion. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Anger det minsta horisontella avståndet mellan dynamiska anslutningar och former på ritningssidan. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Indikerar om former på sidan kan delas automatiskt. |
| [getPlaceDepth()](#getPlaceDepth--) | Anger om placerbara former flyttar bort när användaren drar en placerbar form nära en annan placerbar form på ritningssidan. |
| [getPlaceFlip()](#getPlaceFlip--) | Anger hur placerbara former vänds och/eller roteras på en sida när former läggs ut med kommandot Lay Out Shapes i Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Anger routningsstil och riktning för alla dynamiska anslutningar på ritningssidan som inte har en lokal routningsstil. |
| [getPlowCode()](#getPlowCode--) | Bestämmer de dynamiska anslutningarna som du vill lägga till hopp för. |
| [getResizePage()](#getResizePage--) | Anger om sidan ska förstoras för att omfatta ritningen efter att en användare har valt Lay Out Shapes (Shapes menu). |
| [getRouteStyle()](#getRouteStyle--) | För en ritning som läggs ut automatiskt, anger metoden som ritningen analyseras med innan layouten skapas och bestämmer layouttypen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Bestämmer mängden vertikalt utrymme mellan former på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Bestämmer mängden vertikalt utrymme mellan former på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Anger hur former placeras på sidan när former läggs ut när en användare väljer Lay Out Shapes (menyn Form).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Bestämmer den vertikala blockstorleken, det område där var och en av dina former måste få plats på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Bestämmer mängden horisontellt utrymme mellan former på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Bestämmer vilken form som är förälder när du använder former med kontrollhandtag. Detta element anger beteendet för alla former på ritningssidan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Anger om placerbara former flyttar och anslutningar omdirigeras runt andra former och anslutningar på ritningssidan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Anger om Microsoft Visio placerar former baserat på ett internt sidrutnät när användaren väljer Lay Out Shapes (Shape menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Specificerar vilka dynamiska anslutningar som ska separeras om de ruttas ovanpå varandra.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Specificerar vilka dynamiska anslutningar som ska linjeras ovanpå varandra om de ruttas ovanpå varandra.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Specificerar linjesprångsstilen för alla anslutningar på ritningssidan som inte har en lokal linjesprångsstil.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Anger storleken på linjsprång på horisontella segment av dynamiska anslutningar på sidan, som en procentandel av värdet för elementet LineToLineX (som anger det horisontella avståndet mellan alla anslutningar på ritningssidan). Värdet för detta element varierar från 0 till 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Anger storleken på linjsprång på vertikala segment av dynamiska anslutningar på sidan, som en procentandel av värdet för elementet LineToLineY (som anger det vertikala avståndet mellan alla anslutningar på ritningssidan). Detta element kan ha ett värde från 0 till 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Anger riktningen för linjsprång på horisontella segment av dynamiska anslutningar på ritningssidan där du inte har angett en lokal hoppdirektion.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Specificerar standardutseendet för alla anslutningar på en sida.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Anger det minsta horisontella avståndet mellan dynamiska anslutningar på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Anger det minsta vertikala avståndet mellan dynamiska anslutningar på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Anger det minsta vertikala avståndet mellan dynamiska anslutningar och former på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Bestämmer den horisontella blockstorleken, det område där var och en av dina former måste få plats på ritningssidan när du använder Microsoft Visio för att placera former på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Anger riktningen för linjsprång på vertikala dynamiska anslutningar på ritningssidan där du inte har angett en lokal hoppdirektion.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Anger det minsta horisontella avståndet mellan dynamiska anslutningar och former på ritningssidan.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Indikerar om former på sidan kan delas automatiskt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Anger om placerbara former flyttar bort när användaren drar en placerbar form nära en annan placerbar form på ritningssidan.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Anger hur placerbara former vänds och/eller roteras på en sida när former placeras med kommandot Lay Out Shapes i Microsoft Visio. Följande hexadecimala värden är tillåtna.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Anger routningsstil och riktning för alla dynamiska anslutningar på ritningssidan som inte har en lokal routningsstil.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Bestämmer de dynamiska anslutningarna som du vill lägga till hopp för.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Anger om sidan ska förstoras för att omfatta ritningen efter att en användare har valt Lay Out Shapes (Shapes menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


För en ritning som läggs ut automatiskt, anger metoden som ritningen analyseras med innan layouten skapas och bestämmer layouttypen.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

