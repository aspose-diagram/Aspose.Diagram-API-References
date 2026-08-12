---
title: "Char"
linktitle: "Char"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Contains the formatting attributes for the shape's text, such as font, color, text style, case, position relative to the baseline, and point size."
type: docs
weight: 240
url: /nodejs/aspose.diagram/char/
---

## Char class

Contains the formatting attributes for the shape's text, such as font, color, text style, case, position relative to the baseline, and point size.

```js
new Char()
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [deepClone()](#deepclone) | Creates deep copy of this instance. |
| [getAsianFont()](#getasianfont) | Specifies the ID number of the font used to format text containing Asian characters. |
| [getAsianFontName()](#getasianfontname) | It specified the asian font name of the font used to format the text.It is using for visio 2013 |
| [getCase()](#getcase) | Determines the case of a shape's text. |
| [getColor()](#getcolor) | When contained in a Char element, the Color element. |
| [getColorTrans()](#getcolortrans) | Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely tra |
| [getComplexScriptFont()](#getcomplexscriptfont) | Contains the number of the font used to format text composed of complex script characters. Complex scripts are languages |
| [getComplexScriptFontName()](#getcomplexscriptfontname) | It specified the ComplexScript font name of the font used to format the text.It is using for visio 2013 |
| [getComplexScriptSize()](#getcomplexscriptsize) | The size of the font used to format text composed of complex script characters. Complex scripts are languages whose char |
| [getDblUnderline()](#getdblunderline) | Specifies whether the range of text has a double underline below it. |
| [getDel()](#getdel) | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [getDoubleStrikethrough()](#getdoublestrikethrough) | Determines whether text is formatted as double strikethrough. |
| [getFont()](#getfont) | Specifies the ID number of the font used to format the text. |
| [getFontName()](#getfontname) | It specified the font name of the font used to format the text.It is using for visio 2013 |
| [getFontScale()](#getfontscale) | Specifies the font width. |
| [getHighlight()](#gethighlight) | It specified highlight. |
| [getIX()](#getix) | The zero-based index of the element within its parent element. |
| [getLangID()](#getlangid) | Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. |
| [getLetterspace()](#getletterspace) | Specifies the amount of space between two or more characters. Space can be added or subtracted in 1/20th point increment |
| [getLocale()](#getlocale) | It specified the locale of the text run for spell-checking purposes. |
| [getLocalizeFont()](#getlocalizefont) | Specifies whether the shape text should be localized (translated into another language). |
| [getOverline()](#getoverline) | Specifies whether the text has a line above it. |
| [getPerpendicular()](#getperpendicular) | It specified whether a text field appears perpendicular to the other text in a text block. |
| [getPos()](#getpos) | Specifies the position of the shape's text relative to the baseline. |
| [getRTLText()](#getrtltext) | Determines if the text direction of the current character run is left to right or right to left. |
| [getSize()](#getsize) | Specifies the size of the text in the shape's text block. |
| [getStrikethru()](#getstrikethru) | Specifies whether the text is formatted as strikethrough. |
| [getStyle()](#getstyle) | Specifies the character formatting applied to a range of text in the shape's text block. |
| [getUseVertical()](#getusevertical) | Determines whether the character run is vertical or horizontal. |
| [isBold()](#isbold) | Indicating whether the font is bold. |
| [isDoubleStrikethrough()](#isdoublestrikethrough) | Indicating whether the font is doubleStrikethrough. |
| [isDoubleUnderline()](#isdoubleunderline) | Indicating whether the font is double underline. |
| [isItalic()](#isitalic) | Indicating whether the font is italic. |
| [isStrikethrough()](#isstrikethrough) | Indicating whether the font is strikethrough. |
| [isSubscript()](#issubscript) | Indicating whether the font is subscript. |
| [isSuperscript()](#issuperscript) | Indicating whether the font is superscript. |
| [isUnderline()](#isunderline) | Indicating whether the font is underline. |
| [setAsianFont()](#setasianfont) | Specifies the ID number of the font used to format text containing Asian characters. |
| [setAsianFontName()](#setasianfontname) | It specified the asian font name of the font used to format the text.It is using for visio 2013 |
| [setCase()](#setcase) | Determines the case of a shape's text. |
| [setColor()](#setcolor) | When contained in a Char element, the Color element. |
| [setColorTrans()](#setcolortrans) | Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely tra |
| [setComplexScriptFont()](#setcomplexscriptfont) | Contains the number of the font used to format text composed of complex script characters. Complex scripts are languages |
| [setComplexScriptFontName()](#setcomplexscriptfontname) | It specified the ComplexScript font name of the font used to format the text.It is using for visio 2013 |
| [setComplexScriptSize()](#setcomplexscriptsize) | The size of the font used to format text composed of complex script characters. Complex scripts are languages whose char |
| [setDblUnderline()](#setdblunderline) | Specifies whether the range of text has a double underline below it. |
| [setDel()](#setdel) | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [setDoubleStrikethrough()](#setdoublestrikethrough) | Determines whether text is formatted as double strikethrough. |
| [setFont()](#setfont) | Specifies the ID number of the font used to format the text. |
| [setFontName()](#setfontname) | It specified the font name of the font used to format the text.It is using for visio 2013 |
| [setFontScale()](#setfontscale) | Specifies the font width. |
| [setHighlight()](#sethighlight) | It specified highlight. |
| [setIX()](#setix) | The zero-based index of the element within its parent element. |
| [setLangID()](#setlangid) | Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. |
| [setLetterspace()](#setletterspace) | Specifies the amount of space between two or more characters. Space can be added or subtracted in 1/20th point increment |
| [setLocale()](#setlocale) | It specified the locale of the text run for spell-checking purposes. |
| [setLocalizeFont()](#setlocalizefont) | Specifies whether the shape text should be localized (translated into another language). |
| [setOverline()](#setoverline) | Specifies whether the text has a line above it. |
| [setPerpendicular()](#setperpendicular) | It specified whether a text field appears perpendicular to the other text in a text block. |
| [setPos()](#setpos) | Specifies the position of the shape's text relative to the baseline. |
| [setRTLText()](#setrtltext) | Determines if the text direction of the current character run is left to right or right to left. |
| [setSize()](#setsize) | Specifies the size of the text in the shape's text block. |
| [setStrikethru()](#setstrikethru) | Specifies whether the text is formatted as strikethrough. |
| [setStyle()](#setstyle) | Specifies the character formatting applied to a range of text in the shape's text block. |
| [setUseVertical()](#setusevertical) | Determines whether the character run is vertical or horizontal. |

### deepClone() {#deepclone}

Creates deep copy of this instance.

**Returns:** Object — `Object`

### getAsianFont() {#getasianfont}

Specifies the ID number of the font used to format text containing Asian characters.

### getAsianFontName() {#getasianfontname}

It specified the asian font name of the font used to format the text.It is using for visio 2013

### getCase() {#getcase}

Determines the case of a shape's text.

### getColor() {#getcolor}

When contained in a Char element, the Color element.

### getColorTrans() {#getcolortrans}

Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely transparent).

### getComplexScriptFont() {#getcomplexscriptfont}

Contains the number of the font used to format text composed of complex script characters. Complex scripts are languages whose characters require ligation or shaping, such as the right-to-left languages (Arabic, Farsi, Hebrew, and Urdu) and several South Asian languages.

### getComplexScriptFontName() {#getcomplexscriptfontname}

It specified the ComplexScript font name of the font used to format the text.It is using for visio 2013

### getComplexScriptSize() {#getcomplexscriptsize}

The size of the font used to format text composed of complex script characters. Complex scripts are languages whose characters require ligation or shaping, such as the right-to-left languages (Arabic, Farsi, Hebrew, and Urdu) and several South Asian languages.

### getDblUnderline() {#getdblunderline}

Specifies whether the range of text has a double underline below it.

### getDel() {#getdel}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

### getDoubleStrikethrough() {#getdoublestrikethrough}

Determines whether text is formatted as double strikethrough.

### getFont() {#getfont}

Specifies the ID number of the font used to format the text.

### getFontName() {#getfontname}

It specified the font name of the font used to format the text.It is using for visio 2013

### getFontScale() {#getfontscale}

Specifies the font width.

### getHighlight() {#gethighlight}

It specified highlight.

### getIX() {#getix}

The zero-based index of the element within its parent element.

### getLangID() {#getlangid}

Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. For a list of languages supported by Microsoft Office applications and their corresponding language IDs, see the DocLangID element.

### getLetterspace() {#getletterspace}

Specifies the amount of space between two or more characters. Space can be added or subtracted in 1/20th point increments.

### getLocale() {#getlocale}

It specified the locale of the text run for spell-checking purposes.

### getLocalizeFont() {#getlocalizefont}

Specifies whether the shape text should be localized (translated into another language).

### getOverline() {#getoverline}

Specifies whether the text has a line above it.

### getPerpendicular() {#getperpendicular}

It specified whether a text field appears perpendicular to the other text in a text block.

### getPos() {#getpos}

Specifies the position of the shape's text relative to the baseline.

### getRTLText() {#getrtltext}

Determines if the text direction of the current character run is left to right or right to left.

### getSize() {#getsize}

Specifies the size of the text in the shape's text block.

### getStrikethru() {#getstrikethru}

Specifies whether the text is formatted as strikethrough.

### getStyle() {#getstyle}

Specifies the character formatting applied to a range of text in the shape's text block.

### getUseVertical() {#getusevertical}

Determines whether the character run is vertical or horizontal.

### isBold() {#isbold}

Indicating whether the font is bold.

### isDoubleStrikethrough() {#isdoublestrikethrough}

Indicating whether the font is doubleStrikethrough.

### isDoubleUnderline() {#isdoubleunderline}

Indicating whether the font is double underline.

### isItalic() {#isitalic}

Indicating whether the font is italic.

### isStrikethrough() {#isstrikethrough}

Indicating whether the font is strikethrough.

### isSubscript() {#issubscript}

Indicating whether the font is subscript.

### isSuperscript() {#issuperscript}

Indicating whether the font is superscript.

### isUnderline() {#isunderline}

Indicating whether the font is underline.

### setAsianFont() {#setasianfont}

Specifies the ID number of the font used to format text containing Asian characters.

### setAsianFontName() {#setasianfontname}

It specified the asian font name of the font used to format the text.It is using for visio 2013

### setCase() {#setcase}

Determines the case of a shape's text.

### setColor() {#setcolor}

When contained in a Char element, the Color element.

### setColorTrans() {#setcolortrans}

Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely transparent).

### setComplexScriptFont() {#setcomplexscriptfont}

Contains the number of the font used to format text composed of complex script characters. Complex scripts are languages whose characters require ligation or shaping, such as the right-to-left languages (Arabic, Farsi, Hebrew, and Urdu) and several South Asian languages.

### setComplexScriptFontName() {#setcomplexscriptfontname}

It specified the ComplexScript font name of the font used to format the text.It is using for visio 2013

### setComplexScriptSize() {#setcomplexscriptsize}

The size of the font used to format text composed of complex script characters. Complex scripts are languages whose characters require ligation or shaping, such as the right-to-left languages (Arabic, Farsi, Hebrew, and Urdu) and several South Asian languages.

### setDblUnderline() {#setdblunderline}

Specifies whether the range of text has a double underline below it.

### setDel() {#setdel}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

### setDoubleStrikethrough() {#setdoublestrikethrough}

Determines whether text is formatted as double strikethrough.

### setFont() {#setfont}

Specifies the ID number of the font used to format the text.

### setFontName() {#setfontname}

It specified the font name of the font used to format the text.It is using for visio 2013

### setFontScale() {#setfontscale}

Specifies the font width.

### setHighlight() {#sethighlight}

It specified highlight.

### setIX() {#setix}

The zero-based index of the element within its parent element.

### setLangID() {#setlangid}

Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. For a list of languages supported by Microsoft Office applications and their corresponding language IDs, see the DocLangID element.

### setLetterspace() {#setletterspace}

Specifies the amount of space between two or more characters. Space can be added or subtracted in 1/20th point increments.

### setLocale() {#setlocale}

It specified the locale of the text run for spell-checking purposes.

### setLocalizeFont() {#setlocalizefont}

Specifies whether the shape text should be localized (translated into another language).

### setOverline() {#setoverline}

Specifies whether the text has a line above it.

### setPerpendicular() {#setperpendicular}

It specified whether a text field appears perpendicular to the other text in a text block.

### setPos() {#setpos}

Specifies the position of the shape's text relative to the baseline.

### setRTLText() {#setrtltext}

Determines if the text direction of the current character run is left to right or right to left.

### setSize() {#setsize}

Specifies the size of the text in the shape's text block.

### setStrikethru() {#setstrikethru}

Specifies whether the text is formatted as strikethrough.

### setStyle() {#setstyle}

Specifies the character formatting applied to a range of text in the shape's text block.

### setUseVertical() {#setusevertical}

Determines whether the character run is vertical or horizontal.
