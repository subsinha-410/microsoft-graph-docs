---
title: "baselineProtectionPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# baselineProtectionPolicy resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List baselineProtectionPolicies](../api/baselineprotectionpolicy-list.md)|[baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) collection|Get a list of the [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) objects and their properties.|
|[Create baselineProtectionPolicy](../api/baselineprotectionpolicy-post-baselineprotectionpolicies.md)|[baselineProtectionPolicy](../resources/baselineprotectionpolicy.md)|Create a new [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object.|
|[Get baselineProtectionPolicy](../api/baselineprotectionpolicy-get.md)|[baselineProtectionPolicy](../resources/baselineprotectionpolicy.md)|Read the properties and relationships of a [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object.|
|[Update baselineProtectionPolicy](../api/baselineprotectionpolicy-update.md)|[baselineProtectionPolicy](../resources/baselineprotectionpolicy.md)|Update the properties of a [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object.|
|[Delete baselineProtectionPolicy](../api/baselineprotectionpolicy-delete.md)|None|Deletes a [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|excludedUsers|String collection|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|state|baselineProtectionPolicyState|**TODO: Add Description**. Possible values are: `enabled`, `disabled`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.baselineProtectionPolicy",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.baselineProtectionPolicy",
  "id": "String (identifier)",
  "createdDateTime": "String (timestamp)",
  "modifiedDateTime": "String (timestamp)",
  "displayName": "String",
  "state": "String",
  "excludedUsers": [
    "String"
  ],
  "description": "String"
}
```

