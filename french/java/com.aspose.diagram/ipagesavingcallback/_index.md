---
title: IPageSavingCallback
second_title: Référence API d'Aspose.Diagram pour Java
description: Contrôler/Indiquer la progression du processus d'enregistrement de la page.
type: docs
weight: 456
url: /fr/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Contrôler/Indiquer la progression du processus d'enregistrement de la page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Contrôle/Indique qu'une page se termine pour être sortie. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Contrôle/Indique qu'une page commence à être sortie. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Contrôle/Indique qu'une page se termine pour être sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Informations pour une page terminent le processus d'enregistrement. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Contrôle/Indique qu'une page commence à être sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Informations pour une page démarrent le processus d'enregistrement. |

