---
title: "accessPackageResourceScope resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageResourceScope resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackageResourceScopes](../api/accesspackageresourcescope-list.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md) collection|Get a list of the [accessPackageResourceScope](../resources/accesspackageresourcescope.md) objects and their properties.|
|[Create accessPackageResourceScope](../api/accesspackageresource-post-accesspackageresourcescopes.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|Create a new [accessPackageResourceScope](../resources/accesspackageresourcescope.md) object.|
|[Get accessPackageResourceScope](../api/accesspackageresourcescope-get.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|Read the properties and relationships of an [accessPackageResourceScope](../resources/accesspackageresourcescope.md) object.|
|[Update accessPackageResourceScope](../api/accesspackageresourcescope-update.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|Update the properties of an [accessPackageResourceScope](../resources/accesspackageresourcescope.md) object.|
|[Delete accessPackageResourceScope](../api/accesspackageresourcescope-delete.md)|None|Deletes an [accessPackageResourceScope](../resources/accesspackageresourcescope.md) object.|
|[List accessPackageResource](../api/accesspackageresourcescope-list-accesspackageresource.md)|[accessPackageResource](../resources/accesspackageresource.md) collection|Get the accessPackageResource resources from the accessPackageResource navigation property.|
|[Create accessPackageResource](../api/accesspackageresourcescope-post-accesspackageresource.md)|[accessPackageResource](../resources/accesspackageresource.md)|Create a new accessPackageResource object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isRootScope|Boolean|**TODO: Add Description**|
|originId|String|**TODO: Add Description**|
|originSystem|String|**TODO: Add Description**|
|roleOriginId|String|**TODO: Add Description**|
|url|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageResource|[accessPackageResource](../resources/accesspackageresource.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackageResourceScope",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageResourceScope",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "originId": "String",
  "originSystem": "String",
  "roleOriginId": "String",
  "isRootScope": "Boolean",
  "url": "String"
}
```

