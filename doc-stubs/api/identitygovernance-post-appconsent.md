---
title: "Create appConsentApprovalRoute"
description: "Create a new appConsentApprovalRoute object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create appConsentApprovalRoute
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [appConsentApprovalRoute](../resources/appconsentapprovalroute.md) object.

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
POST ** Collection URI for microsoft.graph.appConsentApprovalRoute not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [appConsentApprovalRoute](../resources/appconsentapprovalroute.md) object.

You can specify the following properties when creating an **appConsentApprovalRoute**.

|Property|Type|Description|
|:---|:---|:---|



## Response

If successful, this method returns a `201 Created` response code and an [appConsentApprovalRoute](../resources/appconsentapprovalroute.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_appconsentapprovalroute_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.appConsentApprovalRoute not found
Content-Type: application/json
Content-length: 65

{
  "@odata.type": "#microsoft.graph.appConsentApprovalRoute"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.appConsentApprovalRoute"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.appConsentApprovalRoute"
}
```

