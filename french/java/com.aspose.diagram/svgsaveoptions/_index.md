---
title: SVGSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en SVG.
type: docs
weight: 347
url: /fr/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en SVG.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document au format Aspose.Diagram.SaveFileFormat. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | Le chemin personnalisé de l'utilisateur (URL) enregistré dans le fichier SVG généré pour l'image. |
| [getDefaultFont()](#getDefaultFont--) | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne valeur de police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Paramètre pour le rendu du métafichier Emf. |
| [getEnlargePage()](#getEnlargePage--) | Spécifie si la page doit être agrandie. |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Définit s'il faut exporter les éléments rectangle sous forme de balise rect ou non. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Définit s'il faut exporter les formes guides ou non. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Définit s'il faut exporter la page cachée ou non. |
| [getPageIndex()](#getPageIndex--) | l'index basé sur zéro de la page à rendre. |
| [getPageSize()](#getPageSize--) | la taille de page pour les images générées. |
| [getQuality()](#getQuality--) | une valeur déterminant la qualité des images générées à appliquer uniquement lors de l'enregistrement des pages au format JPEG. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | si cette propriété est vraie, le SVG généré s'adaptera à la zone d'affichage. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel le document sera enregistré si cet objet d'options d'enregistrement est utilisé. |
| [getShapes()](#getShapes--) | formes à rendre. |
| [getWarningCallback()](#getWarningCallback--) | fonction de rappel d'avertissement. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Définit s'il faut exporter les commentaires ou non. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Définit s'il faut exporter l'échelle sous forme de matrice ou non. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Définit s'il faut enregistrer le motif de ligne personnalisé. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Définit s'il faut enregistrer l'image séparément. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Pour la description de cette propriété, veuillez consulter [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Pour la description de cette propriété, veuillez consulter [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Pour la description de cette propriété, veuillez consulter [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | Pour la description de cette propriété, veuillez consulter [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | Pour la description de cette propriété, veuillez consulter [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | Pour la description de cette propriété, veuillez consulter [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | Pour la description de cette propriété, veuillez consulter [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | Pour la description de cette propriété, veuillez consulter [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


Le chemin personnalisé (URL) de l'utilisateur enregistré dans le fichier SVG généré pour l'image. Si aucun chemin n'est défini par l'utilisateur, le répertoire actuel sera utilisé.

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Définit s'il faut exporter les éléments rectangle sous forme de balise rect ou non. La valeur par défaut est false.

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


l'index basé sur zéro de la page à rendre. La valeur par défaut est 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


la taille de page pour les images générées. Peut être [PageSize](../../com.aspose.diagram/pagesize) ou null. La valeur par défaut est null. Si PageSize est null, alors la taille de page pour l'image générée est obtenue à partir du diagramme source.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


une valeur déterminant la qualité des images générées à appliquer uniquement lors de l'enregistrement des pages au format Jpeg. La valeur par défaut est 100. N'a d'effet que lors de l'enregistrement au format JPEG. La valeur doit être comprise entre 0 et 100. La valeur par défaut est 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


si cette propriété est vraie, le SVG généré s'adaptera à la zone d'affichage.

**Returns:**
booléen
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Spécifie le format dans lequel le document sera enregistré si cet objet d'options d'enregistrement est utilisé.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


formes à rendre. Le nombre par défaut est 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Définit s'il faut exporter l'échelle sous forme de matrice ou non. La valeur par défaut est true.

**Returns:**
booléen
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Définit s'il faut enregistrer le motif de ligne personnalisé.

**Returns:**
booléen
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Définit s'il faut enregistrer l'image séparément.

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




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


Pour la description de cette propriété, veuillez consulter [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

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


Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Pour la description de cette propriété, veuillez consulter [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

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

