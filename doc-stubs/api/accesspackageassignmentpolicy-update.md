---
title: "Update accessPackageAssignmentPolicy"
description: "Update the properties of an accessPackageAssignmentPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update accessPackageAssignmentPolicy
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) object.

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
PATCH /identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}
PATCH /identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/accessPackageAssignmentPolicy
PATCH /identityGovernance/entitlementManagement/accessPackageCatalogs/{accessPackageCatalogId}/accessPackages/{accessPackageId}/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}
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
|accessPackageId|String|**TODO: Add Description** Optional.|
|displayName|String|**TODO: Add Description** Optional.|
|description|String|**TODO: Add Description** Optional.|
|canExtend|Boolean|**TODO: Add Description** Optional.|
|durationInDays|Int32|**TODO: Add Description** Optional.|
|expirationDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|createdBy|String|**TODO: Add Description** Optional.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|modifiedBy|String|**TODO: Add Description** Optional.|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|questions|[Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageQuestion](../resources/accesspackagequestion.md) collection|**TODO: Add Description** Optional.|
|requestorSettings|[Microsoft.IGAELM.EC.FrontEnd.ExternalModel.requestorSettings](../resources/requestorsettings.md)|**TODO: Add Description** Optional.|
|requestApprovalSettings|[Microsoft.IGAELM.EC.FrontEnd.ExternalModel.approvalSettings](../resources/approvalsettings.md)|**TODO: Add Description** Optional.|
|accessReviewSettings|[Microsoft.IGAELM.EC.FrontEnd.ExternalModel.assignmentReviewSettings](../resources/assignmentreviewsettings.md)|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_accesspackageassignmentpolicy"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageAssignmentPolicies/{accessPackageAssignmentPolicyId}
Content-Type: application/json
Content-length: 711

{
  "@odata.type": "#microsoft.graph.accessPackageAssignmentPolicy",
  "accessPackageId": "String",
  "displayName": "String",
  "description": "String",
  "canExtend": "Boolean",
  "durationInDays": "Integer",
  "expirationDateTime": "String (timestamp)",
  "createdBy": "String",
  "modifiedBy": "String",
  "questions": [
    {
      "@odata.type": "microsoft.graph.accessPackageMultipleChoiceQuestion"
    }
  ],
  "requestorSettings": {
    "@odata.type": "microsoft.graph.requestorSettings"
  },
  "requestApprovalSettings": {
    "@odata.type": "microsoft.graph.approvalSettings"
  },
  "accessReviewSettings": {
    "@odata.type": "microsoft.graph.assignmentReviewSettings"
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
  "@odata.type": "#microsoft.graph.accessPackageAssignmentPolicy",
  "id": "c6322eb9-2eb9-c632-b92e-32c6b92e32c6",
  "accessPackageId": "String",
  "displayName": "String",
  "description": "String",
  "canExtend": "Boolean",
  "durationInDays": "Integer",
  "expirationDateTime": "String (timestamp)",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)",
  "questions": [
    {
      "@odata.type": "microsoft.graph.accessPackageMultipleChoiceQuestion"
    }
  ],
  "requestorSettings": {
    "@odata.type": "microsoft.graph.requestorSettings"
  },
  "requestApprovalSettings": {
    "@odata.type": "microsoft.graph.approvalSettings"
  },
  "accessReviewSettings": {
    "@odata.type": "microsoft.graph.assignmentReviewSettings"
  }
}
```

