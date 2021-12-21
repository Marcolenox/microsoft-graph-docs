---
title: "Update accessReviewScheduleDefinition"
description: "Update the properties of an accessReviewScheduleDefinition object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update accessReviewScheduleDefinition
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [accessReviewScheduleDefinition](../resources/accessreviewscheduledefinition.md) object.

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
PATCH /accessReviewScheduleDefinition
PATCH /accessReviewSet/definitions/{accessReviewScheduleDefinitionId}
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
|createdDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|status|String|**TODO: Add Description** Optional.|
|descriptionForAdmins|String|**TODO: Add Description** Optional.|
|descriptionForReviewers|String|**TODO: Add Description** Optional.|
|createdBy|[userIdentity](../resources/useridentity.md)|**TODO: Add Description** Optional.|
|scope|[accessReviewScope](../resources/accessreviewscope.md)|**TODO: Add Description** Optional.|
|reviewers|[accessReviewReviewerScope](../resources/accessreviewreviewerscope.md) collection|**TODO: Add Description** Optional.|
|fallbackReviewers|[accessReviewReviewerScope](../resources/accessreviewreviewerscope.md) collection|**TODO: Add Description** Optional.|
|additionalNotificationRecipients|[accessReviewNotificationRecipientItem](../resources/accessreviewnotificationrecipientitem.md) collection|**TODO: Add Description** Optional.|
|instanceEnumerationScope|[accessReviewScope](../resources/accessreviewscope.md)|**TODO: Add Description** Optional.|
|settings|[accessReviewScheduleSettings](../resources/accessreviewschedulesettings.md)|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [accessReviewScheduleDefinition](../resources/accessreviewscheduledefinition.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_accessreviewscheduledefinition"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/accessReviewScheduleDefinition
Content-Type: application/json
Content-length: 891

{
  "@odata.type": "#microsoft.graph.accessReviewScheduleDefinition",
  "displayName": "String",
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
```

