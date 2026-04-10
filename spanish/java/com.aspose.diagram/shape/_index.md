---
title: Forma
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que definen una forma en una página maestra o en un elemento de forma grupal.
type: docs
weight: 355
url: /es/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Contiene elementos que definen una forma en un Master, una Página o un elemento de forma de grupo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Shape()](#Shape--) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [bringForward()](#bringForward--) | Mueve la forma un puesto hacia adelante en el orden Z. |
| [bringToFront()](#bringToFront--) | Mueve la forma al frente del orden Z. |
| [centerDrawing()](#centerDrawing--) | Centra la forma con respecto a la extensión de la página. |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Devuelve una matriz que contiene los identificadores (IDs) de las formas que están conectadas a la forma. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Devuelve una matriz que contiene los identificadores de las formas que dependen de una forma. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Obtiene el control ActiveX. |
| [getActs()](#getActs--) | Contiene una colección de elementos Act. |
| [getAlign()](#getAlign--) | Indica la alineación de una forma con respecto a la guía o punto de guía al que la forma está adherida. |
| [getChars()](#getChars--) | Contiene una colección de elementos Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contiene una colección de elementos ConnectionABCD. |
| [getConnections()](#getConnections--) | Contiene una colección de elementos Connection. |
| [getConnectorRule()](#getConnectorRule--) | Devuelve un connectorRule que contiene el id de la forma y la conexión que están conectados a la forma. |
| [getConnectorsType()](#getConnectorsType--) | Obtener tipo de conectores |
| [getControlData()](#getControlData--) | Obtiene los datos del control. |
| [getControls()](#getControls--) | Contiene una colección de elementos Control. |
| [getData1()](#getData1--) | Contiene un valor de cadena arbitrario que se utiliza para proporcionar información adicional sobre una forma. |
| [getData2()](#getData2--) | Contiene un valor de cadena arbitrario que se utiliza para proporcionar información adicional sobre una forma. |
| [getData3()](#getData3--) | Contiene un valor de cadena arbitrario que se utiliza para proporcionar información adicional sobre una forma. |
| [getDel()](#getDel--) | Una bandera que indica si el elemento está eliminado localmente. |
| [getDiagram()](#getDiagram--) | Elemento raíz de la jerarquía de objetos de Visio. |
| [getDisplayText()](#getDisplayText--) | Obtener el texto mostrado en la interfaz. |
| [getEvent()](#getEvent--) | Contiene elementos que especifican fórmulas que controlan eventos de forma. |
| [getFields()](#getFields--) | Contiene una colección de elementos Field. |
| [getFill()](#getFill--) | Contiene los valores actuales de formato de relleno para la forma y la sombra paralela de la forma, incluyendo el patrón, el color de primer plano y el color de fondo. |
| [getFillStyle()](#getFillStyle--) | Hoja de estilo de la cual esta forma hereda el formato de relleno. |
| [getForeign()](#getForeign--) | Contiene elementos que especifican el ancho y la altura de un objeto de otro programa utilizado en un documento de Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE. |
| [getGeoms()](#getGeoms--) | Contiene una colección de elementos Geom. |
| [getGroup()](#getGroup--) | Contiene elementos que controlan cómo agregar formas a un grupo, mover miembros de un grupo y seleccionar grupos. |
| [getHelp()](#getHelp--) | Contiene elementos que especifican el tema del archivo de ayuda del elemento Shape y la información de derechos de autor. |
| [getHyperlinks()](#getHyperlinks--) | Contiene una colección de elementos Hyperlink. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getImage()](#getImage--) | Contiene los valores de gamma, brillo, contraste, desenfoque, nitidez, reducción de ruido y transparencia para un mapa de bits. |
| [getInheritChars()](#getInheritChars--) | Contiene los valores de carácter para la forma heredados por la forma maestra. |
| [getInheritFill()](#getInheritFill--) | Contiene los valores de formato de relleno para la forma heredados por el estilo padre y la forma maestra. |
| [getInheritGeoms()](#getInheritGeoms--) | Contiene los valores Geoms de la forma heredados por la forma maestra. |
| [getInheritLine()](#getInheritLine--) | Contiene los valores de formato de línea para la forma heredados por el estilo padre y la forma maestra. |
| [getInheritParas()](#getInheritParas--) | Contiene los paras de la forma heredados por el estilo padre y la forma maestra. |
| [getInheritProps()](#getInheritProps--) | Contiene las props de la forma heredados por la forma maestra. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Contiene los valores del bloque de texto para la forma heredados por el estilo padre y la forma maestra. |
| [getInheritUsers()](#getInheritUsers--) | Contiene los usuarios de la forma heredados por la forma maestra. |
| [getLayerMem()](#getLayerMem--) | Contiene el elemento LayerMember, que especifica cada capa a la que se asigna la forma. |
| [getLayout()](#getLayout--) | Contiene elementos que controlan la colocación de formas y la configuración de enrutamiento de conectores. |
| [getLine()](#getLine--) | Contiene elementos que controlan los atributos de línea de una forma, como patrón, grosor y color. |
| [getLineStyle()](#getLineStyle--) | Hoja de estilo de la cual esta forma hereda el formato de línea |
| [getMaster()](#getMaster--) | El maestro del cual la forma hereda sus datos. |
| [getMasterShape()](#getMasterShape--) | Este atributo solo puede estar presente en formas que son miembros de una forma de grupo, y el grupo es una instancia de un maestro. |
| [getMisc()](#getMisc--) | Contiene elementos que especifican el tema del archivo de ayuda del elemento Shape y la información de derechos de autor. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getOneD()](#getOneD--) | Determina si la forma se comporta como un objeto unidimensional (1-D). |
| [getPage()](#getPage--) | Elemento raíz de la jerarquía de objetos de Visio. |
| [getParas()](#getParas--) | Contiene una colección de elementos Para. |
| [getParentShape()](#getParentShape--) | Padre de la forma. |
| [getProps()](#getProps--) | Contiene una colección de elementos Prop. |
| [getProtection()](#getProtection--) | El bloqueo ayuda a prevenir cambios inadvertidos en la forma, pero no impide que Microsoft Visio restablezca valores en otras circunstancias. |
| [getPureText()](#getPureText--) | Obtener la cadena de texto |
| [getRootShape()](#getRootShape--) | Devuelve la forma de nivel superior de una instancia si esta forma es parte de una instancia maestra. |
| [getScratchs()](#getScratchs--) | Contiene una colección de elementos Scratch. |
| [getShapes()](#getShapes--) | Contiene una colección de elementos Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contiene una colección de elementos SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | Contiene una colección de elementos Tab. |
| [getText()](#getText--) | Contiene el texto de una forma. |
| [getTextBlock()](#getTextBlock--) | Contiene elementos que especifican la alineación, los márgenes y las posiciones predeterminadas de tabulaciones del texto en el bloque de texto de una forma. |
| [getTextStyle()](#getTextStyle--) | Hoja de estilo de la cual esta forma hereda el formato de texto. |
| [getTextXForm()](#getTextXForm--) | Contiene elementos que especifican información de posicionamiento sobre el bloque de texto de una forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Obtiene el ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Determina si la forma se comporta como un objeto bidimensional (2-D). |
| [getType()](#getType--) | El tipo de una forma. |
| [getUniqueID()](#getUniqueID--) | Un GUID (identificador global único) asignado a la forma. |
| [getUsers()](#getUsers--) | Contiene una colección de elementos User. |
| [getXForm()](#getXForm--) | Contiene elementos que especifican información general de posicionamiento sobre una forma. |
| [getXForm1D()](#getXForm1D--) | Contiene las coordenadas x e y del punto inicial y del punto final de una forma 1-D. |
| [getZOrderIndex()](#getZOrderIndex--) | Devuelve el índice de una forma en el orden Z, excepto la forma guía. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Devuelve una matriz que contiene los identificadores de las formas que están pegadas a una forma. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Indica si estas dos formas están conectadas. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Indica si esta forma contiene otra forma. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Indica si estas dos formas están pegadas. |
| [isInGroup()](#isInGroup--) | Indica si esta forma está en una forma de grupo. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Indica si esta forma intersecta otra forma. |
| [isTextEmpty()](#isTextEmpty--) | Indica si la forma tiene texto y si el texto está vacío o no. |
| [move(double dX, double dY)](#move-double-double-) | Mueve la forma dX y dY pulgadas desde la posición actual. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Mueve la forma a una nueva posición absoluta en la página. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Actualiza la posición de la forma, incluyendo xform, conexión y geom, al cambiar el texto de la forma o de otros. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Reemplaza la cadena de texto de una forma. |
| [sendBackward()](#sendBackward--) | Mueve la forma una posición atrás en el orden Z. |
| [sendToBack()](#sendToBack--) | Mueve la forma al fondo del orden Z. |
| [setAngle(double angle)](#setAngle-double-) | Establece un nuevo ángulo para la forma. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Para la descripción de esta propiedad, consulte [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Establecer tipo de conectores |
| [setData1(String value)](#setData1-java.lang.String-) | Para la descripción de esta propiedad, consulte [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Para la descripción de esta propiedad, consulte [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Para la descripción de esta propiedad, consulte [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Para la descripción de esta propiedad, consulte [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Para la descripción de esta propiedad, consulte [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Para la descripción de esta propiedad, consulte [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Establece una nueva altura para la forma. |
| [setID(long value)](#setID-long-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Para la descripción de esta propiedad, consulte [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Para la descripción de esta propiedad, consulte [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Para la descripción de esta propiedad, consulte [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Para la descripción de esta propiedad, consulte [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Para la descripción de esta propiedad, consulte [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Aplicar un tema preestablecido a esta forma |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Aplicar un estilo rápido de variante de tema preestablecido a esta forma |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Aplicar un estilo rápido de variante de tema preestablecido a esta forma, como opciones de estilos de tema en la lista desplegable de estilos de forma |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Aplicar una variante de tema preestablecida a esta forma |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Para la descripción de esta propiedad, consulte [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Para la descripción de esta propiedad, consulte [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Para la descripción de esta propiedad, consulte [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Para la descripción de esta propiedad, consulte [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Para la descripción de esta propiedad, consulte [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Para la descripción de esta propiedad, consulte [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Establece el nuevo ancho de la forma. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Para la descripción de esta propiedad, consulte [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Para la descripción de esta propiedad, consulte [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Crea el HTML de la forma y lo guarda en un flujo en el formato especificado. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Crea el HTML de la forma y lo guarda en un flujo en el formato especificado. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Crea el HTML y lo guarda en un archivo. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Crea la imagen de la forma y la guarda en un flujo en el formato especificado. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Crea la imagen de la forma y la guarda en un flujo en el formato especificado. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Crea la imagen de la forma y la guarda en un archivo. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Crea el PDF de la forma y lo guarda en un flujo. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Crea el PDF de la forma y lo guarda en un flujo. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Guarda la forma en un archivo PDF. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Guarda la forma en un archivo SVG. |
| [ungroup()](#ungroup--) | Desagrupar forma |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Constructor.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Mueve la forma un puesto hacia adelante en el orden Z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Mueve la forma al frente del orden Z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centra la forma con respecto a la extensión de la página.

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Devuelve una matriz que contiene los identificadores (IDs) de las formas que están conectadas a la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bandera | int | Filtra la matriz de IDs de forma devueltos por la direccionalidad de los conectores. Consulte Remarks para los valores posiblesAspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filtra la matriz de IDs de formas devueltos limitándola a los IDs de formas que coincidan con el categoryString especificado. |

**Returns:**
long[] - matriz de IDs long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Devuelve una matriz que contiene los identificadores de las formas que dependen de una forma.

**Returns:**
long[] - matriz de IDs long.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Obtiene el control ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contiene una colección de elementos Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Indica la alineación de una forma con respecto a la guía o punto de guía al que la forma está pegada. El elemento Align aparece solo para formas que están pegadas a guías o puntos de guía.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Contiene una colección de elementos Char.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Contiene una colección de elementos ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Contiene una colección de elementos Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Devuelve un connectorRule que contiene el id de la forma y la conexión que están conectados a la forma.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Obtener tipo de conectores

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Obtiene los datos del control.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Contiene una colección de elementos Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Contiene un valor de cadena arbitrario que se utiliza para proporcionar información adicional sobre una forma.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Contiene un valor de cadena arbitrario que se utiliza para proporcionar información adicional sobre una forma.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Contiene un valor de cadena arbitrario que se utiliza para proporcionar información adicional sobre una forma.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Una bandera que indica si el elemento está eliminado localmente. Un valor de 1 indica que el elemento está eliminado localmente.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Elemento raíz de la jerarquía de objetos de Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Obtener el texto mostrado en la interfaz.

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Contiene elementos que especifican fórmulas que controlan eventos de forma.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Contiene una colección de elementos Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Contiene los valores actuales de formato de relleno para la forma y la sombra paralela de la forma, incluyendo el patrón, el color de primer plano y el color de fondo.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Hoja de estilo de la cual esta forma hereda el formato de relleno.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Contiene elementos que especifican el ancho y la altura de un objeto de otro programa utilizado en un documento Microsoft Visio. También incluye elementos que especifican la distancia a la que la imagen del objeto se desplaza dentro de sus bordes.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Contiene un BLOB codificado en MIME (Multipurpose Internet Mail Extensions) de datos de imagen, como metafile de Windows, bitmap o datos OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Contiene una colección de elementos Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Contiene elementos que controlan cómo agregar formas a un grupo, mover miembros de un grupo y seleccionar grupos.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Contiene elementos que especifican el tema del archivo de ayuda del elemento Shape y la información de derechos de autor.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contiene una colección de elementos Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Contiene los valores de gamma, brillo, contraste, desenfoque, nitidez, reducción de ruido y transparencia para un mapa de bits.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Contiene los valores de carácter para la forma heredados por la forma maestra.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Contiene los valores de formato de relleno para la forma heredados por el estilo padre y la forma maestra.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Contiene los valores Geoms de la forma heredados por la forma maestra.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Contiene los valores de formato de línea para la forma heredados por el estilo padre y la forma maestra.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Contiene los paras de la forma heredados por el estilo padre y la forma maestra.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Contiene las props de la forma heredados por la forma maestra.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Contiene los valores del bloque de texto para la forma heredados por el estilo padre y la forma maestra.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Contiene los usuarios de la forma heredados por la forma maestra.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Contiene el elemento LayerMember, que especifica cada capa a la que se asigna la forma.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Contiene elementos que controlan la colocación de formas y la configuración de enrutamiento de conectores.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Contiene elementos que controlan los atributos de línea de una forma, como el patrón, el grosor y el color. Estos elementos determinan si los extremos de la línea están formateados (por ejemplo, con una punta de flecha), el tamaño de los formatos de los extremos de la línea, el radio del círculo de redondeo aplicado a la línea y el estilo de terminación de la línea (redondo o cuadrado).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Hoja de estilo de la cual esta forma hereda el formato de línea

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


El maestro del cual la forma hereda sus datos.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Este atributo solo puede estar presente en formas que son miembros de una forma de grupo, y el grupo es una instancia de un master. El atributo contiene un ID que hace referencia a la sub‑forma correspondiente en el master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Contiene elementos que especifican el tema del archivo de ayuda del elemento Shape y la información de derechos de autor.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


El nombre del elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


El nombre universal del elemento.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Determina si la forma se comporta como un objeto unidimensional (1‑D). Solo lectura.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Elemento raíz de la jerarquía de objetos de Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Contiene una colección de elementos Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Padre de la forma.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contiene una colección de elementos Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


El bloqueo ayuda a evitar cambios inadvertidos en la forma, pero no impide que Microsoft Visio restablezca valores en otras circunstancias. Tampoco protege contra cambios realizados en la ventana ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Obtener la cadena de texto

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Devuelve la forma de nivel superior de una instancia si esta forma es parte de una instancia de master. Solo lectura.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contiene una colección de elementos Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Contiene una colección de elementos Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contiene una colección de elementos SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Contiene una colección de elementos Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Contiene el texto de una forma.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Contiene elementos que especifican la alineación, los márgenes y las posiciones predeterminadas de tabulaciones del texto en el bloque de texto de una forma.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Hoja de estilo de la cual esta forma hereda el formato de texto.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Contiene elementos que especifican información de posicionamiento sobre el bloque de texto de una forma.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Obtiene el ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Determina si la forma se comporta como un objeto bidimensional (2-D).

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


El tipo de una forma. Puede ser uno de los siguientes valores: Group, Shape, Guide o Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID (identificador global único) asignado a la forma.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Contiene una colección de elementos User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Contiene elementos que especifican información general de posicionamiento sobre una forma.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Contiene las coordenadas x e y del punto inicial y del punto final de una forma 1-D. Este elemento aparece solo para formas 1-D.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Devuelve el índice de una forma en el orden Z, excepto la forma guía.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Devuelve una matriz que contiene los identificadores de las formas que están pegadas a una forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bandera | int | La dimensionalidad y direccionalidad de los puntos de conexión de las formas a devolver. Consulte Remarks para los valores posibles Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filtra la matriz de IDs de formas devueltos limitándola a los IDs de formas que coincidan con el categoryString especificado. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Opcional: forma adicional a la que también deben estar pegadas las formas devueltas, puede ser [Shape](../../com.aspose.diagram/shape) o null. |

**Returns:**
long[] - matriz de IDs long.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


Indica si estas dos formas están conectadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Indica si esta forma contiene otra forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Indica si estas dos formas están pegadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Indica si esta forma está en una forma de grupo.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Indica si esta forma intersecta otra forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Indica si la forma tiene texto y si el texto está vacío o no.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Mueve la forma dX y dY pulgadas desde la posición actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dX | double | Desplazamiento X double. |
| dY | double | Desplazamiento Y double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Mueve la forma a una nueva posición absoluta en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newPinX | double | Nueva coordenada x del pin de la shape (centro de rotación) en relación con el origen de su padre. double. |
| newPinY | double | Nueva coordenada y del pin de la shape (centro de rotación) en relación con el origen de su padre. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Actualiza la posición de la shape incluyendo xform, connection y geom al cambiar el texto de la shape u otros. Recopilaremos los datos de la shape, como el texto de la shape, y luego calcularemos su posición. Este método solo se usa para actualizar los datos de la shape.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Reemplaza la cadena de texto de una forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Mueve la forma una posición atrás en el orden Z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Mueve la forma al fondo del orden Z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Establece el nuevo ángulo de la shape. La unidad del ángulo es radian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | double | Nuevo ángulo cuya unidad es radian y no grado double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Para la descripción de esta propiedad, consulte [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Establecer tipo de conectores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Para la descripción de esta propiedad, consulte [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Para la descripción de esta propiedad, consulte [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Para la descripción de esta propiedad, consulte [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Para la descripción de esta propiedad, consulte [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Para la descripción de esta propiedad, consulte [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Para la descripción de esta propiedad, consulte [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Para la descripción de esta propiedad, consulte [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Establece una nueva altura para la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Para la descripción de esta propiedad, consulte [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Para la descripción de esta propiedad, consulte [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Para la descripción de esta propiedad, consulte [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Para la descripción de esta propiedad, consulte [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Para la descripción de esta propiedad, consulte [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Aplicar un tema preestablecido a esta forma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Aplicar un estilo rápido de variante de tema preestablecido a esta forma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Aplicar un estilo rápido de variante de tema preestablecido a esta forma, como opciones de estilos de tema en la lista desplegable de estilos de forma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Aplicar una variante de tema preestablecida a esta forma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Para la descripción de esta propiedad, consulte [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Para la descripción de esta propiedad, consulte [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Para la descripción de esta propiedad, consulte [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Para la descripción de esta propiedad, consulte [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Para la descripción de esta propiedad, consulte [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Para la descripción de esta propiedad, consulte [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Establece el nuevo ancho de la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Para la descripción de esta propiedad, consulte [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Para la descripción de esta propiedad, consulte [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Crea el HTML de la forma y lo guarda en un flujo en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Crea el HTML de la forma y lo guarda en un flujo en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Crea el HTML y lo guarda en un archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Crea la imagen de la forma y la guarda en un flujo en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Crea la imagen de la forma y la guarda en un flujo en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Crea el PDF de la forma y lo guarda en un flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Crea el PDF de la forma y lo guarda en un flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Guarda la forma en un archivo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


Guarda la forma en un archivo SVG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Desagrupar forma

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

