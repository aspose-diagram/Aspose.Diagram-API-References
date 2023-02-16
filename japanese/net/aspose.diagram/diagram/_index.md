---
title: Diagram
second_title: Aspose.Diagram for .NET API リファレンス
description: Visio オブジェクト階層のルート要素.
type: docs
weight: 1170
url: /ja/net/aspose.diagram/diagram/
---
## Diagram class

Visio オブジェクト階層のルート要素.

```csharp
public class Diagram : IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Diagram](diagram/#constructor)() | デフォルトのコンストラクター。 |
| [Diagram](diagram/#constructor_1)(Stream) | パブリック クラス コンストラクター、 は、ストリームからダイアグラムを読み込みます。 |
| [Diagram](diagram/#constructor_4)(string) | パブリック クラス コンストラクター、 は、ファイルからダイアグラムを読み込みます。 |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | パブリック クラス コンストラクター、 は、定義済みの形式を使用してストリームからダイアグラムを読み込みます。 |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | パブリック クラス コンストラクター、 は、定義済みの読み込みファイル オプションを使用して、ストリームからダイアグラムを読み込みます。 |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | パブリック クラス コンストラクター、 は、定義済みの形式を使用してファイルからダイアグラムを読み込みます。 |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | パブリック クラス コンストラクター、 は、定義済みの読み込みファイル オプションを使用して、ファイルからダイアグラムを読み込みます。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | アクティブなページを指定します |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | ドキュメントの作成に使用された Visio インスタンスのビルド番号. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | ドキュメントのカラー テーブルが含まれます。各ドキュメントには、単一のカラー テーブル が含まれています。これには、ドキュメント内の図形、テキスト、レイヤーなどのオブジェクト に適用できる 24 の標準色がリストされています。 |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | ドキュメントの DataConnection 要素が含まれています。 |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | Document オブジェクトに関連付けられた DataRecordset オブジェクトのコレクション。 |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | ユーザーが Microsoft Office 2010 言語設定で指定したユーザー インターフェイス言語の一意の ID. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | ドキュメントのタイトル、作成者などのドキュメント プロパティ要素が含まれます。 |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | ドキュメントの設定を指定する要素が含まれています. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | ドキュメントのシェイプシート構造を指定します。 |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | ドキュメントの MIME (Multipurpose Internet Mail Extensions) でエンコードされた MAPI 電子メール回覧用紙が含まれています。 |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | オブジェクトが応答する必要がある各イベントの EventItem 要素が含まれます。 |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Fonts フォルダのパスを示します |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | フォント要素のコレクションが含まれています |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | ドキュメントのヘッダーとフッターの要素が含まれています。 |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | 割り込みモニターを取得および設定します。 |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | ドキュメントが Visio の外部で変更されたかどうかを示します。存在する場合、Visio はファイルの内容を完全にテストします。 Visio 以外で作成したファイルの場合は省略します。 |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | コレクション マスター オブジェクト。 |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | 図面でメートル単位を使用するかどうか。メートル単位を使用するには、この属性を True (1) に設定します。英国単位を使用するには、False (0) に設定します。 |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | コレクション ページ オブジェクト。 |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | リボン ユーザー インターフェイスをカスタマイズするためにドキュメントに渡されるリボン XML 文字列。 |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | XML 値. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | ドキュメントが Visio の外部で変更されたかどうかを示します。 存在する場合、Visio はファイルの内容を完全にテストします。 Visio 以外で作成したファイルの場合は省略します。 |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | コレクション StyleSheet オブジェクト。 |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | クイック アクセス ツールバーまたはリボンをカスタマイズするためにドキュメントに渡されるリボン XML 文字列。 |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | ドキュメントの図の検証に関する情報を格納します。 |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | VbaProject を取得します[`VbaProject`](./vbaproject/). |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | MIME (Multipurpose Internet Mail Extensions) エンコード形式の Microsoft Visual Basic for Applications プロジェクト データが含まれています。 |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Visio インスタンスのバージョン番号。 Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | ドキュメントの Window 要素が含まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | マスターの名前または NameU. によってソース ダイアグラムからダイアグラムにマスターを追加します。 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | マスターの ID によって、テンプレート ストリームからダイアグラムにマスターを追加します。 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | マスターの名前または NameU. によって、テンプレート ストリームからダイアグラムにマスターを追加します。 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | マスターの ID によってテンプレート ファイルからダイアグラムにマスターを追加します。 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | マスターの名前または NameU. によって、テンプレート ファイルからダイアグラムにマスターを追加します。 |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | マスターによって作成された形状を特定のページに追加します。 |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | 定義済みの PinX と PinY を使用して、マスターによって作成された形状をページに追加します。 |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | 定義された PinX、PinY、Width、および Height を使用して、マスターによって作成された形状をページに追加します。 |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | 別のダイアグラム オブジェクトを結合します。 |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | ソース ダイアグラムからテーマをコピーします。 |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | アンマネージ リソースの解放、解放、または リセットに関連するアプリケーション定義のタスクを実行します。 |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | 既定のフォント フォルダー パスを取得します |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | 未使用のスタイルを取得 |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | このダイアグラムに非表示の情報があるかどうかを示します. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | ダイアグラムのすべてのページの形状を配置したり、コネクタを再配線したりします。 |
| [Print](../../aspose.diagram/diagram/print/#print)() | ドキュメント全体をデフォルトのプリンターで印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | 標準 (ユーザー インターフェイスなし) プリント コントローラーを使用して、指定されたプリンター設定に従ってドキュメントを印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | ドキュメント全体をデフォルトのプリンターで印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | 標準 (ユーザー インターフェイスなし) 印刷コントローラーを使用して、指定されたプリンターにドキュメント全体を印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | 標準 (ユーザー インターフェイスなし) プリント コントローラーを使用して、指定されたプリンター設定に従ってドキュメントを印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | 標準 (ユーザー インターフェイスなし) プリント コントローラとドキュメント名を使用して、指定されたプリンタ設定に従ってドキュメントを印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | 標準 (ユーザー インターフェイスなし) 印刷コントローラーを使用して、指定されたプリンターにドキュメント全体を印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | 標準 (ユーザー インターフェイスなし) 印刷コントローラとドキュメント名を使用して、ドキュメントを印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | 標準 (ユーザー インターフェイスなし) プリント コントローラとドキュメント名を使用して、指定されたプリンタ設定に従ってドキュメントを印刷します。 |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | 標準 (ユーザー インターフェイスなし) 印刷コントローラとドキュメント名を使用して、ドキュメントを印刷します。 |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | ダイアグラム内のすべての DataRecordSet に対して Refresh メソッドを呼び出します。 |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | 未使用の情報を削除 |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | このダイアグラムから VBA/マクロを削除します。 |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | ダイアグラム データをストリームに保存します。 |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | 指定された保存オプションを使用して、ダイアグラムをストリームに保存します。 |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | ダイアグラム データをファイルに保存します。 |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | 指定された保存オプションを使用してドキュメントをファイルに保存します。 |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | 図を vsd ストリームから vdw ストリーム形式にエクスポートします。まだ実装されていません. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | 図を vsd ストリームから *.vdw ファイル形式にエクスポートします。まだ実装されていません. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | 図を vsd ファイルから vdw ストリーム形式にエクスポートします。まだ実装されていません. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | 図を vsd から vdw 形式にエクスポートします。まだ実装されていません. |

### 関連項目

* 名前空間 [Aspose.Diagram](../../aspose.diagram/)
* 組み立て [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
