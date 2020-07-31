---
title: "conditionalAccessApplications resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# conditionalAccessApplications resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|excludeApplications|String collection|**TODO: Add Description**|
|includeApplications|String collection|**TODO: Add Description**|
|includeProtectionLevels|String collection|**TODO: Add Description**|
|includeUserActions|String collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.conditionalAccessApplications"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.conditionalAccessApplications",
  "includeApplications": [
    "String"
  ],
  "excludeApplications": [
    "String"
  ],
  "includeUserActions": [
    "String"
  ],
  "includeProtectionLevels": [
    "String"
  ]
}
```

