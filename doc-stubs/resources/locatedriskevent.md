---
title: "locatedRiskEvent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# locatedRiskEvent resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [identityRiskEvent](../resources/identityriskevent.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List locatedRiskEvents](../api/locatedriskevent-list.md)|[locatedRiskEvent](../resources/locatedriskevent.md) collection|Get a list of the [locatedRiskEvent](../resources/locatedriskevent.md) objects and their properties.|
|[Create locatedRiskEvent](../api/locatedriskevent-create.md)|[locatedRiskEvent](../resources/locatedriskevent.md)|Create a new [locatedRiskEvent](../resources/locatedriskevent.md) object.|
|[Get locatedRiskEvent](../api/locatedriskevent-get.md)|[locatedRiskEvent](../resources/locatedriskevent.md)|Read the properties and relationships of a [locatedRiskEvent](../resources/locatedriskevent.md) object.|
|[Update locatedRiskEvent](../api/locatedriskevent-update.md)|[locatedRiskEvent](../resources/locatedriskevent.md)|Update the properties of a [locatedRiskEvent](../resources/locatedriskevent.md) object.|
|[Delete locatedRiskEvent](../api/locatedriskevent-delete.md)|None|Deletes a [locatedRiskEvent](../resources/locatedriskevent.md) object.|
|[List impactedUser](../api/locatedriskevent-list-impacteduser.md)|[user](../resources/user.md) collection|Get the users from the impactedUser navigation property.|
|[Add impactedUser](../api/locatedriskevent-post-impacteduser.md)|[user](../resources/user.md)|Add impactedUser by posting to the impactedUser collection.|
|[Remove impactedUser](../api/locatedriskevent-delete-impacteduser.md)|None|Remove a [user](../resources/user.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|ipAddress|String|**TODO: Add Description**|
|location|[signInLocation](../resources/signinlocation.md)|**TODO: Add Description**|
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
  "@odata.type": "microsoft.graph.locatedRiskEvent",
  "baseType": "microsoft.graph.identityRiskEvent",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.locatedRiskEvent",
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

