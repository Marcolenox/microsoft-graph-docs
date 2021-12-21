---
title: "Get accessReviewScheduleDefinition"
description: "Read the properties and relationships of an accessReviewScheduleDefinition object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get accessReviewScheduleDefinition
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of an [accessReviewScheduleDefinition](../resources/accessreviewscheduledefinition.md) object.

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
GET /accessReviewScheduleDefinition
GET /accessReviewSet/definitions/{accessReviewScheduleDefinitionId}
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

If successful, this method returns a `200 OK` response code and an [accessReviewScheduleDefinition](../resources/accessreviewscheduledefinition.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_accessreviewscheduledefinition"
}
-->
``` http
GET https://graph.microsoft.com/beta/accessReviewScheduleDefinition
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.accessReviewScheduleDefinition"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.accessReviewScheduleDefinition",
    "id": "f1f4ef9d-ef9d-f1f4-9def-f4f19deff4f1",
    "displayName": "String",
    "createdDateTime": "String (timestamp)",
    "lastModifiedDateTime": "String (timestamp)",
    "status": "String",
    "descriptionForAdmins": "String",
    "descriptionForReviewers": "String",
    "createdBy": {
      "@odata.type": "microsoft.graph.userIdentity"
    },
    "scope": {
      "@odata.type": "microsoft.graph.accessReviewScope"
    },
    "reviewers": [
      {
        "@odata.type": "microsoft.graph.accessReviewReviewerScope"
      }
    ],
    "fallbackReviewers": [
      {
        "@odata.type": "microsoft.graph.accessReviewReviewerScope"
      }
    ],
    "additionalNotificationRecipients": [
      {
        "@odata.type": "microsoft.graph.accessReviewNotificationRecipientItem"
      }
    ],
    "instanceEnumerationScope": {
      "@odata.type": "microsoft.graph.accessReviewScope"
    },
    "settings": {
      "@odata.type": "microsoft.graph.accessReviewScheduleSettings"
    }
  }
}
```

