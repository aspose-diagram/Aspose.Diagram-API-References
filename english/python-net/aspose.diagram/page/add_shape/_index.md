---
title: add_shape method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.diagram/page/add_shape/
is_root: false
---

## add_shape(new_shape, master_name) {#Shape-str}

Adds shape created by master to specific page.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def add_shape(self, new_shape, master_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| new_shape | [Shape](/diagram/python-net/aspose.diagram/shape) | New shape object[Shape](/diagram/python-net/aspose.diagram/shape). |
| master_name | str | Master's name. |


## add_shape(pin_x, pin_y, master_name) {#float-float-str}

Adds shape created by master on page with defined PinX and PinY.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def add_shape(self, pin_x, pin_y, master_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pin_y | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| master_name | str | Master's name. |


## add_shape(pin_x, pin_y, width, height, master_name) {#float-float-float-float-str}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

### Returns 


The unique ID of the shape within shapes collection on the specified page.


```python
def add_shape(self, pin_x, pin_y, width, height, master_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pin_y | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape in inches. |
| height | float | Specifies the height of the shape in inches. |
| master_name | str | Master's name. |


## add_shape(pin_x, pin_y, width, height, stream) {#float-float-float-float-io.RawIOBase}



```python
def add_shape(self, pin_x, pin_y, width, height, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float |  |
| pin_y | float |  |
| width | float |  |
| height | float |  |
| stream | io.RawIOBase |  |


## add_shape(pin_x, pin_y, width, height, image_stream, object_data_stream) {#float-float-float-float-io.RawIOBase-io.RawIOBase}



```python
def add_shape(self, pin_x, pin_y, width, height, image_stream, object_data_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pin_x | float |  |
| pin_y | float |  |
| width | float |  |
| height | float |  |
| image_stream | io.RawIOBase |  |
| object_data_stream | io.RawIOBase |  |



### See Also
* module [aspose.diagram](../../)
* class [Page](/diagram/python-net/aspose.diagram/page)
