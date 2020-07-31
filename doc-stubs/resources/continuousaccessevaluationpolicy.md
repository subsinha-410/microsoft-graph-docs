---
title: "continuousAccessEvaluationPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# continuousAccessEvaluationPolicy resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List continuousAccessEvaluationPolicies](../api/continuousaccessevaluationpolicy-list.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) collection|Get a list of the [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) objects and their properties.|
|[Create continuousAccessEvaluationPolicy](../api/continuousaccessevaluationpolicy-create.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Create a new [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.|
|[Get continuousAccessEvaluationPolicy](../api/continuousaccessevaluationpolicy-get.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Read the properties and relationships of a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.|
|[Update continuousAccessEvaluationPolicy](../api/continuousaccessevaluationpolicy-update.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Update the properties of a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.|
|[Delete continuousAccessEvaluationPolicy](../api/continuousaccessevaluationpolicy-delete.md)|None|Deletes a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|enforcementMode|continuousAccessEvaluationMode|**TODO: Add Description**. Possible values are: `none`, `enforceStrictLocationConstraints`.|
|groups|String collection|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|isEnabled|Boolean|**TODO: Add Description**|
|users|String collection|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.continuousAccessEvaluationPolicy",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.continuousAccessEvaluationPolicy",
  "id": "String (identifier)",
  "description": "String",
  "displayName": "String",
  "isEnabled": "Boolean",
  "enforcementMode": "String",
  "users": [
    "String"
  ],
  "groups": [
    "String"
  ]
}
```

