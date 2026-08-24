---
title: Varie
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene vari elementi di forme e gruppi, come quelli che controllano l'evidenziazione della selezione e la visibilità.
type: docs
weight: 247
url: /it/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Contiene vari elementi di forme e gruppi, come quelli che controllano l'evidenziazione della selezione e la visibilità.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Contiene una formula trigger generata da Microsoft Visio che determina se spostare il punto iniziale di una forma 1-D per mantenere la sua connessione a un'altra forma. |
| [getCalendar()](#getCalendar--) | Determina il calendario utilizzato per le proprietà personalizzate, i campi di testo e le formule degli elementi. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Contiene il testo del commento in formato stringa per una forma. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Determina la percentuale di scala di una forma quando viene rilasciata sulla pagina di disegno. |
| [getDynFeedback()](#getDynFeedback--) | Specifica il tipo di feedback visivo fornito agli utenti quando trascinano un connettore. |
| [getEndTrigger()](#getEndTrigger--) | Contiene una formula trigger generata da Microsoft Visio. |
| [getGlueType()](#getGlueType--) | Specifica se è consentito l'incollaggio dinamico (forma‑a‑forma) quando si collega a una forma. |
| [getHideText()](#getHideText--) | Nasconde il testo di una forma. |
| [getLangID()](#getLangID--) | Indica l'ID locale (LCID) della lingua in cui è stata inserita la formula della cella, il testo, la proprietà personalizzata o il commento. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Determina se le forme sono localizzate (se il loro elemento LangID viene reimpostato) quando vengono copiate tra documenti. |
| [getNoAlignBox()](#getNoAlignBox--) | Specifica se il rettangolo di selezione è visualizzato quando la forma è selezionata. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Specifica se le maniglie di controllo sono visualizzate quando la forma è selezionata. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Specifica se una forma si ridimensiona o ruota dinamicamente mentre l'utente la manipola. |
| [getNoObjHandles()](#getNoObjHandles--) | Specifica se le maniglie di selezione sono visualizzate quando la forma è selezionata. |
| [getNonPrinting()](#getNonPrinting--) | Specifica se una forma selezionata può essere stampata. |
| [getObjType()](#getObjType--) | Specifica se gli oggetti sono posizionabili o instradabili nei diagrammi quando si utilizza Microsoft Visio per disporre le forme sulla pagina di disegno. |
| [getShapeKeywords()](#getShapeKeywords--) | Contiene parole chiave di ricerca assegnate a forme master personalizzate. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Specifica se ricalcolare il rettangolo di selezione di una forma ogni volta che una maniglia di controllo viene spostata. |
| [getWalkPreference()](#getWalkPreference--) | Specifica se un'estremità di una forma 1-D si sposta verso un punto di connessione orizzontale o verticale sulla forma a cui è incollata, utilizzando la colla dinamica, quando la forma viene spostata in una posizione ambigua. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Specifica se la forma può essere aggiunta a un gruppo rilasciandola sul gruppo. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Indica se i valori delle celle specificate in una forma master sovrascrivono i valori (inclusi quelli locali) di una forma che viene sostituita durante un'operazione di sostituzione della forma. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/misc\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Contiene una formula trigger generata da Microsoft Visio che determina se spostare il punto iniziale di una forma 1-D per mantenere la sua connessione a un'altra forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Determina il calendario utilizzato per le proprietà personalizzate, i campi di testo e le formule degli elementi.

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


Contiene il testo del commento in formato stringa per una forma.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Determina la percentuale di scala di una forma quando viene rilasciata sulla pagina di disegno.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Specifica il tipo di feedback visivo fornito agli utenti quando trascinano un connettore.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Contiene una formula trigger generata da Microsoft Visio. Questa formula trigger determina se spostare il punto finale di una forma 1-D per mantenere la sua connessione a un'altra forma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Specifica se è consentito l'incollaggio dinamico (forma‑a‑forma) quando si collega a una forma.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Nasconde il testo per una forma. È possibile visualizzare il testo, modificare le proprietà e applicare stili al testo nel blocco di testo, anche se le modifiche non appariranno finché non si specifica l'elemento HideText a 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indica l'ID locale (LCID) della lingua in cui è stata inserita la formula della cella, il testo, la proprietà personalizzata o il commento.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Determina se le forme sono localizzate (se il loro elemento LangID viene reimpostato) quando vengono copiate tra documenti.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Specifica se il rettangolo di selezione è visualizzato quando la forma è selezionata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Specifica se le maniglie di controllo sono visualizzate quando la forma è selezionata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Specifica se una forma si ridimensiona o ruota dinamicamente mentre l'utente la manipola.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Specifica se le maniglie di selezione sono visualizzate quando la forma è selezionata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Specifica se una forma selezionata può essere stampata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Specifica se gli oggetti sono posizionabili o instradabili nei diagrammi quando si utilizza Microsoft Visio per disporre le forme sulla pagina di disegno.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Contiene parole chiave di ricerca assegnate a forme master personalizzate.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Specifica se ricalcolare il rettangolo di selezione di una forma ogni volta che una maniglia di controllo viene spostata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Specifica se un'estremità di una forma 1-D si sposta verso un punto di connessione orizzontale o verticale sulla forma a cui è incollata, utilizzando la colla dinamica, quando la forma viene spostata in una posizione ambigua.

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


Specifica se la forma può essere aggiunta a un gruppo rilasciandola sul gruppo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Indica se i valori delle celle specificate in una forma master sovrascrivono i valori (inclusi quelli locali) di una forma che viene sostituita durante un'operazione di sostituzione della forma.

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


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/misc\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

