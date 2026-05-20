---
title: Char
second_title: Aspose.Diagram for Java API リファレンス
description: 形状のテキストの書式属性（フォントカラー、テキストスタイル、ケース、ベースラインに対する位置、ポイントサイズなど）を含みます。
type: docs
weight: 45
url: /ja/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

シェイプのテキストの書式属性（フォント、色、テキストスタイル、大文字小文字、ベースラインに対する位置、ポイントサイズなど）を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Char()](#Char--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | アジア文字を含むテキストの書式設定に使用されるフォントの ID 番号を指定します。 |
| [getAsianFontName()](#getAsianFontName--) | テキストの書式設定に使用されるフォントのアジアフォント名を指定します。Visio 2013 用です。 |
| [getCase()](#getCase--) | シェイプのテキストの大文字小文字を決定します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Char 要素に含まれる場合、Color 要素です。 |
| [getColorTrans()](#getColorTrans--) | レイヤーまたはシェイプのテキストカラーの透明度を決定します。0（完全に不透明）から 1（完全に透明）までの範囲です。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 複合スクリプト文字で構成されたテキストの書式設定に使用されるフォントの番号を含みます。 |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | テキストの書式設定に使用されるフォントの ComplexScript フォント名を指定します。Visio 2013 用です。 |
| [getComplexScriptSize()](#getComplexScriptSize--) | 複合スクリプト文字で構成されたテキストの書式設定に使用されるフォントサイズです。 |
| [getDblUnderline()](#getDblUnderline--) | テキスト範囲に二重下線が付いているかどうかを指定します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | テキストが二重取り消し線として書式設定されているかどうかを判断します。 |
| [getFont()](#getFont--) | テキストの書式設定に使用されるフォントの ID 番号を指定します。 |
| [getFontName()](#getFontName--) | テキストの書式設定に使用されるフォントの名前を指定します。Visio 2013 用です。 |
| [getFontScale()](#getFontScale--) | フォントの幅を指定します。 |
| [getHighlight()](#getHighlight--) | ハイライトを指定します。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getLangID()](#getLangID--) | セルの数式、テキスト、カスタムプロパティ、またはコメントが入力された言語のロケール ID (LCID) を示します。 |
| [getLetterspace()](#getLetterspace--) | 2 文字以上の文字間のスペース量を指定します。 |
| [getLocale()](#getLocale--) | スペルチェック目的でテキスト ランのロケールを指定します。 |
| [getLocalizeFont()](#getLocalizeFont--) | シェイプテキストをローカライズ（別の言語に翻訳）するかどうかを指定します。 |
| [getOverline()](#getOverline--) | テキストの上に線があるかどうかを指定します。 |
| [getPerpendicular()](#getPerpendicular--) | テキスト ブロック内の他のテキストに対してテキスト フィールドが垂直に表示されるかどうかを指定します。 |
| [getPos()](#getPos--) | シェイプのテキストの位置をベースラインに対して指定します。 |
| [getRTLText()](#getRTLText--) | 現在の文字ランのテキスト方向が左から右か右から左かを判断します。 |
| [getSize()](#getSize--) | シェイプのテキスト ブロック内のテキストサイズを指定します。 |
| [getStrikethru()](#getStrikethru--) | テキストが取り消し線として書式設定されているかどうかを指定します。 |
| [getStyle()](#getStyle--) | シェイプのテキスト ブロック内のテキスト範囲に適用される文字書式設定を指定します。 |
| [getUseVertical()](#getUseVertical--) | 文字ランが縦向きか横向きかを判断します。 |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | フォントが太字かどうかを示します。 |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | フォントが二重取り消し線かどうかを示します。 |
| [isDoubleUnderline()](#isDoubleUnderline--) | フォントが二重下線かどうかを示します。 |
| [isItalic()](#isItalic--) | フォントが斜体かどうかを示します。 |
| [isStrikethrough()](#isStrikethrough--) | フォントが取り消し線かどうかを示します。 |
| [isSubscript()](#isSubscript--) | フォントが下付き文字かどうかを示します。 |
| [isSuperscript()](#isSuperscript--) | フォントが上付き文字かどうかを示します。 |
| [isUnderline()](#isUnderline--) | フォントが下線かどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) を参照してください。 |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | このプロパティの説明については、[getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) を参照してください。 |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | このプロパティの説明については、[getCase()](../../com.aspose.diagram/char\#getCase--) を参照してください。 |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getColor()](../../com.aspose.diagram/char\#getColor--) を参照してください。 |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getColorTrans](../../com.aspose.diagram/char\#getColorTrans--) を参照してください。 |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getComplexScriptFont](../../com.aspose.diagram/char\#getComplexScriptFont--) を参照してください。 |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | このプロパティの説明については、[getComplexScriptFontName](../../com.aspose.diagram/char\#getComplexScriptFontName--) を参照してください。 |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getComplexScriptSize](../../com.aspose.diagram/char\#getComplexScriptSize--) を参照してください。 |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getDblUnderline](../../com.aspose.diagram/char\#getDblUnderline--) を参照してください。 |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel](../../com.aspose.diagram/char\#getDel--) を参照してください。 |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getDoubleStrikethrough](../../com.aspose.diagram/char\#getDoubleStrikethrough--) を参照してください。 |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getFont](../../com.aspose.diagram/char\#getFont--) を参照してください。 |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | このプロパティの説明については、[getFontName](../../com.aspose.diagram/char\#getFontName--) を参照してください。 |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getFontScale](../../com.aspose.diagram/char\#getFontScale--) を参照してください。 |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getHighlight](../../com.aspose.diagram/char\#getHighlight--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX](../../com.aspose.diagram/char\#getIX--) を参照してください。 |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getLangID](../../com.aspose.diagram/char\#getLangID--) を参照してください。 |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getLetterspace](../../com.aspose.diagram/char\#getLetterspace--) を参照してください。 |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | このプロパティの説明については、[getLocale](../../com.aspose.diagram/char\#getLocale--) を参照してください。 |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | このプロパティの説明については、[getLocalizeFont](../../com.aspose.diagram/char\#getLocalizeFont--) を参照してください。 |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getOverline](../../com.aspose.diagram/char\#getOverline--) を参照してください。 |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | このプロパティの説明については、[getPerpendicular](../../com.aspose.diagram/char\#getPerpendicular--) を参照してください。 |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | このプロパティの説明については、[getPos](../../com.aspose.diagram/char\#getPos--) を参照してください。 |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getRTLText](../../com.aspose.diagram/char\#getRTLText--) を参照してください。 |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getSize](../../com.aspose.diagram/char\#getSize--) を参照してください。 |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getStrikethru](../../com.aspose.diagram/char\#getStrikethru--) を参照してください。 |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | このプロパティの説明については、[getStyle](../../com.aspose.diagram/char\#getStyle--) を参照してください。 |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getUseVertical](../../com.aspose.diagram/char\#getUseVertical--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
```


コンストラクタ。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


このインスタンスのディープコピーを作成します。

**Returns:**
java.lang.Object -
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
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


アジア文字を含むテキストの書式設定に使用されるフォントの ID 番号を指定します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


テキストの書式設定に使用されるフォントのアジアフォント名を指定します。Visio 2013 用です。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


シェイプのテキストの大文字小文字を決定します。

**Returns:**
[Case](../../com.aspose.diagram/case)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Char 要素に含まれる場合、Color 要素です。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


レイヤーまたはシェイプのテキストカラーの透明度を決定します。0（完全に不透明）から 1（完全に透明）までの範囲です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


複雑スクリプト文字で構成されたテキストの書式設定に使用されるフォントの番号が含まれます。複雑スクリプトとは、文字の結合や形状変化が必要な言語で、右から左へ書く言語（アラビア語、ペルシア語、ヘブライ語、ウルドゥー語）や南アジアのいくつかの言語が該当します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


テキストの書式設定に使用されるフォントの ComplexScript フォント名を指定します。Visio 2013 用です。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


複雑なスクリプト文字で構成されたテキストをフォーマットするために使用されるフォントのサイズ。複雑なスクリプトとは、文字の結合や形状変化が必要な言語で、右から左へ書く言語（アラビア語、ペルシア語、ヘブライ語、ウルドゥー語）やいくつかの南アジア言語が含まれます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


テキスト範囲に二重下線が付いているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


テキストが二重取り消し線として書式設定されているかどうかを判断します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


テキストの書式設定に使用されるフォントの ID 番号を指定します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


テキストの書式設定に使用されるフォントの名前を指定します。Visio 2013 用です。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


フォントの幅を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


ハイライトを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


親要素内の要素のゼロベースインデックスです。

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


セルの数式、テキスト、カスタム プロパティ、またはコメントが入力された言語のロケール ID（LCID）を示します。Microsoft Office アプリケーションでサポートされている言語とそれに対応する言語 ID の一覧については、DocLangID 要素を参照してください。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


2 文字以上の間のスペース量を指定します。スペースは 1/20 ポイント単位で増減できます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


スペルチェック目的でテキスト ランのロケールを指定します。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


シェイプテキストをローカライズ（別の言語に翻訳）するかどうかを指定します。

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


テキストの上に線があるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


テキスト ブロック内の他のテキストに対してテキスト フィールドが垂直に表示されるかどうかを指定します。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


シェイプのテキストの位置をベースラインに対して指定します。

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


現在の文字ランのテキスト方向が左から右か右から左かを判断します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


シェイプのテキスト ブロック内のテキストサイズを指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


テキストが取り消し線として書式設定されているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


シェイプのテキスト ブロック内のテキスト範囲に適用される文字書式設定を指定します。

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


文字ランが縦向きか横向きかを判断します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBold() {#isBold--}
```
public boolean isBold()
```


フォントが太字かどうかを示します。

**Returns:**
boolean
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


フォントが二重取り消し線かどうかを示します。

**Returns:**
boolean
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


フォントが二重下線かどうかを示します。

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


フォントが斜体かどうかを示します。

**Returns:**
boolean
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


フォントが取り消し線かどうかを示します。

**Returns:**
boolean
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


フォントが下付き文字かどうかを示します。

**Returns:**
boolean
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


フォントが上付き文字かどうかを示します。

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


フォントが下線かどうかを示します。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAsianFont(IntValue value) {#setAsianFont-com.aspose.diagram.IntValue-}
```
public void setAsianFont(IntValue value)
```


このプロパティの説明については、[getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


このプロパティの説明については、[getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


このプロパティの説明については、[getCase()](../../com.aspose.diagram/char\#getCase--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


このプロパティの説明については、[getColor()](../../com.aspose.diagram/char\#getColor--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


このプロパティの説明については、[getColorTrans](../../com.aspose.diagram/char\#getColorTrans--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


このプロパティの説明については、[getComplexScriptFont](../../com.aspose.diagram/char\#getComplexScriptFont--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


このプロパティの説明については、[getComplexScriptFontName](../../com.aspose.diagram/char\#getComplexScriptFontName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


このプロパティの説明については、[getComplexScriptSize](../../com.aspose.diagram/char\#getComplexScriptSize--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


このプロパティの説明については、[getDblUnderline](../../com.aspose.diagram/char\#getDblUnderline--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel](../../com.aspose.diagram/char\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


このプロパティの説明については、[getDoubleStrikethrough](../../com.aspose.diagram/char\#getDoubleStrikethrough--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


このプロパティの説明については、[getFont](../../com.aspose.diagram/char\#getFont--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


このプロパティの説明については、[getFontName](../../com.aspose.diagram/char\#getFontName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


このプロパティの説明については、[getFontScale](../../com.aspose.diagram/char\#getFontScale--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


このプロパティの説明については、[getHighlight](../../com.aspose.diagram/char\#getHighlight--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX](../../com.aspose.diagram/char\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


このプロパティの説明については、[getLangID](../../com.aspose.diagram/char\#getLangID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


このプロパティの説明については、[getLetterspace](../../com.aspose.diagram/char\#getLetterspace--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


このプロパティの説明については、[getLocale](../../com.aspose.diagram/char\#getLocale--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


このプロパティの説明については、[getLocalizeFont](../../com.aspose.diagram/char\#getLocalizeFont--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


このプロパティの説明については、[getOverline](../../com.aspose.diagram/char\#getOverline--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


このプロパティの説明については、[getPerpendicular](../../com.aspose.diagram/char\#getPerpendicular--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


このプロパティの説明については、[getPos](../../com.aspose.diagram/char\#getPos--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


このプロパティの説明については、[getRTLText](../../com.aspose.diagram/char\#getRTLText--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


このプロパティの説明については、[getSize](../../com.aspose.diagram/char\#getSize--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


このプロパティの説明については、[getStrikethru](../../com.aspose.diagram/char\#getStrikethru--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


このプロパティの説明については、[getStyle](../../com.aspose.diagram/char\#getStyle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


このプロパティの説明については、[getUseVertical](../../com.aspose.diagram/char\#getUseVertical--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

