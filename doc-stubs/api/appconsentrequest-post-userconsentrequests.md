---
title: "Create userConsentRequest"
description: "Create a new userConsentRequest object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create userConsentRequest
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new userConsentRequest object.

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
POST /appConsentRequest/userConsentRequests
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [userConsentRequest](../resources/userconsentrequest.md) object.

You can specify the following properties when creating a **userConsentRequest**.

|Property|Type|Description|
|:---|:---|:---|
|status|String|**TODO: Add Description** Inherited from [request](../resources/request.md). Required.|
|completedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [request](../resources/request.md). Optional.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [request](../resources/request.md). Optional.|
|approvalId|String|**TODO: Add Description** Inherited from [request](../resources/request.md). Optional.|
|customData|String|**TODO: Add Description** Inherited from [request](../resources/request.md). Optional.|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [request](../resources/request.md). Optional.|
|reason|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `201 Created` response code and a [userConsentRequest](../resources/userconsentrequest.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_userconsentrequest_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/appConsentRequest/userConsentRequests
Content-Type: application/json
Content-length: 280

{
  "@odata.type": "#microsoft.graph.userConsentRequest",
  "status": "String",
  "completedDateTime": "String (timestamp)",
  "approvalId": "String",
  "customData": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "reason": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.userConsentRequest"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.userConsentRequest",
  "id": "c396f1a1-f1a1-c396-a1f1-96c3a1f196c3",
  "status": "String",
  "completedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "approvalId": "String",
  "customData": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "reason": "String"
}
```

