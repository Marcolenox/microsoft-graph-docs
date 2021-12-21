---
title: "agreementFile resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# agreementFile resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [agreementFileProperties](../resources/agreementfileproperties.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List agreementFiles](../api/agreementfile-list.md)|[agreementFile](../resources/agreementfile.md) collection|Get a list of the [agreementFile](../resources/agreementfile.md) objects and their properties.|
|[Create agreementFile](../api/agreement-post-file.md)|[agreementFile](../resources/agreementfile.md)|Create a new [agreementFile](../resources/agreementfile.md) object.|
|[Get agreementFile](../api/agreementfile-get.md)|[agreementFile](../resources/agreementfile.md)|Read the properties and relationships of an [agreementFile](../resources/agreementfile.md) object.|
|[Update agreementFile](../api/agreementfile-update.md)|[agreementFile](../resources/agreementfile.md)|Update the properties of an [agreementFile](../resources/agreementfile.md) object.|
|[Delete agreementFile](../api/agreementfile-delete.md)|None|Deletes an [agreementFile](../resources/agreementfile.md) object.|
|[List localizations](../api/agreementfile-list-localizations.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md) collection|Get the agreementFileLocalization resources from the localizations navigation property.|
|[Create agreementFileLocalization](../api/agreementfile-post-localizations.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md)|Create a new agreementFileLocalization object.|

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
|localizations|[agreementFileLocalization](../resources/agreementfilelocalization.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.agreementFile",
  "baseType": "microsoft.azure.termsOfUse.agreementFileProperties",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.agreementFile",
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

