---
title: "Update agreement"
description: "Update the properties of an agreement object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update agreement
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [agreement](../resources/agreement.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
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
PATCH /agreements/{agreementsId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
[!INCLUDE [table-intro](../../includes/update-property-table-intro.md)]


|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description** Optional.|
|termsExpiration|[microsoft.azure.termsOfUse.termsExpiration](../resources/termsexpiration.md)|**TODO: Add Description** Optional.|
|userReacceptRequiredFrequency|Duration|**TODO: Add Description** Optional.|
|isViewingBeforeAcceptanceRequired|Boolean|**TODO: Add Description** Optional.|
|isPerDeviceAcceptanceRequired|Boolean|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [agreement](../resources/agreement.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_agreement"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/agreements/{agreementsId}
Content-Type: application/json
Content-length: 318

{
  "@odata.type": "#microsoft.graph.agreement",
  "displayName": "String",
  "termsExpiration": {
    "@odata.type": "microsoft.graph.termsExpiration"
  },
  "userReacceptRequiredFrequency": "String (duration)",
  "isViewingBeforeAcceptanceRequired": "Boolean",
  "isPerDeviceAcceptanceRequired": "Boolean"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.agreement",
  "id": "a0552814-2814-a055-1428-55a0142855a0",
  "displayName": "String",
  "termsExpiration": {
    "@odata.type": "microsoft.graph.termsExpiration"
  },
  "userReacceptRequiredFrequency": "String (duration)",
  "isViewingBeforeAcceptanceRequired": "Boolean",
  "isPerDeviceAcceptanceRequired": "Boolean"
}
```

