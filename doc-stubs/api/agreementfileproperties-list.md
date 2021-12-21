---
title: "List agreementFileProperties"
description: "Get a list of the agreementFileProperties objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List agreementFileProperties
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [agreementFileProperties](../resources/agreementfileproperties.md) objects and their properties.

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
GET ** Collection URI for microsoft.azure.termsOfUse.agreementFileProperties not found
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

If successful, this method returns a `200 OK` response code and a collection of [agreementFileProperties](../resources/agreementfileproperties.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_agreementfileproperties"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for microsoft.azure.termsOfUse.agreementFileProperties not found
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.azure.termsOfUse.agreementFileProperties)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.azure.termsOfUse.agreementFileProperties",
      "id": "3dacf7b9-f7b9-3dac-b9f7-ac3db9f7ac3d",
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

