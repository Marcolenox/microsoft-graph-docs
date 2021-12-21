---
title: "Update programControl"
description: "Update the properties of a programControl object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update programControl
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [programControl](../resources/programcontrol.md) object.

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
PATCH /programControls/{programControlsId}
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
|controlId|String|**TODO: Add Description** Required.|
|programId|String|**TODO: Add Description** Required.|
|controlTypeId|String|**TODO: Add Description** Required.|
|displayName|String|**TODO: Add Description** Optional.|
|status|String|**TODO: Add Description** Optional.|
|owner|[userIdentity](../resources/useridentity.md)|**TODO: Add Description** Optional.|
|resource|[programResource](../resources/programresource.md)|**TODO: Add Description** Optional.|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Required.|



## Response

If successful, this method returns a `200 OK` response code and an updated [programControl](../resources/programcontrol.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_programcontrol"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/programControls/{programControlsId}
Content-Type: application/json
Content-length: 337

{
  "@odata.type": "#microsoft.graph.programControl",
  "controlId": "String",
  "programId": "String",
  "controlTypeId": "String",
  "displayName": "String",
  "status": "String",
  "owner": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "resource": {
    "@odata.type": "microsoft.graph.programResource"
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
  "@odata.type": "#microsoft.graph.programControl",
  "id": "ef127bf5-7bf5-ef12-f57b-12eff57b12ef",
  "controlId": "String",
  "programId": "String",
  "controlTypeId": "String",
  "displayName": "String",
  "status": "String",
  "owner": {
    "@odata.type": "microsoft.graph.userIdentity"
  },
  "resource": {
    "@odata.type": "microsoft.graph.programResource"
  },
  "createdDateTime": "String (timestamp)"
}
```

