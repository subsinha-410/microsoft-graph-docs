---
title: "conditionalAccessTimes resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# conditionalAccessTimes resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allTimes|Boolean|**TODO: Add Description**|
|excludeDays|[conditionalAccessDays](../resources/conditionalaccessdays.md)|**TODO: Add Description**|
|excludeRange|[conditionalAccessTimeRange](../resources/conditionalaccesstimerange.md)|**TODO: Add Description**|
|includeDays|[conditionalAccessDays](../resources/conditionalaccessdays.md)|**TODO: Add Description**|
|includeRange|[conditionalAccessTimeRange](../resources/conditionalaccesstimerange.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.conditionalAccessTimes"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.conditionalAccessTimes",
  "allTimes": "Boolean",
  "includeDays": {
    "@odata.type": "microsoft.graph.conditionalAccessDays"
  },
  "excludeDays": {
    "@odata.type": "microsoft.graph.conditionalAccessDays"
  },
  "includeRange": {
    "@odata.type": "microsoft.graph.conditionalAccessTimeRange"
  },
  "excludeRange": {
    "@odata.type": "microsoft.graph.conditionalAccessTimeRange"
  }
}
```

