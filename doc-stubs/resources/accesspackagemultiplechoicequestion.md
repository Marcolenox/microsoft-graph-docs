---
title: "accessPackageMultipleChoiceQuestion resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackageMultipleChoiceQuestion resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [accessPackageQuestion](../resources/accesspackagequestion.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowsMultipleSelection|Boolean|**TODO: Add Description**|
|attribute|[accessPackageResourceAttribute](../resources/accesspackageresourceattribute.md)|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|choices|[accessPackageAnswerChoice](../resources/accesspackageanswerchoice.md) collection|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|isAnswerEditable|Boolean|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|isRequired|Boolean|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|sequence|Int32|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|
|text|[accessPackageLocalizedContent](../resources/accesspackagelocalizedcontent.md)|**TODO: Add Description** Inherited from [accessPackageQuestion](../resources/accesspackagequestion.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.accessPackageMultipleChoiceQuestion"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageMultipleChoiceQuestion",
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
  "choices": [
    {
      "@odata.type": "microsoft.graph.accessPackageAnswerChoice"
    }
  ],
  "allowsMultipleSelection": "Boolean"
}
```

