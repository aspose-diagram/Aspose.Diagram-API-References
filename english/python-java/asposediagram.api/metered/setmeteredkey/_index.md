---
title: "Metered.setMeteredKey"
linktitle: "setMeteredKey"
articleTitle: "setMeteredKey"
second_title: "Aspose.Diagram for Python via Java"
description: "Sets metered public and private key."
type: docs
weight: 10
url: /python-java/asposediagram.api/metered/setmeteredkey/
---

## setMeteredKey(publicKey, privateKey) {#setmeteredkey}

Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | String | public key |
| privateKey | String | private key |
