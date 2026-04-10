---
title: PageProps
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat cellen die paginaparameters regelen, zoals de paginabreedte, -hoogte en schaal.
type: docs
weight: 268
url: /nl/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Bevat cellen die paginagegevens regelen, zoals de paginabreedte, -hoogte en schaal.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Bepaalt of de tekenpagina automatisch wordt aangepast om het diagram te passen. |
| [getDrawingScale()](#getDrawingScale--) | Geeft de waarde van de tekeneenheid weer in de huidige tekenschaling. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Specificeert het type tekenschaling dat voor een pagina moet worden gebruikt. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Specificeert de tekenafmeting van een pagina. |
| [getInhibitSnap()](#getInhibitSnap--) | Specificeert of de vormen op een voorgrondpagina vastklikken op andere objecten op de pagina en vormen op de achtergrondpagina. |
| [getPageHeight()](#getPageHeight--) | Specificeert de hoogte van de pagina in tekeneenheden. |
| [getPageScale()](#getPageScale--) | Specificeert de waarde van de standaard paginaneenheid in de huidige tekenschaling. |
| [getPageWidth()](#getPageWidth--) | Specificeert de breedte van de pagina in tekeneenheden. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Bevat een getal dat de hoek van de schuine richting aangeeft wanneer het standaard paginashaduwtype wordt toegepast. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Specificeert de afstand in paginaneenheden waarmee de slagschaduw van een vorm horizontaal wordt verschoven ten opzichte van de vorm. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Specificeert de afstand in paginaneenheden waarmee de slagschaduw van een vorm verticaal wordt verschoven ten opzichte van de vorm. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Specificeert het percentage waarmee de slagschaduw van een vorm wordt vergroot of verkleind. |
| [getShdwType()](#getShdwType--) | Geeft het standaard schaduwtype voor een pagina aan. |
| [getUIVisibility()](#getUIVisibility--) | Bepaalt of de paginanaam zichtbaar is in de gebruikersinterface (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie alstublieft [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Bepaalt of de tekenpagina automatisch wordt aangepast om het diagram te passen.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Geeft de waarde van de tekeneenheid weer in de huidige tekenschaling. De tekenschaling voor de pagina is de verhouding tussen de paginaneenheid die in het PageScale‑element staat en de tekeneenheid. De eenheden van dit element bepalen de standaard lengteenheden (DL) voor de pagina.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Specificeert het type tekenschaling dat voor een pagina moet worden gebruikt.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Specificeert de tekenafmeting van een pagina.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Specificeert of de vormen op een voorgrondpagina vastklikken op andere objecten op de pagina en vormen op de achtergrondpagina.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Specificeert de hoogte van de pagina in tekeneenheden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Specificeert de waarde van de standaard paginaneenheid in de huidige tekenschaling. De tekenschaling voor de pagina is de verhouding tussen de paginaneenheid in het PageScale‑element en de tekeneenheid die wordt weergegeven in het DrawingScale‑element.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Specificeert de breedte van de pagina in tekeneenheden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Bevat een getal dat de hoek van de schuine richting aangeeft wanneer het standaard paginashaduwtype wordt toegepast.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Specificeert de afstand in paginaneenheden waarmee de slagschaduw van een vorm horizontaal wordt verschoven ten opzichte van de vorm.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Specificeert de afstand in paginaneenheden waarmee de slagschaduw van een vorm verticaal wordt verschoven ten opzichte van de vorm.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Specificeert het percentage waarmee de slagschaduw van een vorm wordt vergroot of verkleind.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Geeft het standaard schaduwtype voor een pagina aan.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Bepaalt of de paginanaam zichtbaar is in de gebruikersinterface (UI). Een waarde van één geeft aan dat de pagina niet zichtbaar is; een waarde van nul geeft aan dat de pagina wel zichtbaar is.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


Voor de beschrijving van deze eigenschap, zie alstublieft [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

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

