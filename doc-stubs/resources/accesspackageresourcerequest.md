---
title: "accessPackageResourceRequest resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageResourceRequest resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackageResourceRequests](../api/accesspackageresourcerequest-list.md)|[accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) collection|Get a list of the [accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) objects and their properties.|
|[Create accessPackageResourceRequest](../api/entitlementmanagement-post-accesspackageresourcerequests.md)|[accessPackageResourceRequest](../resources/accesspackageresourcerequest.md)|Create a new [accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) object.|
|[Get accessPackageResourceRequest](../api/accesspackageresourcerequest-get.md)|[accessPackageResourceRequest](../resources/accesspackageresourcerequest.md)|Read the properties and relationships of an [accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) object.|
|[Update accessPackageResourceRequest](../api/accesspackageresourcerequest-update.md)|[accessPackageResourceRequest](../resources/accesspackageresourcerequest.md)|Update the properties of an [accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) object.|
|[Delete accessPackageResourceRequest](../api/accesspackageresourcerequest-delete.md)|None|Deletes an [accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) object.|
|[List accessPackageResource](../api/accesspackageresourcerequest-list-accesspackageresource.md)|[accessPackageResource](../resources/accesspackageresource.md) collection|Get the accessPackageResource resources from the accessPackageResource navigation property.|
|[Add accessPackageResource](../api/accesspackageresourcerequest-post-accesspackageresource.md)|[accessPackageResource](../resources/accesspackageresource.md)|Add accessPackageResource by posting to the accessPackageResource collection.|
|[List accessPackageSubject](../api/accesspackageresourcerequest-list-requestor.md)|[accessPackageSubject](../resources/accesspackagesubject.md) collection|Get the accessPackageSubject resources from the requestor navigation property.|
|[Create accessPackageSubject](../api/accesspackageresourcerequest-post-requestor.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Create a new accessPackageSubject object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|catalogId|String|**TODO: Add Description**|
|executeImmediately|Boolean|**TODO: Add Description**|
|expirationDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isValidationOnly|Boolean|**TODO: Add Description**|
|justification|String|**TODO: Add Description**|
|requestState|String|**TODO: Add Description**|
|requestStatus|String|**TODO: Add Description**|
|requestType|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageResource|[accessPackageResource](../resources/accesspackageresource.md)|**TODO: Add Description**|
|requestor|[accessPackageSubject](../resources/accesspackagesubject.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackageResourceRequest",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageResourceRequest",
  "id": "String (identifier)",
  "catalogId": "String",
  "executeImmediately": "Boolean",
  "isValidationOnly": "Boolean",
  "requestType": "String",
  "requestState": "String",
  "requestStatus": "String",
  "expirationDateTime": "String (timestamp)",
  "justification": "String"
}
```

