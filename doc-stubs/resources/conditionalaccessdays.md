---
title: "conditionalAccessDays resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# conditionalAccessDays resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allDay|Boolean|**TODO: Add Description**|
|daysOfWeek|conditionalAccessDayOfWeek collection|**TODO: Add Description**|
|endTime|String|**TODO: Add Description**|
|startTime|String|**TODO: Add Description**|
|timeZone|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.conditionalAccessDays"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.conditionalAccessDays",
  "daysOfWeek": [
    "String"
  ],
  "timeZone": "String",
  "startTime": "String",
  "endTime": "String",
  "allDay": "Boolean"
}
```

