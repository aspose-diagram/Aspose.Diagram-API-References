---
title: FontConfigs
second_title: Aspose.Diagram for Java API 참조
description: 글꼴 설정을 지정합니다
type: docs
weight: 160
url: /ko/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

글꼴 설정을 지정합니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | 기본 글꼴 이름. |
| [getFontSources()](#getFontSources--) | 소스 목록을 포함하는 배열의 복사본을 가져옵니다. |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | 원본 글꼴이 없을 경우 사용할 글꼴 대체 이름을 포함하는 배열을 반환합니다. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | 글꼴이 없고 해당 글꼴의 대체가 설정되지 않은 경우 시스템 글꼴 대체를 먼저 사용할지 여부를 나타냅니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | 이 속성에 대한 설명은 [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)을(를) 참조하십시오. |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | 글꼴 폴더를 설정합니다. |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | 글꼴 폴더들을 설정합니다. |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | 글꼴 소스를 설정합니다. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | 주어진 원본 글꼴 이름에 대한 글꼴 대체 이름. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | 이 속성에 대한 설명은 [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontConfigs() {#FontConfigs--}
```
public FontConfigs()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


기본 글꼴 이름.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


소스 목록을 포함하는 배열의 복사본을 가져옵니다.

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


원본 글꼴이 없을 경우 사용할 글꼴 대체 이름을 포함하는 배열을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - 원본 글꼴이 제공되지 않을 경우 사용할 글꼴 대체 이름을 포함하는 배열입니다.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


글꼴이 제공되지 않고 해당 글꼴의 대체가 설정되지 않은 경우 시스템 글꼴 대체를 먼저 사용할지 여부를 지정합니다. 예: Ubuntu에서는 "Arial" 글꼴이 일반적으로 "Liberation Sans"로 대체됩니다. 기본값은 false입니다.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String value)
```


이 속성에 대한 설명은 [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


글꼴 폴더를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontFolder | java.lang.String | TrueType 글꼴을 포함하는 폴더입니다. |
| recursive | boolean | 하위 폴더를 스캔할지 여부를 결정합니다. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


글꼴 폴더들을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontFolders | java.lang.String[] | TrueType 글꼴을 포함하는 폴더들입니다. |
| recursive | boolean | 하위 폴더를 스캔할지 여부를 결정합니다. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


글꼴 소스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | TrueType 글꼴을 포함하는 소스 배열입니다. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


주어진 원본 글꼴 이름에 대한 글꼴 대체 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| originalFontName | java.lang.String | 원본 글꼴 이름입니다. |
| substituteFontNames | java.lang.String[] | 원본 글꼴이 제공되지 않을 경우 사용할 글꼴 대체 이름 목록입니다. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


이 속성에 대한 설명은 [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

