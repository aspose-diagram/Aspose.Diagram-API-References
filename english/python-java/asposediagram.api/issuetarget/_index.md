---
title: "IssueTarget"
linktitle: "IssueTarget"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associate"
type: docs
weight: 1740
url: /python-java/asposediagram.api/issuetarget/
---

## IssueTarget class

Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associated with. If the target of the parent validation issue is a document, IssueTarget specifies neither a page nor a shape.

## Constructors

| Name | Description |
| --- | --- |
| [IssueTarget](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [PageId](#pageid) | long | Specifies the unique identifier of the page that is associated with the parent validation issue. If the target is the do |
| [ShapeId](#shapeid) | long | Specifies the unique identifier of the shape that is associated with the parent validation issue. If the target is the d |

### IssueTarget(pageID, shapeID) {#constructor}

Constructor.

| Parameter | Type | Description |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

### IssueTarget.PageId property {#pageid}

Specifies the unique identifier of the page that is associated with the parent validation issue. If the target is the document, the PageID value can be 0xFFFFFFFF.

**Type:** long

### IssueTarget.ShapeId property {#shapeid}

Specifies the unique identifier of the shape that is associated with the parent validation issue. If the target is the document or a page, the ShapeID value can be 0xFFFFFFFF.

**Type:** long
