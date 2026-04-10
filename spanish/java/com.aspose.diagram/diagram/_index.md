---
title: Diagrama
second_title: Referencia de API de Aspose.Diagram para Java
description: Elemento raíz de la jerarquía de objetos de Visio.
type: docs
weight: 117
url: /es/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Elemento raíz de la jerarquía de objetos de Visio.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Constructor público de clase, carga el diagrama desde el archivo. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Constructor público de clase, carga el diagrama desde el flujo. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Constructor público de clase, carga el diagrama desde el flujo usando un formato predefinido. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Constructor público de clase, carga el diagrama desde el flujo usando opciones de carga de archivo predefinidas. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Constructor público de clase, carga el diagrama desde el archivo usando un formato predefinido. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Constructor público de clase, carga el diagrama desde el archivo usando opciones de carga de archivo predefinidas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Agrega master al diagrama desde el diagrama fuente por el Nombre o NameU del master. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Agrega master al diagrama desde el flujo de plantilla por el ID del master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Agrega master al diagrama desde el flujo de plantilla por el Nombre o NameU del master. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Agrega master al diagrama desde el archivo de plantilla por el ID del master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Agrega master al diagrama desde el archivo de plantilla por el Nombre o NameU del master. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Añade una forma creada por el maestro a una página específica. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Añade una forma creada por el maestro en la página con PinX, PinY, Width y Height definidos. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Añade una forma creada por el maestro en la página con PinX y PinY definidos. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Combina otro objeto Diagram. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Copia Theme de un Diagram fuente. |
| [dispose()](#dispose--) | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Exporta el diagrama desde el flujo vsd al formato de flujo vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Exporta el diagrama desde el flujo vsd al formato de archivo \*.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Exporta el diagrama desde el archivo vsd al formato de flujo vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Exporta el diagrama desde vsd a formato vdw. |
| [getActivePage()](#getActivePage--) | Especifica la página activa |
| [getBuildnum()](#getBuildnum--) | El número de compilación de la instancia de Visio utilizada para crear el documento. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Contiene la tabla de colores del documento. |
| [getDataConnections()](#getDataConnections--) | Contiene los elementos DataConnection del documento. |
| [getDataRecordSets()](#getDataRecordSets--) | La colección de objetos DataRecordset asociados a un objeto Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Obtener la ruta de la carpeta de fuentes predeterminadas |
| [getDocLangID()](#getDocLangID--) | El ID único del idioma de la interfaz de usuario que el usuario ha especificado en las Preferencias de idioma de Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | Contiene elementos de propiedades del documento, como el título del documento, el autor, etc. |
| [getDocumentSettings()](#getDocumentSettings--) | Contiene elementos que especifican la configuración del documento. |
| [getDocumentSheet()](#getDocumentSheet--) | Especifica la estructura ShapeSheet de un documento. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Contiene una hoja de ruta de correo electrónico MAPI codificada en MIME (Multipurpose Internet Mail Extensions) para el documento. |
| [getEventItems()](#getEventItems--) | Contiene un elemento EventItem para cada evento al que un objeto debe responder. |
| [getFonts()](#getFonts--) | Contiene una colección de elementos Font |
| [getHeaderFooter()](#getHeaderFooter--) | Contiene elementos para el encabezado y pie de página de un documento. |
| [getInterruptMonitor()](#getInterruptMonitor--) | el monitor de interrupciones. |
| [getKey()](#getKey--) | Indica si el documento ha sido modificado fuera de Visio. |
| [getMasters()](#getMasters--) | Colección de objetos Master. |
| [getMetric()](#getMetric--) | Indica si se deben usar unidades métricas en el dibujo. |
| [getPages()](#getPages--) | Colección de objetos Page. |
| [getRibbonX()](#getRibbonX--) | La cadena XML del Ribbon que se pasa al documento para personalizar la interfaz de usuario del ribbon. |
| [getSolutionXMLs()](#getSolutionXMLs--) | Valor XML. |
| [getStart()](#getStart--) | Indica si el documento ha sido modificado fuera de Visio. |
| [getStyleSheets()](#getStyleSheets--) | Colección de objetos StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | Obtener estilos no utilizados |
| [getUserCustomUI()](#getUserCustomUI--) | La cadena XML del Ribbon que se pasa al documento para personalizar la barra de acceso rápido o el ribbon. |
| [getValidation()](#getValidation--) | Almacena información sobre la validación del diagrama para el documento. |
| [getVbProjectData()](#getVbProjectData--) | Contiene los datos del proyecto Microsoft Visual Basic for Applications en formato codificado MIME (Multipurpose Internet Mail Extensions). |
| [getVbaProject()](#getVbaProject--) | Obtiene el VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | El número de versión de la instancia de Visio. |
| [getWindows()](#getWindows--) | Contiene los elementos Window para un documento. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Indica si este diagrama tiene información oculta. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Distribuye las formas y/o redirige los conectores para todas las páginas del diagrama. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Imprime todo el documento en la impresora especificada,usando el controlador de impresión estándar (sin interfaz de usuario). |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Imprime todo el documento en la impresora especificada,usando el controlador de impresión estándar (sin interfaz de usuario). |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Imprime el documento,usando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Imprime el documento,usando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Eliminar información no utilizada |
| [removeMacro()](#removeMacro--) | Elimina VBA/macro de este diagrama. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Guarda el diagrama en el flujo. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Guarda el diagrama en el flujo. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Guarda el documento en un archivo usando las opciones de guardado especificadas. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Guarda los datos del diagrama en el archivo. |
| [setBuildnum(long value)](#setBuildnum-long-) | Para la descripción de esta propiedad, consulte [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Para la descripción de esta propiedad, consulte [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Para la descripción de esta propiedad, consulte [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Indica la ruta de la carpeta Fonts |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Para la descripción de esta propiedad, consulte [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Para la descripción de esta propiedad, consulte [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Para la descripción de esta propiedad, consulte [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Para la descripción de esta propiedad, consulte [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Para la descripción de esta propiedad, consulte [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Para la descripción de esta propiedad, consulte [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Para la descripción de esta propiedad, consulte [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Para la descripción de esta propiedad, consulte [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Constructor público de clase, carga el diagrama desde el archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Constructor público de clase, carga el diagrama desde el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Constructor público de clase, carga el diagrama desde el flujo usando un formato predefinido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos. |
| formato | int | Los datos Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Constructor público de clase, carga el diagrama desde el flujo usando opciones de carga de archivo predefinidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo de datos. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Los datos [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Constructor público de clase, carga el diagrama desde el archivo usando un formato predefinido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo. |
| formato | int | El formato de archivo. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Constructor público de clase, carga el diagrama desde el archivo usando opciones de carga de archivo predefinidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | Los datos [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Agrega master al diagrama desde el diagrama fuente por el Nombre o NameU del master.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | diagrama fuente. |
| masterName | java.lang.String | Nombre del Master o NameU. |

**Returns:**
int - El ID único del master dentro de la colección de masters en este diagrama.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Agrega master al diagrama desde el flujo de plantilla por el ID del master.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templateStream | java.io.InputStream | flujo de plantilla. |
| masterID | int | El ID único del master dentro de la colección de masters en la plantilla. |

**Returns:**
int - El ID único del master dentro de la colección de masters en este diagrama.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Agrega master al diagrama desde el flujo de plantilla por el Nombre o NameU del master.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templateStream | java.io.InputStream | flujo de plantilla. |
| masterName | java.lang.String | Nombre del Master o NameU. |

**Returns:**
int - El ID único del master dentro de la colección de masters en este diagrama.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Agrega master al diagrama desde el archivo de plantilla por el ID del master.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templateFilePath | java.lang.String | Ruta al archivo de plantilla (puede ser formato vdx, vst o vsd). |
| masterID | int | El ID único del master dentro de la colección de masters en la plantilla. |

**Returns:**
int - El ID único del master dentro de la colección de masters en este diagrama.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Agrega master al diagrama desde el archivo de plantilla por el Nombre o NameU del master.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templateFilePath | java.lang.String | Ruta al archivo de plantilla (puede ser formato vdx, vst o vsd). |
| masterName | java.lang.String | Nombre del Master o NameU. |

**Returns:**
int - El ID único del master dentro de la colección de masters en este diagrama.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Añade una forma creada por el maestro a una página específica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nuevo objeto de forma[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nombre del maestro. |
| pageNumber | int | Índice de la página. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Añade una forma creada por el maestro en la página con PinX, PinY, Width y Height definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma en pulgadas. |
| height | double | Especifica la altura de la forma en pulgadas. |
| masterName | java.lang.String | Nombre del maestro. |
| pageNumber | int | Índice de la página. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Añade una forma creada por el maestro en la página con PinX y PinY definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| masterName | java.lang.String | Nombre del maestro. |
| pageNumber | int | Índice de la página. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Combina otro objeto Diagram.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Otro objeto Diagram. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Copia Theme de un Diagram fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | diagrama fuente. |

### dispose() {#dispose--}
```
public void dispose()
```


Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exporta el diagrama del flujo vsd al formato de flujo vdw. Aún no implementado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputVsd | java.io.InputStream | flujo vsd. |
| outputVdw | java.io.InputStream | flujo vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exporta el diagrama del flujo vsd al formato de archivo \*.vdw. Aún no implementado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputVsd | java.io.InputStream | Nombre de archivo \*.vsd. |
| outputVdw | java.lang.String | flujo vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exporta el diagrama del archivo vsd al formato de flujo vdw. Aún no implementado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputVsd | java.lang.String | Nombre de archivo \*.vsd. |
| outputVdw | java.io.InputStream | flujo vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exporta el diagrama de vsd a formato vdw. Aún no implementado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputVsd | java.lang.String | Nombre de archivo \*.vsd. |
| outputVdw | java.lang.String | Nombre de archivo \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Especifica la página activa

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


El número de compilación de la instancia de Visio utilizada para crear el documento.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


Contiene la tabla de colores del documento. Cada documento contiene una única tabla de colores, que enumera los 24 colores estándar que están disponibles para aplicarse a objetos como shapes, texto y capas en el documento.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Contiene los elementos DataConnection del documento.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


La colección de objetos DataRecordset asociados a un objeto Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Obtener la ruta de la carpeta de fuentes predeterminadas

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


El ID único del idioma de la interfaz de usuario que el usuario ha especificado en las Preferencias de idioma de Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Contiene elementos de propiedades del documento, como el título del documento, el autor, etc.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Contiene elementos que especifican la configuración del documento.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Especifica la estructura ShapeSheet de un documento.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Contiene una hoja de ruta de correo electrónico MAPI codificada en MIME (Multipurpose Internet Mail Extensions) para el documento.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Contiene un elemento EventItem para cada evento al que un objeto debe responder.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Contiene una colección de elementos Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Contiene elementos para el encabezado y pie de página de un documento.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


el monitor de interrupciones.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Indica si el documento ha sido modificado fuera de Visio. Si está presente, Visio probará completamente el contenido del archivo. Omitir para archivos que cree fuera de Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Colección de objetos Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Indica si se deben usar unidades métricas en el dibujo. Establezca este atributo en True (1) para usar unidades métricas; establézcalo en False (0) para usar unidades inglesas.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Colección de objetos Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


La cadena XML del Ribbon que se pasa al documento para personalizar la interfaz de usuario del ribbon.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


Valor XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Indica si el documento ha sido modificado fuera de Visio. Si está presente, Visio probará completamente el contenido del archivo. Omitir para archivos que cree fuera de Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Colección de objetos StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Obtener estilos no utilizados

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


La cadena XML del Ribbon que se pasa al documento para personalizar la barra de acceso rápido o el ribbon.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Almacena información sobre la validación del diagrama para el documento.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Contiene los datos del proyecto Microsoft Visual Basic for Applications en formato codificado MIME (Multipurpose Internet Mail Extensions).

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Obtiene el VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


El número de versión de la instancia de Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Contiene los elementos Window para un documento.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Indica si este diagrama tiene información oculta.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Distribuye las formas y/o redirige los conectores para todas las páginas del diagrama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Usando [LayoutOptions](../../com.aspose.diagram/layoutoptions) para configurar las opciones de diseño. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


Imprime todo el documento en la impresora especificada, usando el controlador de impresión estándar (sin interfaz de usuario). Si printerName es Null o está vacío, se usará la impresora predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| printerName | java.lang.String | El nombre de la impresora. Puede ser Null. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Imprime todo el documento en la impresora especificada, usando el controlador de impresión estándar (sin interfaz de usuario). Si printerName es Null o está vacío, se usará la impresora predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| printerName | java.lang.String | El nombre de la impresora. Puede ser Null. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Las opciones de impresión. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Imprime el documento,usando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| printerName | java.lang.String | El nombre de la impresora. Puede ser Null. |
| documentName | java.lang.String | El nombre del documento a mostrar (por ejemplo, en un cuadro de diálogo de estado de impresión o en la cola de la impresora) al imprimir el documento. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Imprime el documento,usando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| printerName | java.lang.String | El nombre de la impresora. Puede ser Null. |
| documentName | java.lang.String | El nombre del documento a mostrar (por ejemplo, en un cuadro de diálogo de estado de impresión o en la cola de la impresora) al imprimir el documento. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Las opciones de impresión. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Eliminar información no utilizada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Elimina VBA/macro de este diagrama.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Guarda el diagrama en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | El flujo de archivo. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | Las opciones de guardado. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Guarda el diagrama en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | El flujo de archivo. |
| formato | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Guarda el documento en un archivo usando las opciones de guardado especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) opciones para guardar el diagrama. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Guarda los datos del diagrama en el archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre de archivo | java.lang.String | El nombre del archivo. |
| formato | int | Aspose.Diagram.SaveFileFormat formato de archivo de guardado. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Para la descripción de esta propiedad, consulte [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Para la descripción de esta propiedad, consulte [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Para la descripción de esta propiedad, consulte [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Indica la ruta de la carpeta Fonts

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Para la descripción de esta propiedad, consulte [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Para la descripción de esta propiedad, consulte [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Para la descripción de esta propiedad, consulte [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Para la descripción de esta propiedad, consulte [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Para la descripción de esta propiedad, consulte [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Para la descripción de esta propiedad, consulte [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Para la descripción de esta propiedad, consulte [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Para la descripción de esta propiedad, consulte [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

