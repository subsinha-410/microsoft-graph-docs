---
title: "identityUserRisk resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityUserRisk resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|lastChangedDateTime|DateTimeOffset|**TODO: Add Description**|
|level|userRiskLevel|**TODO: Add Description**. Possible values are: `unknown`, `none`, `low`, `medium`, `high`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.identityUserRisk"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityUserRisk",
  "level": "String",
  "lastChangedDateTime": "String (timestamp)"
}
```

