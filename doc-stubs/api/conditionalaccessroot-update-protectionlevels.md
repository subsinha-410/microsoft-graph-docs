---
title: "Update protectionLevels"
description: "Update the properties of a protectionLevels object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update protectionLevels
Namespace: microsoft.graph

Update the properties of a protectionLevels object.

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
PATCH /conditionalAccess/protectionLevels
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [protectionLevel](../resources/protectionlevel.md) object.

The following table shows the properties that are required when you create the [protectionLevel](../resources/protectionlevel.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|isAvailable|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [protectionLevel](../resources/protectionlevel.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_protectionlevels"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/conditionalAccess/protectionLevels
Content-Type: application/json
Content-length: 142

{
  "@odata.type": "#microsoft.graph.protectionLevel",
  "displayName": "String",
  "description": "String",
  "isAvailable": "Boolean"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.protectionLevel",
  "id": "fdeae9cd-e9cd-fdea-cde9-eafdcde9eafd",
  "displayName": "String",
  "description": "String",
  "isAvailable": "Boolean"
}
```

