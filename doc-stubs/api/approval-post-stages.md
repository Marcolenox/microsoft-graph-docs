---
title: "Create approvalStage"
description: "Create a new approvalStage object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create approvalStage
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new approvalStage object.

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
POST /approval/stages
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [approvalStage](../resources/approvalstage.md) object.

You can specify the following properties when creating an **approvalStage**.

|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description** Optional.|
|status|String|**TODO: Add Description** Optional.|
|assignedToMe|Boolean|**TODO: Add Description** Optional.|
|reviewedBy|[identity](../resources/identity.md)|**TODO: Add Description** Optional.|
|reviewedDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|reviewResult|String|**TODO: Add Description** Optional.|
|justification|String|**TODO: Add Description** Optional.|



## Response

If successful, this method returns a `201 Created` response code and an [approvalStage](../resources/approvalstage.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_approvalstage_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/approval/stages
Content-Type: application/json
Content-length: 312

{
  "@odata.type": "#microsoft.graph.approvalStage",
  "displayName": "String",
  "status": "String",
  "assignedToMe": "Boolean",
  "reviewedBy": {
    "@odata.type": "microsoft.graph.identity"
  },
  "reviewedDateTime": "String (timestamp)",
  "reviewResult": "String",
  "justification": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.approvalStage"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.approvalStage",
  "id": "71ab5b37-5b37-71ab-375b-ab71375bab71",
  "displayName": "String",
  "status": "String",
  "assignedToMe": "Boolean",
  "reviewedBy": {
    "@odata.type": "microsoft.graph.identity"
  },
  "reviewedDateTime": "String (timestamp)",
  "reviewResult": "String",
  "justification": "String"
}
```

