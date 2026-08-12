---
title: "Issue"
linktitle: "Issue"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Represents a single validation issue in the document."
type: docs
weight: 1720
url: /python-java/asposediagram.api/issue/
---

## Issue class

Represents a single validation issue in the document.

## Constructors

| Name | Description |
| --- | --- |
| [Issue](#constructor) | Constructor |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](#id) | long | Specifies the unique identifier of the validation issue. |
| [Ignored](#ignored) | int | Specifies whether the validation issue is currently ignored. The default is False. The value of the property is BOOL int |
| [IssueTarget](#issuetarget) | IssueTarget | Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that  |
| [RuleInfo](#ruleinfo) | RuleInfo | Specifies information about the validation rule that the parent validation issue pertains to. |

### Issue() {#constructor}

Constructor

### Issue.ID property {#id}

Specifies the unique identifier of the validation issue.

**Type:** long

### Issue.Ignored property {#ignored}

Specifies whether the validation issue is currently ignored. The default is False. The value of the property is BOOL integer constant.

**Type:** int

### Issue.IssueTarget property {#issuetarget}

Depending on the target of the parent validation issue, specifies either the page, or both the page and the shape, that the parent validation issue is associated with. If the target of the parent validation issue is a document, IssueTarget specifies neither a page nor a shape.

**Type:** IssueTarget

### Issue.RuleInfo property {#ruleinfo}

Specifies information about the validation rule that the parent validation issue pertains to.

**Type:** RuleInfo
