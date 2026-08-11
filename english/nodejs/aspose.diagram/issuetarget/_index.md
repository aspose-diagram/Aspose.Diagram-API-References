---
title: "IssueTarget"
linktitle: "IssueTarget"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associate"
type: docs
weight: 1280
url: /nodejs/aspose.diagram/issuetarget/
---

## IssueTarget class

Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associated with. If the target of the parent validation issue is a document, IssueTarget specifies neither a page nor a shape.

```js
new IssueTarget(pageID, shapeID)
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [getPageId()](#getpageid) | Specifies the unique identifier of the page that is associated with the parent validation issue. If the target is the do |
| [getShapeId()](#getshapeid) | Specifies the unique identifier of the shape that is associated with the parent validation issue. If the target is the d |
| [setPageId()](#setpageid) | Specifies the unique identifier of the page that is associated with the parent validation issue. If the target is the do |
| [setShapeId()](#setshapeid) | Specifies the unique identifier of the shape that is associated with the parent validation issue. If the target is the d |

### getPageId() {#getpageid}

Specifies the unique identifier of the page that is associated with the parent validation issue. If the target is the document, the PageID value can be 0xFFFFFFFF.

### getShapeId() {#getshapeid}

Specifies the unique identifier of the shape that is associated with the parent validation issue. If the target is the document or a page, the ShapeID value can be 0xFFFFFFFF.

### setPageId() {#setpageid}

Specifies the unique identifier of the page that is associated with the parent validation issue. If the target is the document, the PageID value can be 0xFFFFFFFF.

### setShapeId() {#setshapeid}

Specifies the unique identifier of the shape that is associated with the parent validation issue. If the target is the document or a page, the ShapeID value can be 0xFFFFFFFF.
