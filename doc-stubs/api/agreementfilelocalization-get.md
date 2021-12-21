---
title: "Get agreementFileLocalization"
description: "Read the properties and relationships of an agreementFileLocalization object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get agreementFileLocalization
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of an [agreementFileLocalization](../resources/agreementfilelocalization.md) object.

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
GET /agreements/{agreementsId}/files/{agreementFileLocalizationId}
GET /agreements/{agreementsId}/file/localizations/{agreementFileLocalizationId}
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

If successful, this method returns a `200 OK` response code and an [agreementFileLocalization](../resources/agreementfilelocalization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_agreementfilelocalization"
}
-->
``` http
GET https://graph.microsoft.com/beta/agreements/{agreementsId}/files/{agreementFileLocalizationId}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.azure.termsOfUse.agreementFileLocalization"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.azure.termsOfUse.agreementFileLocalization",
    "id": "d306fe4f-fe4f-d306-4ffe-06d34ffe06d3",
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

