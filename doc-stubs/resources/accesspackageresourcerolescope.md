---
title: "accessPackageResourceRoleScope resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageResourceRoleScope resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackageResourceRoleScopes](../api/accesspackageresourcerolescope-list.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|Get a list of the [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) objects and their properties.|
|[Create accessPackageResourceRoleScope](../api/accesspackage-post-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Create a new [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) object.|
|[Get accessPackageResourceRoleScope](../api/accesspackageresourcerolescope-get.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Read the properties and relationships of an [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) object.|
|[Update accessPackageResourceRoleScope](../api/accesspackageresourcerolescope-update.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Update the properties of an [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) object.|
|[Delete accessPackageResourceRoleScope](../api/accesspackageresourcerolescope-delete.md)|None|Deletes an [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) object.|
|[List accessPackageResourceRole](../api/accesspackageresourcerolescope-list-accesspackageresourcerole.md)|[accessPackageResourceRole](../resources/accesspackageresourcerole.md) collection|Get the accessPackageResourceRole resources from the accessPackageResourceRole navigation property.|
|[Create accessPackageResourceRole](../api/accesspackageresourcerolescope-post-accesspackageresourcerole.md)|[accessPackageResourceRole](../resources/accesspackageresourcerole.md)|Create a new accessPackageResourceRole object.|
|[List accessPackageResourceScope](../api/accesspackageresourcerolescope-list-accesspackageresourcescope.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md) collection|Get the accessPackageResourceScope resources from the accessPackageResourceScope navigation property.|
|[Create accessPackageResourceScope](../api/accesspackageresourcerolescope-post-accesspackageresourcescope.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|Create a new accessPackageResourceScope object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageResourceRole|[accessPackageResourceRole](../resources/accesspackageresourcerole.md)|**TODO: Add Description**|
|accessPackageResourceScope|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackageResourceRoleScope",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageResourceRoleScope",
  "id": "String (identifier)",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)"
}
```

