---
title: "policyRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# policyRoot resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List policyRoots](../api/policyroot-list.md)|[policyRoot](../resources/policyroot.md) collection|Get a list of the [policyRoot](../resources/policyroot.md) objects and their properties.|
|[Create policyRoot](../api/policyroot-create.md)|[policyRoot](../resources/policyroot.md)|Create a new [policyRoot](../resources/policyroot.md) object.|
|[Get policyRoot](../api/policyroot-get.md)|[policyRoot](../resources/policyroot.md)|Read the properties and relationships of a [policyRoot](../resources/policyroot.md) object.|
|[Update policyRoot](../api/policyroot-update.md)|[policyRoot](../resources/policyroot.md)|Update the properties of a [policyRoot](../resources/policyroot.md) object.|
|[Delete policyRoot](../api/policyroot-delete.md)|None|Deletes a [policyRoot](../resources/policyroot.md) object.|
|[List identityProtectionNotificationPolicy](../api/policyroot-list-identityprotectionnotificationpolicy.md)|[identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md) collection|Get the identityProtectionNotificationPolicies from the identityProtectionNotificationPolicy navigation property.|
|[Create identityProtectionNotificationPolicy](../api/policyroot-post-identityprotectionnotificationpolicy.md)|[identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md)|Create a new identityProtectionNotificationPolicy object.|
|[Get identityProtectionNotificationPolicy](../api/policyroot-get-identityprotectionnotificationpolicy.md)|[identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md)|Read the properties and relationships of an [identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md) object.|
|[Update identityProtectionNotificationPolicy](../api/policyroot-update-identityprotectionnotificationpolicy.md)|[identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md)|Update the properties of an identityProtectionNotificationPolicy object.|
|[Delete identityProtectionNotificationPolicy](../api/policyroot-delete-identityprotectionnotificationpolicy.md)|None|Delete an [identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|conditionalAccessPolicies|[conditionalAccessPolicy](../resources/conditionalaccesspolicy.md) collection|**TODO: Add Description**|
|identityProtectionNotificationPolicy|[identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md)|**TODO: Add Description**|
|identitySecurityDefaultsEnforcementPolicy|[identitySecurityDefaultsEnforcementPolicy](../resources/identitysecuritydefaultsenforcementpolicy.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.policyRoot",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.policyRoot",
  "id": "String (identifier)"
}
```

