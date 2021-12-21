---
title: "accessReviewPolicy resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessReviewPolicy resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessReviewPolicies](../api/accessreviewpolicy-list.md)|[accessReviewPolicy](../resources/accessreviewpolicy.md) collection|Get a list of the [accessReviewPolicy](../resources/accessreviewpolicy.md) objects and their properties.|
|[Create accessReviewPolicy](../api/policyroot-post-accessreviewpolicy.md)|[accessReviewPolicy](../resources/accessreviewpolicy.md)|Create a new [accessReviewPolicy](../resources/accessreviewpolicy.md) object.|
|[Get accessReviewPolicy](../api/accessreviewpolicy-get.md)|[accessReviewPolicy](../resources/accessreviewpolicy.md)|Read the properties and relationships of an [accessReviewPolicy](../resources/accessreviewpolicy.md) object.|
|[Update accessReviewPolicy](../api/accessreviewpolicy-update.md)|[accessReviewPolicy](../resources/accessreviewpolicy.md)|Update the properties of an [accessReviewPolicy](../resources/accessreviewpolicy.md) object.|
|[Delete accessReviewPolicy](../api/accessreviewpolicy-delete.md)|None|Deletes an [accessReviewPolicy](../resources/accessreviewpolicy.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|isGroupOwnerManagementEnabled|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessReviewPolicy",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessReviewPolicy",
  "displayName": "String",
  "description": "String",
  "isGroupOwnerManagementEnabled": "Boolean"
}
```

