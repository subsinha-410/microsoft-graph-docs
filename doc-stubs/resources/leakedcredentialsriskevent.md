---
title: "leakedCredentialsRiskEvent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# leakedCredentialsRiskEvent resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [identityRiskEvent](../resources/identityriskevent.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List leakedCredentialsRiskEvents](../api/leakedcredentialsriskevent-list.md)|[leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md) collection|Get a list of the [leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md) objects and their properties.|
|[Create leakedCredentialsRiskEvent](../api/leakedcredentialsriskevent-post-leakedcredentialsriskevents.md)|[leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md)|Create a new [leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md) object.|
|[Get leakedCredentialsRiskEvent](../api/leakedcredentialsriskevent-get.md)|[leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md)|Read the properties and relationships of a [leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md) object.|
|[Update leakedCredentialsRiskEvent](../api/leakedcredentialsriskevent-update.md)|[leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md)|Update the properties of a [leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md) object.|
|[Delete leakedCredentialsRiskEvent](../api/leakedcredentialsriskevent-delete.md)|None|Deletes a [leakedCredentialsRiskEvent](../resources/leakedcredentialsriskevent.md) object.|
|[List impactedUser](../api/leakedcredentialsriskevent-list-impacteduser.md)|[user](../resources/user.md) collection|Get the users from the impactedUser navigation property.|
|[Add impactedUser](../api/leakedcredentialsriskevent-post-impacteduser.md)|[user](../resources/user.md)|Add impactedUser by posting to the impactedUser collection.|
|[Remove impactedUser](../api/leakedcredentialsriskevent-delete-impacteduser.md)|None|Remove a [user](../resources/user.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|riskEventDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|riskEventStatus|riskEventStatus|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md). Possible values are: `active`, `remediated`, `dismissedAsFixed`, `dismissedAsFalsePositive`, `dismissedAsIgnore`, `loginBlocked`, `closedMfaAuto`, `closedMultipleReasons`.|
|riskEventType|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|riskLevel|riskLevel|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md). Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|userDisplayName|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|userId|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|userPrincipalName|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|impactedUser|[user](../resources/user.md)|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.leakedCredentialsRiskEvent",
  "baseType": "microsoft.graph.identityRiskEvent",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.leakedCredentialsRiskEvent",
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

