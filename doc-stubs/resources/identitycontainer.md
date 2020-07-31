---
title: "identityContainer resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityContainer resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityContainers](../api/identitycontainer-list.md)|[identityContainer](../resources/identitycontainer.md) collection|Get a list of the [identityContainer](../resources/identitycontainer.md) objects and their properties.|
|[Create identityContainer](../api/identitycontainer-create.md)|[identityContainer](../resources/identitycontainer.md)|Create a new [identityContainer](../resources/identitycontainer.md) object.|
|[Get identityContainer](../api/identitycontainer-get.md)|[identityContainer](../resources/identitycontainer.md)|Read the properties and relationships of an [identityContainer](../resources/identitycontainer.md) object.|
|[Update identityContainer](../api/identitycontainer-update.md)|[identityContainer](../resources/identitycontainer.md)|Update the properties of an [identityContainer](../resources/identitycontainer.md) object.|
|[Delete identityContainer](../api/identitycontainer-delete.md)|None|Deletes an [identityContainer](../resources/identitycontainer.md) object.|
|[List continuousAccessEvaluationPolicy](../api/identitycontainer-list-continuousaccessevaluationpolicy.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) collection|Get the continuousAccessEvaluationPolicies from the continuousAccessEvaluationPolicy navigation property.|
|[Create continuousAccessEvaluationPolicy](../api/identitycontainer-post-continuousaccessevaluationpolicy.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Create a new continuousAccessEvaluationPolicy object.|
|[Get continuousAccessEvaluationPolicy](../api/identitycontainer-get-continuousaccessevaluationpolicy.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Read the properties and relationships of a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.|
|[Update continuousAccessEvaluationPolicy](../api/identitycontainer-update-continuousaccessevaluationpolicy.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Update the properties of a continuousAccessEvaluationPolicy object.|
|[Delete continuousAccessEvaluationPolicy](../api/identitycontainer-delete-continuousaccessevaluationpolicy.md)|None|Delete a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|conditionalAccess|[conditionalAccessRoot](../resources/conditionalaccessroot.md)|**TODO: Add Description**|
|continuousAccessEvaluationPolicy|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityContainer",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityContainer",
  "id": "String (identifier)"
}
```

