---
title: "agreementFileVersion resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# agreementFileVersion resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [agreementFileProperties](../resources/agreementfileproperties.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List agreementFileVersions](../api/agreementfileversion-list.md)|[agreementFileVersion](../resources/agreementfileversion.md) collection|Get a list of the [agreementFileVersion](../resources/agreementfileversion.md) objects and their properties.|
|[Create agreementFileVersion](../api/agreementfilelocalization-post-versions.md)|[agreementFileVersion](../resources/agreementfileversion.md)|Create a new [agreementFileVersion](../resources/agreementfileversion.md) object.|
|[Get agreementFileVersion](../api/agreementfileversion-get.md)|[agreementFileVersion](../resources/agreementfileversion.md)|Read the properties and relationships of an [agreementFileVersion](../resources/agreementfileversion.md) object.|
|[Update agreementFileVersion](../api/agreementfileversion-update.md)|[agreementFileVersion](../resources/agreementfileversion.md)|Update the properties of an [agreementFileVersion](../resources/agreementfileversion.md) object.|
|[Delete agreementFileVersion](../api/agreementfileversion-delete.md)|None|Deletes an [agreementFileVersion](../resources/agreementfileversion.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|displayName|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|fileData|[agreementFileData](../resources/agreementfiledata.md)|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|fileName|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|id|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|isDefault|Boolean|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|isMajorVersion|Boolean|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|
|language|String|**TODO: Add Description** Inherited from [agreementFileProperties](../resources/agreementfileproperties.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.agreementFileVersion",
  "baseType": "microsoft.azure.termsOfUse.agreementFileProperties",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.agreementFileVersion",
  "id": "String (identifier)",
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
```

