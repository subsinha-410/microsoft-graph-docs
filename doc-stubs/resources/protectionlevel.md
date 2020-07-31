---
title: "protectionLevel resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# protectionLevel resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List protectionLevels](../api/protectionlevel-list.md)|[protectionLevel](../resources/protectionlevel.md) collection|Get a list of the [protectionLevel](../resources/protectionlevel.md) objects and their properties.|
|[Create protectionLevel](../api/protectionlevel-create.md)|[protectionLevel](../resources/protectionlevel.md)|Create a new [protectionLevel](../resources/protectionlevel.md) object.|
|[Get protectionLevel](../api/protectionlevel-get.md)|[protectionLevel](../resources/protectionlevel.md)|Read the properties and relationships of a [protectionLevel](../resources/protectionlevel.md) object.|
|[Update protectionLevel](../api/protectionlevel-update.md)|[protectionLevel](../resources/protectionlevel.md)|Update the properties of a [protectionLevel](../resources/protectionlevel.md) object.|
|[Delete protectionLevel](../api/protectionlevel-delete.md)|None|Deletes a [protectionLevel](../resources/protectionlevel.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|isAvailable|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.protectionLevel",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.protectionLevel",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "isAvailable": "Boolean"
}
```

