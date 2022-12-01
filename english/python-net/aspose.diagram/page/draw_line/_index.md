---
title: draw_line method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 160
url: /python-net/aspose.diagram/page/draw_line/
is_root: false
---

## draw_line(begin_x, begin_y, end_x, end_y) {#float-float-float-float}

The process of drawing a single line.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def draw_line(self, begin_x, begin_y, end_x, end_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| begin_x | float | Specifies the begin x-coordinate of the shape's position in relation to the page. |
| begin_y | float | Specifies the begin y-coordinate of the shape's position in relation to the page. |
| end_x | float | Specifies the end x-coordinate of the shape's position in relation to the page. |
| end_y | float | Specifies the end y-coordinate of the shape's position in relation to the page. |


## draw_line(pin_x, pin_y, width, height, points) {#float-float-float-float-aspose.pydrawing.PointF[]}

The process of drawing line.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def draw_line(self, pin_x, pin_y, width, height, points):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pin_y | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape |
| height | float | Specifies the height of the shape |
| points | aspose.pydrawing.PointF[] | Specifies the points of the line |



### See Also
* module [aspose.diagram](../../)
* class [Page](/diagram/python-net/aspose.diagram/page)
