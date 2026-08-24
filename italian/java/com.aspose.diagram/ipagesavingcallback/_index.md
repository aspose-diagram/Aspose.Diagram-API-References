---
title: IPageSavingCallback
second_title: Riferimento API di Aspose.Diagram per Java
description: Controlla/Indica l'avanzamento del processo di salvataggio della pagina.
type: docs
weight: 456
url: /it/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Controlla/Indica l'avanzamento del processo di salvataggio della pagina.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Controllo/Indicare che una pagina termina per l'output. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Controllo/Indicare che una pagina inizia per l'output. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Controllo/Indicare che una pagina termina per l'output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Informazioni per una pagina terminano il processo di salvataggio. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Controllo/Indicare che una pagina inizia per l'output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Informazioni per una pagina avviano il processo di salvataggio. |

