---
title: Protezione
second_title: Riferimento API di Aspose.Diagram per Java
description: Il blocco aiuta a prevenire modifiche involontarie alla forma ma non impedisce a Microsoft Visio di ripristinare i valori in altre circostanze.
type: docs
weight: 312
url: /it/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Il blocco aiuta a prevenire modifiche involontarie alla forma ma non impedisce a Microsoft Visio di ripristinare i valori in altre circostanze. Inoltre non protegge dalle modifiche apportate nella finestra ShapeSheet.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getLockAspect()](#getLockAspect--) | Specifica se il rapporto d'aspetto della forma è bloccato. |
| [getLockBegin()](#getLockBegin--) | Specifica se il punto iniziale di una forma 1-D è bloccato in una posizione specifica. |
| [getLockCalcWH()](#getLockCalcWH--) | Specifica se il rettangolo di selezione di una forma è bloccato in modo che non possa essere ricalcolato quando un vertice viene modificato o il tipo di elemento viene cambiato nell'elemento Geom. |
| [getLockCrop()](#getLockCrop--) | Specifica se un oggetto esterno è bloccato contro il ritaglio con lo strumento Crop in Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Determina se l'utente può aggiungere, eliminare o modificare proprietà personalizzate nell'interfaccia utente (UI) utilizzando la finestra di dialogo Definisci proprietà personalizzate. |
| [getLockDelete()](#getLockDelete--) | Specifica se una forma è bloccata contro l'eliminazione. |
| [getLockEnd()](#getLockEnd--) | Specifica se il punto finale di una forma 1-D è bloccato in una posizione specifica. |
| [getLockFormat()](#getLockFormat--) | Specifica se la formattazione di una forma è bloccata in modo che non possa essere modificata. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Consente a una sottoforma di bloccare le modifiche di formattazione che vengono applicate a una forma di gruppo padre nell'interfaccia utente di Visio e che altrimenti si propagherebbero alle singole forme di gruppo. |
| [getLockGroup()](#getLockGroup--) | Specifica se un gruppo è bloccato in modo che non possa essere separato. |
| [getLockHeight()](#getLockHeight--) | Specifica se l'altezza della forma è bloccata. |
| [getLockMoveX()](#getLockMoveX--) | Specifica se la posizione orizzontale della forma è bloccata in modo che non possa essere spostata orizzontalmente. |
| [getLockMoveY()](#getLockMoveY--) | Specifica se la posizione verticale della forma è bloccata in modo che non possa essere spostata verticalmente. |
| [getLockRotate()](#getLockRotate--) | Specifica se la forma è bloccata contro la rotazione con lo strumento Rotazione o i comandi Ruota a sinistra o Ruota a destra in Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Specifica se il rettangolo di selezione di una forma è bloccato in modo che non possa essere ricalcolato quando un vertice viene modificato o il tipo di elemento viene cambiato nell'elemento Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | Specifica se il testo di una forma è bloccato in modo che non possa essere modificato. |
| [getLockThemeColors()](#getLockThemeColors--) | Impedisce agli utenti di applicare i colori del tema alla forma. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Impedisce agli utenti di applicare effetti tema alla forma. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Specifica se i vertici di una forma sono bloccati in modo che non possano essere modificati con alcuno strumento sulla barra degli strumenti. |
| [getLockWidth()](#getLockWidth--) | Specifica se la larghezza della forma è bloccata in modo che rimanga invariata quando la forma viene ridimensionata. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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


Un flag che indica se l'elemento è stato eliminato localmente. Un valore di 1 indica che l'elemento è stato eliminato localmente.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Specifica se le proporzioni della forma sono bloccate. Se bloccate, la forma può essere ridimensionata solo proporzionalmente; non può essere ridimensionata in una singola dimensione.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Specifica se il punto iniziale di una forma 1-D è bloccato in una posizione specifica.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Specifica se il rettangolo di selezione di una forma è bloccato in modo che non possa essere ricalcolato quando un vertice viene modificato o il tipo di elemento viene cambiato nell'elemento Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Specifica se un oggetto esterno è bloccato contro il ritaglio con lo strumento Crop in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Determina se l'utente può aggiungere, eliminare o modificare proprietà personalizzate nell'interfaccia utente (UI) utilizzando la finestra di dialogo Definisci proprietà personalizzate.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Specifica se una forma è bloccata contro l'eliminazione.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Specifica se il punto finale di una forma 1-D è bloccato in una posizione specifica.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Specifica se la formattazione di una forma è bloccata in modo che non possa essere modificata. In particolare, questo elemento protegge dalla modifica del testo, della linea e della formattazione di riempimento, o dalla modifica dell'elemento Style da cui la forma eredita.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Consente a una sottoforma di bloccare le modifiche di formattazione che vengono applicate a una forma di gruppo padre nell'interfaccia utente di Visio e che altrimenti si propagherebbero alle singole forme di gruppo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Specifica se un gruppo è bloccato in modo che non possa essere separato.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Specifica se l'altezza della forma è bloccata. Se bloccata, la sua altezza rimane invariata quando la forma viene ridimensionata.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Specifica se la posizione orizzontale della forma è bloccata in modo che non possa essere spostata orizzontalmente.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Specifica se la posizione verticale della forma è bloccata in modo che non possa essere spostata verticalmente.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Specifica se la forma è bloccata contro la rotazione con lo strumento Rotazione o i comandi Ruota a sinistra o Ruota a destra in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Specifica se il rettangolo di selezione di una forma è bloccato in modo che non possa essere ricalcolato quando un vertice viene modificato o il tipo di elemento viene cambiato nell'elemento Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Specifica se il testo di una forma è bloccato in modo che non possa essere modificato. Tuttavia, il testo può ancora essere formattato applicando uno stile, usando le opzioni Style nella scheda Font della finestra di dialogo Testo.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Impedisce agli utenti di applicare i colori del tema alla forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Impedisce agli utenti di applicare effetti tema alla forma.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Specifica se i vertici di una forma sono bloccati in modo che non possano essere modificati con alcuno strumento sulla barra degli strumenti.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Specifica se la larghezza della forma è bloccata in modo che rimanga invariata quando la forma viene ridimensionata.

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


Per la descrizione di questa proprietà, consultare [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

