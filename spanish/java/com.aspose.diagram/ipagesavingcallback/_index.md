---
title: IPageSavingCallback
second_title: Referencia de API de Aspose.Diagram para Java
description: Controlar/Indicar el progreso del proceso de guardado de la página.
type: docs
weight: 456
url: /es/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

Controlar/Indicar el progreso del proceso de guardado de la página.
## Métodos

| Método | Descripción |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/Indicar que una página finaliza para ser salida. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/Indicar que una página comienza para ser salida. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/Indicar que una página finaliza para ser salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | Información para una página finaliza el proceso de guardado. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/Indicar que una página comienza para ser salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | Información para una página inicia el proceso de guardado. |

