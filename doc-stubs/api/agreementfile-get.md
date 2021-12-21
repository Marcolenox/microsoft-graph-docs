---
title: "Get agreementFile"
description: "Read the properties and relationships of an agreementFile object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get agreementFile
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of an [agreementFile](../resources/agreementfile.md) object.

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
GET /agreements/{agreementsId}/file
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

If successful, this method returns a `200 OK` response code and an [agreementFile](../resources/agreementfile.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_agreementfile"
}
-->
``` http
GET https://graph.microsoft.com/beta/agreements/{agreementsId}/file
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.azure.termsOfUse.agreementFile"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.azure.termsOfUse.agreementFile",
    "id": "1b2a1a7d-1a7d-1b2a-7d1a-2a1b7d1a2a1b",
    "fileName": "String",
    "language": "String",
    "isDefault": "Boolean",
    "isMajorVersion": "Boolean",
    "createdDateTime": "String (timestamp)",
    "displayName": "String",
    "fileData": {
      "@odata.type": "microsoft.graph.agreementFileData"
    }
  }
}
```

