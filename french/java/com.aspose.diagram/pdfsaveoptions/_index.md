---
title: PdfSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en PDF.
type: docs
weight: 281
url: /fr/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en PDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document au format Aspose.Diagram.SaveFileFormat. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crée un objet d'options d'enregistrement d'une classe adaptée au format d'enregistrement spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Niveau de conformité souhaité pour le document PDF généré. |
| [getDefaultFont()](#getDefaultFont--) | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la bonne valeur de police ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de blocs dans le PDF, l'image ou le XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Paramètre pour le rendu du métafichier Emf. |
| [getEncryptionDetails()](#getEncryptionDetails--) | des détails de chiffrement. |
| [getEnlargePage()](#getEnlargePage--) | Spécifie si la page doit être agrandie. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Définit s'il faut exporter les formes guides ou non. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Définit s'il faut exporter la page cachée ou non. |
| [getHorizontalResolution()](#getHorizontalResolution--) | la résolution horizontale des images générées, en points par pouce. |
| [getJpegQuality()](#getJpegQuality--) | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). |
| [getPageCount()](#getPageCount--) | le nombre de pages à rendre dans le PDF. |
| [getPageIndex()](#getPageIndex--) | l'index basé sur zéro de la première page à rendre. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Contrôler/Indiquer la progression du processus d'enregistrement de la page. |
| [getPageSize()](#getPageSize--) | la taille de page pour les images générées. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Spécifie si toutes les pages seront enregistrées en image ou uniquement le premier plan. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel les pages du diagramme rendu seront enregistrées si cet objet d'options d'enregistrement est utilisé. |
| [getShapes()](#getShapes--) | formes à rendre. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Définit si le diagramme doit être divisé en plusieurs pages selon les paramètres de la page. |
| [getTextCompression()](#getTextCompression--) | Spécifie le type de compression à utiliser pour tous les flux de contenu, sauf les images. |
| [getVerticalResolution()](#getVerticalResolution--) | la résolution verticale des images générées, en points par pouce. |
| [getWarningCallback()](#getWarningCallback--) | fonction de rappel d'avertissement. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Définit s'il faut exporter les commentaires ou non. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | Pour la description de cette propriété, veuillez consulter [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Pour la description de cette propriété, veuillez consulter [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | Pour la description de cette propriété, veuillez consulter [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Pour la description de cette propriété, veuillez consulter [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Pour la description de cette propriété, veuillez consulter [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Pour la description de cette propriété, veuillez consulter [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Pour la description de cette propriété, veuillez consulter [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | Pour la description de cette propriété, veuillez consulter [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | Pour la description de cette propriété, veuillez consulter [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | Pour la description de cette propriété, veuillez consulter [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Pour la description de cette propriété, veuillez consulter [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Niveau de conformité souhaité pour le document PDF généré. La valeur par défaut est PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


des détails de chiffrement. Si non défini, aucun chiffrement ne sera effectué.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


la résolution horizontale des images générées, en points par pouce. S'applique à la méthode de génération d'image sauf pour les images au format Emf. La valeur par défaut est 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). La valeur par défaut est 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


le nombre de pages à rendre dans le PDF. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


l'index basé sur zéro de la première page à rendre. La valeur par défaut est 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Contrôler/Indiquer la progression du processus d'enregistrement de la page.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


la taille de page pour les images générées. Peut être [PageSize](../../com.aspose.diagram/pagesize) ou null. La valeur par défaut est null. Si PageSize est null, alors la taille de page pour l'image générée est obtenue à partir du diagramme source.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


formes à rendre. Le nombre par défaut est 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Définit si le diagramme doit être divisé en plusieurs pages selon les paramètres de la page. La valeur par défaut est false.

**Returns:**
booléen
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Spécifie le type de compression à utiliser pour tous les flux de contenu, sauf les images. La valeur par défaut est PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


la résolution verticale des images générées, en points par pouce. S'applique à la méthode de génération d'image sauf pour les images au format Emf. La valeur par défaut est 96.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


Pour la description de cette propriété, veuillez consulter [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


Pour la description de cette propriété, veuillez consulter [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


Pour la description de cette propriété, veuillez consulter [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


Pour la description de cette propriété, veuillez consulter [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Pour la description de cette propriété, veuillez consulter [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


Pour la description de cette propriété, veuillez consulter [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


Pour la description de cette propriété, veuillez consulter [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


Pour la description de cette propriété, veuillez consulter [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

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

