---
title: "Update accessPackageAssignmentRequest"
description: "Update the properties of an accessPackageAssignmentRequest object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update accessPackageAssignmentRequest
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [accessPackageAssignmentRequest](../resources/accesspackageassignmentrequest.md) object.

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
PATCH /identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{accessPackageAssignmentRequestId}
PATCH /identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/accessPackageAssignmentRequests/{accessPackageAssignmentRequestId}
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
|requestType|String|**TODO: Add Description** Optional.|
|requestState|String|**TODO: Add Description** Optional.|
|requestStatus|String|**TODO: Add Description** Optional.|
|isValidationOnly|Boolean|**TODO: Add Description** Optional.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|completedDate|DateTimeOffset|**TODO: Add Description** Optional.|
|expirationDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|justification|String|**TODO: Add Description** Optional.|
|schedule|[Microsoft.IGAELM.EC.FrontEnd.ExternalModel.requestSchedule](../resources/requestschedule.md)|**TODO: Add Description** Optional.|
|answers|[Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAnswer](../resources/accesspackageanswer.md) collection|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [accessPackageAssignmentRequest](../resources/accesspackageassignmentrequest.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_accesspackageassignmentrequest"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageAssignmentRequests/{accessPackageAssignmentRequestId}
Content-Type: application/json
Content-length: 491

{
  "@odata.type": "#microsoft.graph.accessPackageAssignmentRequest",
  "requestType": "String",
  "requestState": "String",
  "requestStatus": "String",
  "isValidationOnly": "Boolean",
  "completedDate": "String (timestamp)",
  "expirationDateTime": "String (timestamp)",
  "justification": "String",
  "schedule": {
    "@odata.type": "microsoft.graph.requestSchedule"
  },
  "answers": [
    {
      "@odata.type": "microsoft.graph.accessPackageAnswerString"
    }
  ]
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
  "@odata.type": "#microsoft.graph.accessPackageAssignmentRequest",
  "id": "2a36a7a8-a7a8-2a36-a8a7-362aa8a7362a",
  "requestType": "String",
  "requestState": "String",
  "requestStatus": "String",
  "isValidationOnly": "Boolean",
  "createdDateTime": "String (timestamp)",
  "completedDate": "String (timestamp)",
  "expirationDateTime": "String (timestamp)",
  "justification": "String",
  "schedule": {
    "@odata.type": "microsoft.graph.requestSchedule"
  },
  "answers": [
    {
      "@odata.type": "microsoft.graph.accessPackageAnswerString"
    }
  ]
}
```

