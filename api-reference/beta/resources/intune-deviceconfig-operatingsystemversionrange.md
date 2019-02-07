---
title: "operatingSystemVersionRange resource type"
description: "Operating System version range."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# operatingSystemVersionRange resource type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Operating System version range.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|The description of this range (e.g. Valid 1702 builds)|
|lowestVersion|String|The lowest inclusive version that this range contains.|
|highestVersion|String|The highest inclusive version that this range contains.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.operatingSystemVersionRange"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.operatingSystemVersionRange",
  "description": "String",
  "lowestVersion": "String",
  "highestVersion": "String"
}
```



