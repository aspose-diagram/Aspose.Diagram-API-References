---
title: "RuleSet"
linktitle: "RuleSet"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Represents one set of diagram validation rules."
type: docs
weight: 2920
url: /python-java/asposediagram.api/ruleset/
---

## RuleSet class

Represents one set of diagram validation rules.

## Constructors

| Name | Description |
| --- | --- |
| [RuleSet](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](#id) | long | Specifies the unique identifier of the validation rule set. |
| [NameU](#nameu) | String | Specifies the universal name of the validation rule set. |
| [Name](#name) | String | Specifies the local name of the validation rule set. Defaults to NameU attribute value. |
| [Description](#description) | String | Specifies the description of the validation rule set that appears in the user interface. Default is an empty string. |
| [Enabled](#enabled) | int | Specifies whether the rules in the specified validation rule set are checked when validation is triggered for the curren |
| [RuleSetFlags](#rulesetflags) | int | Specifies whether the rule set appears in the Rules to Check list. The value of the property is BOOL integer constant. |
| [Rules](#rules) | RuleCollection | Rule collection. |

### RuleSet() {#constructor}

Constructor.

### RuleSet.ID property {#id}

Specifies the unique identifier of the validation rule set.

**Type:** long

### RuleSet.NameU property {#nameu}

Specifies the universal name of the validation rule set.

**Type:** String

### RuleSet.Name property {#name}

Specifies the local name of the validation rule set. Defaults to NameU attribute value.

**Type:** String

### RuleSet.Description property {#description}

Specifies the description of the validation rule set that appears in the user interface. Default is an empty string.

**Type:** String

### RuleSet.Enabled property {#enabled}

Specifies whether the rules in the specified validation rule set are checked when validation is triggered for the current document. Default is True. The value of the property is BOOL integer constant.

**Type:** int

### RuleSet.RuleSetFlags property {#rulesetflags}

Specifies whether the rule set appears in the Rules to Check list. The value of the property is BOOL integer constant.

**Type:** int

### RuleSet.Rules property {#rules}

Rule collection.

**Type:** RuleCollection
