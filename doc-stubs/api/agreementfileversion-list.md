---
title: "List agreementFileVersions"
description: "Get a list of the agreementFileVersion objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List agreementFileVersions
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [agreementFileVersion](../resources/agreementfileversion.md) objects and their properties.

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
GET /agreements/{agreementsId}/file/localizations/{agreementFileLocalizationId}/versions
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

If successful, this method returns a `200 OK` response code and a collection of [agreementFileVersion](../resources/agreementfileversion.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_agreementfileversion"
}
-->
``` http
GET https://graph.microsoft.com/beta/agreements/{agreementsId}/file/localizations/{agreementFileLocalizationId}/versions
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.azure.termsOfUse.agreementFileVersion)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.azure.termsOfUse.agreementFileVersion",
      "id": "9527b6d5-b6d5-9527-d5b6-2795d5b62795",
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
  ]
}
```

