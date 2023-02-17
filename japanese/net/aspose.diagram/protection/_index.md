---
title: Protection
second_title: Aspose.Diagram for .NET API リファレンス
description: ロックは不注意による図形の変更を防ぐのに役立ちますがMicrosoft Visio が他の状況で値をリセットするのを防ぐことはできませんまたシェイプシート ウィンドウで行われた変更に対しても保護されません
type: docs
weight: 2880
url: /ja/net/aspose.diagram/protection/
---
## Protection class

ロックは、不注意による図形の変更を防ぐのに役立ちますが、Microsoft Visio が他の状況で値をリセットするのを防ぐことはできません。また、シェイプシート ウィンドウで行われた変更に対しても保護されません。

```csharp
public class Protection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Del](../../aspose.diagram/protection/del/) { get; set; } | 要素がローカルで削除されたかどうかを示すフラグ。値 1 は、要素がローカルで削除されたことを示します。 |
| [LockAspect](../../aspose.diagram/protection/lockaspect/) { get; } | 形状の縦横比をロックするかどうかを指定します。ロックされている場合、形状は比例してのみサイズ変更できます。 1 次元でサイズを変更することはできません. |
| [LockBegin](../../aspose.diagram/protection/lockbegin/) { get; } | 1-D 形状の始点が特定の位置に固定されているかどうかを指定します. |
| [LockCalcWH](../../aspose.diagram/protection/lockcalcwh/) { get; } | 頂点が編集されたとき、または Geom 要素で要素タイプが変更されたときに再計算できないように、形状の選択四角形をロックするかどうかを指定します. |
| [LockCrop](../../aspose.diagram/protection/lockcrop/) { get; } | Microsoft Visio のトリミング ツールで外部オブジェクトがトリミングされないようにロックするかどうかを指定します。 |
| [LockCustProp](../../aspose.diagram/protection/lockcustprop/) { get; } | [カスタム プロパティの定義] ダイアログ ボックスを使用して、ユーザーがユーザー インターフェイス (UI) でカスタム プロパティを追加、削除、または変更できるかどうかを決定します。 |
| [LockDelete](../../aspose.diagram/protection/lockdelete/) { get; } | 図形が削除されないようにロックするかどうかを指定します. |
| [LockEnd](../../aspose.diagram/protection/lockend/) { get; } | 1-D 形状の終点が特定の位置に固定されているかどうかを指定します. |
| [LockFormat](../../aspose.diagram/protection/lockformat/) { get; } | 図形の書式設定をロックして変更できないようにするかどうかを指定します。具体的には、この要素は、テキスト、線、および塗りつぶしの書式設定の変更、または形状が継承する Style 要素の変更から保護します. |
| [LockFromGroupFormat](../../aspose.diagram/protection/lockfromgroupformat/) { get; } | サブシェイプは、Visio ユーザー インターフェイスで親グループ図形に適用される書式変更をブロックできます。そうしないと、個々のグループ図形にカスケードされます。 |
| [LockGroup](../../aspose.diagram/protection/lockgroup/) { get; } | グループをロックしてグループ化を解除できないようにするかどうかを指定します。 |
| [LockHeight](../../aspose.diagram/protection/lockheight/) { get; } | 形状の高さをロックするかどうかを指定します。ロックされている場合、形状のサイズを変更しても高さは変わりません。 |
| [LockMoveX](../../aspose.diagram/protection/lockmovex/) { get; } | 形状の水平位置をロックして、水平方向に移動できないようにするかどうかを指定します。 |
| [LockMoveY](../../aspose.diagram/protection/lockmovey/) { get; } | 図形の垂直位置をロックして、垂直方向に移動できないようにするかどうかを指定します。 |
| [LockRotate](../../aspose.diagram/protection/lockrotate/) { get; } | 回転ツールまたは Microsoft Visio の [左に回転] コマンドまたは [右に回転] コマンドを使用して回転しないように図形をロックするかどうかを指定します。 |
| [LockSelect](../../aspose.diagram/protection/lockselect/) { get; } | 頂点が編集されたとき、または Geom 要素で要素タイプが変更されたときに再計算できないように、形状の選択四角形をロックするかどうかを指定します. |
| [LockTextEdit](../../aspose.diagram/protection/locktextedit/) { get; } | 図形のテキストをロックして編集できないようにするかどうかを指定します。ただし、[テキスト] ダイアログ ボックスの [フォント] タブにある [スタイル] オプションを使用して、スタイルを適用することにより、テキストを書式設定することができます. |
| [LockThemeColors](../../aspose.diagram/protection/lockthemecolors/) { get; } | ユーザーがシェイプにテーマ カラーを適用できないようにします。 |
| [LockThemeEffects](../../aspose.diagram/protection/lockthemeeffects/) { get; } | ユーザーがシェイプにテーマ効果を適用できないようにします。 |
| [LockVtxEdit](../../aspose.diagram/protection/lockvtxedit/) { get; } | シェイプの頂点をロックして、ツールバーのどのツールでも編集できないようにするかどうかを指定します。 |
| [LockWidth](../../aspose.diagram/protection/lockwidth/) { get; } | 形状のサイズが変更されたときに変更されないように、形状の幅をロックするかどうかを指定します。 |

### 関連項目

* 名前空間 [Aspose.Diagram](../../aspose.diagram/)
* 組み立て [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->