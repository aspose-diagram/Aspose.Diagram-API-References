---
title: Char
second_title: Aspose.Diagram for Java API 참조
description: 도형 텍스트의 서식 속성(예: 글꼴 색상, 텍스트 스타일, 대소문자, 기준선에 대한 위치 및 포인트 크기)을 포함합니다.
type: docs
weight: 45
url: /ko/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

도형 텍스트의 서식 속성을 포함합니다(예: 글꼴, 색상, 텍스트 스타일, 대소문자, 기준선에 대한 위치 및 포인트 크기).
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Char()](#Char--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | 아시아 문자 텍스트를 서식 지정하는 데 사용되는 글꼴의 ID 번호를 지정합니다. |
| [getAsianFontName()](#getAsianFontName--) | 텍스트 서식에 사용되는 아시아 글꼴 이름을 지정합니다. Visio 2013에서 사용됩니다. |
| [getCase()](#getCase--) | 도형 텍스트의 대소문자를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Char 요소에 포함될 때, Color 요소입니다. |
| [getColorTrans()](#getColorTrans--) | 레이어 또는 도형 텍스트 색상의 투명도 정도를 0(완전히 불투명)에서 1(완전히 투명)까지 결정합니다. |
| [getComplexScriptFont()](#getComplexScriptFont--) | 복합 스크립트 문자로 구성된 텍스트를 서식 지정하는 데 사용되는 글꼴 번호를 포함합니다. |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | 텍스트 서식에 사용되는 ComplexScript 글꼴 이름을 지정합니다. Visio 2013에서 사용됩니다. |
| [getComplexScriptSize()](#getComplexScriptSize--) | 복합 스크립트 문자로 구성된 텍스트를 서식 지정하는 데 사용되는 글꼴 크기. |
| [getDblUnderline()](#getDblUnderline--) | 텍스트 범위에 이중 밑줄이 있는지 여부를 지정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | 텍스트가 이중 취소선으로 서식 지정되는지 여부를 결정합니다. |
| [getFont()](#getFont--) | 텍스트 서식에 사용되는 글꼴의 ID 번호를 지정합니다. |
| [getFontName()](#getFontName--) | 텍스트 서식에 사용되는 글꼴의 이름을 지정합니다. Visio 2013에 사용됩니다. |
| [getFontScale()](#getFontScale--) | 글꼴 너비를 지정합니다. |
| [getHighlight()](#getHighlight--) | 하이라이트를 지정합니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getLangID()](#getLangID--) | 셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다. |
| [getLetterspace()](#getLetterspace--) | 두 개 이상의 문자 사이의 간격을 지정합니다. |
| [getLocale()](#getLocale--) | 맞춤법 검사 목적으로 텍스트 실행의 로케일을 지정합니다. |
| [getLocalizeFont()](#getLocalizeFont--) | 도형 텍스트를 현지화(다른 언어로 번역)할지 여부를 지정합니다. |
| [getOverline()](#getOverline--) | 텍스트 위에 선이 있는지 여부를 지정합니다. |
| [getPerpendicular()](#getPerpendicular--) | 텍스트 블록에서 텍스트 필드가 다른 텍스트에 대해 수직으로 표시되는지 여부를 지정합니다. |
| [getPos()](#getPos--) | 도형 텍스트의 기준선에 대한 위치를 지정합니다. |
| [getRTLText()](#getRTLText--) | 현재 문자 실행의 텍스트 방향이 왼쪽에서 오른쪽인지 오른쪽에서 왼쪽인지 결정합니다. |
| [getSize()](#getSize--) | 도형 텍스트 블록 내 텍스트 크기를 지정합니다. |
| [getStrikethru()](#getStrikethru--) | 텍스트가 취소선으로 서식 지정되는지 여부를 지정합니다. |
| [getStyle()](#getStyle--) | 도형 텍스트 블록의 텍스트 범위에 적용되는 문자 서식을 지정합니다. |
| [getUseVertical()](#getUseVertical--) | 문자 실행이 수직인지 수평인지 결정합니다. |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | 글꼴이 굵게 표시되는지 여부를 나타냅니다. |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | 글꼴이 이중 취소선인지 여부를 나타냅니다. |
| [isDoubleUnderline()](#isDoubleUnderline--) | 글꼴이 이중 밑줄인지 여부를 나타냅니다. |
| [isItalic()](#isItalic--) | 글꼴이 이탤릭인지 여부를 나타냅니다. |
| [isStrikethrough()](#isStrikethrough--) | 글꼴이 취소선인지 여부를 나타냅니다. |
| [isSubscript()](#isSubscript--) | 글꼴이 아래 첨자인지 여부를 나타냅니다. |
| [isSuperscript()](#isSuperscript--) | 글꼴이 위 첨자인지 여부를 나타냅니다. |
| [isUnderline()](#isUnderline--) | 글꼴이 밑줄인지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)을 참조하십시오. |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | 이 속성에 대한 설명은 [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)을 참조하십시오. |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | 이 속성에 대한 설명은 [getCase()](../../com.aspose.diagram/char\#getCase--)을 참조하십시오. |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getColor()](../../com.aspose.diagram/char\#getColor--)을 참조하십시오. |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)를 참조하십시오. |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)를 참조하십시오. |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | 이 속성에 대한 설명은 [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)를 참조하십시오. |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)를 참조하십시오. |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)를 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/char\#getDel--)를 참조하십시오. |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)를 참조하십시오. |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getFont()](../../com.aspose.diagram/char\#getFont--)를 참조하십시오. |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | 이 속성에 대한 설명은 [getFontName()](../../com.aspose.diagram/char\#getFontName--)를 참조하십시오. |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)를 참조하십시오. |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)를 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/char\#getIX--)를 참조하십시오. |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getLangID()](../../com.aspose.diagram/char\#getLangID--)를 참조하십시오. |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)를 참조하십시오. |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | 이 속성에 대한 설명은 [getLocale()](../../com.aspose.diagram/char\#getLocale--)를 참조하십시오. |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | 이 속성에 대한 설명은 [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)를 참조하십시오. |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getOverline()](../../com.aspose.diagram/char\#getOverline--)를 참조하십시오. |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | 이 속성에 대한 설명은 [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)를 참조하십시오. |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | 이 속성에 대한 설명은 [getPos()](../../com.aspose.diagram/char\#getPos--)를 참조하십시오. |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)를 참조하십시오. |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getSize()](../../com.aspose.diagram/char\#getSize--)를 참조하십시오. |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)를 참조하십시오. |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | 이 속성에 대한 설명은 [getStyle()](../../com.aspose.diagram/char\#getStyle--)를 참조하십시오. |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)를 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
```


생성자.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 인스턴스의 깊은 복사본을 생성합니다.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


아시아 문자 텍스트를 서식 지정하는 데 사용되는 글꼴의 ID 번호를 지정합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


텍스트 서식에 사용되는 아시아 글꼴 이름을 지정합니다. Visio 2013에서 사용됩니다.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


도형 텍스트의 대소문자를 결정합니다.

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


Char 요소에 포함될 때, Color 요소입니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


레이어 또는 도형 텍스트 색상의 투명도 정도를 0(완전히 불투명)에서 1(완전히 투명)까지 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


복합 스크립트 문자로 구성된 텍스트를 서식 지정하는 데 사용되는 글꼴 번호를 포함합니다. 복합 스크립트는 문자 결합이나 형태 변환이 필요한 언어로, 오른쪽에서 왼쪽으로 쓰는 언어(아라비아어, 파르시어, 히브리어 및 우르두어)와 여러 남아시아 언어가 있습니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


텍스트 서식에 사용되는 ComplexScript 글꼴 이름을 지정합니다. Visio 2013에서 사용됩니다.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


복잡한 스크립트 문자로 구성된 텍스트를 서식 지정하는 데 사용되는 글꼴 크기입니다. 복잡한 스크립트는 문자 결합이나 형태 변환이 필요한 언어로, 오른쪽에서 왼쪽으로 쓰는 언어(아라비아어, 파르시어, 히브리어 및 우르두어)와 여러 남아시아 언어가 포함됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


텍스트 범위에 이중 밑줄이 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


텍스트가 이중 취소선으로 서식 지정되는지 여부를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


텍스트 서식에 사용되는 글꼴의 ID 번호를 지정합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


텍스트 서식에 사용되는 글꼴의 이름을 지정합니다. Visio 2013에 사용됩니다.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


글꼴 너비를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


하이라이트를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다. Microsoft Office 응용 프로그램에서 지원하는 언어와 해당 언어 ID 목록은 DocLangID 요소를 참조하십시오.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


두 개 이상의 문자 사이의 간격을 지정합니다. 간격은 1/20 포인트 단위로 추가하거나 감소시킬 수 있습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


맞춤법 검사 목적으로 텍스트 실행의 로케일을 지정합니다.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


도형 텍스트를 현지화(다른 언어로 번역)할지 여부를 지정합니다.

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


텍스트 위에 선이 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


텍스트 블록에서 텍스트 필드가 다른 텍스트에 대해 수직으로 표시되는지 여부를 지정합니다.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


도형 텍스트의 기준선에 대한 위치를 지정합니다.

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


현재 문자 실행의 텍스트 방향이 왼쪽에서 오른쪽인지 오른쪽에서 왼쪽인지 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


도형 텍스트 블록 내 텍스트 크기를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


텍스트가 취소선으로 서식 지정되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


도형 텍스트 블록의 텍스트 범위에 적용되는 문자 서식을 지정합니다.

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


문자 실행이 수직인지 수평인지 결정합니다.

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


글꼴이 굵게 표시되는지 여부를 나타냅니다.

**Returns:**
boolean
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


글꼴이 이중 취소선인지 여부를 나타냅니다.

**Returns:**
boolean
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


글꼴이 이중 밑줄인지 여부를 나타냅니다.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


글꼴이 이탤릭인지 여부를 나타냅니다.

**Returns:**
boolean
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


글꼴이 취소선인지 여부를 나타냅니다.

**Returns:**
boolean
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


글꼴이 아래 첨자인지 여부를 나타냅니다.

**Returns:**
boolean
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


글꼴이 위 첨자인지 여부를 나타냅니다.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


글꼴이 밑줄인지 여부를 나타냅니다.

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


이 속성에 대한 설명은 [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


이 속성에 대한 설명은 [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


이 속성에 대한 설명은 [getCase()](../../com.aspose.diagram/char\#getCase--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


이 속성에 대한 설명은 [getColor()](../../com.aspose.diagram/char\#getColor--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


이 속성에 대한 설명은 [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


이 속성에 대한 설명은 [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


이 속성에 대한 설명은 [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


이 속성에 대한 설명은 [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


이 속성에 대한 설명은 [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/char\#getDel--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


이 속성에 대한 설명은 [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


이 속성에 대한 설명은 [getFont()](../../com.aspose.diagram/char\#getFont--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


이 속성에 대한 설명은 [getFontName()](../../com.aspose.diagram/char\#getFontName--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


이 속성에 대한 설명은 [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


이 속성에 대한 설명은 [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/char\#getIX--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


이 속성에 대한 설명은 [getLangID()](../../com.aspose.diagram/char\#getLangID--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


이 속성에 대한 설명은 [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


이 속성에 대한 설명은 [getLocale()](../../com.aspose.diagram/char\#getLocale--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


이 속성에 대한 설명은 [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


이 속성에 대한 설명은 [getOverline()](../../com.aspose.diagram/char\#getOverline--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


이 속성에 대한 설명은 [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


이 속성에 대한 설명은 [getPos()](../../com.aspose.diagram/char\#getPos--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


이 속성에 대한 설명은 [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


이 속성에 대한 설명은 [getSize()](../../com.aspose.diagram/char\#getSize--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


이 속성에 대한 설명은 [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


이 속성에 대한 설명은 [getStyle()](../../com.aspose.diagram/char\#getStyle--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


이 속성에 대한 설명은 [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

