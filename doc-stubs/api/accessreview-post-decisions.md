---
title: "Create accessReviewDecision"
description: "Create a new accessReviewDecision object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create accessReviewDecision
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new accessReviewDecision object.

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
POST /accessReviews/{accessReviewsId}/decisions
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [accessReviewDecision](../resources/accessreviewdecision.md) object.

You can specify the following properties when creating an **accessReviewDecision**.

|Property|Type|Description|
|:---|:---|:---|
|accessReviewId|String|**TODO: Add Description** Optional.|
|reviewedBy|[userIdentity](../resources/useridentity.md)|**TODO: Add Description** Optional.|
|reviewedDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|reviewResult|String|**TODO: Add Description** Optional.|
|justification|String|**TODO: Add Description** Optional.|
|appliedBy|[userIdentity](../resources/useridentity.md)|**TODO: Add Description** Optional.|
|appliedDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|applyResult|String|**TODO: Add Description** Optional.|
|accessRecommendation|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `201 Created` response code and an [accessReviewDecision](../resources/accessreviewdecision.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_accessreviewdecision_from_accessreviewdecisions"
}
-->
``` http
POST https://graph.microsoft.com/beta/accessReviews/{accessReviewsId}/decisions
Content-Type: application/json
Content-length: 457

{
  "@odata.type": "#microsoft.graph.accessReviewDecision",
  "accessReviewId": "String",
  "reviewedBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "reviewedDateTime": "String (timestamp)",
  "reviewResult": "String",
  "justification": "String",
  "appliedBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "appliedDateTime": "String (timestamp)",
  "applyResult": "String",
  "accessRecommendation": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.accessReviewDecision"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.accessReviewDecision",
  "id": "18f500cf-00cf-18f5-cf00-f518cf00f518",
  "accessReviewId": "String",
  "reviewedBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "reviewedDateTime": "String (timestamp)",
  "reviewResult": "String",
  "justification": "String",
  "appliedBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "appliedDateTime": "String (timestamp)",
  "applyResult": "String",
  "accessRecommendation": "String"
}
```

