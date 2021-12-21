---
title: "accessPackageAssignmentResourceRole resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageAssignmentResourceRole resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackageAssignmentResourceRoles](../api/accesspackageassignmentresourcerole-list.md)|[accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) collection|Get a list of the [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) objects and their properties.|
|[Create accessPackageAssignmentResourceRole](../api/accesspackageassignment-post-accesspackageassignmentresourceroles.md)|[accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md)|Create a new [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object.|
|[Get accessPackageAssignmentResourceRole](../api/accesspackageassignmentresourcerole-get.md)|[accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md)|Read the properties and relationships of an [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object.|
|[Update accessPackageAssignmentResourceRole](../api/accesspackageassignmentresourcerole-update.md)|[accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md)|Update the properties of an [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object.|
|[Delete accessPackageAssignmentResourceRole](../api/accesspackageassignmentresourcerole-delete.md)|None|Deletes an [accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) object.|
|[My](../api/accesspackageassignmentresourcerole-my.md)|[accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) collection|**TODO: Add Description**|
|[List accessPackageAssignments](../api/accesspackageassignmentresourcerole-list-accesspackageassignments.md)|[accessPackageAssignment](../resources/accesspackageassignment.md) collection|Get the accessPackageAssignment resources from the accessPackageAssignments navigation property.|
|[Create accessPackageAssignment](../api/accesspackageassignmentresourcerole-post-accesspackageassignments.md)|[accessPackageAssignment](../resources/accesspackageassignment.md)|Create a new accessPackageAssignment object.|
|[List accessPackageResourceRole](../api/accesspackageassignmentresourcerole-list-accesspackageresourcerole.md)|[accessPackageResourceRole](../resources/accesspackageresourcerole.md) collection|Get the accessPackageResourceRole resources from the accessPackageResourceRole navigation property.|
|[Create accessPackageResourceRole](../api/accesspackageassignmentresourcerole-post-accesspackageresourcerole.md)|[accessPackageResourceRole](../resources/accesspackageresourcerole.md)|Create a new accessPackageResourceRole object.|
|[List accessPackageResourceScope](../api/accesspackageassignmentresourcerole-list-accesspackageresourcescope.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md) collection|Get the accessPackageResourceScope resources from the accessPackageResourceScope navigation property.|
|[Create accessPackageResourceScope](../api/accesspackageassignmentresourcerole-post-accesspackageresourcescope.md)|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|Create a new accessPackageResourceScope object.|
|[List accessPackageSubject](../api/accesspackageassignmentresourcerole-list-accesspackagesubject.md)|[accessPackageSubject](../resources/accesspackagesubject.md) collection|Get the accessPackageSubject resources from the accessPackageSubject navigation property.|
|[Create accessPackageSubject](../api/accesspackageassignmentresourcerole-post-accesspackagesubject.md)|[accessPackageSubject](../resources/accesspackagesubject.md)|Create a new accessPackageSubject object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|originId|String|**TODO: Add Description**|
|originSystem|String|**TODO: Add Description**|
|status|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageAssignments|[accessPackageAssignment](../resources/accesspackageassignment.md) collection|**TODO: Add Description**|
|accessPackageResourceRole|[accessPackageResourceRole](../resources/accesspackageresourcerole.md)|**TODO: Add Description**|
|accessPackageResourceScope|[accessPackageResourceScope](../resources/accesspackageresourcescope.md)|**TODO: Add Description**|
|accessPackageSubject|[accessPackageSubject](../resources/accesspackagesubject.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackageAssignmentResourceRole",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageAssignmentResourceRole",
  "id": "String (identifier)",
  "originId": "String",
  "originSystem": "String",
  "status": "String"
}
```

