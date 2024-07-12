---
title: Shape.ToImage
second_title: Aspose.Diagram for .NET API Reference
description: Shape method. Creates the shape image and saves it to a file. The extension of the file name determines the format of the image
type: docs
url: /net/aspose.diagram/shape/toimage/
---
## ToImage(string, ImageSaveOptions) {#toimage_1}

Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

```csharp
public void ToImage(string imageFile, ImageSaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | The image file name with full path. |
| options | ImageSaveOptions | Additional image creation options |

## Remarks

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

### See Also

* class [ImageSaveOptions](../../../aspose.diagram.saving/imagesaveoptions/)
* class [Shape](../)
* namespace [Aspose.Diagram](../../shape/)
* assembly [Aspose.Diagram](../../../)

---

## ToImage(Stream, ImageSaveOptions) {#toimage}

Creates the shape image and saves it to a stream in the specified format.

```csharp
public void ToImage(Stream stream, ImageSaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The output stream. |
| options | ImageSaveOptions | Additional image creation options |

### See Also

* class [ImageSaveOptions](../../../aspose.diagram.saving/imagesaveoptions/)
* class [Shape](../)
* namespace [Aspose.Diagram](../../shape/)
* assembly [Aspose.Diagram](../../../)


