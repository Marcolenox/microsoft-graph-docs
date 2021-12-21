---
title: "accessReviewReviewer resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessReviewReviewer resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessReviewReviewers](../api/accessreviewreviewer-list.md)|[accessReviewReviewer](../resources/accessreviewreviewer.md) collection|Get a list of the [accessReviewReviewer](../resources/accessreviewreviewer.md) objects and their properties.|
|[Create accessReviewReviewer](../api/accessreview-post-reviewers.md)|[accessReviewReviewer](../resources/accessreviewreviewer.md)|Create a new [accessReviewReviewer](../resources/accessreviewreviewer.md) object.|
|[Get accessReviewReviewer](../api/accessreviewreviewer-get.md)|[accessReviewReviewer](../resources/accessreviewreviewer.md)|Read the properties and relationships of an [accessReviewReviewer](../resources/accessreviewreviewer.md) object.|
|[Update accessReviewReviewer](../api/accessreviewreviewer-update.md)|[accessReviewReviewer](../resources/accessreviewreviewer.md)|Update the properties of an [accessReviewReviewer](../resources/accessreviewreviewer.md) object.|
|[Delete accessReviewReviewer](../api/accessreviewreviewer-delete.md)|None|Deletes an [accessReviewReviewer](../resources/accessreviewreviewer.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessReviewReviewer",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessReviewReviewer",
  "id": "String (identifier)",
  "displayName": "String",
  "userPrincipalName": "String",
  "createdDateTime": "String (timestamp)"
}
```

