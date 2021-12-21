---
title: "Get accessReviewInstanceDecisionItem"
description: "Read the properties and relationships of an accessReviewInstanceDecisionItem object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get accessReviewInstanceDecisionItem
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of an [accessReviewInstanceDecisionItem](../resources/accessreviewinstancedecisionitem.md) object.

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
GET /accessReviewScheduleDefinition/instances/{accessReviewInstanceId}/decisions/{accessReviewInstanceDecisionItemId}
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and an [accessReviewInstanceDecisionItem](../resources/accessreviewinstancedecisionitem.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_accessreviewinstancedecisionitem"
}
-->
``` http
GET https://graph.microsoft.com/beta/accessReviewScheduleDefinition/instances/{accessReviewInstanceId}/decisions/{accessReviewInstanceDecisionItemId}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.accessReviewInstanceDecisionItem"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.accessReviewInstanceDecisionItem",
    "id": "e47ba547-a547-e47b-47a5-7be447a57be4",
    "accessReviewId": "String",
    "reviewedBy": {
      "@odata.type": "microsoft.graph.userIdentity"
    },
    "reviewedDateTime": "String (timestamp)",
    "decision": "String",
    "justification": "String",
    "appliedBy": {
      "@odata.type": "microsoft.graph.userIdentity"
    },
    "appliedDateTime": "String (timestamp)",
    "applyResult": "String",
    "recommendation": "String",
    "principal": {
      "@odata.type": "microsoft.graph.identity"
    },
    "principalLink": "String",
    "resource": {
      "@odata.type": "microsoft.graph.accessReviewInstanceDecisionItemResource"
    },
    "resourceLink": "String"
  }
}
```

