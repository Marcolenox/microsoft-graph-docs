---
title: "Create accessReviewHistoryDefinition"
description: "Create a new accessReviewHistoryDefinition object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create accessReviewHistoryDefinition
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new accessReviewHistoryDefinition object.

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
POST /accessReviewSet/historyDefinitions
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [accessReviewHistoryDefinition](../resources/accessreviewhistorydefinition.md) object.

You can specify the following properties when creating an **accessReviewHistoryDefinition**.

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description** Required.|
|status|accessReviewHistoryStatus|**TODO: Add Description**. The possible values are: `done`, `inprogress`, `error`, `requested`, `unknownFutureValue`. Optional.|
|decisions|accessReviewHistoryDecisionFilter collection|**TODO: Add Description**. The possible values are: `approve`, `deny`, `notReviewed`, `dontKnow`, `notNotified`, `unknownFutureValue`. Optional.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Required.|
|fulfilledDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|reviewHistoryPeriodStartDateTime|DateTimeOffset|**TODO: Add Description** Required.|
|reviewHistoryPeriodEndDateTime|DateTimeOffset|**TODO: Add Description** Required.|
|createdBy|[userIdentity](../resources/useridentity.md)|**TODO: Add Description** Required.|
|scopes|[accessReviewScope](../resources/accessreviewscope.md) collection|**TODO: Add Description** Required.|
|downloadUri|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `201 Created` response code and an [accessReviewHistoryDefinition](../resources/accessreviewhistorydefinition.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_accessreviewhistorydefinition_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/accessReviewSet/historyDefinitions
Content-Type: application/json
Content-length: 522

{
  "@odata.type": "#microsoft.graph.accessReviewHistoryDefinition",
  "displayName": "String",
  "status": "String",
  "decisions": [
    "String"
  ],
  "fulfilledDateTime": "String (timestamp)",
  "reviewHistoryPeriodStartDateTime": "String (timestamp)",
  "reviewHistoryPeriodEndDateTime": "String (timestamp)",
  "createdBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "scopes": [
    {
      "@odata.type": "microsoft.graph.accessReviewScope"
    }
  ],
  "downloadUri": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.accessReviewHistoryDefinition"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.accessReviewHistoryDefinition",
  "id": "b5785e1b-5e1b-b578-1b5e-78b51b5e78b5",
  "displayName": "String",
  "status": "String",
  "decisions": [
    "String"
  ],
  "createdDateTime": "String (timestamp)",
  "fulfilledDateTime": "String (timestamp)",
  "reviewHistoryPeriodStartDateTime": "String (timestamp)",
  "reviewHistoryPeriodEndDateTime": "String (timestamp)",
  "createdBy": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "scopes": [
    {
      "@odata.type": "microsoft.graph.accessReviewScope"
    }
  ],
  "downloadUri": "String"
}
```

