---
title: "Rule Class"
linktitle: "Rule"
articleTitle: "Rule"
second_title: "Aspose.Diagram for Python via Java"
description: "Represents a single validation rule in a diagram validation rule set."
type: docs
weight: 2890
url: /python-java/asposediagram.api/rule/
---

## Rule class

Represents a single validation rule in a diagram validation rule set.

```python
Rule()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [RuleFilter](./rulefilter/) | RuleValue | Specifies the logical expression that determines whether the validation rule should be applied to a target object. |
| [RuleTest](./ruletest/) | RuleValue | Specifies the logical expression that determines whether the target object satisfies the validation rule |
| [ID](./id/) | long | Specifies the unique identifier of the validation rule. |
| [NameU](./nameu/) | String | Specifies the universal name of the validation rule. |
| [Category](./category/) | String | Specifies the text displayed in the Category column of the Issues window. Default is an empty string. |
| [Description](./description/) | String | the description of the validation rule that appears in the user interface. Default is "Unknown". |
| [RuleTarget](./ruletarget/) | int | Specifies the type of object to which the validation rule applies. The value of the property is VisRuleTargetsValue inte |
| [Ignored](./ignored/) | int | Specifies whether the validation rule is currently ignored. Default is False. The value of the property is BOOL integer  |
