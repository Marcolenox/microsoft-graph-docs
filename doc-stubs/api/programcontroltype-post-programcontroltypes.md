---
title: "Create programControlType"
description: "Create a new programControlType object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create programControlType
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [programControlType](../resources/programcontroltype.md) object.

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
POST /programControlTypes
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [programControlType](../resources/programcontroltype.md) object.

You can specify the following properties when creating a **programControlType**.

|Property|Type|Description|
|:---|:---|:---|
|controlTypeGroupId|String|**TODO: Add Description** Optional.|
|displayName|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `201 Created` response code and a [programControlType](../resources/programcontroltype.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_programcontroltype_from_programcontroltypes"
}
-->
``` http
POST https://graph.microsoft.com/beta/programControlTypes
Content-Type: application/json
Content-length: 123

{
  "@odata.type": "#microsoft.graph.programControlType",
  "controlTypeGroupId": "String",
  "displayName": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.programControlType"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.programControlType",
  "id": "93da38dd-38dd-93da-dd38-da93dd38da93",
  "controlTypeGroupId": "String",
  "displayName": "String"
}
```

