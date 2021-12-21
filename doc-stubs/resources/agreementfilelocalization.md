---
title: "agreementFileLocalization resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# agreementFileLocalization resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [agreementFileProperties](../resources/agreementfileproperties.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List agreementFileLocalizations](../api/agreementfilelocalization-list.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md) collection|Get a list of the [agreementFileLocalization](../resources/agreementfilelocalization.md) objects and their properties.|
|[Create agreementFileLocalization](../api/agreementfile-post-localizations.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md)|Create a new [agreementFileLocalization](../resources/agreementfilelocalization.md) object.|
|[Get agreementFileLocalization](../api/agreementfilelocalization-get.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md)|Read the properties and relationships of an [agreementFileLocalization](../resources/agreementfilelocalization.md) object.|
|[Update agreementFileLocalization](../api/agreementfilelocalization-update.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md)|Update the properties of an [agreementFileLocalization](../resources/agreementfilelocalization.md) object.|
|[Delete agreementFileLocalization](../api/agreementfilelocalization-delete.md)|None|Deletes an [agreementFileLocalization](../resources/agreementfilelocalization.md) object.|
|[List versions](../api/agreementfilelocalization-list-versions.md)|[agreementFileVersion](../resources/agreementfileversion.md) collection|Get the agreementFileVersion resources from the versions navigation property.|
|[Create agreementFileVersion](../api/agreementfilelocalization-post-versions.md)|[agreementFileVersion](../resources/agreementfileversion.md)|Create a new agreementFileVersion object.|

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
|Relationship|Type|Description|
|:---|:---|:---|
|versions|[agreementFileVersion](../resources/agreementfileversion.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.agreementFileLocalization",
  "baseType": "microsoft.azure.termsOfUse.agreementFileProperties",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.agreementFileLocalization",
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

