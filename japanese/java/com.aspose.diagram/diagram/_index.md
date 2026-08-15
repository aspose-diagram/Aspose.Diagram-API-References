---
title: 図
second_title: Aspose.Diagram for Java API リファレンス
description: Visio オブジェクト階層のルート要素です。
type: docs
weight: 117
url: /ja/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Visio オブジェクト階層のルート要素です。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | パブリック クラス コンストラクタは、ファイルからダイアグラムをロードします。 |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | パブリック クラス コンストラクタは、ストリームからダイアグラムをロードします。 |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | パブリック クラス コンストラクタは、事前定義された形式を使用してストリームからダイアグラムをロードします。 |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | パブリック クラス コンストラクタは、事前定義されたロード ファイル オプションを使用してストリームからダイアグラムをロードします。 |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | パブリック クラス コンストラクタは、事前定義された形式を使用してファイルからダイアグラムをロードします。 |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | パブリック クラス コンストラクタは、事前定義されたロード ファイル オプションを使用してファイルからダイアグラムをロードします。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | マスターの Name または NameU によって、ソース ダイアグラムからマスターをダイアグラムに追加します。 |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | マスターの ID によって、テンプレート ストリームからマスターをダイアグラムに追加します。 |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | マスターの Name または NameU によって、テンプレート ストリームからマスターをダイアグラムに追加します。 |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | マスターの ID によって、テンプレート ファイルからマスターをダイアグラムに追加します。 |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | マスターの Name または NameU によって、テンプレート ファイルからマスターをダイアグラムに追加します。 |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | マスターで作成されたシェイプを特定のページに追加します。 |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | 定義された PinX、PinY、幅、そして高さを使用して、ページ上にマスターで作成されたシェイプを追加します。 |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | 定義された PinX と PinY を使用して、ページ上にマスターで作成されたシェイプを追加します。 |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | 別の Diagram オブジェクトを結合します。 |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | ソース Diagram から Theme をコピーします。 |
| [dispose()](#dispose--) | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | vsd ストリームから vdw ストリーム形式へダイアグラムをエクスポートします。 |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | vsd ストリームから *.vdw ファイル形式へダイアグラムをエクスポートします。 |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | vsd ファイルから vdw ストリーム形式へダイアグラムをエクスポートします。 |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | vsd から vdw 形式へダイアグラムをエクスポートします。 |
| [getActivePage()](#getActivePage--) | アクティブ ページを指定します |
| [getBuildnum()](#getBuildnum--) | ドキュメント作成に使用された Visio インスタンスのビルド番号です。 |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | ドキュメントのカラーテーブルを含みます。 |
| [getDataConnections()](#getDataConnections--) | ドキュメントの DataConnection 要素を含みます。 |
| [getDataRecordSets()](#getDataRecordSets--) | Document オブジェクトに関連付けられた DataRecordset オブジェクトのコレクションです。 |
| [getDefaultFontDir()](#getDefaultFontDir--) | デフォルト フォント フォルダーのパスを取得します |
| [getDocLangID()](#getDocLangID--) | ユーザーが Microsoft Office 2010 言語設定で指定したユーザー インターフェイス言語の一意の ID です。 |
| [getDocumentProps()](#getDocumentProps--) | ドキュメントのタイトル、作成者などのプロパティ要素を含みます。 |
| [getDocumentSettings()](#getDocumentSettings--) | ドキュメント設定を指定する要素を含みます。 |
| [getDocumentSheet()](#getDocumentSheet--) | ドキュメントの ShapeSheet 構造を指定します。 |
| [getEmailRoutingData()](#getEmailRoutingData--) | ドキュメント用の MIME（Multipurpose Internet Mail Extensions） エンコードされた MAPI 電子メールルーティングスリップを含みます。 |
| [getEventItems()](#getEventItems--) | オブジェクトが応答すべき各イベントに対する EventItem 要素を含みます。 |
| [getFonts()](#getFonts--) | Font 要素のコレクションを含みます |
| [getHeaderFooter()](#getHeaderFooter--) | ドキュメントのヘッダーとフッターの要素を含みます。 |
| [getInterruptMonitor()](#getInterruptMonitor--) | 割り込みモニター。 |
| [getKey()](#getKey--) | ドキュメントが Visio の外部で変更されたかどうかを示します。 |
| [getMasters()](#getMasters--) | Master オブジェクトのコレクションです。 |
| [getMetric()](#getMetric--) | 図面でメートル法単位を使用するかどうか。 |
| [getPages()](#getPages--) | Page オブジェクトのコレクションです。 |
| [getRibbonX()](#getRibbonX--) | リボンのユーザーインターフェイスをカスタマイズするためにドキュメントに渡される Ribbon XML 文字列です。 |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML 値です。 |
| [getStart()](#getStart--) | ドキュメントが Visio の外部で変更されたかどうかを示します。 |
| [getStyleSheets()](#getStyleSheets--) | StyleSheet オブジェクトのコレクションです。 |
| [getUnusedStyles()](#getUnusedStyles--) | 未使用のスタイルを取得する |
| [getUserCustomUI()](#getUserCustomUI--) | クイックアクセスツールバーまたはリボンをカスタマイズするためにドキュメントに渡される Ribbon XML 文字列です。 |
| [getValidation()](#getValidation--) | ドキュメントの図表検証に関する情報を格納します。 |
| [getVbProjectData()](#getVbProjectData--) | MIME（Multipurpose Internet Mail Extensions） エンコード形式の Microsoft Visual Basic for Applications プロジェクト データを含みます。 |
| [getVbaProject()](#getVbaProject--) | VbaProject を取得します[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--)。 |
| [getVersion()](#getVersion--) | Visio インスタンスのバージョン番号です。 |
| [getWindows()](#getWindows--) | ドキュメントの Window 要素を含みます。 |
| [hasHiddenInfo()](#hasHiddenInfo--) | この図が非表示情報を持つかどうかを示します。 |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | 図のすべてのページのシェイプを配置し、またはコネクタを再ルーティングします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | 指定されたプリンターへドキュメント全体を印刷します、標準（ユーザーインターフェイスなし）印刷コントローラを使用して。 |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | 指定されたプリンターへドキュメント全体を印刷します、標準（ユーザーインターフェイスなし）印刷コントローラを使用して。 |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | ドキュメントを印刷します、標準（ユーザーインターフェイスなし）印刷コントローラとドキュメント名を使用して。 |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | ドキュメントを印刷します、標準（ユーザーインターフェイスなし）印刷コントローラとドキュメント名を使用して。 |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | 未使用情報を削除する |
| [removeMacro()](#removeMacro--) | この図から VBA/マクロ を削除します。 |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | 図をストリームに保存します。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 図をストリームに保存します。 |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | 指定された保存オプションを使用してドキュメントをファイルに保存します。 |
| [save(String filename, int format)](#save-java.lang.String-int-) | 図データをファイルに保存します。 |
| [setBuildnum(long value)](#setBuildnum-long-) | このプロパティの説明については、[getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) を参照してください。 |
| [setDocLangID(int value)](#setDocLangID-int-) | このプロパティの説明については、[getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) を参照してください。 |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | このプロパティの説明については、[getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) を参照してください。 |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | フォント フォルダーのパスを示します |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | このプロパティの説明については、[getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) を参照してください。 |
| [setKey(String value)](#setKey-java.lang.String-) | このプロパティの説明については、[getKey()](../../com.aspose.diagram/diagram\#getKey--) を参照してください。 |
| [setMetric(int value)](#setMetric-int-) | このプロパティの説明については、[getMetric()](../../com.aspose.diagram/diagram\#getMetric--) を参照してください。 |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | このプロパティの説明については、[getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) を参照してください。 |
| [setStart(long value)](#setStart-long-) | このプロパティの説明については、[getStart()](../../com.aspose.diagram/diagram\#getStart--) を参照してください。 |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | このプロパティの説明については、[getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) を参照してください。 |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | このプロパティの説明については、[getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) を参照してください。 |
| [setVersion(String value)](#setVersion-java.lang.String-) | このプロパティの説明については、[getVersion()](../../com.aspose.diagram/diagram\#getVersion--) を参照してください。 |
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


パブリック クラス コンストラクタは、ファイルからダイアグラムをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


パブリック クラス コンストラクタは、ストリームからダイアグラムをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | データ ストリームです。 |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


パブリック クラス コンストラクタは、事前定義された形式を使用してストリームからダイアグラムをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | データ ストリームです。 |
| フォーマット | int | Aspose.Diagram.LoadFileFormat のデータです。 |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


パブリック クラス コンストラクタは、事前定義されたロード ファイル オプションを使用してストリームからダイアグラムをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | データ ストリームです。 |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | データ [LoadOptions](../../com.aspose.diagram/loadoptions) です。 |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


パブリック クラス コンストラクタは、事前定義された形式を使用してファイルからダイアグラムをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |
| フォーマット | int | ファイル形式です。 |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


パブリック クラス コンストラクタは、事前定義されたロード ファイル オプションを使用してファイルからダイアグラムをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | データ [LoadOptions](../../com.aspose.diagram/loadoptions) です。 |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


マスターの Name または NameU によって、ソース ダイアグラムからマスターをダイアグラムに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | ソース ダイアグラムです。 |
| masterName | java.lang.String | マスターの Name または NameU。 |

**Returns:**
int - このダイアグラムのマスター コレクション内のマスターの一意の ID です。
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


マスターの ID によって、テンプレート ストリームからマスターをダイアグラムに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| templateStream | java.io.InputStream | テンプレート ストリームです。 |
| masterID | int | テンプレートのマスター コレクション内のマスターの一意の ID です。 |

**Returns:**
int - このダイアグラムのマスター コレクション内のマスターの一意の ID です。
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


マスターの Name または NameU によって、テンプレート ストリームからマスターをダイアグラムに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| templateStream | java.io.InputStream | テンプレート ストリームです。 |
| masterName | java.lang.String | マスターの Name または NameU。 |

**Returns:**
int - このダイアグラムのマスター コレクション内のマスターの一意の ID です。
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


マスターの ID によって、テンプレート ファイルからマスターをダイアグラムに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| templateFilePath | java.lang.String | Path to template file(can be vdx, vst or vsd format). |
| masterID | int | テンプレートのマスター コレクション内のマスターの一意の ID です。 |

**Returns:**
int - このダイアグラムのマスター コレクション内のマスターの一意の ID です。
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


マスターの Name または NameU によって、テンプレート ファイルからマスターをダイアグラムに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| templateFilePath | java.lang.String | Path to template file(can be vdx, vst or vsd format). |
| masterName | java.lang.String | マスターの Name または NameU。 |

**Returns:**
int - このダイアグラムのマスター コレクション内のマスターの一意の ID です。
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


マスターで作成されたシェイプを特定のページに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | 新しいシェイプオブジェクト[Shape](../../com.aspose.diagram/shape)。 |
| masterName | java.lang.String | マスターの名前です。 |
| pageNumber | int | Index of page. |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


定義された PinX、PinY、幅、そして高さを使用して、ページ上にマスターで作成されたシェイプを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| width | double | シェイプの幅をインチ単位で指定します。 |
| height | double | シェイプの高さをインチ単位で指定します。 |
| masterName | java.lang.String | マスターの名前です。 |
| pageNumber | int | Index of page. |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


定義された PinX と PinY を使用して、ページ上にマスターで作成されたシェイプを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pinX | double | ページに対するシェイプのピン（回転中心）のX座標を指定します。 |
| pinY | double | ページに対するシェイプのピン（回転中心）のY座標を指定します。 |
| masterName | java.lang.String | マスターの名前です。 |
| pageNumber | int | Index of page. |

**Returns:**
long - 指定されたページ上のシェイプコレクション内でのシェイプの一意のIDです。
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


別の Diagram オブジェクトを結合します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Another Diagram object. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


ソース Diagram から Theme をコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | ソース ダイアグラムです。 |

### dispose() {#dispose--}
```
public void dispose()
```


アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Exports the diagram from vsd stream to vdw stream format. Not implemented yet.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd stream. |
| outputVdw | java.io.InputStream | vdw stream. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Exports the diagram from vsd stream to \*.vdw file format. Not implemented yet.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd file name. |
| outputVdw | java.lang.String | vdw stream. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Exports the diagram from vsd file to vdw stream format. Not implemented yet.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd file name. |
| outputVdw | java.io.InputStream | vdw stream. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Exports the diagram from vsd to vdw format. Not implemented yet.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd file name. |
| outputVdw | java.lang.String | \*.vdw file name. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


アクティブ ページを指定します

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


ドキュメント作成に使用された Visio インスタンスのビルド番号です。

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


ドキュメントのカラーテーブルを含みます。各ドキュメントは 1 つのカラーテーブルを持ち、シェイプ、テキスト、レイヤーなどのオブジェクトに適用できる 24 の標準色が一覧されています。

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


ドキュメントの DataConnection 要素を含みます。

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Document オブジェクトに関連付けられた DataRecordset オブジェクトのコレクションです。

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


デフォルト フォント フォルダーのパスを取得します

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


ユーザーが Microsoft Office 2010 言語設定で指定したユーザー インターフェイス言語の一意の ID です。

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


ドキュメントのタイトル、作成者などのプロパティ要素を含みます。

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


ドキュメント設定を指定する要素を含みます。

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


ドキュメントの ShapeSheet 構造を指定します。

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


ドキュメント用の MIME（Multipurpose Internet Mail Extensions） エンコードされた MAPI 電子メールルーティングスリップを含みます。

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


オブジェクトが応答すべき各イベントに対する EventItem 要素を含みます。

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Font 要素のコレクションを含みます

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


ドキュメントのヘッダーとフッターの要素を含みます。

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


割り込みモニター。

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Master オブジェクトのコレクションです。

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Whether to use metric units in the drawing. Set this attribute to True (1) to use metric units; set it to False (0) to use English units.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Page オブジェクトのコレクションです。

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


リボンのユーザーインターフェイスをカスタマイズするためにドキュメントに渡される Ribbon XML 文字列です。

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML 値です。

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Indicates whether the document has been modified outside of Visio. If present, Visio will fully test the contents of the file. Omit for files you create outside of Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


StyleSheet オブジェクトのコレクションです。

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


未使用のスタイルを取得する

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


クイックアクセスツールバーまたはリボンをカスタマイズするためにドキュメントに渡される Ribbon XML 文字列です。

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


ドキュメントの図表検証に関する情報を格納します。

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


MIME（Multipurpose Internet Mail Extensions） エンコード形式の Microsoft Visual Basic for Applications プロジェクト データを含みます。

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


VbaProject を取得します[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--)。

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


The version number of the Visio instance. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


ドキュメントの Window 要素を含みます。

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


この図が非表示情報を持つかどうかを示します。

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


図のすべてのページのシェイプを配置し、またはコネクタを再ルーティングします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | [LayoutOptions](../../com.aspose.diagram/layoutoptions) を使用してレイアウトのオプションを構成します。 |

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


Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerName is Null or empty will be used default printer.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Print the whole document to the specified printer,using the standard (no User Interface) print controller. If printerName is Null or empty will be used default printer.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | The print options. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


ドキュメントを印刷します、標準（ユーザーインターフェイスなし）印刷コントローラとドキュメント名を使用して。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |
| documentName | java.lang.String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


ドキュメントを印刷します、標準（ユーザーインターフェイスなし）印刷コントローラとドキュメント名を使用して。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| printerName | java.lang.String | The name of the printer.Can be Null |
| documentName | java.lang.String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | The print options. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


未使用情報を削除する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


この図から VBA/マクロ を削除します。

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


図をストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | ファイルストリーム。 |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | 保存オプション。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


図をストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | ファイルストリーム。 |
| フォーマット | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


指定された保存オプションを使用してドキュメントをファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) ダイアグラム保存オプション。 |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


図データをファイルに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル名 | java.lang.String | ファイル名です。 |
| フォーマット | int | Aspose.Diagram.SaveFileFormat 保存ファイル形式。 |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


このプロパティの説明については、[getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


このプロパティの説明については、[getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


このプロパティの説明については、[getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


フォント フォルダーのパスを示します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


このプロパティの説明については、[getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


このプロパティの説明については、[getKey()](../../com.aspose.diagram/diagram\#getKey--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


このプロパティの説明については、[getMetric()](../../com.aspose.diagram/diagram\#getMetric--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


このプロパティの説明については、[getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


このプロパティの説明については、[getStart()](../../com.aspose.diagram/diagram\#getStart--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


このプロパティの説明については、[getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


このプロパティの説明については、[getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


このプロパティの説明については、[getVersion()](../../com.aspose.diagram/diagram\#getVersion--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

