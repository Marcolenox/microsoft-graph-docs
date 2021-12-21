---
title: "request resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# request resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List requests](../api/request-list.md)|[request](../resources/request.md) collection|Get a list of the [request](../resources/request.md) objects and their properties.|
|[Create request](../api/approval-post-request.md)|[request](../resources/request.md)|Create a new [request](../resources/request.md) object.|
|[Get request](../api/request-get.md)|[request](../resources/request.md)|Read the properties and relationships of a [request](../resources/request.md) object.|
|[Update request](../api/request-update.md)|[request](../resources/request.md)|Update the properties of a [request](../resources/request.md) object.|
|[Delete request](../api/request-delete.md)|None|Deletes a [request](../resources/request.md) object.|
|[stop](../api/request-stop.md)|None|**TODO: Add Description**|
|[recordDecisions](../api/request-recorddecisions.md)|None|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|approvalId|String|**TODO: Add Description**|
|completedDateTime|DateTimeOffset|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|customData|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|status|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.request",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.request",
  "id": "String (identifier)",
  "status": "String",
  "completedDateTime": "String (timestamp)",
  "createdDateTime": "String (timestamp)",
  "approvalId": "String",
  "customData": "String",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  }
}
```

