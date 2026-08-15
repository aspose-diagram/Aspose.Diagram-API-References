---
title: CoordinateCollection
second_title: Aspose.Diagram for Java API Reference
description: निर्देशांक संग्रह।
type: docs
weight: 102
url: /hi/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

निर्देशांक संग्रह।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | संग्रह में ArcTo ऑब्जेक्ट जोड़ें। |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | संग्रह में Coordinate ऑब्जेक्ट जोड़ें। |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | संग्रह में Ellipse ऑब्जेक्ट जोड़ें। |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | संग्रह में EllipticalArcTo ऑब्जेक्ट जोड़ें। |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | संग्रह में InfiniteLine ऑब्जेक्ट जोड़ें। |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | संग्रह में LineTo ऑब्जेक्ट जोड़ें। |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | संग्रह में MoveTo ऑब्जेक्ट जोड़ें। |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | संग्रह में NURBSTo ऑब्जेक्ट जोड़ें। |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | संग्रह में PolylineTo ऑब्जेक्ट जोड़ें। |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | संग्रह में RelCubBezTo ऑब्जेक्ट जोड़ें। |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | संग्रह में RelEllipticalArcTo ऑब्जेक्ट जोड़ें। |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | संग्रह में RelLineTo ऑब्जेक्ट जोड़ें। |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | संग्रह में RelMoveTo ऑब्जेक्ट जोड़ें। |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | संग्रह में RelQuadBezTo ऑब्जेक्ट जोड़ें। |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | संग्रह में SplineKnot ऑब्जेक्ट जोड़ें। |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | संग्रह में SplineStart ऑब्जेक्ट जोड़ें। |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getArcToCol()](#getArcToCol--) | X, Y और A तत्वों द्वारा क्रमशः दर्शाए गए एक वृत्तीय चाप के x और y निर्देशांक तथा बाउ को शामिल करता है। |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getEllipseCol()](#getEllipseCol--) | दीर्घवृत्त के केंद्र बिंदु और दो बिंदुओं के x- तथा y-निर्देशांक निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | एक दीर्घवृत्तीय चाप के बारे में जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | असीम रेखा पर दो बिंदुओं के x- और y-निर्देशांक निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getLineToCol()](#getLineToCol--) | एक सीधी रेखा खंड के अंतिम शीर्ष के x- और y-निर्देशांक शामिल करता है। |
| [getMoveToCol()](#getMoveToCol--) | एक आकार के पहले शीर्ष के x- और y-निर्देशांक शामिल करता है, या पथ में टूटने के बाद पहले शीर्ष के x- और y-निर्देशांक शामिल करता है। |
| [getNURBSToCol()](#getNURBSToCol--) | x- और y-निर्देशांक, दूसरे से अंतिम गाँठ की स्थिति, अंतिम वजन की स्थिति, पहली गाँठ की स्थिति, पहले वजन की स्थिति, और एक nonuniform rational B-spline (NURBS) के लिए सूत्र शामिल करता है। |
| [getPolylineToCol()](#getPolylineToCol--) | एक बहुरेखा के अंतिम बिंदु और बहुरेखा सूत्र के x- और y-निर्देशांक शामिल करता है। |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | RelCubBezTo के बिंदुओं के लिए x- और y-निर्देशांक शामिल हैं। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए गए हैं। |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | एक दीर्घवृत्तीय चाप के बारे में जानकारी निर्दिष्ट करने वाले तत्व शामिल करता है। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट होते हैं। |
| [getRelLineToCol()](#getRelLineToCol--) | एक सीधी रेखा खंड के अंतिम शीर्ष के x- और y-निर्देशांक शामिल करता है। |
| [getRelMoveToCol()](#getRelMoveToCol--) | एक आकार के पहले शीर्ष के x और y निर्देशांक शामिल करता है, या पथ में एक ब्रेक के बाद पहले शीर्ष के x और y निर्देशांक शामिल करता है। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए जाते हैं। |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | RelQuadBezTo के बिंदुओं के लिए x- और y-निर्देशांक शामिल हैं। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए गए हैं। |
| [getSplineKnotCol()](#getSplineKnotCol--) | स्प्लाइन के नियंत्रण बिंदु और स्प्लाइन के नॉट के x और y निर्देशांक को सम्मिलित करता है, जो क्रमशः X, Y, और A तत्वों द्वारा दर्शाए गए हैं। |
| [getSplineStartCol()](#getSplineStartCol--) | स्प्लाइन के दूसरे नियंत्रण बिंदु, उसके दूसरे नॉट, पहले नॉट, अंतिम नॉट, और स्प्लाइन की डिग्री के x और y निर्देशांक को सम्मिलित करता है। |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [iterator()](#iterator--) | एक गैर-जनरिक संग्रह पर सरल पुनरावृत्ति का समर्थन करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | संग्रह से ArcTo ऑब्जेक्ट हटाएँ। |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | संग्रह से Coordinate ऑब्जेक्ट हटाएँ। |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | संग्रह से Ellipse ऑब्जेक्ट हटाएँ। |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | संग्रह से EllipticalArcTo ऑब्जेक्ट हटाएँ। |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | संग्रह से InfiniteLine ऑब्जेक्ट हटाएँ। |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | संग्रह से LineTo ऑब्जेक्ट हटाएँ। |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | संग्रह से MoveTo ऑब्जेक्ट हटाएँ। |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | संग्रह से NURBSTo ऑब्जेक्ट हटाएँ। |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | संग्रह से PolylineTo ऑब्जेक्ट हटाएँ। |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | संग्रह से RelCubBezTo ऑब्जेक्ट हटाएँ। |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | संग्रह से RelEllipticalArcTo ऑब्जेक्ट हटाएँ। |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | संग्रह से RelLineTo ऑब्जेक्ट हटाएँ। |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | संग्रह से RelMoveTo ऑब्जेक्ट हटाएँ। |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | संग्रह से RelQuadBezTo ऑब्जेक्ट हटाएँ। |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | संग्रह से SplineKnot ऑब्जेक्ट हटाएँ। |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | संग्रह से SplineStart ऑब्जेक्ट हटाएँ। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


संग्रह में ArcTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


संग्रह में Coordinate ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


संग्रह में Ellipse ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


संग्रह में EllipticalArcTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


संग्रह में InfiniteLine ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


संग्रह में LineTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


संग्रह में MoveTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


संग्रह में NURBSTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


संग्रह में PolylineTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


संग्रह में RelCubBezTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


संग्रह में RelEllipticalArcTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


संग्रह में RelLineTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


संग्रह में RelMoveTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


संग्रह में RelQuadBezTo ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


संग्रह में SplineKnot ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


संग्रह में SplineStart ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Removes all elements from collection.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
बूलियन
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Gets the element at the specified index.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


X, Y और A तत्वों द्वारा क्रमशः दर्शाए गए एक वृत्तीय चाप के x और y निर्देशांक तथा बाउ को शामिल करता है।

**Returns:**
[ArcToCollection](../../com.aspose.diagram/arctocollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Gets the number of elements actually contained in the collection.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


दीर्घवृत्त के केंद्र बिंदु और दो बिंदुओं के x- तथा y-निर्देशांक निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


एक दीर्घवृत्तीय चाप के बारे में जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


एक अनंत रेखा पर दो बिंदुओं के x- और y-निर्देशांक निर्दिष्ट करने वाले तत्व शामिल हैं। X और Y तत्व पहले बिंदु के x- और y-निर्देशांक निर्दिष्ट करते हैं, और A और B तत्व दूसरे बिंदु के x- और y-निर्देशांक निर्दिष्ट करते हैं।

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


एक सीधी रेखा खंड के समाप्ति शीर्ष बिंदु के x- और y-निर्देशांक शामिल करता है। ये निर्देशांक क्रमशः X और Y तत्वों में होते हैं।

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


एक आकार के पहले शीर्ष के x- और y-निर्देशांक शामिल करता है, या पथ में टूटने के बाद पहले शीर्ष के x- और y-निर्देशांक शामिल करता है।

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


गैर-समरूप तर्कसंगत B-स्प्लाइन (NURBS) के सूत्र के साथ x और y निर्देशांक, दूसरे अंतिम नॉट की स्थिति, अंतिम वजन की स्थिति, पहले नॉट की स्थिति, पहले वजन की स्थिति को शामिल करता है। यह जानकारी क्रमशः X, Y, A, B, C, D, और E तत्वों में निर्दिष्ट की गई है।

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


पॉलीलाइन के अंतिम बिंदु के x- और y-निर्देशांक तथा पॉलीलाइन सूत्र को शामिल करता है। निर्देशांक X और Y तत्वों में निर्दिष्ट होते हैं, और सूत्र A तत्व में निर्दिष्ट होता है।

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


RelCubBezTo के बिंदुओं के लिए x- और y-निर्देशांक शामिल हैं। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए गए हैं।

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


एक दीर्घवृत्तीय चाप के बारे में जानकारी निर्दिष्ट करने वाले तत्व शामिल करता है। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट होते हैं।

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


एक सीधी रेखा खंड के समाप्ति शीर्ष बिंदु के x- और y-निर्देशांक शामिल करता है। ये निर्देशांक क्रमशः X और Y तत्वों में होते हैं।निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए जाते हैं।

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


एक आकार के पहले शीर्ष के x और y निर्देशांक शामिल करता है, या पथ में एक ब्रेक के बाद पहले शीर्ष के x और y निर्देशांक शामिल करता है। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए जाते हैं।

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


RelQuadBezTo के बिंदुओं के लिए x- और y-निर्देशांक शामिल हैं। निर्देशांक सापेक्ष निर्देशांक के रूप में निर्दिष्ट किए गए हैं।

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


स्प्लाइन के नियंत्रण बिंदु और स्प्लाइन के नॉट के x और y निर्देशांक को सम्मिलित करता है, जो क्रमशः X, Y, और A तत्वों द्वारा दर्शाए गए हैं।

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


स्प्लाइन के दूसरे नियंत्रण बिंदु, उसके दूसरे नॉट, पहले नॉट, अंतिम नॉट और स्प्लाइन की डिग्री के लिए x और y निर्देशांक शामिल करता है। यह जानकारी क्रमशः X, Y, A, B, C, और D तत्वों में निहित है।

**Returns:**
[SplineStartCollection](../../com.aspose.diagram/splinestartcollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


Is exist item in the collection.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | int | तत्व का सूचकांक। |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


एक गैर-जनरिक संग्रह पर सरल पुनरावृत्ति का समर्थन करता है।

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(ArcTo item) {#remove-com.aspose.diagram.ArcTo-}
```
public void remove(ArcTo item)
```


संग्रह से ArcTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


संग्रह से Coordinate ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


संग्रह से Ellipse ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


संग्रह से EllipticalArcTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


संग्रह से InfiniteLine ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


संग्रह से LineTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


संग्रह से MoveTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


संग्रह से NURBSTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


संग्रह से PolylineTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


संग्रह से RelCubBezTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


संग्रह से RelEllipticalArcTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


संग्रह से RelLineTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


संग्रह से RelMoveTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


संग्रह से RelQuadBezTo ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


संग्रह से SplineKnot ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


संग्रह से SplineStart ऑब्जेक्ट हटाएँ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

