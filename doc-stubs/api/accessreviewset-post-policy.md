---
title: "Create accessReviewPolicy"
description: "Create a new accessReviewPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create accessReviewPolicy
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new accessReviewPolicy object.

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
POST /accessReviewSet/policy
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [accessReviewPolicy](../resources/accessreviewpolicy.md) object.

You can specify the following properties when creating an **accessReviewPolicy**.

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description** Required.|
|description|String|**TODO: Add Description** Optional.|
|isGroupOwnerManagementEnabled|Boolean|**TODO: Add Description** Required.|



## Response

If successful, this method returns a `201 Created` response code and an [accessReviewPolicy](../resources/accessreviewpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_accessreviewpolicy_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/accessReviewSet/policy
Content-Type: application/json
Content-length: 163

{
  "@odata.type": "#microsoft.graph.accessReviewPolicy",
  "displayName": "String",
  "description": "String",
  "isGroupOwnerManagementEnabled": "Boolean"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.accessReviewPolicy"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.accessReviewPolicy",
  "displayName": "String",
  "description": "String",
  "isGroupOwnerManagementEnabled": "Boolean"
}
```

