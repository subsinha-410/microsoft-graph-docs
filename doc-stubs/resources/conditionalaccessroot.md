---
title: "conditionalAccessRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# conditionalAccessRoot resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List conditionalAccessRoots](../api/conditionalaccessroot-list.md)|[conditionalAccessRoot](../resources/conditionalaccessroot.md) collection|Get a list of the [conditionalAccessRoot](../resources/conditionalaccessroot.md) objects and their properties.|
|[Create conditionalAccessRoot](../api/conditionalaccessroot-create.md)|[conditionalAccessRoot](../resources/conditionalaccessroot.md)|Create a new [conditionalAccessRoot](../resources/conditionalaccessroot.md) object.|
|[Get conditionalAccessRoot](../api/conditionalaccessroot-get.md)|[conditionalAccessRoot](../resources/conditionalaccessroot.md)|Read the properties and relationships of a [conditionalAccessRoot](../resources/conditionalaccessroot.md) object.|
|[Update conditionalAccessRoot](../api/conditionalaccessroot-update.md)|[conditionalAccessRoot](../resources/conditionalaccessroot.md)|Update the properties of a [conditionalAccessRoot](../resources/conditionalaccessroot.md) object.|
|[Delete conditionalAccessRoot](../api/conditionalaccessroot-delete.md)|None|Deletes a [conditionalAccessRoot](../resources/conditionalaccessroot.md) object.|
|[List protectionLevels](../api/conditionalaccessroot-list-protectionlevels.md)|[protectionLevel](../resources/protectionlevel.md) collection|Get the protectionLevels from the protectionLevels navigation property.|
|[Create protectionLevels](../api/conditionalaccessroot-post-protectionlevels.md)|[protectionLevel](../resources/protectionlevel.md)|Create a new protectionLevels object.|
|[Get protectionLevels](../api/conditionalaccessroot-get-protectionlevel.md)|[protectionLevel](../resources/protectionlevel.md)|Read the properties and relationships of a [protectionLevel](../resources/protectionlevel.md) object.|
|[Update protectionLevels](../api/conditionalaccessroot-update-protectionlevels.md)|[protectionLevel](../resources/protectionlevel.md)|Update the properties of a protectionLevels object.|
|[Delete protectionLevels](../api/conditionalaccessroot-delete-protectionlevels.md)|None|Delete a [protectionLevel](../resources/protectionlevel.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|namedLocations|[namedLocation](../resources/namedlocation.md) collection|**TODO: Add Description**|
|policies|[conditionalAccessPolicy](../resources/conditionalaccesspolicy.md) collection|**TODO: Add Description**|
|protectionLevels|[protectionLevel](../resources/protectionlevel.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.conditionalAccessRoot",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.conditionalAccessRoot",
  "id": "String (identifier)"
}
```

