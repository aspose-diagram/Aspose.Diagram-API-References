---
title: Övrigt
second_title: Aspose.Diagram för Java API-referens
description: Innehåller olika element av former och grupper, såsom de som styr markeringsmarkering och synlighet.
type: docs
weight: 247
url: /sv/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Innehåller olika element för former och grupper, såsom de som styr markeringsframhävning och synlighet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Innehåller en triggerformel genererad av Microsoft Visio som avgör om startpunkten för en 1‑D‑form ska flyttas för att behålla dess anslutning till en annan form. |
| [getCalendar()](#getCalendar--) | Bestämmer den kalender som används för anpassade egenskaper, textfält och elementformler. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Innehåller kommentartexten i strängformat för en form. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Bestämmer den procentandel med vilken en form skalas när den släpps på ritningssidan. |
| [getDynFeedback()](#getDynFeedback--) | Anger vilken typ av visuell återkoppling som ges till användare när de drar en anslutning. |
| [getEndTrigger()](#getEndTrigger--) | Innehåller en triggerformel genererad av Microsoft Visio. |
| [getGlueType()](#getGlueType--) | Anger om dynamisk (form‑till‑form) limning är tillåten när man ansluter till en form. |
| [getHideText()](#getHideText--) | Döljer texten för en form. |
| [getLangID()](#getLangID--) | Anger språk‑ID (LCID) för det språk som cellformeln, texten, den anpassade egenskapen eller kommentaren angavs i. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Bestämmer om former lokalanpassas (om deras LangID‑element återställs) när de kopieras mellan dokument. |
| [getNoAlignBox()](#getNoAlignBox--) | Anger om markeringsrektangeln visas när formen är markerad. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Anger om kontrollhandtagen visas när formen är markerad. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Anger om en form dynamiskt ändrar storlek eller roteras när användaren manipulerar den. |
| [getNoObjHandles()](#getNoObjHandles--) | Anger om markeringshandtagen visas när formen är markerad. |
| [getNonPrinting()](#getNonPrinting--) | Anger om en markerad form kan skrivas ut. |
| [getObjType()](#getObjType--) | Anger om objekt kan placeras eller routas i diagram när du använder Microsoft Visio för att placera former på ritningssidan. |
| [getShapeKeywords()](#getShapeKeywords--) | Innehåller sökord som har tilldelats anpassade masterformer. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Anger om en forms markeringsrektangel ska beräknas om varje gång ett kontrollhandtag flyttas. |
| [getWalkPreference()](#getWalkPreference--) | Anger om en ändpunkt på en 1‑D-form flyttas till en horisontell eller vertikal anslutningspunkt på den form den är limmad till, med dynamisk limning, när formen flyttas till en tvetydig position. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Anger om formen kan läggas till i en grupp genom att släppa den på gruppen. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Indikerar om värdena i angivna celler i en masterform skriver över värdena (inklusive lokala värden) för en form som ersätts under en formutbytesoperation. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Innehåller en triggerformel genererad av Microsoft Visio som avgör om startpunkten för en 1‑D‑form ska flyttas för att behålla dess anslutning till en annan form.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Bestämmer den kalender som används för anpassade egenskaper, textfält och elementformler.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


Innehåller kommentartexten i strängformat för en form.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Bestämmer den procentandel med vilken en form skalas när den släpps på ritningssidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Anger vilken typ av visuell återkoppling som ges till användare när de drar en anslutning.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Innehåller en triggerformel genererad av Microsoft Visio. Denna triggerformel avgör om slutpunkten för en 1‑D‑form ska flyttas för att behålla dess anslutning till en annan form.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Anger om dynamisk (form‑till‑form) limning är tillåten när man ansluter till en form.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Döljer texten för en form. Du kan visa text, redigera egenskaper och tillämpa stilar på texten i textblocket, men ändringarna visas inte förrän du anger HideText element till 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Anger språk‑ID (LCID) för det språk som cellformeln, texten, den anpassade egenskapen eller kommentaren angavs i.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Bestämmer om former lokalanpassas (om deras LangID‑element återställs) när de kopieras mellan dokument.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Anger om markeringsrektangeln visas när formen är markerad.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Anger om kontrollhandtagen visas när formen är markerad.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Anger om en form dynamiskt ändrar storlek eller roteras när användaren manipulerar den.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Anger om markeringshandtagen visas när formen är markerad.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Anger om en markerad form kan skrivas ut.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Anger om objekt kan placeras eller routas i diagram när du använder Microsoft Visio för att placera former på ritningssidan.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Innehåller sökord som har tilldelats anpassade masterformer.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Anger om en forms markeringsrektangel ska beräknas om varje gång ett kontrollhandtag flyttas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Anger om en ändpunkt på en 1‑D-form flyttas till en horisontell eller vertikal anslutningspunkt på den form den är limmad till, med dynamisk limning, när formen flyttas till en tvetydig position.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


Anger om formen kan läggas till i en grupp genom att släppa den på gruppen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Indikerar om värdena i angivna celler i en masterform skriver över värdena (inklusive lokala värden) för en form som ersätts under en formutbytesoperation.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

