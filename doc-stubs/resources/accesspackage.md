---
title: "accessPackage resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackage resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackages](../api/accesspackage-list.md)|[accessPackage](../resources/accesspackage.md) collection|Get a list of the [accessPackage](../resources/accesspackage.md) objects and their properties.|
|[Create accessPackage](../api/accesspackagecatalog-post-accesspackages.md)|[accessPackage](../resources/accesspackage.md)|Create a new [accessPackage](../resources/accesspackage.md) object.|
|[Get accessPackage](../api/accesspackage-get.md)|[accessPackage](../resources/accesspackage.md)|Read the properties and relationships of an [accessPackage](../resources/accesspackage.md) object.|
|[Update accessPackage](../api/accesspackage-update.md)|[accessPackage](../resources/accesspackage.md)|Update the properties of an [accessPackage](../resources/accesspackage.md) object.|
|[Delete accessPackage](../api/accesspackage-delete.md)|None|Deletes an [accessPackage](../resources/accesspackage.md) object.|
|[Search](../api/accesspackage-search.md)|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|
|[filterByCurrentUser](../api/accesspackage-filterbycurrentuser.md)|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|
|[getApplicablePolicyRequirements](../api/accesspackage-getapplicablepolicyrequirements.md)|[accessPackageAssignmentRequestRequirements](../resources/accesspackageassignmentrequestrequirements.md) collection|**TODO: Add Description**|
|[List accessPackageAssignmentPolicies](../api/accesspackage-list-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|Get the accessPackageAssignmentPolicy resources from the accessPackageAssignmentPolicies navigation property.|
|[Create accessPackageAssignmentPolicy](../api/accesspackage-post-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md)|Create a new accessPackageAssignmentPolicy object.|
|[List accessPackageCatalog](../api/accesspackage-list-accesspackagecatalog.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md) collection|Get the accessPackageCatalog resources from the accessPackageCatalog navigation property.|
|[Add accessPackageCatalog](../api/accesspackage-post-accesspackagecatalog.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md)|Add accessPackageCatalog by posting to the accessPackageCatalog collection.|
|[List accessPackageResourceRoleScopes](../api/accesspackage-list-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|Get the accessPackageResourceRoleScope resources from the accessPackageResourceRoleScopes navigation property.|
|[Create accessPackageResourceRoleScope](../api/accesspackage-post-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Create a new accessPackageResourceRoleScope object.|
|[List accessPackagesIncompatibleWith](../api/accesspackage-list-accesspackagesincompatiblewith.md)|[accessPackage](../resources/accesspackage.md) collection|Get the accessPackage resources from the accessPackagesIncompatibleWith navigation property.|
|[Add accessPackage](../api/accesspackage-post-accesspackagesincompatiblewith.md)|[accessPackage](../resources/accesspackage.md)|Add accessPackagesIncompatibleWith by posting to the accessPackagesIncompatibleWith collection.|
|[List incompatibleAccessPackages](../api/accesspackage-list-incompatibleaccesspackages.md)|[accessPackage](../resources/accesspackage.md) collection|Get the accessPackage resources from the incompatibleAccessPackages navigation property.|
|[Add accessPackage](../api/accesspackage-post-incompatibleaccesspackages.md)|[accessPackage](../resources/accesspackage.md)|Add incompatibleAccessPackages by posting to the incompatibleAccessPackages collection.|
|[List incompatibleGroups](../api/accesspackage-list-incompatiblegroups.md)|[group](../resources/group.md) collection|Get the group resources from the incompatibleGroups navigation property.|
|[Create group](../api/accesspackage-post-incompatiblegroups.md)|[group](../resources/group.md)|Create a new group object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|catalogId|String|**TODO: Add Description**|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isHidden|Boolean|**TODO: Add Description**|
|isRoleScopesVisible|Boolean|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageAssignmentPolicies|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|**TODO: Add Description**|
|accessPackageCatalog|[accessPackageCatalog](../resources/accesspackagecatalog.md)|**TODO: Add Description**|
|accessPackageResourceRoleScopes|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|**TODO: Add Description**|
|accessPackagesIncompatibleWith|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|
|incompatibleAccessPackages|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|
|incompatibleGroups|[group](../resources/group.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackage",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackage",
  "id": "String (identifier)",
  "catalogId": "String",
  "displayName": "String",
  "description": "String",
  "isHidden": "Boolean",
  "isRoleScopesVisible": "Boolean",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)"
}
```

