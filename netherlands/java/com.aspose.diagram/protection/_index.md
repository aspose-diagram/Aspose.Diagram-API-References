---
title: Bescherming
second_title: Aspose.Diagram voor Java API-referentie
description: Vergrendeling helpt onbedoelde wijzigingen aan de vorm te voorkomen, maar voorkomt niet dat Microsoft Visio waarden reset in andere omstandigheden.
type: docs
weight: 312
url: /nl/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Vergrendelen helpt onbedoelde wijzigingen aan de vorm te voorkomen, maar voorkomt niet dat Microsoft Visio waarden onder andere omstandigheden opnieuw instelt. Het beschermt ook niet tegen wijzigingen die in het ShapeSheet‑venster worden aangebracht.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getLockAspect()](#getLockAspect--) | Specificeert of de beeldverhouding van de vorm vergrendeld is. |
| [getLockBegin()](#getLockBegin--) | Specificeert of het beginpunt van een 1-D-vorm vergrendeld is op een specifieke locatie. |
| [getLockCalcWH()](#getLockCalcWH--) | Specificeert of het selectierechthoek van een vorm vergrendeld is zodat deze niet opnieuw kan worden berekend wanneer een vertex wordt bewerkt of een elementtype wordt gewijzigd in het Geom-element. |
| [getLockCrop()](#getLockCrop--) | Specificeert of een extern object vergrendeld is tegen bijsnijden met het Crop-gereedschap in Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Bepaalt of de gebruiker aangepaste eigenschappen kan toevoegen, verwijderen of wijzigen in de gebruikersinterface (UI) via het dialoogvenster Definieer aangepaste eigenschappen. |
| [getLockDelete()](#getLockDelete--) | Specificeert of een vorm vergrendeld is tegen verwijdering. |
| [getLockEnd()](#getLockEnd--) | Specificeert of het eindpunt van een 1-D-vorm vergrendeld is op een specifieke locatie. |
| [getLockFormat()](#getLockFormat--) | Specificeert of de opmaak van een vorm vergrendeld is zodat deze niet kan worden gewijzigd. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Staat een subvorm toe om opmaakwijzigingen te blokkeren die op een bovenliggende groepsvorm worden toegepast in de Visio-gebruikersinterface en anders naar individuele groepsvormen zouden doorstromen. |
| [getLockGroup()](#getLockGroup--) | Specificeert of een groep vergrendeld is zodat deze niet kan worden ontgroepeerd. |
| [getLockHeight()](#getLockHeight--) | Specificeert of de hoogte van de vorm vergrendeld is. |
| [getLockMoveX()](#getLockMoveX--) | Specificeert of de horizontale positie van de vorm vergrendeld is zodat deze niet horizontaal kan worden verplaatst. |
| [getLockMoveY()](#getLockMoveY--) | Specificeert of de verticale positie van de vorm vergrendeld is zodat deze niet verticaal kan worden verplaatst. |
| [getLockRotate()](#getLockRotate--) | Specificeert of de vorm vergrendeld is tegen draaien met het Rotatie-gereedschap of de opdrachten Roteren naar links of Roteren naar rechts in Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Specificeert of het selectierechthoek van een vorm vergrendeld is zodat deze niet opnieuw kan worden berekend wanneer een vertex wordt bewerkt of een elementtype wordt gewijzigd in het Geom-element. |
| [getLockTextEdit()](#getLockTextEdit--) | Specificeert of de tekst van een vorm vergrendeld is zodat deze niet kan worden bewerkt. |
| [getLockThemeColors()](#getLockThemeColors--) | Voorkomt dat gebruikers themakleuren op de vorm toepassen. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Voorkomt dat gebruikers themaeffecten op de vorm toepassen. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Specificeert of de hoekpunten van een vorm vergrendeld zijn zodat ze niet bewerkt kunnen worden met enige gereedschappen op de werkbalk. |
| [getLockWidth()](#getLockWidth--) | Specificeert of de breedte van de vorm vergrendeld is zodat deze ongewijzigd blijft wanneer de vorm wordt vergroot of verkleind. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/protection\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Specificeert of de beeldverhouding van de vorm vergrendeld is. Indien vergrendeld, kan de vorm alleen proportioneel worden geschaald; hij kan niet in één dimensie worden aangepast.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Specificeert of het beginpunt van een 1-D-vorm vergrendeld is op een specifieke locatie.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Specificeert of het selectierechthoek van een vorm vergrendeld is zodat deze niet opnieuw kan worden berekend wanneer een vertex wordt bewerkt of een elementtype wordt gewijzigd in het Geom-element.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Specificeert of een extern object vergrendeld is tegen bijsnijden met het Crop-gereedschap in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Bepaalt of de gebruiker aangepaste eigenschappen kan toevoegen, verwijderen of wijzigen in de gebruikersinterface (UI) via het dialoogvenster Definieer aangepaste eigenschappen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Specificeert of een vorm vergrendeld is tegen verwijdering.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Specificeert of het eindpunt van een 1-D-vorm vergrendeld is op een specifieke locatie.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Specificeert of de opmaak van een vorm vergrendeld is zodat deze niet kan worden gewijzigd. Specifiek beschermt dit element tegen het wijzigen van tekst-, lijn- en vulopmaak, of tegen het wijzigen van welk Stijl-element de vorm erft.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Staat een subvorm toe om opmaakwijzigingen te blokkeren die op een bovenliggende groepsvorm worden toegepast in de Visio-gebruikersinterface en anders naar individuele groepsvormen zouden doorstromen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Specificeert of een groep vergrendeld is zodat deze niet kan worden ontgroepeerd.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Specificeert of de hoogte van de vorm vergrendeld is. Indien vergrendeld, blijft de hoogte ongewijzigd wanneer de vorm wordt vergroot of verkleind.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Specificeert of de horizontale positie van de vorm vergrendeld is zodat deze niet horizontaal kan worden verplaatst.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Specificeert of de verticale positie van de vorm vergrendeld is zodat deze niet verticaal kan worden verplaatst.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Specificeert of de vorm vergrendeld is tegen draaien met het Rotatie-gereedschap of de opdrachten Roteren naar links of Roteren naar rechts in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Specificeert of het selectierechthoek van een vorm vergrendeld is zodat deze niet opnieuw kan worden berekend wanneer een vertex wordt bewerkt of een elementtype wordt gewijzigd in het Geom-element.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Specificeert of de tekst van een vorm vergrendeld is zodat deze niet bewerkt kan worden. De tekst kan echter nog steeds worden opgemaakt door een stijl toe te passen, met behulp van de Stijl-opties op het tabblad Lettertype van het Tekst-dialoogvenster.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Voorkomt dat gebruikers themakleuren op de vorm toepassen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Voorkomt dat gebruikers themaeffecten op de vorm toepassen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Specificeert of de hoekpunten van een vorm vergrendeld zijn zodat ze niet bewerkt kunnen worden met enige gereedschappen op de werkbalk.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Specificeert of de breedte van de vorm vergrendeld is zodat deze ongewijzigd blijft wanneer de vorm wordt vergroot of verkleind.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

