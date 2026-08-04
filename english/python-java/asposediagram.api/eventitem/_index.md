---
title: "EventItem Class"
linktitle: "EventItem"
articleTitle: "EventItem"
second_title: "Aspose.Diagram for Python via Java"
description: "Encapsulates an event code."
type: docs
weight: 1150
url: /python-java/asposediagram.api/eventitem/
---

## EventItem class

Encapsulates an event code. An EventItem element can trigger two kinds of actions: it can run an add-on, or it can send a notification of the event to the calling program.

```python
EventItem()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](./id/) | int | The ID of the event. |
| [Action](./action/) | int | Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file,  |
| [EventCode](./eventcode/) | int | A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Micros |
| [Target](./target/) | String | Specifies the target of an event. |
| [TargetArgs](./targetargs/) | String | Specifies a string containing arguments to be sent to the target of an event. |
| [Enabled](./enabled/) | int | Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant. |
