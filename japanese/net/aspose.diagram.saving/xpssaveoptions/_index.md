---
title: XPSSaveOptions
second_title: Aspose.Diagram for .NET API リファレンス
description: ダイアグラム ページを XPS にレンダリングするときに追加のオプションを指定できます
type: docs
weight: 3520
url: /ja/net/aspose.diagram.saving/xpssaveoptions/
---
## XPSSaveOptions class

ダイアグラム ページを XPS にレンダリングするときに、追加のオプションを指定できます。

```csharp
public class XPSSaveOptions : SaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XPSSaveOptions](xpssaveoptions/)() | にドキュメントを保存するために使用できる、このクラスの新しいインスタンスを初期化します。[`XPS`](../../aspose.diagram/savefileformat/) format. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | ダイアグラム内の文字が Unicode であり、正しいフォント値が設定されていないか、フォントがローカルにインストールされていない場合、 PDF、画像、または XPS でブロックとして表示される場合があります。 これらを表示するには、MingLiu や MS ゴシックなどの DefaultFont を設定します。文字. |
| [ExportHiddenPage](../../aspose.diagram.saving/xpssaveoptions/exporthiddenpage/) { get; set; } | 隠しページをエクスポートする必要があるかどうかを定義します. |
| [PageCount](../../aspose.diagram.saving/xpssaveoptions/pagecount/) { get; set; } | XPS でレンダリングするページ数を取得または設定します。 デフォルトは MaxValue で、ダイアグラムのすべてのページがレンダリングされることを意味します。 |
| [PageIndex](../../aspose.diagram.saving/xpssaveoptions/pageindex/) { get; set; } | レンダリングする最初のページの 0 から始まるインデックスを取得または設定します。デフォルトは 0. です |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/xpssaveoptions/saveforegroundpagesonly/) { get; set; } | すべてのページを画像で保存するか、前景のみで保存するかを指定します。 |
| override [SaveFormat](../../aspose.diagram.saving/xpssaveoptions/saveformat/) { get; set; } | この保存オプション オブジェクトが使用される場合、レンダリングされたダイアグラム ページが保存される形式を指定します。[`XPS`](../../aspose.diagram/savefileformat/)のみ. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | 警告コールバックを取得または設定します。 |

### 関連項目

* class [SaveOptions](../saveoptions/)
* 名前空間 [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* 組み立て [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
