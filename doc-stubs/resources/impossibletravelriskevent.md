---
title: "impossibleTravelRiskEvent resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# impossibleTravelRiskEvent resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [locatedRiskEvent](../resources/locatedriskevent.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List impossibleTravelRiskEvents](../api/impossibletravelriskevent-list.md)|[impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md) collection|Get a list of the [impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md) objects and their properties.|
|[Create impossibleTravelRiskEvent](../api/impossibletravelriskevent-post-impossibletravelriskevents.md)|[impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md)|Create a new [impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md) object.|
|[Get impossibleTravelRiskEvent](../api/impossibletravelriskevent-get.md)|[impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md)|Read the properties and relationships of an [impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md) object.|
|[Update impossibleTravelRiskEvent](../api/impossibletravelriskevent-update.md)|[impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md)|Update the properties of an [impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md) object.|
|[Delete impossibleTravelRiskEvent](../api/impossibletravelriskevent-delete.md)|None|Deletes an [impossibleTravelRiskEvent](../resources/impossibletravelriskevent.md) object.|
|[List impactedUser](../api/impossibletravelriskevent-list-impacteduser.md)|[user](../resources/user.md) collection|Get the users from the impactedUser navigation property.|
|[Add impactedUser](../api/impossibletravelriskevent-post-impacteduser.md)|[user](../resources/user.md)|Add impactedUser by posting to the impactedUser collection.|
|[Remove impactedUser](../api/impossibletravelriskevent-delete-impacteduser.md)|None|Remove a [user](../resources/user.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|closedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|deviceInformation|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|ipAddress|String|**TODO: Add Description** Inherited from [locatedRiskEvent](../resources/locatedriskevent.md)|
|isAtypicalLocation|Boolean|**TODO: Add Description**|
|location|[signInLocation](../resources/signinlocation.md)|**TODO: Add Description** Inherited from [locatedRiskEvent](../resources/locatedriskevent.md)|
|previousIpAddress|String|**TODO: Add Description**|
|previousLocation|[signInLocation](../resources/signinlocation.md)|**TODO: Add Description**|
|previousSigninDateTime|DateTimeOffset|**TODO: Add Description**|
|riskEventDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|riskEventStatus|riskEventStatus|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md). Possible values are: `active`, `remediated`, `dismissedAsFixed`, `dismissedAsFalsePositive`, `dismissedAsIgnore`, `loginBlocked`, `closedMfaAuto`, `closedMultipleReasons`.|
|riskEventType|String|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md)|
|riskLevel|riskLevel|**TODO: Add Description** Inherited from [identityRiskEvent](../resources/identityriskevent.md). Possible values are: `low`, `medium`, `high`, `hidden`, `none`, `unknownFutureValue`.|
|userAgent|String|**TODO: Add Description**|
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
  "@odata.type": "microsoft.graph.impossibleTravelRiskEvent",
  "baseType": "microsoft.graph.locatedRiskEvent",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.impossibleTravelRiskEvent",
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
  "ipAddress": "String",
  "userAgent": "String",
  "deviceInformation": "String",
  "isAtypicalLocation": "Boolean",
  "previousSigninDateTime": "String (timestamp)",
  "previousLocation": {
    "@odata.type": "microsoft.graph.signInLocation"
  },
  "previousIpAddress": "String"
}
```

