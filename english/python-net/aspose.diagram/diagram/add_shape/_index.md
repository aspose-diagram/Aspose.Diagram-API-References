---
title: add_shape method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.diagram/diagram/add_shape/
is_root: false
---

## add_shape(new_shape, master_name, page_number) {#Shape-str-int}

Adds shape created by master to specific page.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def add_shape(self, new_shape, master_name, page_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| new_shape | [Shape](/diagram/python-net/aspose.diagram/shape) | New shape object[Shape](/diagram/python-net/aspose.diagram/shape). |
| master_name | str | Master's name. |
| page_number | int | Index of page. |


## add_shape(pin_x, pin_y, master_name, page_number) {#float-float-str-int}

Adds shape created by master on page with defined PinX and PinY.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def add_shape(self, pin_x, pin_y, master_name, page_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pin_y | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| master_name | str | Master's name. |
| page_number | int | Index of page. |


## add_shape(pin_x, pin_y, width, height, master_name, page_number) {#float-float-float-float-str-int}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def add_shape(self, pin_x, pin_y, width, height, master_name, page_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pin_y | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape in inches. |
| height | float | Specifies the height of the shape in inches. |
| master_name | str | Master's name. |
| page_number | int | Index of page. |



### See Also
* module [aspose.diagram](../../)
* class [Diagram](/diagram/python-net/aspose.diagram/diagram)
