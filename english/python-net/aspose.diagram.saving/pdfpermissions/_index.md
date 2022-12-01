---
title: PdfPermissions enumeration
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 270
url: /python-net/aspose.diagram.saving/pdfpermissions/
is_root: false
---

## PdfPermissions enumeration

Specifies user permissions for PDF document.



The PdfPermissions type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| DISALLOW_ALL | Disallows all operations on the PDF document. This is the default value. |
| PRINTING | Allows printing the document. |
| MODIFY_CONTENTS | Allows modifying the document’s contents. |
| CONTENT_COPY | Allows copying or otherwise extracting text and graphics from the document, including extraction for accessibility purposes. |
| MODIFY_ANNOTATIONS | Allows adding or modifying text annotations. When using RC4 40-bit encryption, this option also allows filling in form fields. |
| FILL_IN | Allows filling in forms and signing the document. When using RC4 40-bit encryption, this option is ignored and filling in form is allowed whenever ModifyAnnotations is set. |
| CONTENT_COPY_FOR_ACCESSIBILITY | Allows extract text and graphics in support of accessibility to disabled users or for other purposes. When using RC4 40-bit encryption, this option is ignored and accessibility is allowed whenever ContentCopy is set. |
| DOCUMENT_ASSEMBLY | Allows assembling the document: inserting, rotating, or deleting pages and creating navigation elements such as bookmarks or thumbnail images. When using RC4 40-bit encryption, this option is ignored and document assembly is allowed when ModifyContents is set. |
| HIGH_RESOLUTION_PRINTING | Allows printing the document to the highest resolution possible.When using RC4 40-bit encryption, this option is ignored and high resolution printing is allowed when Printing is set. |
| ALLOW_ALL | Allows all operations on the PDF document. |


### See Also

* module [aspose.diagram.saving](../)
