---
title: "accessPackageTextInputQuestion resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageTextInputQuestion resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [accessPackageQuestion](../resources/accesspackagequestion.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|attribute|[accessPackageResourceAttribute](../resources/accesspackageresourceattribute.md)|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|id|String|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|isAnswerEditable|Boolean|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|isRequired|Boolean|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|isSingleLineQuestion|Boolean|**TODO: Add Description**|
|sequence|Int32|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|text|[accessPackageLocalizedContent](../resources/accesspackagelocalizedcontent.md)|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.accessPackageTextInputQuestion"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageTextInputQuestion",
  "id": "String (identifier)",
  "isRequired": "Boolean",
  "isAnswerEditable": "Boolean",
  "text": {
    "@odata.type": "microsoft.graph.accessPackageLocalizedContent"
  },
  "sequence": "Integer",
  "attribute": {
    "@odata.type": "microsoft.graph.accessPackageResourceAttribute"
  },
  "isSingleLineQuestion": "Boolean"
}
```

