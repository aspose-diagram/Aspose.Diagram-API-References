---
title: "EventItem"
linktitle: "EventItem"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Encapsulates an event code."
type: docs
weight: 830
url: /nodejs/aspose.diagram/eventitem/
---

## EventItem class

Encapsulates an event code. An EventItem element can trigger two kinds of actions: it can run an add-on, or it can send a notification of the event to the calling program.

```js
new EventItem()
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [getAction()](#getaction) | Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file,  |
| [getEnabled()](#getenabled) | Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant. |
| [getEventCode()](#geteventcode) | A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Micros |
| [getID()](#getid) | The ID of the event. |
| [getTarget()](#gettarget) | Specifies the target of an event. |
| [getTargetArgs()](#gettargetargs) | Specifies a string containing arguments to be sent to the target of an event. |
| [setAction()](#setaction) | Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file,  |
| [setEnabled()](#setenabled) | Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant. |
| [setEventCode()](#seteventcode) | A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Micros |
| [setID()](#setid) | The ID of the event. |
| [setTarget()](#settarget) | Specifies the target of an event. |
| [setTargetArgs()](#settargetargs) | Specifies a string containing arguments to be sent to the target of an event. |

### getAction() {#getaction}

Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file, it must be persistable. Currently, the only valid action code a persistable event can have is 1 (ONEVENT_ACT_RUNADDON).

### getEnabled() {#getenabled}

Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant.

### getEventCode() {#geteventcode}

A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Microsoft Visio 2007 Automation Reference.

### getID() {#getid}

The ID of the event.

### getTarget() {#gettarget}

Specifies the target of an event.

### getTargetArgs() {#gettargetargs}

Specifies a string containing arguments to be sent to the target of an event.

### setAction() {#setaction}

Specifies the action code of the parent EventItem element.For an EventItem element to be saved in a DatadiagramML file, it must be persistable. Currently, the only valid action code a persistable event can have is 1 (ONEVENT_ACT_RUNADDON).

### setEnabled() {#setenabled}

Represents a flag indicating if the event is enabled or disabled. The value of the property is BOOL integer constant.

### setEventCode() {#seteventcode}

A code indicating the event that triggers the add-on. For more information on event codes, see Event Codes in the Microsoft Visio 2007 Automation Reference.

### setID() {#setid}

The ID of the event.

### setTarget() {#settarget}

Specifies the target of an event.

### setTargetArgs() {#settargetargs}

Specifies a string containing arguments to be sent to the target of an event.
