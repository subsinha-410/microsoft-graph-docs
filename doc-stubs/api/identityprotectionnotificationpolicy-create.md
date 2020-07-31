---
title: "Create identityProtectionNotificationPolicy"
description: "Create a new identityProtectionNotificationPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create identityProtectionNotificationPolicy
Namespace: microsoft.graph

Create a new [identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST ** Collection URI for microsoft.graph.identityProtectionNotificationPolicy not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md) object.

The following table shows the properties that are required when you create the [identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|weeklyDigestSettings|[weeklyDigestSettings](../resources/weeklydigestsettings.md)|**TODO: Add Description**|
|userAlertsSettings|[userAlertsSettings](../resources/useralertssettings.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and an [identityProtectionNotificationPolicy](../resources/identityprotectionnotificationpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_identityprotectionnotificationpolicy_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.identityProtectionNotificationPolicy not found
Content-Type: application/json
Content-length: 318

{
  "@odata.type": "#microsoft.graph.identityProtectionNotificationPolicy",
  "displayName": "String",
  "description": "String",
  "weeklyDigestSettings": {
    "@odata.type": "microsoft.graph.weeklyDigestSettings"
  },
  "userAlertsSettings": {
    "@odata.type": "microsoft.graph.userAlertsSettings"
  }
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.identityProtectionNotificationPolicy"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.identityProtectionNotificationPolicy",
  "id": "401454b7-54b7-4014-b754-1440b7541440",
  "displayName": "String",
  "description": "String",
  "weeklyDigestSettings": {
    "@odata.type": "microsoft.graph.weeklyDigestSettings"
  },
  "userAlertsSettings": {
    "@odata.type": "microsoft.graph.userAlertsSettings"
  }
}
```

