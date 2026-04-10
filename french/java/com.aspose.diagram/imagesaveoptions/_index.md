---
title: ImageSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en images.
type: docs
weight: 200
url: /fr/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer des images rendues au format Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ou Aspose.Diagram.SaveFileFormat. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Spécifie le niveau de qualité à utiliser lors du compositing. |
| [getContentZoom()](#getContentZoom--) | Ce paramètre est similaire à l'échelle, mais n'affecte pas la taille de l'image générée. |
| [getDefaultFont()](#getDefaultFont--) | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne valeur de police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Paramètre pour le rendu du métafichier Emf. |
| [getEnlargePage()](#getEnlargePage--) | Spécifie si la page doit être agrandie. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Définit s'il faut exporter les formes guides ou non. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Définit s'il faut exporter la page cachée ou non. |
| [getImageBrightness()](#getImageBrightness--) | la luminosité des images générées. |
| [getImageColorMode()](#getImageColorMode--) | le mode couleur des images générées. |
| [getImageContrast()](#getImageContrast--) | le contraste des images générées. |
| [getInterpolationMode()](#getInterpolationMode--) | Spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées. |
| [getJpegQuality()](#getJpegQuality--) | une valeur déterminant la qualité des images JPEG générées. |
| [getPageCount()](#getPageCount--) | le nombre de pages à rendre lors de l'enregistrement dans un fichier TIFF multipage. |
| [getPageIndex()](#getPageIndex--) | l'index basé sur zéro de la première page à rendre. |
| [getPageSize()](#getPageSize--) | la taille de page pour les images générées. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | une valeur spécifiant comment les pixels sont décalés pendant le rendu. |
| [getResolution()](#getResolution--) | la résolution des images générées, en points par pouce. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Spécifie si la zone d'enregistrement est identique au PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Spécifie si toutes les pages seront enregistrées en image ou uniquement le premier plan. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d'options d'enregistrement est utilisé. |
| [getScale()](#getScale--) | le facteur de zoom des images générées. |
| [getShapes()](#getShapes--) | formes à rendre. |
| [getSmoothingMode()](#getSmoothingMode--) | Spécifie si le lissage (anticrénelage) est appliqué aux lignes et courbes ainsi qu'aux bords des zones remplies. |
| [getTiffCompression()](#getTiffCompression--) | le type de compression à appliquer lors de l'enregistrement des images générées au format TIFF. |
| [getWarningCallback()](#getWarningCallback--) | fonction de rappel d'avertissement. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Définit s'il faut exporter les commentaires ou non. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Pour la description de cette propriété, veuillez consulter [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Pour la description de cette propriété, veuillez consulter [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Pour la description de cette propriété, veuillez consulter [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Pour la description de cette propriété, veuillez consulter [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Pour la description de cette propriété, veuillez consulter [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Pour la description de cette propriété, veuillez consulter [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Pour la description de cette propriété, veuillez consulter [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Pour la description de cette propriété, veuillez consulter [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Pour la description de cette propriété, veuillez consulter [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Pour la description de cette propriété, veuillez consulter [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Pour la description de cette propriété, veuillez consulter [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Pour la description de cette propriété, veuillez consulter [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Pour la description de cette propriété, veuillez consulter [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Pour la description de cette propriété, veuillez consulter [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Pour la description de cette propriété, veuillez consulter [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Pour la description de cette propriété, veuillez consulter [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer des images rendues au format Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ou Aspose.Diagram.SaveFileFormat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| saveFormat | int | Peut être Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ou Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Spécifie le niveau de qualité à utiliser lors du compositing. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Ce paramètre est similaire à l’échelle, mais n’affecte pas la taille de l’image générée. La valeur par défaut est 1,0. La valeur doit être supérieure à 0.

**Returns:**
flottant
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


la luminosité des images générées. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est 0,5. La valeur doit être comprise entre 0 et 1.

**Returns:**
flottant
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


le mode couleur des images générées. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


le contraste des images générées. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est 0,5. La valeur doit être comprise entre 0 et 1.

**Returns:**
flottant
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Spécifie l’algorithme utilisé lorsque les images sont redimensionnées ou pivotées. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


une valeur déterminant la qualité des images JPEG générées. N’a d’effet que lors de l’enregistrement au format JPEG. Utilisez cette propriété pour obtenir ou définir la qualité des images générées lors de l’enregistrement au format JPEG. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale. La valeur par défaut est 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


le nombre de pages à rendre lors de l’enregistrement dans un fichier TIFF multipage. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues.

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


une valeur spécifiant comment les pixels sont décalés pendant le rendu. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


la résolution des images générées, en points par pouce. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est 96.

**Returns:**
flottant
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Spécifie si la zone d’enregistrement est identique à celle du pdf. Si vrai – la zone rendue est identique au pdf. Si faux – la zone rendue est la valeur par défaut. La valeur par défaut est false.

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


Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d’options d’enregistrement est utilisé. Peut être Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ou Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


le facteur de zoom des images générées. La valeur par défaut est 1,0. La valeur doit être supérieure à 0.

**Returns:**
flottant
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


formes à rendre. Le nombre par défaut est 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Spécifie si le lissage (antialiasing) est appliqué aux lignes et courbes ainsi qu’aux bords des zones remplies. Cette propriété n’a d’effet que lors de l’enregistrement aux formats d’image raster. La valeur par défaut est Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


le type de compression à appliquer lors de l’enregistrement des images générées au format TIFF. N’a d’effet que lors de l’enregistrement au format TIFF. La valeur par défaut est Aspose.Diagram.Saving.TiffCompression.

**Returns:**
int
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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Pour la description de cette propriété, veuillez consulter [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Pour la description de cette propriété, veuillez consulter [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | flottant |  |

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


Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Pour la description de cette propriété, veuillez consulter [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | flottant |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Pour la description de cette propriété, veuillez consulter [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Pour la description de cette propriété, veuillez consulter [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | flottant |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Pour la description de cette propriété, veuillez consulter [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Pour la description de cette propriété, veuillez consulter [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Pour la description de cette propriété, veuillez consulter [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Pour la description de cette propriété, veuillez consulter [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | flottant |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Pour la description de cette propriété, veuillez consulter [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | flottant |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Pour la description de cette propriété, veuillez consulter [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Pour la description de cette propriété, veuillez consulter [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

