---
title: "Create accessPackageAssignmentResourceRole"
description: "Create a new accessPackageAssignmentResourceRole object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create accessPackageAssignmentResourceRole
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object.

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
POST /identityGovernance/entitlementManagement/accessPackageAssignmentResourceRoles
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object.

You can specify the following properties when creating an **accessPackageAssignmentResourceRole**.

|Property|Type|Description|
|:---|:---|:---|
|originId|String|**TODO: Add Description** Optional.|
|originSystem|String|**TODO: Add Description** Optional.|
|status|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `201 Created` response code and an [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_accesspackageassignmentresourcerole_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/accessPackageAssignmentResourceRoles
Content-Type: application/json
Content-length: 181

{
  "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentResourceRole",
  "originId": "String",
  "originSystem": "String",
  "status": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentResourceRole"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.accessPackageAssignmentResourceRole",
  "id": "7770e3a7-e3a7-7770-a7e3-7077a7e37077",
  "originId": "String",
  "originSystem": "String",
  "status": "String"
}
```

