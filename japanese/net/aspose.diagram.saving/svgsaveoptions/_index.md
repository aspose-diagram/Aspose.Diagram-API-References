---
title: SVGSaveOptions
second_title: Aspose.Diagram for .NET API リファレンス
description: ダイアグラム ページを SVG にレンダリングするときに追加オプションを指定できます
type: docs
weight: 3460
url: /ja/net/aspose.diagram.saving/svgsaveoptions/
---
## SVGSaveOptions class

ダイアグラム ページを SVG にレンダリングするときに追加オプションを指定できます。

```csharp
public class SVGSaveOptions : RenderingSaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SVGSaveOptions](svgsaveoptions/)() | にドキュメントを保存するために使用できる、このクラスの新しいインスタンスを初期化します。[`XPS`](../../aspose.diagram/savefileformat/) format. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | 保存される形状の領域を取得または設定します. |
| [CustomImagePath](../../aspose.diagram.saving/svgsaveoptions/customimagepath/) { get; set; } | 画像用に生成された svg ファイルに保存されたユーザー カスタム パス (URL)。ユーザーによって定義されていない場合、現在のディレクトリが使用されます. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | ダイアグラム内の文字が Unicode であり、正しいフォント値が設定されていないか、フォントがローカルにインストールされていない場合、 PDF、画像、または XPS でブロックとして表示される場合があります。 これらを表示するには、MingLiu や MS ゴシックなどの DefaultFont を設定します。文字. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Emf メタファイルをレンダリングするための設定. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | ページを拡大するかどうかを指定します。 |
| [ExportElementAsRectTag](../../aspose.diagram.saving/svgsaveoptions/exportelementasrecttag/) { get; set; } | 長方形要素を rect タグとしてエクスポートする必要があるかどうかを定義します. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | ガイド形状をエクスポートする必要があるかどうかを定義します. |
| [ExportHiddenPage](../../aspose.diagram.saving/svgsaveoptions/exporthiddenpage/) { get; set; } | 隠しページをエクスポートする必要があるかどうかを定義します. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | コメントをエクスポートする必要があるかどうかを定義します. |
| [IsExportScaleInMatrix](../../aspose.diagram.saving/svgsaveoptions/isexportscaleinmatrix/) { get; set; } | マトリックスでエクスポート スケールが必要かどうかを定義します。 |
| [IsSavingCustomLinePattern](../../aspose.diagram.saving/svgsaveoptions/issavingcustomlinepattern/) { get; set; } | カスタム線パターンを保存するかどうかを定義します. |
| [IsSavingImageSeparately](../../aspose.diagram.saving/svgsaveoptions/issavingimageseparately/) { get; set; } | 画像を個別に保存するかどうかを定義します。 |
| [PageIndex](../../aspose.diagram.saving/svgsaveoptions/pageindex/) { get; set; } | レンダリングするページの 0 から始まるインデックスを取得または設定します。デフォルトは 0. です |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | 生成された画像のページ サイズを取得または設定します。[`PageSize`](../pagesize/)または null. |
| [Quality](../../aspose.diagram.saving/svgsaveoptions/quality/) { get; set; } | 生成された images の品質を決定する値を取得または設定し、ページを`JPEG`フォーマット。デフォルト値は 100 です |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat/) { get; set; } | この保存オプション オブジェクトが使用される場合にドキュメントが保存される形式を指定します。 |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | レンダリングする形状を取得または設定します。デフォルトのカウントは 0. です |
| [SVGFitToViewPort](../../aspose.diagram.saving/svgsaveoptions/svgfittoviewport/) { get; set; } | このプロパティが true の場合、生成された svg はビュー ポートに適合します。 |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | 警告コールバックを取得または設定します。 |

### 関連項目

* class [RenderingSaveOptions](../renderingsaveoptions/)
* 名前空間 [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* 組み立て [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
