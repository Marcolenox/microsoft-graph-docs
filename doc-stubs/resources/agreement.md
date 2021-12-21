---
title: "agreement resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# agreement resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List agreements](../api/agreement-list.md)|[agreement](../resources/agreement.md) collection|Get a list of the [agreement](../resources/agreement.md) objects and their properties.|
|[Create agreement](../api/agreement-post-agreements.md)|[agreement](../resources/agreement.md)|Create a new [agreement](../resources/agreement.md) object.|
|[Get agreement](../api/agreement-get.md)|[agreement](../resources/agreement.md)|Read the properties and relationships of an [agreement](../resources/agreement.md) object.|
|[Update agreement](../api/agreement-update.md)|[agreement](../resources/agreement.md)|Update the properties of an [agreement](../resources/agreement.md) object.|
|[Delete agreement](../api/agreement-delete.md)|None|Deletes an [agreement](../resources/agreement.md) object.|
|[List acceptances](../api/agreement-list-acceptances.md)|[agreementAcceptance](../resources/agreementacceptance.md) collection|Get the agreementAcceptance resources from the acceptances navigation property.|
|[Create agreementAcceptance](../api/agreement-post-acceptances.md)|[agreementAcceptance](../resources/agreementacceptance.md)|Create a new agreementAcceptance object.|
|[List agreementFile](../api/agreement-list-file.md)|[agreementFile](../resources/agreementfile.md) collection|Get the agreementFile resources from the file navigation property.|
|[Create agreementFile](../api/agreement-post-file.md)|[agreementFile](../resources/agreementfile.md)|Create a new agreementFile object.|
|[List files](../api/agreement-list-files.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md) collection|Get the agreementFileLocalization resources from the files navigation property.|
|[Create agreementFileLocalization](../api/agreement-post-files.md)|[agreementFileLocalization](../resources/agreementfilelocalization.md)|Create a new agreementFileLocalization object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isPerDeviceAcceptanceRequired|Boolean|**TODO: Add Description**|
|isViewingBeforeAcceptanceRequired|Boolean|**TODO: Add Description**|
|termsExpiration|[termsExpiration](../resources/termsexpiration.md)|**TODO: Add Description**|
|userReacceptRequiredFrequency|Duration|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|acceptances|[agreementAcceptance](../resources/agreementacceptance.md) collection|**TODO: Add Description**|
|file|[agreementFile](../resources/agreementfile.md)|**TODO: Add Description**|
|files|[agreementFileLocalization](../resources/agreementfilelocalization.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.agreement",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.agreement",
  "id": "String (identifier)",
  "displayName": "String",
  "termsExpiration": {
    "@odata.type": "microsoft.graph.termsExpiration"
  },
  "userReacceptRequiredFrequency": "String (duration)",
  "isViewingBeforeAcceptanceRequired": "Boolean",
  "isPerDeviceAcceptanceRequired": "Boolean"
}
```

