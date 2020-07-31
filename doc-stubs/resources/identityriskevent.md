---
title: "identityRiskEvent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityRiskEvent resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityRiskEvents](../api/identityriskevent-list.md)|[identityRiskEvent](../resources/identityriskevent.md) collection|Get a list of the [identityRiskEvent](../resources/identityriskevent.md) objects and their properties.|
|[Create identityRiskEvent](../api/identityriskevent-post-identityriskevents.md)|[identityRiskEvent](../resources/identityriskevent.md)|Create a new [identityRiskEvent](../resources/identityriskevent.md) object.|
|[Get identityRiskEvent](../api/identityriskevent-get.md)|[identityRiskEvent](../resources/identityriskevent.md)|Read the properties and relationships of an [identityRiskEvent](../resources/identityriskevent.md) object.|
|[Update identityRiskEvent](../api/identityriskevent-update.md)|[identityRiskEvent](../resources/identityriskevent.md)|Update the properties of an [identityRiskEvent](../resources/identityriskevent.md) object.|
|[Delete identityRiskEvent](../api/identityriskevent-delete.md)|None|Deletes an [identityRiskEvent](../resources/identityriskevent.md) object.|
|[List impactedUser](../api/identityriskevent-list-impacteduser.md)|[user](../resources/user.md) collection|Get the users from the impactedUser navigation property.|
|[Add impactedUser](../api/identityriskevent-post-impacteduser.md)|[user](../resources/user.md)|Add impactedUser by posting to the impactedUser collection.|
|[Remove impactedUser](../api/identityriskevent-delete-impacteduser.md)|None|Remove a [user](../resources/user.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedDateTime|DateTimeOffset|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|riskEventDateTime|DateTimeOffset|**TODO: Add Description**|
|riskEventStatus|riskEventStatus|**TODO: Add Description**. Possible values are: `active`, `remediated`, `dismissedAsFixed`, `dismissedAsFalsePositive`, `dismissedAsIgnore`, `loginBlocked`, `closedMfaAuto`, `closedMultipleReasons`.|
|riskEventType|String|**TODO: Add Description**|
|riskLevel|riskLevel|**TODO: Add Description**. Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|userDisplayName|String|**TODO: Add Description**|
|userId|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|impactedUser|[user](../resources/user.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityRiskEvent",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityRiskEvent",
  "id": "String (identifier)",
  "userDisplayName": "String",
  "userPrincipalName": "String",
  "riskEventDateTime": "String (timestamp)",
  "riskEventType": "String",
  "riskLevel": "String",
  "riskEventStatus": "String",
  "closedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "userId": "String"
}
```

