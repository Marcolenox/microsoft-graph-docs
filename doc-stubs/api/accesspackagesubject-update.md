---
title: "Update accessPackageSubject"
description: "Update the properties of an accessPackageSubject object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update accessPackageSubject
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [accessPackageSubject](../resources/accesspackagesubject.md) object.

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
PATCH /identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/target
PATCH /identityGovernance/entitlementManagement/accessPackageResourceRequests/{accessPackageResourceRequestId}/requestor
PATCH /identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/accessPackageAssignmentRequests/{accessPackageAssignmentRequestId}/requestor
PATCH /identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/accessPackageAssignmentResourceRoles/{accessPackageAssignmentResourceRoleId}/accessPackageSubject
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
|objectId|String|**TODO: Add Description** Optional.|
|altSecId|String|**TODO: Add Description** Optional.|
|displayName|String|**TODO: Add Description** Optional.|
|principalName|String|**TODO: Add Description** Optional.|
|email|String|**TODO: Add Description** Optional.|
|onPremisesSecurityIdentifier|String|**TODO: Add Description** Optional.|
|type|String|**TODO: Add Description** Optional.|
|connectedOrganizationId|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [accessPackageSubject](../resources/accesspackagesubject.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_accesspackagesubject"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageAssignments/{accessPackageAssignmentId}/target
Content-Type: application/json
Content-length: 298

{
  "@odata.type": "#microsoft.graph.accessPackageSubject",
  "objectId": "String",
  "altSecId": "String",
  "displayName": "String",
  "principalName": "String",
  "email": "String",
  "onPremisesSecurityIdentifier": "String",
  "type": "String",
  "connectedOrganizationId": "String"
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
  "@odata.type": "#microsoft.graph.accessPackageSubject",
  "id": "984a2870-2870-984a-7028-4a9870284a98",
  "objectId": "String",
  "altSecId": "String",
  "displayName": "String",
  "principalName": "String",
  "email": "String",
  "onPremisesSecurityIdentifier": "String",
  "type": "String",
  "connectedOrganizationId": "String"
}
```

