---
title: IPageSavingCallback
second_title: Aspose.Diagram for Java API 참조
description: 페이지 저장 프로세스의 진행 상황을 제어/표시합니다.
type: docs
weight: 456
url: /ko/java/com.aspose.diagram/ipagesavingcallback/
---
```
public interface IPageSavingCallback
```

페이지 저장 프로세스의 진행 상황을 제어/표시합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [pageEndSaving(PageEndSavingArgs args)](#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-) | Control/페이지가 출력될 끝을 나타냅니다. |
| [pageStartSaving(PageStartSavingArgs args)](#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-) | Control/페이지가 출력되기 시작함을 나타냅니다. |
### pageEndSaving(PageEndSavingArgs args) {#pageEndSaving-com.aspose.diagram.PageEndSavingArgs-}
```
public abstract void pageEndSaving(PageEndSavingArgs args)
```


Control/페이지가 출력될 끝을 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | [PageEndSavingArgs](../../com.aspose.diagram/pageendsavingargs) | 페이지 저장 프로세스 종료에 대한 정보. |

### pageStartSaving(PageStartSavingArgs args) {#pageStartSaving-com.aspose.diagram.PageStartSavingArgs-}
```
public abstract void pageStartSaving(PageStartSavingArgs args)
```


Control/페이지가 출력되기 시작함을 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | [PageStartSavingArgs](../../com.aspose.diagram/pagestartsavingargs) | 페이지 저장 프로세스 시작에 대한 정보. |

