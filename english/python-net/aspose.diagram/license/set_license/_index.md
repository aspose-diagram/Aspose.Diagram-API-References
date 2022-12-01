---
title: set_license method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.diagram/license/set_license/
is_root: false
---

## set_license(license_name) {#str}

Licenses the component.



```python
def set_license(self, license_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_name | str |  |
### Remarks

Tries to find the license in the following locations:


1. Explicit path.


2. The folder of the component assembly.


3. The folder of the client's calling assembly.


4. The folder of the entry assembly.


5. An embedded resource in the client's calling assembly.


**Note:** On the .NET Compact Framework, tries to find the license only in these locations:


1. Explicit path.


2. An embedded resource in the client's calling assembly.

## set_license(stream) {#io.RawIOBase}

Licenses the component.



```python
def set_license(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | A stream that contains the license. |
### Remarks

Use this method to load a license from a stream.


### See Also
* module [aspose.diagram](../../)
* class [License](/diagram/python-net/aspose.diagram/license)
