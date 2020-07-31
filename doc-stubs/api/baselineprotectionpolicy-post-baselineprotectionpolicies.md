---
title: "Create baselineProtectionPolicy"
description: "Create a new baselineProtectionPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create baselineProtectionPolicy
Namespace: microsoft.graph

Create a new [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object.

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
POST /baselineProtectionPolicies
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object.

The following table shows the properties that are required when you create the [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|state|baselineProtectionPolicyState|**TODO: Add Description**. Possible values are: `enabled`, `disabled`.|
|excludedUsers|String collection|**TODO: Add Description**|
|description|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [baselineProtectionPolicy](../resources/baselineprotectionpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_baselineprotectionpolicy_from_baselineprotectionpolicies"
}
-->
``` http
POST https://graph.microsoft.com/beta/baselineProtectionPolicies
Content-Type: application/json
Content-length: 186

{
  "@odata.type": "#microsoft.graph.baselineProtectionPolicy",
  "displayName": "String",
  "state": "String",
  "excludedUsers": [
    "String"
  ],
  "description": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.baselineProtectionPolicy"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.baselineProtectionPolicy",
  "id": "ec0dd4c9-d4c9-ec0d-c9d4-0decc9d40dec",
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

