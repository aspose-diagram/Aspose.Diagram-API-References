---
title: to_image method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 300
url: /python-net/aspose.diagram/shape/to_image/
is_root: false
---

## to_image(image_file, options) {#str-aspose.diagram.saving.ImageSaveOptions}

Creates the shape image and saves it to a file.
The extension of the file name determines the format of the image.



```python
def to_image(self, image_file, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_file | str | The image file name with full path. |
| options | aspose.diagram.saving.ImageSaveOptions | Additional image creation options |
### Remarks

The format of the image is specified by using the extension of the file name.
For example, if you specify "myfile.png", then the image will be saved
in the PNG format. The following file extensions are recognized: 
.bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

## to_image(stream, options) {#io.RawIOBase-aspose.diagram.saving.ImageSaveOptions}

Creates the shape image and saves it to a stream in the specified format.



```python
def to_image(self, stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The output stream. |
| options | aspose.diagram.saving.ImageSaveOptions | Additional image creation options |



### See Also
* module [aspose.diagram](../../)
* class [Shape](/diagram/python-net/aspose.diagram/shape)
