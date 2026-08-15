---
title: HTMLSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en HTML.
type: docs
weight: 187
url: /fr/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en HTML.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document au format Aspose.Diagram.SaveFileFormat. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne valeur de police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Paramètre pour le rendu du métafichier Emf. |
| [getEnlargePage()](#getEnlargePage--) | Spécifie si la page doit être agrandie. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Définit s'il faut exporter les formes guides ou non. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Définit s'il faut exporter la page cachée ou non. |
| [getPageCount()](#getPageCount--) | le nombre de pages à rendre en HTML. |
| [getPageIndex()](#getPageIndex--) | l'index basé sur zéro de la première page à rendre. |
| [getPageSize()](#getPageSize--) | la taille de page pour les images générées. |
| [getResolution()](#getResolution--) | la résolution pour le HTML généré, en points par pouce. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Indique s'il faut enregistrer le HTML en un seul fichier. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Spécifie si toutes les pages seront enregistrées en image ou uniquement le premier plan. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d'options d'enregistrement est utilisé. |
| [getSaveTitle()](#getSaveTitle--) | Définit s'il faut exporter le titre ou non. |
| [getSaveToolBar()](#getSaveToolBar--) | Spécifie si la barre d'outils doit être enregistrée. La valeur par défaut est true. |
| [getShapes()](#getShapes--) | formes à rendre. |
| [getStreamProvider()](#getStreamProvider--) | le IStreamProvider pour l'exportation des objets. |
| [getTitle()](#getTitle--) | le titre du diagramme à rendre en HTML. |
| [getWarningCallback()](#getWarningCallback--) | fonction de rappel d'avertissement. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Définit s'il faut exporter les commentaires ou non. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Pour la description de cette propriété, veuillez consulter [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Pour la description de cette propriété, veuillez consulter [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Pour la description de cette propriété, veuillez consulter [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | Pour la description de cette propriété, veuillez consulter [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Pour la description de cette propriété, veuillez consulter [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
```


Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document au format Aspose.Diagram.SaveFileFormat.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| saveFormat | int | Le Aspose.Diagram.SaveFileFormat pour lequel créer un objet d'options d'enregistrement. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. Définissez la DefaultFont, telle que MingLiu ou MS Gothic, pour afficher ces caractères.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Paramètre pour le rendu du fichier métadonnées Emf. Les fichiers métadonnées EMF identifiés comme "EMF+ Dual" peuvent contenir à la fois des enregistrements EMF+ et des enregistrements EMF. Chaque type d'enregistrement peut être utilisé pour rendre l'image, uniquement les enregistrements EMF+, ou uniquement les enregistrements EMF. Lorsque EmfPlusPrefer est défini, les enregistrements EMF+ seront analysés, sinon seuls les enregistrements EMF seront analysés. La valeur par défaut est EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Spécifie si la page doit être agrandie. Si vrai - agrandir la page. Si faux - ne pas agrandir la page. La valeur par défaut est vraie.

**Returns:**
booléen
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Définit s'il faut exporter les formes guides ou non. La valeur par défaut est vraie.

**Returns:**
booléen
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Définit s'il faut exporter la page cachée ou non. La valeur par défaut est vraie.

**Returns:**
booléen
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


le nombre de pages à rendre en HTML. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


l'index basé sur zéro de la première page à rendre. La valeur par défaut est 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


la taille de page pour les images générées. Peut être [PageSize](../../com.aspose.diagram/pagesize) ou null. La valeur par défaut est null. Si PageSize est null, alors la taille de page pour l'image générée est obtenue à partir du diagramme source.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


la résolution pour le html généré, en points par pouce. Cette propriété n’a d’effet que lors de l’enregistrement au format html. La valeur par défaut est 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Indique s’il faut enregistrer le html en un seul fichier. La valeur par défaut est false. S’il y a plusieurs pages, ces pages et les autres ressources doivent être enregistrées dans des fichiers séparés. Dans certains scénarios, l’utilisateur peut avoir besoin d’obtenir un seul fichier résultant, par exemple pour faciliter le transfert. Dans ce cas, l’utilisateur peut définir cette propriété sur true.

**Returns:**
booléen
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Spécifie si toutes les pages seront enregistrées dans l'image ou seulement le premier plan. Si true - seules les pages de premier plan sont rendues (avec l’arrière‑plan si présent). Si false - les pages de premier plan sont rendues (avec l’arrière‑plan si présent) puis les pages d’arrière‑plan vides. Peut renvoyer true uniquement lorsque PageCount > 1. La valeur par défaut est false.

**Returns:**
booléen
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d’options d’enregistrement est utilisé. Ne peut être que Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Définit s’il faut exporter le titre ou non. La valeur par défaut est true.

**Returns:**
booléen
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Spécifie si la barre d'outils doit être enregistrée. La valeur par défaut est true.

**Returns:**
booléen
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


formes à rendre. Le nombre par défaut est 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


le IStreamProvider pour l'exportation des objets.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


le titre du diagramme à rendre en HTML. Si Title est null, Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) sera utilisé comme titre. Si Diagram.DocumentProperties.Title est null ou vide, le nom de fichier du diagramme sera utilisé comme titre.

**Returns:**
java.lang.String
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


fonction de rappel d'avertissement.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


Définit s’il faut exporter les commentaires ou non. La valeur par défaut est false.

**Returns:**
booléen
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Pour la description de cette propriété, veuillez consulter [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Pour la description de cette propriété, veuillez consulter [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Pour la description de cette propriété, veuillez consulter [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Pour la description de cette propriété, veuillez consulter [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

