---
title: Layer
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die een enkele laag en de eigenschappen ervan voor een pagina definiëren.
type: docs
weight: 212
url: /nl/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Bevat elementen die een enkele laag en de eigenschappen ervan voor een pagina definiëren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Layer()](#Layer--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Specificeert of een laag actief is. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | De index van de kleur in de kleurtabel die wordt gebruikt om de laag weer te geven of een RGB-waarde die een aangepaste kleur specificeert die niet in de kleurtabel staat (bijvoorbeeld \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Bepaalt de mate van transparantie voor de tekstkleur van een laag of vorm, van 0 (volledig ondoorzichtig) tot 1 (volledig transparant). |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getGlue()](#getGlue--) | Specificeert of vormen die tot de laag behoren, kunnen worden vastgelijmd. |
| [getIX()](#getIX--) | De nulgebaseerde index van het element binnen zijn bovenliggende element. |
| [getLock()](#getLock--) | Specificeert of vormen die tot de laag behoren, vergrendeld zijn tegen selectie of bewerking. |
| [getName()](#getName--) | Naam‑element specificeert de naam van een laag. |
| [getNameUniv()](#getNameUniv--) | Specificeert de universele naam van een laag. |
| [getPrint()](#getPrint--) | Specificeert of vormen die tot de laag behoren, worden afgedrukt wanneer de tekening wordt afgedrukt. |
| [getSnap()](#getSnap--) | Specificeert of andere vormen kunnen snapen op vormen die aan de laag zijn toegewezen. |
| [getStatus()](#getStatus--) | Specificeert of de laag een geldige laag voor een document is. |
| [getVisible()](#getVisible--) | Specificeert of vormen die tot de laag behoren, zichtbaar zijn op de tekenpagina. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Een vlag die aangeeft of het element lokaal is gecontroleerd. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Voor de beschrijving van deze eigenschap, zie [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Constructor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Specificeert of een laag actief is. Vormen die niet vooraf aan lagen zijn toegewezen, worden toegewezen aan de actieve laag(en) wanneer ze op de tekenpagina worden geplaatst.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


De index van de kleur in de kleurtabel die wordt gebruikt om de laag weer te geven of een RGB-waarde die een aangepaste kleur specificeert die niet in de kleurtabel staat (bijvoorbeeld \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Bepaalt de mate van transparantie voor de tekstkleur van een laag of vorm, van 0 (volledig ondoorzichtig) tot 1 (volledig transparant).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Specificeert of vormen die tot de laag behoren, kunnen worden vastgelijmd.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


De nulgebaseerde index van het element binnen zijn bovenliggende element.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Specificeert of vormen die tot de laag behoren, vergrendeld zijn tegen selectie of bewerking.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Naam‑element specificeert de naam van een laag.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Specificeert de universele naam van een laag.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Specificeert of vormen die tot de laag behoren, worden afgedrukt wanneer de tekening wordt afgedrukt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Specificeert of andere vormen kunnen snapen op vormen die aan de laag zijn toegewezen. Vormen die aan de laag zijn toegewezen, kunnen snapen op andere vormen, maar andere vormen kunnen niet op hen snapen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Specificeert of de laag een geldige laag voor een document is.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Specificeert of vormen die tot de laag behoren, zichtbaar zijn op de tekenpagina.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Een vlag die aangeeft of het element lokaal is gecontroleerd. Een waarde van 1 geeft aan dat het element lokaal is gecontroleerd.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Voor de beschrijving van deze eigenschap, zie [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/layer\#getIX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

