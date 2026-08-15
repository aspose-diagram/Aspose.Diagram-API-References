---
title: PrintSaveOptions
second_title: Référence API d'Aspose.Diagram pour Java
description: Permet de spécifier des options supplémentaires lors de l'impression du diagramme.
type: docs
weight: 308
url: /fr/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Permet de spécifier des options supplémentaires lors de l'impression du diagramme.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Initialise une nouvelle instance de cette classe |
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
| [getPageCount()](#getPageCount--) | le nombre de pages à rendre lors de l'enregistrement dans un fichier multipage. |
| [getPageSize()](#getPageSize--) | la taille de page pour les images générées. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Spécifie si toutes les pages seront imprimées ou uniquement le premier plan. |
| [getSaveFormat()](#getSaveFormat--) | Spécifie le format dans lequel le document sera enregistré si cet objet d'options d'enregistrement est utilisé. |
| [getShapes()](#getShapes--) | formes à rendre. |
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
| [setPageCount(int value)](#setPageCount-int-) | Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Pour la description de cette propriété, veuillez consulter [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Pour la description de cette propriété, veuillez consulter [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Pour la description de cette propriété, veuillez consulter [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Initialise une nouvelle instance de cette classe

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


le nombre de pages à rendre lors de l'enregistrement dans un fichier multipage. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront imprimées.

**Returns:**
int
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


Spécifie si toutes les pages seront imprimées ou uniquement le premier plan. Si vrai – seules les pages de premier plan sont imprimées (avec l'arrière-plan si présent). Si faux – les pages de premier plan sont imprimées (avec l'arrière-plan si présent) suivies de pages d'arrière-plan vides. Peut renvoyer vrai uniquement lorsque PageCount > 1. La valeur par défaut est false.

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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Pour la description de cette propriété, veuillez consulter [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

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

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

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

