---
title: "EventItem"
linktitle: "EventItem"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Encapsulates an event code."
type: docs
weight: 1150
url: /python-java/asposediagram.api/eventitem/
---

## EventItem class

Encapsulates an event code. An EventItem element can trigger two kinds of actions: it can run an add-on, or it can send a notification of the event to the calling program.

## Constructors

| Name | Description |
| --- | --- |
| [EventItem](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](#id) | int | The ID of the event. |
| [Action](#action) | int | Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file,  |
| [EventCode](#eventcode) | int | A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Micros |
| [Target](#target) | String | Specifies the target of an event. |
| [TargetArgs](#targetargs) | String | Specifies a string containing arguments to be sent to the target of an event. |
| [Enabled](#enabled) | int | Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant. |

### EventItem() {#constructor}

Constructor.

### EventItem.ID property {#id}

The ID of the event.

**Type:** int

### EventItem.Action property {#action}

Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file, it must be persistable. Currently, the only valid action code a persistable event can have is 1 (ONEVENT_ACT_RUNADDON).

**Type:** int

### EventItem.EventCode property {#eventcode}

A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Microsoft Visio 2007 Automation Reference.

**Type:** int

### EventItem.Target property {#target}

Specifies the target of an event.

**Type:** String

### EventItem.TargetArgs property {#targetargs}

Specifies a string containing arguments to be sent to the target of an event.

**Type:** String

### EventItem.Enabled property {#enabled}

Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant.

**Type:** int
