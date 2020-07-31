---
title: "unfamiliarLocationRiskEvent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# unfamiliarLocationRiskEvent resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [locatedRiskEvent](../resources/locatedriskevent.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List unfamiliarLocationRiskEvents](../api/unfamiliarlocationriskevent-list.md)|[unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md) collection|Get a list of the [unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md) objects and their properties.|
|[Create unfamiliarLocationRiskEvent](../api/unfamiliarlocationriskevent-post-unfamiliarlocationriskevents.md)|[unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md)|Create a new [unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md) object.|
|[Get unfamiliarLocationRiskEvent](../api/unfamiliarlocationriskevent-get.md)|[unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md)|Read the properties and relationships of an [unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md) object.|
|[Update unfamiliarLocationRiskEvent](../api/unfamiliarlocationriskevent-update.md)|[unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md)|Update the properties of an [unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md) object.|
|[Delete unfamiliarLocationRiskEvent](../api/unfamiliarlocationriskevent-delete.md)|None|Deletes an [unfamiliarLocationRiskEvent](../resources/unfamiliarlocationriskevent.md) object.|
|[List impactedUser](../api/unfamiliarlocationriskevent-list-impacteduser.md)|[user](../resources/user.md) collection|Get the users from the impactedUser navigation property.|
|[Add impactedUser](../api/unfamiliarlocationriskevent-post-impacteduser.md)|[user](../resources/user.md)|Add impactedUser by posting to the impactedUser collection.|
|[Remove impactedUser](../api/unfamiliarlocationriskevent-delete-impacteduser.md)|None|Remove a [user](../resources/user.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|ipAddress|String|**TODO: Add Description** Inherited from [locatedRiskEvent](../resources/locatedriskevent.md)|
|location|[signInLocation](../resources/signinlocation.md)|**TODO: Add Description** Inherited from [locatedRiskEvent](../resources/locatedriskevent.md)|
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
  "@odata.type": "microsoft.graph.unfamiliarLocationRiskEvent",
  "baseType": "microsoft.graph.locatedRiskEvent",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.unfamiliarLocationRiskEvent",
  "id": "String (identifier)",
  "userDisplayName": "String",
  "userPrincipalName": "String",
  "riskEventDateTime": "String (timestamp)",
  "riskEventType": "String",
  "riskLevel": "String",
  "riskEventStatus": "String",
  "closedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "userId": "String",
  "location": {
    "@odata.type": "microsoft.graph.signInLocation"
  },
  "ipAddress": "String"
}
```

